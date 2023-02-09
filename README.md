# Awesome Machine Generated Text

## TOC
- [Resource List about Machine Generated Text](#awesome-machine-generated-text)
  - [Large Scale Pre-training for Language Generation](#large-scale-pre-training-for-language-generation)
  - [Analysis ![](https://img.shields.io/badge/Building-red)](#analysis)
    - [Comprehensive](#comprehensive)
    - [Hallucination & Disinformation](#hallucination--disinformation)
    - [Biases & Toxicities](#biases--toxicities)
    - [Security Risks](#security-risks)
    - [LM Attacks](#lm-attacks)
  - [Detection ![](https://img.shields.io/badge/Building-red)](#detection)

## Large Scale Pre-training for Language Generation
> **Note:** #params > 1B only

- OpenAI
  - (GPT-2) **Language Models are Unsupervised Multitask Learners.** [[paper]](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) [[blog]](https://openai.com/blog/better-language-models/) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Open-purple) ![](https://img.shields.io/badge/2019.02-blue)

    *Alec Radford, Jeffrey Wu, Rewon Child, David Luan, Dario Amodei and Ilya Sutskever.*

  - (GPT-3) **Language Models are Few-Shot Learners.** [[paper]](https://proceedings.neurips.cc/paper/2020/file/1457c0d6bfcb4967418bfb8ac142f64a-Paper.pdf) ![](https://img.shields.io/badge/NeurIPS%202020-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Limited-purple) ![](https://img.shields.io/badge/2020.05-blue)

    <details><summary>Show Authors</summary><i>Tom B. Brown, Benjamin Mann, Nick Ryder, Melanie Subbiah, Jared Kaplan, Prafulla Dhariwal, Arvind Neelakantan, Pranav Shyam, Girish Sastry, Amanda Askell, Sandhini Agarwal, Ariel Herbert-Voss, Gretchen Krueger, Tom Henighan, Rewon Child, Aditya Ramesh, Daniel M. Ziegler, Jeffrey Wu, Clemens Winter, Christopher Hesse, Mark Chen, Eric Sigler, Mateusz Litwin, Scott Gray, Benjamin Chess, Jack Clark, Christopher Berner, Sam McCandlish, Alec Radford, Ilya Sutskever and Dario Amodei.</i></details>

  - **WebGPT: Browser-assisted question-answering with human feedback.** [[paper]](https://arxiv.org/pdf/2112.09332) [[blog]](https://openai.com/blog/webgpt/) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Closed-purple) ![](https://img.shields.io/badge/2021.12-blue)

    *Reiichiro Nakano, Jacob Hilton, Suchir Balaji, Jeff Wu, Long Ouyang, Christina Kim, Christopher Hesse, Shantanu Jain, Vineet Kosaraju, William Saunders, Xu Jiang, Karl Cobbe, Tyna Eloundou, Gretchen Krueger, Kevin Button, Matthew Knight, Benjamin Chess and John Schulman.*

  - (InstructGPT) **Training language models to follow instructions with human feedback.** [[paper]](https://arxiv.org/pdf/2203.02155) [[blog]](https://openai.com/blog/instruction-following/) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Limited-purple) ![](https://img.shields.io/badge/2022.01-blue)

    *Long Ouyang, Jeff Wu, Xu Jiang, Diogo Almeida, Carroll L. Wainwright, Pamela Mishkin, Chong Zhang, Sandhini Agarwal, Katarina Slama, Alex Ray, John Schulman, Jacob Hilton, Fraser Kelton, Luke Miller, Maddie Simens, Amanda Askell, Peter Welinder, Paul Christiano, Jan Leike and Ryan Lowe.*

  - **ChatGPT: Optimizing Language Models for Dialogue.** [[blog]](https://openai.com/blog/chatgpt/) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Limited-purple) ![](https://img.shields.io/badge/2022.11-blue)

- DeepMind
  - (Gopher) **Scaling Language Models: Methods, Analysis & Insights from Training Gopher.** [[paper]](https://arxiv.org/pdf/2112.11446) [[blog]](https://www.deepmind.com/blog/language-modelling-at-scale-gopher-ethical-considerations-and-retrieval) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Closed-purple) ![](https://img.shields.io/badge/2021.12-blue)

    <details><summary>Show Authors</summary><i>Jack W. Rae, Sebastian Borgeaud, Trevor Cai, Katie Millican, Jordan Hoffmann, Francis Song, John Aslanides, Sarah Henderson, Roman Ring, Susannah Young, Eliza Rutherford, Tom Hennigan, Jacob Menick, Albin Cassirer, Richard Powell, George van den Driessche, Lisa Anne Hendricks, Maribeth Rauh, Po-Sen Huang, Amelia Glaese, Johannes Welbl, Sumanth Dathathri, Saffron Huang, Jonathan Uesato, John Mellor, Irina Higgins, Antonia Creswell, Nat McAleese, Amy Wu, Erich Elsen, Siddhant Jayakumar, Elena Buchatskaya, David Budden, Esme Sutherland, Karen Simonyan, Michela Paganini, Laurent Sifre, Lena Martens, Xiang Lorraine Li, Adhiguna Kuncoro, Aida Nematzadeh, Elena Gribovskaya, Domenic Donato, Angeliki Lazaridou, Arthur Mensch, Jean-Baptiste Lespiau, Maria Tsimpoukelli, Nikolai Grigorev, Doug Fritz, Thibault Sottiaux, Mantas Pajarskas, Toby Pohlen, Zhitao Gong, Daniel Toyama, Cyprien de Masson d'Autume, Yujia Li, Tayfun Terzi, Vladimir Mikulik, Igor Babuschkin, Aidan Clark, Diego de Las Casas, Aurelia Guy, Chris Jones, James Bradbury, Matthew Johnson, Blake Hechtman, Laura Weidinger, Iason Gabriel, William Isaac, Ed Lockhart, Simon Osindero, Laura Rimell, Chris Dyer, Oriol Vinyals, Kareem Ayoub, Jeff Stanway, Lorrayne Bennett, Demis Hassabis, Koray Kavukcuoglu and Geoffrey Irving.</i></details>

  - (RETRO) **Improving language models by retrieving from trillions of tokens.** [[paper]](https://arxiv.org/pdf/2112.04426) [[blog]](https://www.deepmind.com/blog/improving-language-models-by-retrieving-from-trillions-of-tokens) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Closed-purple) ![](https://img.shields.io/badge/2021.12-blue)

    <details><summary>Show Authors</summary><i>Sebastian Borgeaud, Arthur Mensch, Jordan Hoffmann, Trevor Cai, Eliza Rutherford, Katie Millican, George van den Driessche, Jean-Baptiste Lespiau, Bogdan Damoc, Aidan Clark, Diego de Las Casas, Aurelia Guy, Jacob Menick, Roman Ring, Tom Hennigan, Saffron Huang, Loren Maggiore, Chris Jones, Albin Cassirer, Andy Brock, Michela Paganini, Geoffrey Irving, Oriol Vinyals, Simon Osindero, Karen Simonyan, Jack W. Rae, Erich Elsen and Laurent Sifre.</i></details>

  - (Chinchilla) **Training Compute-Optimal Large Language Models.** [[paper]](https://arxiv.org/pdf/2203.15556) [[blog]](https://www.deepmind.com/blog/an-empirical-analysis-of-compute-optimal-large-language-model-training) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Closed-purple) ![](https://img.shields.io/badge/2022.04-blue)

    <details><summary>Show Authors</summary><i>Jordan Hoffmann, Sebastian Borgeaud, Arthur Mensch, Elena Buchatskaya, Trevor Cai, Eliza Rutherford, Diego de Las Casas, Lisa Anne Hendricks, Johannes Welbl, Aidan Clark, Tom Hennigan, Eric Noland, Katie Millican, George van den Driessche, Bogdan Damoc, Aurelia Guy, Simon Osindero, Karen Simonyan, Erich Elsen, Jack W. Rae, Oriol Vinyals and Laurent Sifre.</i></details>
  
  - (Sparrow) **Improving alignment of dialogue agents via targeted human judgements.** [[paper]](https://arxiv.org/pdf/2209.14375) [[blog]](https://www.deepmind.com/blog/building-safer-dialogue-agents) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Closed-purple) ![](https://img.shields.io/badge/2022.09-blue)

    <details><summary>Show Authors</summary><i>Amelia Glaese, Nat McAleese, Maja Trębacz, John Aslanides, Vlad Firoiu, Timo Ewalds, Maribeth Rauh, Laura Weidinger, Martin Chadwick, Phoebe Thacker, Lucy Campbell-Gillingham, Jonathan Uesato, Po-Sen Huang, Ramona Comanescu, Fan Yang, Abigail See, Sumanth Dathathri, Rory Greig, Charlie Chen, Doug Fritz, Jaume Sanchez Elias, Richard Green, Soňa Mokrá, Nicholas Fernando, Boxi Wu, Rachel Foley, Susannah Young, Iason Gabriel, William Isaac, John Mellor, Demis Hassabis, Koray Kavukcuoglu, Lisa Anne Hendricks and Geoffrey Irving.</i></details>

- Nvidia & Microsoft
  - **Megatron-LM: Training Multi-Billion Parameter Language Models Using Model Parallelism.** [[paper]](https://arxiv.org/pdf/1909.08053) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Limited-purple) ![](https://img.shields.io/badge/2019.09-blue)

    *Mohammad Shoeybi, Mostofa Patwary, Raul Puri, Patrick LeGresley, Jared Casper and Bryan Catanzaro.*

  - **Turing-NLG: A 17-billion-parameter language model by Microsoft.** [[blog]](https://www.microsoft.com/en-us/research/blog/turing-nlg-a-17-billion-parameter-language-model-by-microsoft/) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Closed-purple) ![](https://img.shields.io/badge/2020.02-blue)

  - (Megatron-Turing NLG) **Using DeepSpeed and Megatron to Train Megatron-Turing NLG 530B, A Large-Scale Generative Language Model.** [[paper]](https://arxiv.org/pdf/2201.11990) [[blog]](https://developer.nvidia.com/blog/using-deepspeed-and-megatron-to-train-megatron-turing-nlg-530b-the-worlds-largest-and-most-powerful-generative-language-model/) [[blog]](https://www.microsoft.com/en-us/research/blog/using-deepspeed-and-megatron-to-train-megatron-turing-nlg-530b-the-worlds-largest-and-most-powerful-generative-language-model/) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Closed-purple) ![](https://img.shields.io/badge/2021.10-blue)

    <details><summary>Show Authors</summary><i>Shaden Smith, Mostofa Patwary, Brandon Norick, Patrick LeGresley, Samyam Rajbhandari, Jared Casper, Zhun Liu, Shrimai Prabhumoye, George Zerveas, Vijay Korthikanti, Elton Zhang, Rewon Child, Reza Yazdani Aminabadi, Julie Bernauer, Xia Song, Mohammad Shoeybi, Yuxiong He, Michael Houston, Saurabh Tiwary and Bryan Catanzaro.</i></details>

- Google
  - (Meena) **Towards a Human-like Open-Domain Chatbot.** [[paper]](https://arxiv.org/pdf/2001.09977) [[blog]](https://ai.googleblog.com/2020/01/towards-conversational-agent-that-can.html) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Closed-purple) ![](https://img.shields.io/badge/2020.01-blue)

    *Daniel Adiwardana, Minh-Thang Luong, David R. So, Jamie Hall, Noah Fiedel, Romal Thoppilan, Zi Yang, Apoorv Kulshreshtha, Gaurav Nemade, Yifeng Lu and Quoc V. Le.*

  - (T5) **Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer.** [[paper]](https://www.jmlr.org/papers/volume21/20-074/20-074.pdf) [[blog]](https://ai.googleblog.com/2020/02/exploring-transfer-learning-with-t5.html) ![](https://img.shields.io/badge/JMLR%202020-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Open-purple) ![](https://img.shields.io/badge/2020.02-blue)

    *Colin Raffel, Noam Shazeer, Adam Roberts, Katherine Lee, Sharan Narang, Michael Matena, Yanqi Zhou, Wei Li and Peter J. Liu.*

  - **mT5: A massively multilingual pre-trained text-to-text transformer.** [[paper]](https://aclanthology.org/2021.naacl-main.41.pdf) ![](https://img.shields.io/badge/NAACL%202021-orange) ![](https://img.shields.io/badge/Multilingual-darkcyan) ![](https://img.shields.io/badge/Open-purple) ![](https://img.shields.io/badge/2020.10-blue)

    *Linting Xue, Noah Constant, Adam Roberts, Mihir Kale, Rami Al-Rfou, Aditya Siddhant, Aditya Barua and Colin Raffel.*

  - (FLAN) **Finetuned Language Models Are Zero-Shot Learners.** [[paper]](https://openreview.net/pdf?id=gEZrGCozdqR) [[blog]](https://ai.googleblog.com/2021/10/introducing-flan-more-generalizable.html) ![](https://img.shields.io/badge/ICLR%202022-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Closed-purple) ![](https://img.shields.io/badge/2021.10-blue)

    *Jason Wei, Maarten Bosma, Vincent Y. Zhao, Kelvin Guu, Adams Wei Yu, Brian Lester, Nan Du, Andrew M. Dai and Quoc V. Le.*

  - **GLaM: Efficient Scaling of Language Models with Mixture-of-Experts.** [[paper]](https://arxiv.org/pdf/2112.06905) [[slides]](https://icml.cc/media/icml-2022/Slides/17378.pdf) [[blog]](https://ai.googleblog.com/2021/12/more-efficient-in-context-learning-with.html) ![](https://img.shields.io/badge/ICML%202022-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Closed-purple) ![](https://img.shields.io/badge/2021.12-blue)

    <details><summary>Show Authors</summary><i>Nan Du, Yanping Huang, Andrew M. Dai, Simon Tong, Dmitry Lepikhin, Yuanzhong Xu, Maxim Krikun, Yanqi Zhou, Adams Wei Yu, Orhan Firat, Barret Zoph, Liam Fedus, Maarten Bosma, Zongwei Zhou, Tao Wang, Yu Emma Wang, Kellie Webster, Marie Pellat, Kevin Robinson, Kathleen Meier-Hellstern, Toju Duke, Lucas Dixon, Kun Zhang, Quoc V Le, Yonghui Wu, Zhifeng Chen and Claire Cui.</i></details>
  
  - **LaMDA: Language Models for Dialog Applications.** [[paper]](https://arxiv.org/pdf/2201.08239) [[blog]](https://ai.googleblog.com/2022/01/lamda-towards-safe-grounded-and-high.html) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Closed-purple) ![](https://img.shields.io/badge/2022.01-blue)

    <details><summary>Show Authors</summary><i>Romal Thoppilan, Daniel De Freitas, Jamie Hall, Noam Shazeer, Apoorv Kulshreshtha, Heng-Tze Cheng, Alicia Jin, Taylor Bos, Leslie Baker, Yu Du, YaGuang Li, Hongrae Lee, Huaixiu Steven Zheng, Amin Ghafouri, Marcelo Menegali, Yanping Huang, Maxim Krikun, Dmitry Lepikhin, James Qin, Dehao Chen, Yuanzhong Xu, Zhifeng Chen, Adam Roberts, Maarten Bosma, Vincent Zhao, Yanqi Zhou, Chung-Ching Chang, Igor Krivokon, Will Rusch, Marc Pickett, Pranesh Srinivasan, Laichee Man, Kathleen Meier-Hellstern, Meredith Ringel Morris, Tulsee Doshi, Renelito Delos Santos, Toju Duke, Johnny Soraker, Ben Zevenbergen, Vinodkumar Prabhakaran, Mark Diaz, Ben Hutchinson, Kristen Olson, Alejandra Molina, Erin Hoffman-John, Josh Lee, Lora Aroyo, Ravi Rajakumar, Alena Butryna, Matthew Lamm, Viktoriya Kuzmina, Joe Fenton, Aaron Cohen, Rachel Bernstein, Ray Kurzweil, Blaise Aguera-Arcas, Claire Cui, Marian Croak, Ed Chi and Quoc Le.</i></details>

  - **PaLM: Scaling Language Modeling with Pathways.** [[paper]](https://arxiv.org/pdf/2204.02311) [[blog]](https://ai.googleblog.com/2022/04/pathways-language-model-palm-scaling-to.html) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Closed-purple) ![](https://img.shields.io/badge/2022.04-blue)

    <details><summary>Show Authors</summary><i>Aakanksha Chowdhery, Sharan Narang, Jacob Devlin, Maarten Bosma, Gaurav Mishra, Adam Roberts, Paul Barham, Hyung Won Chung, Charles Sutton, Sebastian Gehrmann, Parker Schuh, Kensen Shi, Sasha Tsvyashchenko, Joshua Maynez, Abhishek Rao, Parker Barnes, Yi Tay, Noam Shazeer, Vinodkumar Prabhakaran, Emily Reif, Nan Du, Ben Hutchinson, Reiner Pope, James Bradbury, Jacob Austin, Michael Isard, Guy Gur-Ari, Pengcheng Yin, Toju Duke, Anselm Levskaya, Sanjay Ghemawat, Sunipa Dev, Henryk Michalewski, Xavier Garcia, Vedant Misra, Kevin Robinson, Liam Fedus, Denny Zhou, Daphne Ippolito, David Luan, Hyeontaek Lim, Barret Zoph, Alexander Spiridonov, Ryan Sepassi, David Dohan, Shivani Agrawal, Mark Omernick, Andrew M. Dai, Thanumalayan Sankaranarayana Pillai, Marie Pellat, Aitor Lewkowycz, Erica Moreira, Rewon Child, Oleksandr Polozov, Katherine Lee, Zongwei Zhou, Xuezhi Wang, Brennan Saeta, Mark Diaz, Orhan Firat, Michele Catasta, Jason Wei, Kathy Meier-Hellstern, Douglas Eck, Jeff Dean, Slav Petrov and Noah Fiedel.</i></details>

  - **UL2: Unifying Language Learning Paradigms.** [[paper]](https://arxiv.org/pdf/2205.05131) [[blog]](https://ai.googleblog.com/2022/10/ul2-20b-open-source-unified-language.html) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Open-purple) ![](https://img.shields.io/badge/2022.10-blue)

    *Yi Tay, Mostafa Dehghani, Vinh Q. Tran, Xavier Garcia, Jason Wei, Xuezhi Wang, Hyung Won Chung, Dara Bahri, Tal Schuster, Huaixiu Steven Zheng, Denny Zhou, Neil Houlsby and Donald Metzler.*
  
  - (Flan-T5 & Flan-PaLM & Flan-U-PaLM) **Scaling Instruction-Finetuned Language Models.** [[paper]](https://arxiv.org/pdf/2210.11416) [[blog]](https://ai.googleblog.com/2022/10/ul2-20b-open-source-unified-language.html) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Open-purple) ![](https://img.shields.io/badge/2022.10-blue)

    *Yi Tay, Mostafa Dehghani, Vinh Q. Tran, Xavier Garcia, Jason Wei, Xuezhi Wang, Hyung Won Chung, Dara Bahri, Tal Schuster, Huaixiu Steven Zheng, Denny Zhou, Neil Houlsby and Donald Metzler.*

- Meta
  - (Generative BST) **Recipes for Building an Open-Domain Chatbot.** [[paper]](https://aclanthology.org/2021.eacl-main.24.pdf) ![](https://img.shields.io/badge/EACL%202021-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Open-purple) ![](https://img.shields.io/badge/2020.04-blue)

    *Stephen Roller, Emily Dinan, Naman Goyal, Da Ju, Mary Williamson, Yinhan Liu, Jing Xu, Myle Ott, Kurt Shuster, Eric M. Smith, Y-Lan Boureau and Jason Weston.*
  
  - (XGLM) **Few-shot Learning with Multilingual Language Models.** [[paper]](https://arxiv.org/pdf/2112.10668) ![](https://img.shields.io/badge/EMNLP%202022-orange) ![](https://img.shields.io/badge/Multilingual-darkcyan) ![](https://img.shields.io/badge/Open-purple) ![](https://img.shields.io/badge/2021.12-blue)

    *Xi Victoria Lin, Todor Mihaylov, Mikel Artetxe, Tianlu Wang, Shuohui Chen, Daniel Simig, Myle Ott, Naman Goyal, Shruti Bhosale, Jingfei Du, Ramakanth Pasunuru, Sam Shleifer, Punit Singh Koura, Vishrav Chaudhary, Brian O'Horo, Jeff Wang, Luke Zettlemoyer, Zornitsa Kozareva, Mona Diab, Veselin Stoyanov and Xian Li.*
  
  - **OPT: Open Pre-trained Transformer Language Models.** [[paper]](https://arxiv.org/pdf/2205.01068) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Open-purple) ![](https://img.shields.io/badge/2022.05-blue)

    *Susan Zhang, Stephen Roller, Naman Goyal, Mikel Artetxe, Moya Chen, Shuohui Chen, Christopher Dewan, Mona Diab, Xian Li, Xi Victoria Lin, Todor Mihaylov, Myle Ott, Sam Shleifer, Kurt Shuster, Daniel Simig, Punit Singh Koura, Anjali Sridhar, Tianlu Wang and Luke Zettlemoyer.*
  
  - **BlenderBot 3: a deployed conversational agent that continually learns to responsibly engage.** [[paper]](https://arxiv.org/pdf/2208.03188) [[blog]](https://ai.facebook.com/blog/blenderbot-3-a-175b-parameter-publicly-available-chatbot-that-improves-its-skills-and-safety-over-time/) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Closed-purple) ![](https://img.shields.io/badge/2022.08-blue)

    *Kurt Shuster, Jing Xu, Mojtaba Komeili, Da Ju, Eric Michael Smith, Stephen Roller, Megan Ung, Moya Chen, Kushal Arora, Joshua Lane, Morteza Behrooz, William Ngan, Spencer Poff, Naman Goyal, Arthur Szlam, Y-Lan Boureau, Melanie Kambadur and Jason Weston.*
  
  - **Atlas: Few-shot Learning with Retrieval Augmented Language Models.** [[paper]](https://arxiv.org/pdf/2208.03299) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Open-purple) ![](https://img.shields.io/badge/2022.08-blue)

    *Gautier Izacard, Patrick Lewis, Maria Lomeli, Lucas Hosseini, Fabio Petroni, Timo Schick, Jane Dwivedi-Yu, Armand Joulin, Sebastian Riedel and Edouard Grave.*

- BigScience
  - (T0++) **Multitask Prompted Training Enables Zero-Shot Task Generalization.** [[paper]](https://openreview.net/pdf?id=9Vrb9D0WI4) ![](https://img.shields.io/badge/ICLR%202022-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Open-purple) ![](https://img.shields.io/badge/2021.10-blue)

    <details><summary>Show Authors</summary><i>Victor Sanh, Albert Webson, Colin Raffel, Stephen H. Bach, Lintang Sutawika, Zaid Alyafeai, Antoine Chaffin, Arnaud Stiegler, Teven Le Scao, Arun Raja, Manan Dey, M Saiful Bari, Canwen Xu, Urmish Thakker, Shanya Sharma Sharma, Eliza Szczechla, Taewoon Kim, Gunjan Chhablani, Nihal Nayak, Debajyoti Datta, Jonathan Chang, Mike Tian-Jian Jiang, Han Wang, Matteo Manica, Sheng Shen, Zheng Xin Yong, Harshit Pandey, Rachel Bawden, Thomas Wang, Trishala Neeraj, Jos Rozen, Abheesht Sharma, Andrea Santilli, Thibault Fevry, Jason Alan Fries, Ryan Teehan, Tali Bers, Stella Biderman, Leo Gao, Thomas Wolf and Alexander M. Rush.</i></details>
  
  - **BLOOM: A 176B-Parameter Open-Access Multilingual Language Model.** [[paper]](https://arxiv.org/pdf/2211.05100) ![](https://img.shields.io/badge/Preprint-orange)  ![](https://img.shields.io/badge/Multilingual-darkcyan) ![](https://img.shields.io/badge/Open-purple) ![](https://img.shields.io/badge/2022.11-blue)

    <details><summary>Show Authors</summary><i>BigScience Workshop: Teven Le Scao, Angela Fan, Christopher Akiki, Ellie Pavlick, Suzana Ilić, Daniel Hesslow, Roman Castagné, Alexandra Sasha Luccioni, François Yvon, Matthias Gallé, Jonathan Tow, Alexander M. Rush, Stella Biderman, Albert Webson, Pawan Sasanka Ammanamanchi, Thomas Wang, Benoît Sagot, Niklas Muennighoff, Albert Villanova del Moral, Olatunji Ruwase, Rachel Bawden, Stas Bekman, Angelina McMillan-Major, Iz Beltagy, Huu Nguyen, Lucile Saulnier, Samson Tan, Pedro Ortiz Suarez, Victor Sanh, Hugo Laurençon, Yacine Jernite, Julien Launay, Margaret Mitchell, Colin Raffel, Aaron Gokaslan, Adi Simhi, Aitor Soroa, Alham Fikri Aji, Amit Alfassy, Anna Rogers, Ariel Kreisberg Nitzav, Canwen Xu, Chenghao Mou, Chris Emezue, Christopher Klamm, Colin Leong, Daniel van Strien, David Ifeoluwa Adelani, Dragomir Radev, Eduardo González Ponferrada, Efrat Levkovizh, Ethan Kim, Eyal Bar Natan, Francesco De Toni, Gérard Dupont, Germán Kruszewski, Giada Pistilli, Hady Elsahar, Hamza Benyamina, Hieu Tran, Ian Yu, Idris Abdulmumin, Isaac Johnson, Itziar Gonzalez-Dios, Javier de la Rosa, Jenny Chim, Jesse Dodge, Jian Zhu, Jonathan Chang, Jörg Frohberg, Joseph Tobing, Joydeep Bhattacharjee, Khalid Almubarak, Kimbo Chen, Kyle Lo, Leandro Von Werra, Leon Weber, Long Phan, Loubna Ben allal, Ludovic Tanguy, Manan Dey, Manuel Romero Muñoz, Maraim Masoud, María Grandury, Mario Šaško, Max Huang, Maximin Coavoux, Mayank Singh, Mike Tian-Jian Jiang, Minh Chien Vu, Mohammad A. Jauhar, Mustafa Ghaleb, Nishant Subramani, Nora Kassner, Nurulaqilla Khamis, Olivier Nguyen, Omar Espejel, Ona de Gibert, Paulo Villegas , Peter Henderson, Pierre Colombo, Priscilla Amuok, Quentin Lhoest, Rheza Harliman, Rishi Bommasani, Roberto Luis López, Rui Ribeiro, Salomey Osei, Sampo Pyysalo, Sebastian Nagel, Shamik Bose, Shamsuddeen Hassan Muhammad, Shanya Sharma, Shayne Longpre, Somaieh Nikpoor, Stanislav Silberberg, Suhas Pai, Sydney Zink, Tiago Timponi Torrent, Timo Schick, Tristan Thrush, Valentin Danchev, Vassilina Nikoulina, Veronika Laippala, Violette Lepercq, Vrinda Prabhu, Zaid Alyafeai, Zeerak Talat, Arun Raja, Benjamin Heinzerling, Chenglei Si, Davut Emre Taşar, Elizabeth Salesky, Sabrina J. Mielke, Wilson Y. Lee, Abheesht Sharma, Andrea Santilli, Antoine Chaffin, Arnaud Stiegler, Debajyoti Datta, Eliza Szczechla, Gunjan Chhablani, Han Wang, Harshit Pandey, Hendrik Strobelt, Jason Alan Fries, Jos Rozen, Leo Gao, Lintang Sutawika, M Saiful Bari, Maged S. Al-shaibani, Matteo Manica, Nihal Nayak, Ryan Teehan, Samuel Albanie, Sheng Shen, Srulik Ben-David, Stephen H. Bach, Taewoon Kim, Tali Bers, Thibault Fevry, Trishala Neeraj, Urmish Thakker, Vikas Raunak, Xiangru Tang, Zheng-Xin Yong, Zhiqing Sun, Shaked Brody, Yallow Uri, Hadar Tojarieh, Adam Roberts, Hyung Won Chung, Jaesung Tae, Jason Phang, Ofir Press, Conglong Li, Deepak Narayanan, Hatim Bourfoune, Jared Casper, Jeff Rasley, Max Ryabinin, Mayank Mishra, Minjia Zhang, Mohammad Shoeybi, Myriam Peyrounette, Nicolas Patry, Nouamane Tazi, Omar Sanseviero, Patrick von Platen, Pierre Cornette, Pierre François Lavallée, Rémi Lacroix, Samyam Rajbhandari, Sanchit Gandhi, Shaden Smith, Stéphane Requena, Suraj Patil, Tim Dettmers, Ahmed Baruwa, Amanpreet Singh, Anastasia Cheveleva, Anne-Laure Ligozat, Arjun Subramonian, Aurélie Névéol, Charles Lovering, Dan Garrette, Deepak Tunuguntla, Ehud Reiter, Ekaterina Taktasheva, Ekaterina Voloshina, Eli Bogdanov, Genta Indra Winata, Hailey Schoelkopf, Jan-Christoph Kalo, Jekaterina Novikova, Jessica Zosa Forde, Jordan Clive, Jungo Kasai, Ken Kawamura, Liam Hazan, Marine Carpuat, Miruna Clinciu, Najoung Kim, Newton Cheng, Oleg Serikov, Omer Antverg, Oskar van der Wal, Rui Zhang, Ruochen Zhang, Sebastian Gehrmann, Shachar Mirkin, Shani Pais, Tatiana Shavrina, Thomas Scialom, Tian Yun, Tomasz Limisiewicz, Verena Rieser, Vitaly Protasov, Vladislav Mikhailov, Yada Pruksachatkun, Yonatan Belinkov, Zachary Bamberger, Zdeněk Kasner, Alice Rueda, Amanda Pestana, Amir Feizpour, Ammar Khan, Amy Faranak, Ana Santos, Anthony Hevia, Antigona Unldreaj, Arash Aghagol, Arezoo Abdollahi, Aycha Tammour, Azadeh HajiHosseini, Bahareh Behroozi, Benjamin Ajibade, Bharat Saxena, Carlos Muñoz Ferrandis, Danish Contractor, David Lansky, Davis David, Douwe Kiela, Duong A. Nguyen, Edward Tan, Emi Baylor, Ezinwanne Ozoani, Fatima Mirza, Frankline Ononiwu, Habib Rezanejad, Hessie Jones, Indrani Bhattacharya, Irene Solaiman, Irina Sedenko, Isar Nejadgholi, Jesse Passmore, Josh Seltzer, Julio Bonis Sanz, Livia Dutra, Mairon Samagaio, Maraim Elbadri, Margot Mieskes, Marissa Gerchick, Martha Akinlolu, Michael McKenna, Mike Qiu, Muhammed Ghauri, Mykola Burynok, Nafis Abrar, Nazneen Rajani, Nour Elkott, Nour Fahmy, Olanrewaju Samuel, Ran An, Rasmus Kromann, Ryan Hao, Samira Alizadeh, Sarmad Shubber, Silas Wang, Sourav Roy, Sylvain Viguier, Thanh Le, Tobi Oyebade, Trieu Le, Yoyo Yang, Zach Nguyen, Abhinav Ramesh Kashyap, Alfredo Palasciano, Alison Callahan, Anima Shukla, Antonio Miranda-Escalada, Ayush Singh, Benjamin Beilharz, Bo Wang, Caio Brito, Chenxi Zhou, Chirag Jain, Chuxin Xu, Clémentine Fourrier, Daniel León Periñán, Daniel Molano, Dian Yu, Enrique Manjavacas, Fabio Barth, Florian Fuhrimann, Gabriel Altay, Giyaseddin Bayrak, Gully Burns, Helena U. Vrabec, Imane Bello, Ishani Dash, Jihyun Kang, John Giorgi, Jonas Golde, Jose David Posada, Karthik Rangasai Sivaraman, Lokesh Bulchandani, Lu Liu, Luisa Shinzato, Madeleine Hahn de Bykhovetz, Maiko Takeuchi, Marc Pàmies, Maria A Castillo, Marianna Nezhurina, Mario Sänger, Matthias Samwald, Michael Cullan, Michael Weinberg, Michiel De Wolf, Mina Mihaljcic, Minna Liu, Moritz Freidank, Myungsun Kang, Natasha Seelam, Nathan Dahlberg, Nicholas Michio Broad, Nikolaus Muellner, Pascale Fung, Patrick Haller, Ramya Chandrasekhar, Renata Eisenberg, Robert Martin, Rodrigo Canalli, Rosaline Su, Ruisi Su, Samuel Cahyawijaya, Samuele Garda, Shlok S Deshmukh, Shubhanshu Mishra, Sid Kiblawi, Simon Ott, Sinee Sang-aroonsiri, Srishti Kumar, Stefan Schweter, Sushil Bharati, Tanmay Laud, Théo Gigant, Tomoya Kainuma, Wojciech Kusa, Yanis Labrak, Yash Shailesh Bajaj, Yash Venkatraman, Yifan Xu, Yingxin Xu, Yu Xu, Zhe Tan, Zhongli Xie, Zifan Ye, Mathilde Bras, Younes Belkada and Thomas Wolf.</i></details>

- Amazon
  - **AlexaTM 20B: Few-Shot Learning Using a Large-Scale Multilingual Seq2Seq Model.** [[paper]](https://arxiv.org/pdf/2208.01448) [[blog]](https://www.amazon.science/blog/20b-parameter-alexa-model-sets-new-marks-in-few-shot-learning) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Limited-purple) ![](https://img.shields.io/badge/2022.08-blue)

    *Saleh Soltan, Shankar Ananthakrishnan, Jack FitzGerald, Rahul Gupta, Wael Hamza, Haidar Khan, Charith Peris, Stephen Rawls, Andy Rosenbaum, Anna Rumshisky, Chandana Satya Prakash, Mukund Sridhar, Fabian Triefenbach, Apurv Verma, Gokhan Tur and Prem Natarajan.*

- AI21 Labs
  - **Jurassic-1: Technical Details and Evaluation.** [[paper]](https://uploads-ssl.webflow.com/60fd4503684b466578c0d307/61138924626a6981ee09caf6_jurassic_tech_paper.pdf) [[blog]](https://www.ai21.com/blog/announcing-ai21-studio-and-jurassic-1) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Limited-purple) ![](https://img.shields.io/badge/2021.08-blue)

    *Opher Lieber, Or Sharir, Barak Lenz and Yoav Shoham.*

- Baidu
  - **ERNIE 3.0: Large-scale Knowledge Enhanced Pre-training for Language Understanding and Generation.** [[paper]](https://arxiv.org/pdf/2107.02137) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/Multilingual-darkcyan) ![](https://img.shields.io/badge/Limited-purple) ![](https://img.shields.io/badge/2021.07-blue)

    *Yu Sun, Shuohuan Wang, Shikun Feng, Siyu Ding, Chao Pang, Junyuan Shang, Jiaxiang Liu, Xuyi Chen, Yanbin Zhao, Yuxiang Lu, Weixin Liu, Zhihua Wu, Weibao Gong, Jianzhong Liang, Zhizhou Shang, Peng Sun, Wei Liu, Xuan Ouyang, Dianhai Yu, Hao Tian, Hua Wu and Haifeng Wang.*

  - **ERNIE 3.0 Titan: Exploring Larger-scale Knowledge Enhanced Pre-training for Language Understanding and Generation.** [[paper]](https://arxiv.org/pdf/2112.12731) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/Multilingual-darkcyan) ![](https://img.shields.io/badge/Closed-purple) ![](https://img.shields.io/badge/2021.12-blue)

    <details><summary>Show Authors</summary><i>Shuohuan Wang, Yu Sun, Yang Xiang, Zhihua Wu, Siyu Ding, Weibao Gong, Shikun Feng, Junyuan Shang, Yanbin Zhao, Chao Pang, Jiaxiang Liu, Xuyi Chen, Yuxiang Lu, Weixin Liu, Xi Wang, Yangfan Bai, Qiuliang Chen, Li Zhao, Shiyong Li, Peng Sun, Dianhai Yu, Yanjun Ma, Hao Tian, Hua Wu, Tian Wu, Wei Zeng, Ge Li, Wen Gao and Haifeng Wang.</i></details>

  - **PLATO-XL: Exploring the Large-scale Pre-training of Dialogue Generation.** [[paper]](https://aclanthology.org/2022.findings-aacl.10.pdf) ![](https://img.shields.io/badge/AACL--IJCNLP%202022%20Findings-orange) ![](https://img.shields.io/badge/Multilingual-darkcyan) ![](https://img.shields.io/badge/Open-purple) ![](https://img.shields.io/badge/2021.09-blue)

    *Siqi Bao, Huang He, Fan Wang, Hua Wu, Haifeng Wang, Wenquan Wu, Zhihua Wu, Zhen Guo, Hua Lu, Xinxian Huang, Xin Tian, Xinchao Xu, Yingzhan Lin and Zheng-Yu Niu.*

  - ERNIE Bot [[news]](https://mp.weixin.qq.com/s/0-8X9FPouteKzNiK6DPaiA) ![](https://img.shields.io/badge/2023.02-blue)

- Anthropic
  - (Anthropic-52) **Training a Helpful and Harmless Assistant with Reinforcement Learning from Human Feedback** [[paper]](https://arxiv.org/pdf/2204.05862) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Closed-purple) ![](https://img.shields.io/badge/2022.04-blue)

    <details><summary>Show Authors</summary><i>Yuntao Bai, Andy Jones, Kamal Ndousse, Amanda Askell, Anna Chen, Nova DasSarma, Dawn Drain, Stanislav Fort, Deep Ganguli, Tom Henighan, Nicholas Joseph, Saurav Kadavath, Jackson Kernion, Tom Conerly, Sheer El-Showk, Nelson Elhage, Zac Hatfield-Dodds, Danny Hernandez, Tristan Hume, Scott Johnston, Shauna Kravec, Liane Lovitt, Neel Nanda, Catherine Olsson, Dario Amodei, Tom Brown, Jack Clark, Sam McCandlish, Chris Olah, Ben Mann and Jared Kaplan.</i></details>

  - (Claude) **Constitutional AI: Harmlessness from AI Feedback.** [[paper]](https://arxiv.org/pdf/2212.08073) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Closed-purple) ![](https://img.shields.io/badge/2022.12-blue)

    <details><summary>Show Authors</summary><i>Yuntao Bai, Saurav Kadavath, Sandipan Kundu, Amanda Askell, Jackson Kernion, Andy Jones, Anna Chen, Anna Goldie, Azalia Mirhoseini, Cameron McKinnon, Carol Chen, Catherine Olsson, Christopher Olah, Danny Hernandez, Dawn Drain, Deep Ganguli, Dustin Li, Eli Tran-Johnson, Ethan Perez, Jamie Kerr, Jared Mueller, Jeffrey Ladish, Joshua Landau, Kamal Ndousse, Kamile Lukosuite, Liane Lovitt, Michael Sellitto, Nelson Elhage, Nicholas Schiefer, Noemi Mercado, Nova DasSarma, Robert Lasenby, Robin Larson, Sam Ringer, Scott Johnston, Shauna Kravec, Sheer El Showk, Stanislav Fort, Tamera Lanham, Timothy Telleen-Lawton, Tom Conerly, Tom Henighan, Tristan Hume, Samuel R. Bowman, Zac Hatfield-Dodds, Ben Mann, Dario Amodei, Nicholas Joseph, Sam McCandlish, Tom Brown and Jared Kaplan.</i></details>

- EleutherAI
  - **GPT-J-6B: 6B JAX-Based Transformer.** [[blog]](https://arankomatsuzaki.wordpress.com/2021/06/04/gpt-j/) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Open-purple) ![](https://img.shields.io/badge/2021.06-blue)

  - **GPT-NeoX-20B: An Open-Source Autoregressive Language Model.** [[paper]](https://aclanthology.org/2022.bigscience-1.9.pdf) [[blog]](https://blog.eleuther.ai/announcing-20b/) ![](https://img.shields.io/badge/ACL%202022%20Workshop-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Open-purple) ![](https://img.shields.io/badge/2022.02-blue)

    *Sid Black, Stella Biderman, Eric Hallahan, Quentin Anthony, Leo Gao, Laurence Golding, Horace He, Connor Leahy, Kyle McDonell, Jason Phang, Michael Pieler, USVSN Sai Prashanth, Shivanshu Purohit, Laria Reynolds, Jonathan Tow, Ben Wang, Samuel Weinbach.*

- Tsinghua University
  - **CPM: A Large-scale Generative Chinese Pre-trained Language Model.** [[paper]](https://www.sciencedirect.com/science/article/pii/S266665102100019X/pdfft?md5=c9c82038f6f237b8708270ed0fbbf80b&pid=1-s2.0-S266665102100019X-main.pdf) ![](https://img.shields.io/badge/AI%20Open%202021-orange) ![](https://img.shields.io/badge/Chinese-darkcyan) ![](https://img.shields.io/badge/Open-purple) ![](https://img.shields.io/badge/2020.12-blue)

    *Zhengyan Zhang, Xu Han, Hao Zhou, Pei Ke, Yuxian Gu, Deming Ye, Yujia Qin, Yusheng Su, Haozhe Ji, Jian Guan, Fanchao Qi, Xiaozhi Wang, Yanan Zheng, Guoyang Zeng, Huanqi Cao, Shengqi Chen, Daixuan Li, Zhenbo Sun, Zhiyuan Liu, Minlie Huang, Wentao Han, Jie Tang, Juanzi Li, Xiaoyan Zhu, Maosong Sun.*
  
  - **CPM-2: Large-scale Cost-effective Pre-trained Language Models.** [[paper]](https://www.sciencedirect.com/science/article/pii/S2666651021000310/pdfft?md5=46efc536c128aefd0ff69139f8627ddb&pid=1-s2.0-S2666651021000310-main.pdf) ![](https://img.shields.io/badge/AI%20Open%202021-orange) ![](https://img.shields.io/badge/Multilingual-darkcyan) ![](https://img.shields.io/badge/Open-purple) ![](https://img.shields.io/badge/2021.06-blue)

    *Zhengyan Zhang, Yuxian Gu, Xu Han, Shengqi Chen, Chaojun Xiao, Zhenbo Sun, Yuan Yao, Fanchao Qi, Jian Guan, Pei Ke, Yanzheng Cai, Guoyang Zeng, Zhixing Tan, Zhiyuan Liu, Minlie Huang, Wentao Han, Yang Liu, Xiaoyan Zhu, Maosong Sun.*

  - Chinese-Transformer-XL [[repo]](https://github.com/THUDM/Chinese-Transformer-XL) ![](https://img.shields.io/badge/Chinese-darkcyan) ![](https://img.shields.io/badge/Open-purple) ![](https://img.shields.io/badge/2021.03-blue)
  
  - **EVA: An Open-Domain Chinese Dialogue System with Large-Scale Generative Pre-Training.** [[paper]](https://arxiv.org/pdf/2108.01547) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/Chinese-darkcyan) ![](https://img.shields.io/badge/Open-purple) ![](https://img.shields.io/badge/2021.08-blue)

    *Hao Zhou, Pei Ke, Zheng Zhang, Yuxian Gu, Yinhe Zheng, Chujie Zheng, Yida Wang, Chen Henry Wu, Hao Sun, Xiaocong Yang, Bosi Wen, Xiaoyan Zhu, Minlie Huang, Jie Tang.*
  
  - **EVA2.0: Investigating Open-Domain Chinese Dialogue Systems with Large-Scale Pre-Training.** [[paper]](https://arxiv.org/pdf/2203.09313) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/Chinese-darkcyan) ![](https://img.shields.io/badge/Open-purple) ![](https://img.shields.io/badge/2022.03-blue)

    *Yuxian Gu, Jiaxin Wen, Hao Sun, Yi Song, Pei Ke, Chujie Zheng, Zheng Zhang, Jianzhu Yao, Xiaoyan Zhu, Jie Tang, Minlie Huang.*
  
  - **GLM: General Language Model Pretraining with Autoregressive Blank Infilling.** [[paper]](https://aclanthology.org/2022.acl-long.26.pdf) ![](https://img.shields.io/badge/ACL%202022-orange) ![](https://img.shields.io/badge/English%20or%20Chinese-darkcyan) ![](https://img.shields.io/badge/Limited-purple) ![](https://img.shields.io/badge/2021.03-blue)

    *Zhengxiao Du, Yujie Qian, Xiao Liu, Ming Ding, Jiezhong Qiu, Zhilin Yang, Jie Tang.*

  - **GLM-130B: An Open Bilingual Pre-trained Model.** [[paper]](https://arxiv.org/pdf/2210.02414) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/Multilingual-darkcyan) ![](https://img.shields.io/badge/Open-purple) ![](https://img.shields.io/badge/2022.10-blue)

    *Aohan Zeng, Xiao Liu, Zhengxiao Du, Zihan Wang, Hanyu Lai, Ming Ding, Zhuoyi Yang, Yifan Xu, Wendi Zheng, Xiao Xia, Weng Lam Tam, Zixuan Ma, Yufei Xue, Jidong Zhai, Wenguang Chen, Peng Zhang, Yuxiao Dong, Jie Tang.*

- IDEA
  - **Fengshenbang 1.0: Being the Foundation of Chinese Cognitive Intelligence.** [[paper]](https://arxiv.org/pdf/2209.02970) [[blog]](https://idea.edu.cn/fengshenbang-lm.html) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/Open-purple) ![](https://img.shields.io/badge/2022.09-blue)

    *Junjie Wang, Yuxiang Zhang, Lin Zhang, Ping Yang, Xinyu Gao, Ziwei Wu, Xiaoqun Dong, Junqing He, Jianheng Zhuo, Qi Yang, Yongfeng Huang, Xiayu Li, Yanghan Wu, Junyu Lu, Xinyu Zhu, Weifeng Chen, Ting Han, Kunhao Pan, Rui Wang, Hao Wang, Xiaojun Wu, Zhongshen Zeng, Chongpei Chen, Ruyi Gan and Jiaxing Zhang.*
    - Wenzhong ![](https://img.shields.io/badge/Chinese-darkcyan)
    - Randeng ![](https://img.shields.io/badge/Chinese-darkcyan)
    - Yuyuan ![](https://img.shields.io/badge/English-darkcyan)
    - Zhouwenwang ![](https://img.shields.io/badge/Chinese-darkcyan)

- Huawei
  - **PanGu-α: Large-scale Autoregressive Pretrained Chinese Language Models with Auto-parallel Computation.** [[paper]](https://arxiv.org/pdf/2104.12369) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/Chinese-darkcyan) ![](https://img.shields.io/badge/Open-purple) ![](https://img.shields.io/badge/2021.04-blue)

    <details><summary>Show Authors</summary><i>Wei Zeng, Xiaozhe Ren, Teng Su, Hui Wang, Yi Liao, Zhiwei Wang, Xin Jiang, ZhenZhang Yang, Kaisheng Wang, Xiaoda Zhang, Chen Li, Ziyan Gong, Yifan Yao, Xinjing Huang, Jun Wang, Jianfeng Yu, Qi Guo, Yue Yu, Yan Zhang, Jin Wang, Hengtao Tao, Dasen Yan, Zexuan Yi, Fang Peng, Fangqing Jiang, Han Zhang, Lingfeng Deng, Yehong Zhang, Zhe Lin, Chao Zhang, Shaojie Zhang, Mingyue Guo, Shanzhi Gu, Gaojun Fan, Yaowei Wang, Xuefeng Jin, Qun Liu and Yonghong Tian.</i></details>
  
  - **PanGu-Bot: Efficient Generative Dialogue Pre-training from Pre-trained Language Model.** [[paper]](https://arxiv.org/pdf/2203.17090) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/Chinese-darkcyan) ![](https://img.shields.io/badge/Closed-purple) ![](https://img.shields.io/badge/2022.03-blue)

    *Fei Mi, Yitong Li, Yulong Zeng, Jingyan Zhou, Yasheng Wang, Chuanfei Xu, Lifeng Shang, Xin Jiang, Shiqi Zhao and Qun Liu.*

- Inspur
  - **Yuan 1.0: Large-Scale Pre-trained Language Model in Zero-Shot and Few-Shot Learning.** [[paper]](https://arxiv.org/pdf/2110.04725) [[blog]](https://www.inspur.com/lcjtww/445068/445237/2588228/index.html) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/Chinese-darkcyan) ![](https://img.shields.io/badge/Limited-purple) ![](https://img.shields.io/badge/2021.09-blue)

    *Shaohua Wu, Xudong Zhao, Tong Yu, Rongguo Zhang, Chong Shen, Hongli Liu, Feng Li, Hong Zhu, Jiangang Luo, Liang Xu and Xuanwei Zhang.*

- WeChat AI
  - **WeLM: A Well-Read Pre-trained Language Model for Chinese.** [[paper]](https://arxiv.org/pdf/2209.10372) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/Chinese-darkcyan) ![](https://img.shields.io/badge/Limited-purple) ![](https://img.shields.io/badge/2022.09-blue)

    *Hui Su, Xiao Zhou, Houjin Yu, Yuwen Chen, Zilin Zhu, Yang Yu and Jie Zhou.*

## Analysis
### Comprehensive
- **Holistic Evaluation of Language Models.** [[paper]](https://arxiv.org/pdf/2211.09110) [[blog]](https://crfm.stanford.edu/2022/11/17/helm.html) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2022.11-blue)

  <details><summary>Show Authors</summary><i>Percy Liang, Rishi Bommasani, Tony Lee, Dimitris Tsipras, Dilara Soylu, Michihiro Yasunaga, Yian Zhang, Deepak Narayanan, Yuhuai Wu, Ananya Kumar, Benjamin Newman, Binhang Yuan, Bobby Yan, Ce Zhang, Christian Cosgrove, Christopher D. Manning, Christopher Ré, Diana Acosta-Navas, Drew A. Hudson, Eric Zelikman, Esin Durmus, Faisal Ladhak, Frieda Rong, Hongyu Ren, Huaxiu Yao, Jue Wang, Keshav Santhanam, Laurel Orr, Lucia Zheng, Mert Yuksekgonul, Mirac Suzgun, Nathan Kim, Neel Guha, Niladri Chatterji, Omar Khattab, Peter Henderson, Qian Huang, Ryan Chi, Sang Michael Xie, Shibani Santurkar, Surya Ganguli, Tatsunori Hashimoto, Thomas Icard, Tianyi Zhang, Vishrav Chaudhary, William Wang, Xuechen Li, Yifan Mai, Yuhui Zhang and Yuta Koreeda.</i></details>

  > Benchmark 30 prominent language models across a wide range of scenarios and for a broad range of metrics to elucidate their capabilities and risks.

- **On the Dangers of Stochastic Parrots: Can Language Models Be Too Big? 🦜** [[paper]](https://dl.acm.org/doi/pdf/10.1145/3442188.3445922) ![](https://img.shields.io/badge/FAccT%202021-orange) ![](https://img.shields.io/badge/2021.03-blue)

  *Emily M. Bender, Timnit Gebru, Angelina McMillan-Major and Shmargaret Shmitchell.*
  > Identified a wide variety of costs and risks associated with the rush for ever larger LMs, including: environmental costs, financial costs, opportunity cost and the risk of substantial harms.

- **TruthfulQA: Measuring How Models Mimic Human Falsehoods.** [[paper]](https://aclanthology.org/2022.acl-long.229.pdf) ![](https://img.shields.io/badge/ACL%202022-orange) ![](https://img.shields.io/badge/2021.09-blue)

  *Stephanie Lin, Jacob Hilton and Owain Evans.*
  > Models generated many false answers that mimic popular misconceptions and have the potential to deceive humans. The largest models were generally the least truthful.

- **How Much Knowledge Can You Pack Into the Parameters of a Language Model?** [[paper]](https://aclanthology.org/2020.emnlp-main.437.pdf) ![](https://img.shields.io/badge/EMNLP%202020-orange) ![](https://img.shields.io/badge/2020.02-blue)

  *Adam Roberts, Colin Raffel and Noam Shazeer.*
  > The maximum-likelihood objective used to train our model provides no guarantees as to whether a model will learn a fact or not. This makes it difficult to ensure that the model obtains specific knowledge over the course of pre-training and prevents us from explicitly updating or removing knowledge from a pre-trained model.

- **On the Opportunities and Risks of Foundation Models.** [[paper]](https://arxiv.org/pdf/2108.07258) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2021.08-blue)

  <details><summary>Show Authors</summary><i>Rishi Bommasani, Drew A. Hudson, Ehsan Adeli, Russ Altman, Simran Arora, Sydney von Arx, Michael S. Bernstein, Jeannette Bohg, Antoine Bosselut, Emma Brunskill, Erik Brynjolfsson, Shyamal Buch, Dallas Card, Rodrigo Castellon, Niladri Chatterji, Annie Chen, Kathleen Creel, Jared Quincy Davis, Dora Demszky, Chris Donahue, Moussa Doumbouya, Esin Durmus, Stefano Ermon, John Etchemendy, Kawin Ethayarajh, Li Fei-Fei, Chelsea Finn, Trevor Gale, Lauren Gillespie, Karan Goel, Noah Goodman, Shelby Grossman, Neel Guha, Tatsunori Hashimoto, Peter Henderson, John Hewitt, Daniel E. Ho, Jenny Hong, Kyle Hsu, Jing Huang, Thomas Icard, Saahil Jain, Dan Jurafsky, Pratyusha Kalluri, Siddharth Karamcheti, Geoff Keeling, Fereshte Khani, Omar Khattab, Pang Wei Koh, Mark Krass, Ranjay Krishna, Rohith Kuditipudi, Ananya Kumar, Faisal Ladhak, Mina Lee, Tony Lee, Jure Leskovec, Isabelle Levent, Xiang Lisa Li, Xuechen Li, Tengyu Ma, Ali Malik, Christopher D. Manning, Suvir Mirchandani, Eric Mitchell, Zanele Munyikwa, Suraj Nair, Avanika Narayan, Deepak Narayanan, Ben Newman, Allen Nie, Juan Carlos Niebles, Hamed Nilforoshan, Julian Nyarko, Giray Ogut, Laurel Orr, Isabel Papadimitriou, Joon Sung Park, Chris Piech, Eva Portelance, Christopher Potts, Aditi Raghunathan, Rob Reich, Hongyu Ren, Frieda Rong, Yusuf Roohani, Camilo Ruiz, Jack Ryan, Christopher Ré, Dorsa Sadigh, Shiori Sagawa, Keshav Santhanam, Andy Shih, Krishnan Srinivasan, Alex Tamkin, Rohan Taori, Armin W. Thomas, Florian Tramèr, Rose E. Wang, William Wang , Bohan Wu, Jiajun Wu, Yuhuai Wu, Sang Michael Xie, Michihiro Yasunaga, Jiaxuan You, Matei Zaharia, Michael Zhang, Tianyi Zhang, Xikun Zhang, Yuhui Zhang, Lucia Zheng, Kaitlyn Zhou and Percy Liang.</i></details>

  > This report provides a thorough account of the opportunities and risks of foundation models, ranging from their capabilities and technical principles to their applications and societal impact.

### Hallucination & Disinformation
- **Survey of Hallucination in Natural Language Generation.** [[paper]](https://dl.acm.org/doi/pdf/10.1145/3571730) ![](https://img.shields.io/badge/CSUR%202022-orange) ![](https://img.shields.io/badge/2022.02-blue)

  <details><summary>Show Authors</summary><i>Percy Liang, Rishi Bommasani, Tony Lee, Dimitris Tsipras, Dilara Soylu, Michihiro Yasunaga, Yian Zhang, Deepak Narayanan, Yuhuai Wu, Ananya Kumar, Benjamin Newman, Binhang Yuan, Bobby Yan, Ce Zhang, Christian Cosgrove, Christopher D. Manning, Christopher Ré, Diana Acosta-Navas, Drew A. Hudson, Eric Zelikman, Esin Durmus, Faisal Ladhak, Frieda Rong, Hongyu Ren, Huaxiu Yao, Jue Wang, Keshav Santhanam, Laurel Orr, Lucia Zheng, Mert Yuksekgonul, Mirac Suzgun, Nathan Kim, Neel Guha, Niladri Chatterji, Omar Khattab, Peter Henderson, Qian Huang, Ryan Chi, Sang Michael Xie, Shibani Santurkar, Surya Ganguli, Tatsunori Hashimoto, Thomas Icard, Tianyi Zhang, Vishrav Chaudhary, William Wang, Xuechen Li, Yifan Mai, Yuhui Zhang and Yuta Koreeda.</i></details>

  > Benchmark 30 prominent language models across a wide range of scenarios and for a broad range of metrics to elucidate their capabilities and risks.

- **On the Origin of Hallucinations in Conversational Models: Is it the Datasets or the Models?** [[paper]](https://aclanthology.org/2022.naacl-main.387.pdf) ![](https://img.shields.io/badge/NAACL%202022-orange) ![](https://img.shields.io/badge/2022.04-blue)

  *Nouha Dziri, Sivan Milton, Mo Yu, Osmar Zaiane and Siva Reddy.*
  > Reveals that the standard benchmarks consist of >60% hallucinated responses, leading to models that not only hallucinate but even amplify hallucinations..

- **Generative Language Models and Automated Influence Operations: Emerging Threats and Potential Mitigations.** [[paper]](https://arxiv.org/pdf/2301.04246) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.01-blue)

  *Josh A. Goldstein, Girish Sastry, Micah Musser, Renee DiResta, Matthew Gentzel and Katerina Sedova.*
  > This report aims to assess: how might language models change influence operations, and what steps can be taken to mitigate these threats? This task is inherently speculative, as both AI and influence operations are changing quickly.

- **Forecasting Potential Misuses of Language Models for Disinformation Campaigns—and How to Reduce Risk.** [[blog]](https://openai.com/blog/forecasting-misuse/) ![](https://img.shields.io/badge/2023.01-blue)
  > OpenAI researchers collaborated with Georgetown University’s Center for Security and Emerging Technology and the Stanford Internet Observatory to investigate how large language models might be misused for disinformation purposes.

- **ChatGPT Wrote a Terrible Gizmodo Article.** [[blog]](https://gizmodo.com/chatgpt-gizmodo-artificial-intelligence-openai-media-1849876066) ![](https://img.shields.io/badge/2022.12-blue)
  > ChatGPT kept including incorrect information in its explainer—sometimes mixing up basic facts about the history of its own technology.

- **Temporary policy: ChatGPT is banned.** [[blog]](https://meta.stackoverflow.com/questions/421831/temporary-policy-chatgpt-is-banned) ![](https://img.shields.io/badge/2022.12-blue)
  > While the answers which ChatGPT produces have a high rate of being incorrect, they typically look like they might be good and the answers are very easy to produce.

### Biases & Toxicities
- **On Second Thought, Let's Not Think Step by Step! Bias and Toxicity in Zero-Shot Reasoning.** [[paper]](https://arxiv.org/pdf/2212.08061) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.12-blue)

  *Omar Shaikh, Hongxin Zhang, William Held, Michael Bernstein and Diyi Yang.*
  > Find that using zero-shot CoT reasoning in a prompt can significantly increase a model’s likelihood to produce undesirable output.

- **The Woman Worked as a Babysitter: On Biases in Language Generation.** [[paper]](https://aclanthology.org/D19-1339.pdf) ![](https://img.shields.io/badge/EMNLP%202019-orange) ![](https://img.shields.io/badge/2019.09-blue)

  *Emily Sheng, Kai-Wei Chang, Premkumar Natarajan and Nanyun Peng.*
  > A systematic study of biases in natural language generation (NLG) by analyzing text generated from prompts that contain mentions of different demographic groups.

- **RealToxicityPrompts: Evaluating Neural Toxic Degeneration in Language Models.** [[paper]](https://aclanthology.org/2020.findings-emnlp.301.pdf) ![](https://img.shields.io/badge/EMNLP%202020%20Findings-orange) ![](https://img.shields.io/badge/2020.09-blue)

  *Samuel Gehman, Suchin Gururangan, Maarten Sap, Yejin Choi and Noah A. Smith.*
  > Using RealToxicityPrompts, we find that pretrained LMs can degenerate into toxic text even from seemingly innocuous prompts.

- **OpenAI's new ChatGPT bot: 10 dangerous things it's capable of.** [[blog]](https://www.bleepingcomputer.com/news/technology/openais-new-chatgpt-bot-10-dangerous-things-its-capable-of/) ![](https://img.shields.io/badge/2022.12-blue)
  > As the erudite machinery turns into a viral sensation, humans have started to discover some of the AI's biases, like the desire to wipe out humanity.
### Security Risks
- **OpwnAI: AI That Can Save the Day or HACK it Away.** [[blog]](https://research.checkpoint.com/2022/opwnai-ai-that-can-save-the-day-or-hack-it-away/) ![](https://img.shields.io/badge/2022.12-blue)
  > AI models can be used to create a full infection flow, from spear-phishing to running a reverse shell.

- **OpwnAI : Cybercriminals Starting to Use ChatGPT.** [[blog]](https://research.checkpoint.com/2023/opwnai-cybercriminals-starting-to-use-chatgpt/) ![](https://img.shields.io/badge/2023.01-blue)
  > There are already instances of cybercriminals using OpenAI to develop malicious tools.

- **Security risks of ChatGPT and other AI text generators.** [[blog]](https://www.scmagazine.com/resource/emerging-technology/security-risks-of-chatgpt-and-other-ai-text-generators) ![](https://img.shields.io/badge/2023.01-blue)
  > Successfully asked ChatGPT to write a convincing phishing email and to create JavaScript that could be used to steal personal information.

- **The security threat of AI-powered cyberattacks.** [[paper]](https://www.traficom.fi/sites/default/files/media/publication/TRAFICOM_The_security_threat_of_AI-enabled_cyberattacks%202022-12-12_en_web.pdf) ![](https://img.shields.io/badge/2022.12-blue)

  *Matti Aksela, Samuel Marchal, Andrew Patel, Lina Rosenstedt and WithSecure.*
  > Investigate the security threat of AI-enabled cyberattacks by summarising current knowledge on the topic.

- **How hackers might be exploiting ChatGPT.** [[blog]](https://cybernews.com/security/hackers-exploit-chatgpt/) ![](https://img.shields.io/badge/2023.01-blue)
  > The viral AI chatbot ChatGPT might advise threat actors how to hack into networks with ease.

### LM Attacks
- **Extracting Training Data from Large Language Models.** [[paper]](https://arxiv.org/pdf/2012.07805) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2020.12-blue)

  *Nicholas Carlini, Florian Tramer, Eric Wallace, Matthew Jagielski, Ariel Herbert-Voss, Katherine Lee, Adam Roberts, Tom Brown, Dawn Song, Ulfar Erlingsson, Alina Oprea and Colin Raffel.*
  > This paper demonstrates that an adversary can perform a training data extraction attack to recover individual training examples by querying the language model.

- **Ignore Previous Prompt: Attack Techniques For Language Models.** [[paper]](https://openreview.net/pdf?id=qiaRo_7Zmug) ![](https://img.shields.io/badge/NeurIPS%202022%20Workshop-orange) ![](https://img.shields.io/badge/2022.11-blue)

  *Fábio Perez and Ian Ribeiro.*
  > Study prompt injection attacks against LLMs and propose a framework to explore such attacks; Investigate two specific attacks: goal hijacking and prompt leaking.

### Environment
- **Carbon Emissions and Large Neural Network Training.** [[paper]](https://arxiv.org/pdf/2104.10350) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2021.04-blue)

  *David Patterson, Joseph Gonzalez, Quoc Le, Chen Liang, Lluis-Miquel Munguia, Daniel Rothchild, David So, Maud Texier and Jeff Dean.*
  > Calculate the energy use and carbon footprint of several recent large models-T5, Meena, GShard, Switch Transformer, and GPT-3..

## Detection
### Survey
- **Automatic Detection of Machine Generated Text: A Critical Survey.** [[paper]](https://aclanthology.org/2020.coling-main.208.pdf) ![](https://img.shields.io/badge/COLING%202020-orange) ![](https://img.shields.io/badge/2020.11-blue)

  *Ganesh Jawahar, Muhammad Abdul-Mageed and Laks V.S. Lakshmanan.*

- **Machine Generated Text: A Comprehensive Survey of Threat Models and Detection Methods.** [[paper]](https://arxiv.org/pdf/2210.07321) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2022.10-blue)

  *Evan Crothers, Nathalie Japkowicz and Herna Viktor.*

- **Deepfake Text Detection: Limitations and Opportunities.** [[paper]](https://arxiv.org/pdf/2210.09421) ![](https://img.shields.io/badge/IEEE%20S&P%202023-orange) ![](https://img.shields.io/badge/2022.10-blue)

  *Jiameng Pu, Zain Sarwar, Sifat Muhammad Abdullah, Abdullah Rehman, Yoonjin Kim, Parantapa Bhattacharya, Mobin Javed and Bimal Viswanath.*

- **The Scicence of LLM-generated Text Detection.** [[paper]](https://drive.google.com/file/d/1U8oQNU4f-1c4hJG9vdFuV4xfa10mrKXC/view?usp=sharing) ![](https://img.shields.io/badge/2023.02-blue)

  *Ruixiang Tang, Yu-Neng Chuang and Xia Hu.*

### Human Detection
- **RoFT: A Tool for Evaluating Human Detection of Machine-Generated Text.** [[paper]](https://aclanthology.org/2020.emnlp-demos.25.pdf) ![](https://img.shields.io/badge/EMNLP%202020-orange) ![](https://img.shields.io/badge/2020.10-blue)

  *Liam Dugan, Daphne Ippolito, Arun Kirubarajan and Chris Callison-Burch.*
  > Develop the Real or Fake Text (RoFT) system, a novel application for simultaneously collecting quality annotations of machinegenerated text while allowing the public to assess and improve their skill at detecting machinegenerated text.

- **All That's 'Human' Is Not Gold: Evaluating Human Evaluation of Generated Text.** [[paper]](https://aclanthology.org/2021.acl-long.565.pdf) ![](https://img.shields.io/badge/ACL%202021-orange) ![](https://img.shields.io/badge/2021.06-blue)

  *Elizabeth Clark, Tal August, Sofia Serrano, Nikita Haduong, Suchin Gururangan and Noah A. Smith.*
  > Assess nonexperts’ ability to distinguish between humanand machine-authored text, and test three evaluator-training methods to see if we could improve people’s ability to identify machinegenerated text.

- **Real or Fake Text?: Investigating Human Ability to Detect Boundaries Between Human-Written and Machine-Generated Text.** [[paper]](https://arxiv.org/pdf/2212.12672) ![](https://img.shields.io/badge/AAAI%202023-orange) ![](https://img.shields.io/badge/2022.12-blue)

  *Liam Dugan, Daphne Ippolito, Arun Kirubarajan, Sherry Shi and Chris Callison-Burch.*
  > Analyze how a variety of variables (model size, decoding strategy, fine-tuning, prompt genre, etc.) affect human detection performance.

### Automatic Detection
- **Defending Against Neural Fake News.** [[paper]](https://proceedings.neurips.cc/paper/2019/file/3e9f0fc9b2f89e043bc6233994dfcf76-Paper.pdf) ![](https://img.shields.io/badge/NeurIPS%202019-orange) ![](https://img.shields.io/badge/2019.05-blue)

  *Rowan Zellers, Ari Holtzman, Hannah Rashkin, Yonatan Bisk, Ali Farhadi, Franziska Roesner and Yejin Choi.*
  > Present a model for controllable text generation called Grover. Find that the best way to detect neural fake news is to use a model that is also a generator.

- **GLTR: Statistical Detection and Visualization of Generated Text.** [[paper]](https://aclanthology.org/P19-3019.pdf) ![](https://img.shields.io/badge/ACL%202019-orange) ![](https://img.shields.io/badge/2019.06-blue)

  *Sebastian Gehrmann, Hendrik Strobelt and Alexander M. Rush.*
  > A Giant Language model Test Room. GLTR aims to both teach users what to be aware of when assessing whether a text is real, and to assist them in performing forensic analyses.

- **Real or Fake? Learning to Discriminate Machine from Human Generated Text.** [[paper]](https://arxiv.org/pdf/1906.03351) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2019.06-blue)

  *Anton Bakhtin, Sam Gross, Myle Ott, Yuntian Deng, Marc'Aurelio Ranzato and Arthur Szlam.*
  > Use Energy-based models to discriminate real text from text generated by the auto-regressive models.

- **The Limitations of Stylometry for Detecting Machine-Generated Fake News.** [[paper]](https://direct.mit.edu/coli/article-pdf/46/2/499/1847559/coli_a_00380.pdf) ![](https://img.shields.io/badge/Computational%20Linguistics%202020-orange) ![](https://img.shields.io/badge/2019.08-blue)

  *Tal Schuster, Roei Schuster, Darsh J Shah and Regina Barzilay.*
  > Examine the state-of-the-art stylometry model, and find it effective in preventing impersonation, but limited in detecting LM-generated misinformation.

- **Automatic Detection of Generated Text is Easiest when Humans are Fooled.** [[paper]](https://aclanthology.org/2020.acl-main.164.pdf) ![](https://img.shields.io/badge/ACL%202020-orange) ![](https://img.shields.io/badge/2019.11-blue)

  *Daphne Ippolito, Daniel Duckworth, Chris Callison-Burch and Douglas Eck.*
  > A comprehensive study of generated text detection systems’ sensitivity to model structure, decoding strategy, and excerpt length.

- **Neural Deepfake Detection with Factual Structure of Text.** [[paper]](https://aclanthology.org/2020.emnlp-main.193.pdf) ![](https://img.shields.io/badge/EMNLP%202020-orange) ![](https://img.shields.io/badge/2020.10-blue)

  *Wanjun Zhong, Duyu Tang, Zenan Xu, Ruize Wang, Nan Duan, Ming Zhou, Jiahai Wang and Jian Yin.*
  > Propose a graph-based model that utilizes the factual structure of a document for deepfake detection of text.

- **Feature-based detection of automated language models: tackling GPT-2, GPT-3 and Grover.** [[paper]](https://peerj.com/articles/cs-443.pdf) ![](https://img.shields.io/badge/PeerJ%20Computer%20Science%202021-orange) ![](https://img.shields.io/badge/2021.04-blue)

  *Leon Fröhling and Arkaitz Zubiaga.*
  > A feature-based detection approach relies on features that discriminate between human and machine text by modelling properties and dimensions in which both types of text differ.

- **Detecting Bot-Generated Text by Characterizing Linguistic Accommodation in Human-Bot Interactions.** [[paper]](https://aclanthology.org/2021.findings-acl.286.pdf) ![](https://img.shields.io/badge/ACL%202021%20Findings-orange) ![](https://img.shields.io/badge/2021.06-blue)

  *Paras Bhatt and Anthony Rios.*
  > Show that bot-generated text detection methods are more robust across datasets and models if we use information about how people respond to it rather than using the bot’s text directly.

- **Unsupervised and Distributional Detection of Machine-Generated Text.** [[paper]](https://arxiv.org/pdf/2111.02878) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2021.11-blue)

  *Matthias Gallé, Jos Rozen, Germán Kruszewski and Hady Elsahar.*
  > Propose a method to detect those machine-generated documents leveraging repeated higher-order n-grams, which we show over-appear in machine-generated text as compared to human ones.

- **Adversarial Robustness of Neural-Statistical Features in Detection of Generative Transformers.** [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9892269) ![](https://img.shields.io/badge/IJCNN%202022-orange) ![](https://img.shields.io/badge/2022.03-blue)

  *Evan Crothers, Nathalie Japkowicz, Herna Viktor and Paula Branco.*
  > Assess each model’s relative performance at classifying computer-generated text. Evaluat models for robustness in the presence of text adversarial attacks.

- **Cross-Domain Detection of GPT-2-Generated Technical Text.** [[paper]](https://aclanthology.org/2022.naacl-main.88.pdf) ![](https://img.shields.io/badge/NAACL%202022-orange) ![](https://img.shields.io/badge/2022.07-blue)

  *Juan Rodriguez, Todd Hay, David Gros, Zain Shamsi and Ravi Srinivasan.*
  > Find that RoBERTa-based detectors can be successfully adapted from one scientific discipline (physics) to another (biomedicine), requiring relatively small amounts of in-domain labeled data.

- **Automatic Detection of Machine Generated Texts: Need More Tokens.** [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9983964) ![](https://img.shields.io/badge/IVMEM%202022-orange) ![](https://img.shields.io/badge/2022.09-blue)

  *Paras Bhatt and Anthony Rios.*
  > Present a dataset for Russian language and conduct a set of learning experiments to build accurate machine-generated text detectors for both English and Russian languages.

- **Threat Scenarios and Best Practices to Detect Neural Fake News.** [[paper]](https://aclanthology.org/2022.coling-1.106.pdf) ![](https://img.shields.io/badge/COLING%202022-orange) ![](https://img.shields.io/badge/2022.10-blue)

  *Artidoro Pagnoni, Martin Graciarena and Yulia Tsvetkov.*
  > Provide an assessment of the current landscape of generated text detection and identify three primary threat scenarios. Establish the minimax strategies that minimize the worst case scenario for the detector.

- **CoCo: Coherence-Enhanced Machine-Generated Text Detection Under Data Limitation With Contrastive Learning.** [[paper]](https://arxiv.org/pdf/2212.10341) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2022.12-blue)

  *Xiaoming Liu, Zhaohan Zhang, Yichen Wang, Yu Lan and Chao Shen.*
  > Present a coherence-based contrastive learning model named CoCo to detect the possible machine-generated text under low-resource scenario.

- **How Close is ChatGPT to Human Experts? Comparison Corpus, Evaluation, and Detection.** [[paper]](https://arxiv.org/pdf/2301.07597) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.01-blue)

  *Biyang Guo, Xin Zhang, Ziyuan Wang, Minqi Jiang, Jinran Nie, Yuxuan Ding, Jianwei Yue and Yupeng Wu.*
  > Collect dataset the Human ChatGPT Comparison Corpus (HC3) and build three different detection systems to detect whether a certain text is generated by ChatGPT or humans.

### Benchmark
- **TURINGBENCH: A Benchmark Environment for Turing Test in the Age of Neural Text Generation.** [[paper]](https://aclanthology.org/2021.findings-emnlp.172.pdf) ![](https://img.shields.io/badge/EMNLP%202021%20Findings-orange) ![](https://img.shields.io/badge/2021.09-blue)

  *Adaku Uchendu, Zeyu Ma, Thai Le, Rui Zhang and Dongwon Lee.*
  > TuringBench is a benchmark environment that contains: (1)Benchmark tasks- Turing Test (i.e., human vs. machine) and Authorship Attribution: (i.e., who is the author of this texts?) (2) Datasets (Binary and Multi-class settings) (3) Website with leaderboard.

- **A Benchmark Corpus for the Detection of Automatically Generated Text in Academic Publications.** [[paper]](http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.501.pdf) ![](https://img.shields.io/badge/LREC%202022-orange) ![](https://img.shields.io/badge/2022.02-blue)

  *Vijini Liyanage, Davide Buscaldi and Adeline Nazarenko.*
  > Propose two datasets comprised of artificially generated research content: a completely synthetic dataset and a partial text substitution dataset.

### Tracing Text Provenance & Watermarking
- **Adversarial Watermarking Transformer: Towards Tracing Text Provenance with Data Hiding.** [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9519400) ![](https://img.shields.io/badge/S&P%202021-orange) ![](https://img.shields.io/badge/2020.09-blue)

  *Sahar Abdelnabi and Mario Fritz.*

- **Tracing Text Provenance via Context-Aware Lexical Substitution.** [[paper]](https://ojs.aaai.org/index.php/AAAI/article/download/21415/21164) ![](https://img.shields.io/badge/AAAI%202022-orange) ![](https://img.shields.io/badge/2021.12-blue)

  *Xi Yang, Jie Zhang, Kejiang Chen, Weiming Zhang, Zehua Ma, Feng Wang and Nenghai Yu.*

- **On Information Hiding in Natural Language Systems.** [[paper]](https://journals.flvc.org/FLAIRS/article/download/130602/133919/233024) ![](https://img.shields.io/badge/FLAIRS%202022-orange) ![](https://img.shields.io/badge/2022.03-blue)

  *Geetanjali Bihani, Julia Taylor Rayz.*

- **DeepHider: A Covert NLP Watermarking Framework Based on Multi-task Learning.** [[paper]](https://arxiv.org/pdf/2208.04676) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2022.08-blue)

  *Long Dai, Jiarong Mao, Xuefeng Fan and Xiaoyi Zhou.*

### Other Related Work
- **MAUVE: Measuring the Gap Between Neural Text and Human Text using Divergence Frontiers.** [[paper]](https://proceedings.neurips.cc/paper/2021/file/260c2432a0eecc28ce03c10dadc078a4-Paper.pdf) ![](https://img.shields.io/badge/NeurIPS%202021-orange) ![](https://img.shields.io/badge/2021.02-blue)

  *Krishna Pillutla, Swabha Swayamdipta, Rowan Zellers, John Thickstun, Sean Welleck, Yejin Choi and Zaid Harchaoui.*
  > Develop MAUVE, a comparison measure for open-ended text generation, which directly compares the learnt distribution from a text generation model to the distribution of human-written text using divergence frontiers.

- **Is GPT-3 Text Indistinguishable from Human Text? Scarecrow: A Framework for Scrutinizing Machine Text.** [[paper]](https://aclanthology.org/2022.acl-long.501.pdf) ![](https://img.shields.io/badge/ACL%202022-orange) ![](https://img.shields.io/badge/2021.07-blue)

  *Yao Dou, Maxwell Forbes, Rik Koncel-Kedziorski, Noah A. Smith and Yejin Choi.*
  > Develop Scarecrow, a methodology for eliciting categorical judgements of errors in machine-generated text from crowd workers. Quantify measurable gaps between human authored text and generations from models of several sizes.

- **Unraveling the Mystery of Artifacts in Machine Generated Text.** [[paper]](http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.744.pdf) ![](https://img.shields.io/badge/LREC%202022-orange) ![](https://img.shields.io/badge/2022.06-blue)

  *Jiashu Pu, Ziyi Huang, Yadong Xi, Guandan Chen, Weijie Chen and Rongsheng Zhang.*
  > Reveal characteristics and possible manifestations of artifacts. Locate artifacts mainly based on the performance variation of the classifier against different corruptions.
