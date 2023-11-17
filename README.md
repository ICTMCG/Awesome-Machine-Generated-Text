# Awesome Machine Generated Text

## TOC
- [Resource List about Machine Generated Text](#awesome-machine-generated-text)
  - [Large Scale Pre-training for Language Generation](#large-scale-pre-training-for-language-generation)
  - [Analysis ![](https://img.shields.io/badge/Building-red)](#analysis)
    <!-- - [Comprehensive](#comprehensive)
    - [Hallucination & Disinformation](#hallucination--disinformation)
    - [Bias & Toxicity](#bias--toxicity)
    - [Security Risk](#security-risk)
    - [LM Attack](#lm-attack)
    - [Environment](#environment) -->
  - [Detection](#detection)
    - [Papers](#papers)
      - [Survey](#survey)
      - [Human Detection](#human-detection)
      - [Automatic Detection](#automatic-detection)
      - [Detector Attack](#detector-attack)
      - [Benchmark](#benchmark)
      - [Tracing Text Provenance & Watermarking](#tracing-text-provenance--watermarking)
      - [Other Related Work](#other-related-work)
    - [Demos & Products](#demos--products)
    - [Datasets](#datasets)
    - [Shared Tasks](#shared-tasks)

## Large Scale Pre-training for Language Generation
> **Note:** #params > 1B only

- OpenAI
  - (GPT-2) **Language Models are Unsupervised Multitask Learners.** [[paper]](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) [[blog]](https://openai.com/blog/better-language-models/) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/English-darkcyan) ![](https://img.shields.io/badge/Open-purple) ![](https://img.shields.io/badge/2019.02-blue)

    *Alec Radford, Jeffrey Wu, Rewon Child, David Luan, Dario Amodei and Ilya Sutskever.*

  - (GPT-3) **Language Models are Few-Shot Learners.** [[paper]](https://proceedings.neurips.cc/paper/2020/file/1457c0d6bfcb4967418bfb8ac142f64a-Paper.pdf) ![](https://img.shields.io/badge/NeurIPS%202020-orange) ![](https://img.shields.io/badge/Multilingual-darkcyan) ![](https://img.shields.io/badge/Limited-purple) ![](https://img.shields.io/badge/2020.05-blue)

    <details><summary>Show Authors</summary><i>Tom B. Brown, Benjamin Mann, Nick Ryder, Melanie Subbiah, Jared Kaplan, Prafulla Dhariwal, Arvind Neelakantan, Pranav Shyam, Girish Sastry, Amanda Askell, Sandhini Agarwal, Ariel Herbert-Voss, Gretchen Krueger, Tom Henighan, Rewon Child, Aditya Ramesh, Daniel M. Ziegler, Jeffrey Wu, Clemens Winter, Christopher Hesse, Mark Chen, Eric Sigler, Mateusz Litwin, Scott Gray, Benjamin Chess, Jack Clark, Christopher Berner, Sam McCandlish, Alec Radford, Ilya Sutskever and Dario Amodei.</i></details>

  - **WebGPT: Browser-assisted question-answering with human feedback.** [[paper]](https://arxiv.org/pdf/2112.09332) [[blog]](https://openai.com/blog/webgpt/) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/Multilingual-darkcyan) ![](https://img.shields.io/badge/Closed-purple) ![](https://img.shields.io/badge/2021.12-blue)

    *Reiichiro Nakano, Jacob Hilton, Suchir Balaji, Jeff Wu, Long Ouyang, Christina Kim, Christopher Hesse, Shantanu Jain, Vineet Kosaraju, William Saunders, Xu Jiang, Karl Cobbe, Tyna Eloundou, Gretchen Krueger, Kevin Button, Matthew Knight, Benjamin Chess and John Schulman.*

  - (InstructGPT) **Training language models to follow instructions with human feedback.** [[paper]](https://arxiv.org/pdf/2203.02155) [[blog]](https://openai.com/blog/instruction-following/) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/Multilingual-darkcyan) ![](https://img.shields.io/badge/Limited-purple) ![](https://img.shields.io/badge/2022.01-blue)

    *Long Ouyang, Jeff Wu, Xu Jiang, Diogo Almeida, Carroll L. Wainwright, Pamela Mishkin, Chong Zhang, Sandhini Agarwal, Katarina Slama, Alex Ray, John Schulman, Jacob Hilton, Fraser Kelton, Luke Miller, Maddie Simens, Amanda Askell, Peter Welinder, Paul Christiano, Jan Leike and Ryan Lowe.*

  - **ChatGPT: Optimizing Language Models for Dialogue.** [[blog]](https://openai.com/blog/chatgpt/) ![](https://img.shields.io/badge/Multilingual-darkcyan) ![](https://img.shields.io/badge/Limited-purple) ![](https://img.shields.io/badge/2022.11-blue)

  - (GPT-4) **GPT-4 Technical Report.** [[paper]](https://cdn.openai.com/papers/gpt-4.pdf) [[blog]](https://openai.com/product/gpt-4) [[blog]](https://openai.com/research/gpt-4) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/Multilingual-darkcyan) ![](https://img.shields.io/badge/Limited-purple) ![](https://img.shields.io/badge/2023.03-blue)

    *OpenAI.*

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

  - **LLaMA: Open and Efficient Foundation Language Models.** [[paper]](https://research.facebook.com/file/1574548786327032/LLaMA--Open-and-Efficient-Foundation-Language-Models.pdf) [[blog]](https://ai.facebook.com/blog/large-language-model-llama-meta-ai/) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/Multilingual-darkcyan) ![](https://img.shields.io/badge/Open-purple) ![](https://img.shields.io/badge/2023.02-blue)

    *Hugo Touvron, Thibaut Lavril, Gautier Izacard, Xavier Martinet, Marie-Anne Lachaux, Timothée Lacroix, Baptiste Rozière, Naman Goyal, Eric Hambro, Faisal Azhar, Aurelien Rodriguez, Armand Joulin, Edouard Grave and Guillaume Lample.*

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

  - **GLM-130B: An Open Bilingual Pre-trained Model.** [[paper]](https://openreview.net/pdf?id=-Aw0rrrPUF) ![](https://img.shields.io/badge/ICLR%202023-orange) ![](https://img.shields.io/badge/Multilingual-darkcyan) ![](https://img.shields.io/badge/Open-purple) ![](https://img.shields.io/badge/2022.10-blue)

    *Aohan Zeng, Xiao Liu, Zhengxiao Du, Zihan Wang, Hanyu Lai, Ming Ding, Zhuoyi Yang, Yifan Xu, Wendi Zheng, Xiao Xia, Weng Lam Tam, Zixuan Ma, Yufei Xue, Jidong Zhai, Wenguang Chen, Zhiyuan Liu, Peng Zhang, Yuxiao Dong and Jie Tang.*

  - **ChatGLM.** [[blog]](https://chatglm.cn/blog) ![](https://img.shields.io/badge/Multilingual-darkcyan) ![](https://img.shields.io/badge/Open-purple) ![](https://img.shields.io/badge/2023.03-blue)

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
<details><summary>Preview</summary>

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

### Bias & Toxicity
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
### Security Risk
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

### LM Attack
- **Extracting Training Data from Large Language Models.** [[paper]](https://arxiv.org/pdf/2012.07805) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2020.12-blue)

  *Nicholas Carlini, Florian Tramer, Eric Wallace, Matthew Jagielski, Ariel Herbert-Voss, Katherine Lee, Adam Roberts, Tom Brown, Dawn Song, Ulfar Erlingsson, Alina Oprea and Colin Raffel.*
  > This paper demonstrates that an adversary can perform a training data extraction attack to recover individual training examples by querying the language model.

- **Ignore Previous Prompt: Attack Techniques For Language Models.** [[paper]](https://openreview.net/pdf?id=qiaRo_7Zmug) ![](https://img.shields.io/badge/NeurIPS%202022%20Workshop-orange) ![](https://img.shields.io/badge/2022.11-blue)

  *Fábio Perez and Ian Ribeiro.*
  > Study prompt injection attacks against LLMs and propose a framework to explore such attacks; Investigate two specific attacks: goal hijacking and prompt leaking.

### Environment
- **Carbon Emissions and Large Neural Network Training.** [[paper]](https://arxiv.org/pdf/2104.10350) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2021.04-blue)

  *David Patterson, Joseph Gonzalez, Quoc Le, Chen Liang, Lluis-Miquel Munguia, Daniel Rothchild, David So, Maud Texier and Jeff Dean.*
  > Calculate the energy use and carbon footprint of several recent large models-T5, Meena, GShard, Switch Transformer, and GPT-3.
</details>

## Detection
### Papers
#### Survey
- **Automatic Detection of Machine Generated Text: A Critical Survey.** [[paper]](https://aclanthology.org/2020.coling-main.208.pdf) ![](https://img.shields.io/badge/COLING%202020-orange) ![](https://img.shields.io/badge/2020.11-blue)

  *Ganesh Jawahar, Muhammad Abdul-Mageed and Laks V.S. Lakshmanan.*

- **在线社交网络文本内容对抗技术.** [[paper]](http://cjc.ict.ac.cn/online/onlinepaper/lxm-202286133102.pdf) ![](https://img.shields.io/badge/计算机学报%202022-orange) ![](https://img.shields.io/badge/2022.08-blue)

  *刘晓明, 张兆晗, 杨晨阳, 张宇辰, 沈超, 周亚东 and 管晓宏.*

- **Synthetic Text Detection: Systemic Literature Review.** [[paper]](https://arxiv.org/pdf/2210.06336) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2022.10-blue)

  *Jesus Guerrero, Izzat Alsmadi.*

- **Machine Generated Text: A Comprehensive Survey of Threat Models and Detection Methods.** [[paper]](https://arxiv.org/pdf/2210.07321) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2022.10-blue)

  *Evan Crothers, Nathalie Japkowicz and Herna Viktor.*

- **Deepfake Text Detection: Limitations and Opportunities.** [[paper]](https://arxiv.org/pdf/2210.09421) ![](https://img.shields.io/badge/S&P%202023-orange) ![](https://img.shields.io/badge/2022.10-blue)

  *Jiameng Pu, Zain Sarwar, Sifat Muhammad Abdullah, Abdullah Rehman, Yoonjin Kim, Parantapa Bhattacharya, Mobin Javed and Bimal Viswanath.*

- **The Science of Detecting LLM-Generated Texts.** [[paper]](https://arxiv.org/pdf/2303.07205) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.02-blue)

  *Ruixiang Tang, Yu-Neng Chuang and Xia Hu.*

- **To ChatGPT, or not to ChatGPT: That is the question!** [[paper]](https://arxiv.org/pdf/2304.01487) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.04-blue)

  *Alessandro Pegoraro, Kavita Kumari, Hossein Fereidooni and Ahmad-Reza Sadeghi.*

- **REVERSE TURING TEST IN THE AGE OF DEEPFAKE TEXTS.** [[paper]](https://pike.psu.edu/publications/thesis-adaku.pdf) ![](https://img.shields.io/badge/Dissertation-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Adaku Uchendu.*

- **The Age of Synthetic Realities: Challenges and Opportunities.** [[paper]](https://arxiv.org/pdf/2306.11503) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.06-blue)

  *João Phillipe Cardenuto, Jing Yang, Rafael Padilha, Renjie Wan, Daniel Moreira, Haoliang Li, Shiqi Wang, Fernanda Andaló, Sébastien Marcel and Anderson Rocha.*

- **Detecting Artificial Intelligence: A New Cyberarms Race Begins.** [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10206065) ![](https://img.shields.io/badge/Computer%202023-orange) ![](https://img.shields.io/badge/2023.08-blue)

  *Mark Campbell and Mlađan Jovanović.*

- **Detecting ChatGPT: A Survey of the State of Detecting ChatGPT-Generated Text.** [[paper]](https://arxiv.org/pdf/2309.07689.pdf) ![](https://img.shields.io/badge/RANLP%202023%20Workshop-orange) ![](https://img.shields.io/badge/2023.08-blue)

  *Mahdi Dhaini, Wessel Poelman and Ege Erdogan.*

- **A Survey on LLM-gernerated Text Detection: Necessity, Methods, and Future Directions.** [[paper]](https://arxiv.org/pdf/2310.14724.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Junchao Wu, Shu Yang, Runzhe Zhan, Yulin Yuan, Derek F. Wong and Lidia S. Chao.*

- **Towards Possibilities & Impossibilities of AI-generated Text Detection: A Survey.** [[paper]](https://arxiv.org/pdf/2310.15264.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Soumya Suvra Ghosal, Souradip Chakraborty, Jonas Geiping, Furong Huang, Dinesh Manocha and Amrit Singh Bedi.*

- **A Survey on Detection of LLMs-Generated Content.** [[paper]](https://arxiv.org/pdf/2310.15654.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Xianjun Yang, Liangming Pan, Xuandong Zhao, Haifeng Chen, Linda Petzold, William Yang Wang and Wei Cheng.*

#### Human Detection
- **Deepfake Bot Submissions to Federal Public Comment Websites Cannot Be Distinguished from Human Submissions.** [[paper]](https://techscience.org/a/2019121801/download) ![](https://img.shields.io/badge/Technology%20Science%202019-orange) ![](https://img.shields.io/badge/2019.12-blue)

  *Max Weiss.*
  > Generate and submit 1,001 deepfake comments regarding a Medicaid reform waiver to a federal public comment website. The human classification results are no better than would have been gotten by random guessing.

- **RoFT: A Tool for Evaluating Human Detection of Machine-Generated Text.** [[paper]](https://aclanthology.org/2020.emnlp-demos.25.pdf) ![](https://img.shields.io/badge/EMNLP%202020-orange) ![](https://img.shields.io/badge/2020.10-blue)

  *Liam Dugan, Daphne Ippolito, Arun Kirubarajan and Chris Callison-Burch.*
  > Develop the Real or Fake Text (RoFT) system, a novel application for simultaneously collecting quality annotations of machinegenerated text while allowing the public to assess and improve their skill at detecting machinegenerated text.

- **All That's 'Human' Is Not Gold: Evaluating Human Evaluation of Generated Text.** [[paper]](https://aclanthology.org/2021.acl-long.565.pdf) ![](https://img.shields.io/badge/ACL%202021-orange) ![](https://img.shields.io/badge/2021.06-blue)

  *Elizabeth Clark, Tal August, Sofia Serrano, Nikita Haduong, Suchin Gururangan and Noah A. Smith.*
  > Assess nonexperts’ ability to distinguish between humanand machine-authored text, and test three evaluator-training methods to see if we could improve people’s ability to identify machinegenerated text.

- **Human Heuristics for AI-Generated Language Are Flawed.** [[paper]](https://arxiv.org/pdf/2206.07271) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2022.06-blue)

  *Maurice Jakesch, Jeffrey Hancock and Mor Naaman.*
  > Study how humans discern whether verbal self-presentations were generated by AI. Show that human judgments of AI-generated language are handicapped by intuitive but flawed heuristics.

- **Real or Fake Text?: Investigating Human Ability to Detect Boundaries Between Human-Written and Machine-Generated Text.** [[paper]](https://arxiv.org/pdf/2212.12672) ![](https://img.shields.io/badge/AAAI%202023-orange) ![](https://img.shields.io/badge/2022.12-blue)

  *Liam Dugan, Daphne Ippolito, Arun Kirubarajan, Sherry Shi and Chris Callison-Burch.*
  > Analyze how a variety of variables (model size, decoding strategy, fine-tuning, prompt genre, etc.) affect human detection performance.

- **AI model GPT-3 (dis)informs us better than humans.** [[paper]](https://arxiv.org/pdf/2301.11924) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.01-blue)

  *Giovanni Spitale, Nikola Biller-Andorno and Federico Germani.*
  > Evaluate whether recruited individuals can distinguish disinformation from accurate information, and determine whether a tweet has been written by a Twitter user or by GPT-3.

- **Creating a Large Language Model of a Philosopher.** [[paper]](https://arxiv.org/pdf/2302.01339) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.02-blue)

  *Eric Schwitzgebel, David Schwitzgebel and Anna Strasser.*
  > Fine-tuned the GPT-3 on the corpus of Daniel Dennett, then asked it a series of philosophical questions. Ordinary research participants untrained in philosophy were at or near chance in distinguishing GPT-3’s answers from those of an “actual human philosopher”. .

- **Does Human Collaboration Enhance the Accuracy of Identifying LLM-Generated Deepfake Texts?** [[paper]](https://arxiv.org/pdf/2304.01002) ![](https://img.shields.io/badge/HCOMP%202023-orange) ![](https://img.shields.io/badge/2023.04-blue)

  *Adaku Uchendu, Jooyoung Lee, Hua Shen, Thai Le, Ting-Hao 'Kenneth' Huang and Dongwon Lee.*
  > Find that: (1) expert humans detect deepfake texts significantly better than non-expert humans, (2) synchronous teams on the Upwork detect deepfake texts significantly better than individuals, while asynchronous teams on the AMT detect deepfake texts weakly better than individuals, and (3) among various error categories, examining coherence and consistency in texts is useful in detecting deepfake texts.

- **Too Good to Be True? An Empirical Study of ChatGPT Capabilities for Academic Writing and Implications for Academic Misconduct.** [[paper]](https://www.researchgate.net/profile/Peter-Andre-Busch/publication/370106469_Too_Good_to_Be_True_An_Empirical_Study_of_ChatGPT_Capabilities_for_Academic_Writing_and_Implications_for_Academic_Misconduct/links/64403aa91b8d044c6335d7ce/Too-Good-to-Be-True-An-Empirical-Study-of-ChatGPT-Capabilities-for-Academic-Writing-and-Implications-for-Academic-Misconduct.pdf) ![](https://img.shields.io/badge/AMCIS%202023-orange) ![](https://img.shields.io/badge/2023.04-blue)

  *Peter André Busch and Geir Inge Hausvik.*
  > Ask 15 faculty members to assess a total of ten answers (two each) to an actual IS exam question, of which students wrote five, and ChatGPT generated five. Find that ChatGPT can generate answers of generally good quality that may pass as human-written text by examiners.

- **Game of Tones: Faculty detection of GPT-4 generated content in university assessments.** [[paper]](https://arxiv.org/pdf/2305.18081) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Mike Perkins, Jasper Roe, Darius Postma, James McGaughran and Don Hickerson.*
  > This study explores the robustness of university assessments against the use of Open AI's Generative Pre-Trained Transformer 4 (GPT-4) generated content and evaluates the ability of academic staff to detect its use when supported by the Turnitin Artificial Intelligence (AI) detection tool.

- **The Unseen A+ Student: Navigating the Impact of Large Language Models in the Classroom.** [[paper]](https://openreview.net/pdf?id=9ZKJLYg5EQ) ![](https://img.shields.io/badge/ICML%202023%20Workshop-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Matyas Bohacek.*
  > Collect a dataset of authentic high school coursework and generate their AI alternatives and text continuations using ChatGPT with 4.0, 3.5, and 3.5 Legacy backbones. Through a study involving student peers, we found that ChatGPT can quickly produce high-school-level coursework that peers consider better than human-written text, even in a low-resourced language like Czech. Moreover, show that the AI text detectors fail to identify these texts in Czech.

- **Can linguists distinguish between ChatGPT/AI and human writing?: A study of research ethics and academic publishing.** [[paper]](https://www.sciencedirect.com/science/article/pii/S2772766123000289/pdfft?md5=40e5bb4675092f7b0002d6a91c84d79b&pid=1-s2.0-S2772766123000289-main.pdf) ![](https://img.shields.io/badge/Research%20Methods%20in%20Applied%20Linguistics%202023-orange) ![](https://img.shields.io/badge/2023.08-blue)

  *J. Elliott Casal and Matt Kessler.*
  > Investigate: 1) the extent to which linguists/reviewers from top journals can distinguish AI- from human-generated writing, 2) what the basis of reviewers’ decisions are, and 3) the extent to which editors of top Applied Linguistics journals believe AI tools are ethical for research purposes.

- **Detection of GPT-4 Generated Text in Higher Education: Combining Academic Judgement and Software to Identify Generative AI Tool Misuse.** [[paper]](https://link.springer.com/content/pdf/10.1007/s10805-023-09492-6.pdf) ![](https://img.shields.io/badge/Journal%20of%20Academic%20Ethics%202023-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Mike Perkins, Jasper Roe, Darius Postma, James McGaughran and Don Hickerson.*
  > Explore the capability of academic staff assisted by the Turnitin Artificial Intelligence (AI) detection tool to identify the use of AI-generated content in university assessments.

- **ChatGPT versus Human Essayists: An Exploration of the Impact of Artificial Intelligence for Authorship and Academic Integrity in the Humanities.** [[paper]](https://www.researchsquare.com/article/rs-3483059/v1.pdf?c=1699337517000) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.11-blue)

  *Tom Revell, Will Yeadon, Glenn Cahilly-Bretzin, Isabella Clarke, George Manning, Jasmine Jones, Clare Mulley, Rafael Pascual, Natasha Bradley, Daniel Thomas and Francis Leneghan.*
  > Examine AI’s ability to write essays analysing Old English poetry; human markers assessed and attempted to distinguish them from authentic analyses of poetry by first-year undergraduate students in English at the University of Oxford.

#### Automatic Detection
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

- **Reverse Engineering Configurations of Neural Text Generation Models.** [[paper]](https://aclanthology.org/2020.acl-main.25.pdf) ![](https://img.shields.io/badge/ACL%202020-orange) ![](https://img.shields.io/badge/2020.04-blue)

  *Yi Tay, Dara Bahri, Che Zheng, Clifford Brunk, Donald Metzler and Andrew Tomkins.*
  > Propose the new task of distinguishing which of several variants (e.g., sampling methods, top-k probabilities, model architectures, etc.) of a given model generated some piece of text. Find that detectable artifacts are present and that different modeling choices can be inferred by looking at generated text alone.

- **TweepFake: about Detecting Deepfake Tweets.** [[paper]](https://journals.plos.org/plosone/article/file?id=10.1371/journal.pone.0251415&type=printable) ![](https://img.shields.io/badge/PLoS%20ONE%202021-orange) ![](https://img.shields.io/badge/2020.07-blue)

  *Tiziano Fagni, Fabrizio Falchi, Margherita Gambini, Antonio Martella and Maurizio Tesconi.*
  > Collect the first dataset of real deepfake tweets, TweepFake. Evaluate 13 deepfake text detection methods.

- **Identifying Automatically Generated Headlines using Transformers.** [[paper]](https://aclanthology.org/2021.nlp4if-1.1.pdf) ![](https://img.shields.io/badge/NAACL%202021%20Workshop-orange) ![](https://img.shields.io/badge/2020.09-blue)

  *Antonis Maronikolakis, Hinrich Schutze and Mark Stevenson.*
  > Create a dataset containing human and computer-generated headlines. Transformers achieved an overall accuracy of 85.7%.

- **Detecting Cross-Modal Inconsistency to Defend Against Neural Fake News.** [[paper]](https://aclanthology.org/2020.emnlp-main.163.pdf) ![](https://img.shields.io/badge/EMNLP%202020-orange) ![](https://img.shields.io/badge/2020.09-blue)

  *Reuben Tan, Bryan A. Plummer and Kate Saenko.*
  > Present DIDAN, a approach which exploits possible semantic inconsistencies between the text and image/captions to detect machine-generated articles.

- **Neural Deepfake Detection with Factual Structure of Text.** [[paper]](https://aclanthology.org/2020.emnlp-main.193.pdf) ![](https://img.shields.io/badge/EMNLP%202020-orange) ![](https://img.shields.io/badge/2020.10-blue)

  *Wanjun Zhong, Duyu Tang, Zenan Xu, Ruize Wang, Nan Duan, Ming Zhou, Jiahai Wang and Jian Yin.*
  > Propose a graph-based model that utilizes the factual structure of a document for deepfake detection of text.

- **Authorship Attribution for Neural Text Generation.** [[paper]](https://aclanthology.org/2020.emnlp-main.673.pdf) ![](https://img.shields.io/badge/EMNLP%202020-orange) ![](https://img.shields.io/badge/2020.11-blue)

  *Adaku Uchendu, Thai Le, Kai Shu and Dongwon Lee.*
  > Investigate the authorship attribution problem in three versions: (1) given two texts T1 and T2, are both generated by the same method or not? (2) is the given text T written by a human or machine? (3) given a text T and k candidate neural methods, can we single out the method (among k alternatives) that generated T?

- **How Effectively Can Machines Defend Against Machine-Generated Fake News? An Empirical Study.** [[paper]](https://aclanthology.org/2020.insights-1.7.pdf) ![](https://img.shields.io/badge/EMNLP%202020%20Workshop-orange) ![](https://img.shields.io/badge/2020.11-blue)

  *Meghana Moorthy Bhat and Srinivasan Parthasarathy.*
  > Measure the performance of models by looking at accuracy with respect to perturbations introduced in this work. Find that success of style-based classifiers are limited when real articles are perturbed even under extreme modifications.

- **Feature-based detection of automated language models: tackling GPT-2, GPT-3 and Grover.** [[paper]](https://peerj.com/articles/cs-443.pdf) ![](https://img.shields.io/badge/PeerJ%20Computer%20Science%202021-orange) ![](https://img.shields.io/badge/2021.04-blue)

  *Leon Fröhling and Arkaitz Zubiaga.*
  > A feature-based detection approach relies on features that discriminate between human and machine text by modelling properties and dimensions in which both types of text differ.

- **Detecting Bot-Generated Text by Characterizing Linguistic Accommodation in Human-Bot Interactions.** [[paper]](https://aclanthology.org/2021.findings-acl.286.pdf) ![](https://img.shields.io/badge/ACL%202021%20Findings-orange) ![](https://img.shields.io/badge/2021.06-blue)

  *Paras Bhatt and Anthony Rios.*
  > Show that bot-generated text detection methods are more robust across datasets and models if we use information about how people respond to it rather than using the bot’s text directly.

- **Artificial Text Detection via Examining the Topology of Attention Maps.** [[paper]](https://aclanthology.org/2021.emnlp-main.50v2.pdf) ![](https://img.shields.io/badge/EMNLP%202021-orange) ![](https://img.shields.io/badge/2021.09-blue)

  *Laida Kushnareva, Daniil Cherniavskii, Vladislav Mikhailov, Ekaterina Artemova, Serguei Barannikov, Alexander Bernstein, Irina Piontkovskaya, Dmitri Piontkovski and Evgeny Burnaev.*
  > Propose three novel types of interpretable topological features based on Topological Data Analysis (TDA). The features derived from the BERT model outperform count- and neural-based baselines up to 10% on three common datasets, and tend to be the most robust towards unseen GPT-style generation models as opposed to existing methods.

- **Unsupervised and Distributional Detection of Machine-Generated Text.** [[paper]](https://arxiv.org/pdf/2111.02878) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2021.11-blue)

  *Matthias Gallé, Jos Rozen, Germán Kruszewski and Hady Elsahar.*
  > Propose a method to detect those machine-generated documents leveraging repeated higher-order n-grams, which we show over-appear in machine-generated text as compared to human ones.

- **Detecting computer-generated disinformation.** [[paper]](https://link.springer.com/content/pdf/10.1007/s41060-021-00299-5.pdf) ![](https://img.shields.io/badge/IJDSA%202022-orange) ![](https://img.shields.io/badge/2021.12-blue)

  *Harald Stiff and Fredrik Johansson.*
  > Evaluate promising Transformer-based detection algorithms in a large variety of experiments involving both in-distribution and out-of-distribution test data, as well as evaluation on more realistic in-the-wild data.

- **On pushing DeepFake Tweet Detection capabilities to the limits.** [[paper]](https://dl.acm.org/doi/pdf/10.1145/3501247.3531560) ![](https://img.shields.io/badge/WebSci%202022-orange) ![](https://img.shields.io/badge/2022.06-blue)

  *Margherita Gambini, Tiziano Fagni, Fabrizio Falchi and Maurizio Tesconi.*
  > Study and improve the performance of the stateof-the-art deepfake tweet detection methods over GPT-2 tweets and the detectors’ capabilities to generalize over tweets generated by GPT-3.

- **Cross-Domain Detection of GPT-2-Generated Technical Text.** [[paper]](https://aclanthology.org/2022.naacl-main.88.pdf) ![](https://img.shields.io/badge/NAACL%202022-orange) ![](https://img.shields.io/badge/2022.07-blue)

  *Juan Rodriguez, Todd Hay, David Gros, Zain Shamsi and Ravi Srinivasan.*
  > Find that RoBERTa-based detectors can be successfully adapted from one scientific discipline (physics) to another (biomedicine), requiring relatively small amounts of in-domain labeled data.

- **Automatic Detection of Machine Generated Texts: Need More Tokens.** [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9983964) ![](https://img.shields.io/badge/IVMEM%202022-orange) ![](https://img.shields.io/badge/2022.09-blue)

  *Paras Bhatt and Anthony Rios.*
  > Present a dataset for Russian language and conduct a set of learning experiments to build accurate machine-generated text detectors for both English and Russian languages.

- **Threat Scenarios and Best Practices to Detect Neural Fake News.** [[paper]](https://aclanthology.org/2022.coling-1.106.pdf) ![](https://img.shields.io/badge/COLING%202022-orange) ![](https://img.shields.io/badge/2022.10-blue)

  *Artidoro Pagnoni, Martin Graciarena and Yulia Tsvetkov.*
  > Provide an assessment of the current landscape of generated text detection and identify three primary threat scenarios. Establish the minimax strategies that minimize the worst case scenario for the detector.

- **Demystifying Neural Fake News via Linguistic Feature-Based Interpretation.** [[paper]](https://aclanthology.org/2022.coling-1.573.pdf) ![](https://img.shields.io/badge/COLING%202022-orange) ![](https://img.shields.io/badge/2022.10-blue)

  *Ankit Aich, Souvik Bhattacharya and Natalie Parde.*
  > Conduct a linguistically interpretative examination of the feature vulnerabilities exploited by neural fake news generators. Establish 21 stylistic, complexity, and psychological features for detection.

- **CoCo: Coherence-Enhanced Machine-Generated Text Detection Under Data Limitation With Contrastive Learning.** [[paper]](https://arxiv.org/pdf/2212.10341) ![](https://img.shields.io/badge/EMNLP%202023-orange) ![](https://img.shields.io/badge/2022.12-blue)

  *Xiaoming Liu, Zhaohan Zhang, Yichen Wang, Yu Lan and Chao Shen.*
  > Present a coherence-based contrastive learning model named CoCo to detect the possible machine-generated text under low-resource scenario.

- **How Close is ChatGPT to Human Experts? Comparison Corpus, Evaluation, and Detection.** [[paper]](https://arxiv.org/pdf/2301.07597) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.01-blue)

  *Biyang Guo, Xin Zhang, Ziyuan Wang, Minqi Jiang, Jinran Nie, Yuxuan Ding, Jianwei Yue and Yupeng Wu.*
  > Collect dataset the Human ChatGPT Comparison Corpus (HC3) and build three different detection systems to detect whether a certain text is generated by ChatGPT or humans.

- **DetectGPT: Zero-Shot Machine-Generated Text Detection using Probability Curvature.** [[paper]](https://arxiv.org/pdf/2301.11305) ![](https://img.shields.io/badge/ICML%202023-orange) ![](https://img.shields.io/badge/2023.01-blue)

  *Eric Mitchell, Yoonho Lee, Alexander Khazatsky, Christopher D. Manning and Chelsea Finn.*
  > Propose DetectGPT, a zero-shot method for automated machine-generated text detection. To test if a passage came from a source model, DetectGPT compares the log probability of a candidate passage with the average log probability of several perturbations of the passage.

- **ChatGPT or Human? Detect and Explain. Explaining Decisions of Machine Learning Model for Detecting Short ChatGPT-generated Text.** [[paper]](https://arxiv.org/pdf/2301.13852) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.01-blue)

  *Sandra Mitrović, Davide Andreoletti and Omran Ayoub.*
  > Build Transformer-based model to discriminate between human-written and seemingly human text, focusing on short texts. Give some insights about ChatGPT writing style by SHAP explanations of the predictions.

- **AI vs. Human -- Differentiation Analysis of Scientific Content Generation.** [[paper]](https://arxiv.org/pdf/2301.10416) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.01-blue)

  *Yongqiang Ma, Jiawei Liu, Fan Yi, Qikai Cheng, Yong Huang, Wei Lu and Xiaozhong Liu.*
  > Investigate the detection methods from three perspectives: (1) feature-based detection method; (2) fine-tuned pre-trained detection model; (3) explainability of detection model. Further investigate the gap between AI-generated text and human-written text.

- **ChatGPT Generated Text Detection.** [[paper]](https://www.researchgate.net/profile/Ercan-Canhasi/publication/366898047_ChatGPT_Generated_Text_Detection/links/63b76718097c7832ca932473/ChatGPT-Generated-Text-Detection.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.01-blue)

  *Rexhep Shijaku and Ercan Canhasi.*
  > Present a classification model based on XGBoost for automatically detecting essays generated by ChatGPT.

- **Linguistic Markers of AI-Generated Text Versus Human-Generated Text: Evidence from Hotel Reviews and News Headlines.** [[paper]](https://psyarxiv.com/mnyz8/download) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.01-blue)

  *David M. Markowitz, Jeffrey Hancock and Jeremy Bailenson.*
  > Use ChatGPT to compare how it wrote hotel reviews and news headlines to human-generated counterparts across content, style, and structural features.

- **Mutation-Based Adversarial Attacks on Neural Text Detectors.** [[paper]](https://arxiv.org/pdf/2302.05794) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.02-blue)

  *Gongbo Liang, Jesus Guerrero and Izzat Alsmadi.*
  > Propose character- and word-based mutation operators for generating adversarial samples to attack state-of-the-art natural text detectors.

- **GAN-Based Unsupervised Learning Approach to Generate and Detect Fake News.** [[paper]](https://link.springer.com/chapter/10.1007/978-3-031-22018-0_37) ![](https://img.shields.io/badge/ICSPN%202022-orange) ![](https://img.shields.io/badge/2023.02-blue)

  *Pranjal Bhardwaj, Krishna Yadav, Hind Alsharif and Rania Anwar Aboalela.*
  > Develop an unsupervised-based approach to generate fake news using autoencoder and GAN. Further describe the use of discriminators in detecting machine-generated fake news.

- **Accurate Generated Text Detection Based on Deep Layer-wise Relevance Propagation.** [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10104941) ![](https://img.shields.io/badge/ICBDA%202023-orange) ![](https://img.shields.io/badge/2023.03-blue)

  *Mengjie Guo, Limin Liu, Meicheng Guo, Siyuan Liu and Zhiwei Xu.*
  > Propose a deep interpretable model to achieve accurate detection of the generated texts. In detail, a feature extraction method based on Layer-wise Relevance Propagation is proposed to improve the feature mining performance for detection of generated texts.

- **Stylometric Detection of AI-Generated Text in Twitter Timelines.** [[paper]](https://arxiv.org/pdf/2303.03697) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.03-blue)

  *Tharindu Kumarage, Joshua Garland, Amrita Bhattacharjee, Kirill Trapeznikov, Scott Ruston and Huan Liu.*
  > Propose two simple architectures to utilize three categories of stylometric features towards 1) discriminating between human-written and AI-generated tweets and 2) detecting if and when an AI starts to generate tweets in a given Twitter timeline.

- **ChatGPT or academic scientist? Distinguishing authorship with over 99% accuracy using off-the-shelf machine learning tools.** [[paper]](https://arxiv.org/pdf/2303.16352) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.03-blue)

  *Heather Desaire, Aleesa E. Chua, Madeline Isom, Romana Jarosova and David Hua.*
  > With a set of 20 features, build a model that assigned the author, as human or AI, at well over 99% accuracy, resulting in 20 times fewer misclassified documents compared to the field-leading approach.

- **Detection of AI-generated Essays in Writing Assessments.** [[paper]](https://www.psychologie-aktuell.com/fileadmin/Redaktion/Journale/ptam_2023-1/PTAM__1-2023_5_kor.pdf) ![](https://img.shields.io/badge/Psychological%20Testing%20and%20Assessment%20Modeling%202023-orange) ![](https://img.shields.io/badge/2023.03-blue)

  *Duanli Yan, Michael Fauss, Jiangang Hao, Wenju Cui.*
  > Show how AI-generated essays are similar or different from human-written essays based on a set of typical prompts for a sample from a large-scale assessment. Introduce two classifiers that can detect AI-generated essays with a high accuracy of over 95%.

- **Comparing Abstractive Summaries Generated by ChatGPT to Real Summaries Through Blinded Reviewers and Text Classification Algorithms.** [[paper]](https://arxiv.org/pdf/2303.17650) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.03-blue)

  *Mayank Soni, Vincent Wade.*
  > Evaluate the performance of ChatGPT on Abstractive Summarization by the means of automated metrics and blinded human reviewers. Also build automatic text classifiers to detect ChatGPT generated summaries. Find that while text classification algorithms can distinguish between real and generated summaries, humans are unable to distinguish between real summaries and those produced by ChatGPT.

- **Distinguishing ChatGPT(-3.5, -4)-generated and human-written papers through Japanese stylometric analysis.** [[paper]](https://arxiv.org/pdf/2304.05534) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.04-blue)

  *Wataru Zaitsu and Mingzhe Jin.*
  > Perform multi-dimensional scaling (MDS) to confirm the distributions of 216 texts of three classes (human, GPT-3.5, GPT-4) focusing on the following stylometric features: (1) bigrams of parts-of-speech, (2) bigram of postpositional particle words, (3) positioning of commas, and (4) rate of function words.

- **Evaluating AIGC Detectors on Code Content.** [[paper]](https://arxiv.org/pdf/2304.05193) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.04-blue)

  *Jian Wang, Shangqing Liu, Xiaofei Xie and Yi Li.*
  > Present the first empirical study on evaluating existing AIGC detectors in the software domain. Create a comprehensive dataset including 492.5K samples comprising code-related content produced by ChatGPT and evaluate six AIGC detectors on this dataset.

- **Detection of Fake Generated Scientific Abstracts.** [[paper]](https://arxiv.org/pdf/2304.06148) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.04-blue)

  *Panagiotis C. Theocharopoulos, Panagiotis Anagnostou, Anastasia Tsoukala, Spiros V. Georgakopoulos, Sotiris K. Tasoulis and Vassilis P. Plagianakos.*
  > Utilize the GPT-3 model to generate scientific paper abstracts through Artificial Intelligence and explore various text representation methods when combined with Machine Learning models with the aim of identifying machine-written text.

- **ArguGPT: evaluating, understanding and identifying argumentative essays generated by GPT models.** [[paper]](https://arxiv.org/pdf/2304.07666) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.04-blue)

  *Yikang Liu, Ziyin Zhang, Wanyang Zhang, Shisen Yue, Xiaojing Zhao, Xinyuan Cheng, Yiwen Zhang and Hai Hu.*
  > Present ArguGPT, a balanced corpus of 4,038 argumentative essays generated by 7 GPT models in response to essay prompts from three sources: (1) in-class or homework exercises, (2) TOEFL and (3) GRE writing tasks. A RoBERTa fine-tuned with the training set of ArguGPT achieves above 90% accuracy in both essay- and sentence-level classification.

- **Improving Detection of ChatGPT-Generated Fake Science Using Real Publication Text: Introducing xFakeBibs a Supervised Learning Network Algorithm.** [[paper]](https://www.preprints.org/manuscript/202304.0350/v2/download) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.04-blue)

  *Ahmed Abdeen Hamed.*
  > By means of a new algorithm, called xFakeBibs, show the significant difference between ChatGPT-generated fake publications and real publications. The algorithm predicted 98 of the 100 publications as fake, while 2 articles failed the test and were classified as real publications.

- **Differentiate ChatGPT-generated and Human-written Medical Texts.** [[paper]](https://arxiv.org/pdf/2304.11567) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.04-blue)

  *Wenxiong Liao, Zhengliang Liu, Haixing Dai, Shaochen Xu, Zihao Wu, Yiyang Zhang, Xiaoke Huang, Dajiang Zhu, Hongmin Cai, Tianming Liu and Xiang Li.*
  > Construct a suite of datasets containing medical texts written by human experts and generated by ChatGPT. Analyze the linguistic features of these two types of content and uncover differences in vocabulary, part-of-speech, dependency, sentiment, perplexity, etc. Finally, design and implement machine learning methods to detect medical text generated by ChatGPT.

- **CHEAT: A Large-scale Dataset for Detecting ChatGPT-writtEn AbsTracts.** [[paper]](https://arxiv.org/pdf/2304.12008) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.04-blue)

  *Peipeng Yu, Jiahan Chen, Xuan Feng and Zhihua Xia.*
  > Present a large-scale CHatGPT-writtEn AbsTract dataset (CHEAT) contains 35,304 synthetic abstracts, with Generation, Polish, and Mix as prominent representatives. Show that ChatGPT-written abstracts are detectable, while the detection difficulty increases with human involvement.

- **Origin Tracing and Detecting of LLMs.** [[paper]](https://arxiv.org/pdf/2304.14072) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.04-blue)

  *Linyang Li, Pengyu Wang, Ke Ren, Tianxiang Sun and Xipeng Qiu.*
  > First raise the concern of the origin tracing of LLMs and propose an effective method to trace and detect AI-generated contexts. Introduce a novel algorithm that leverages the contrastive features between LLMs and extracts model-wise features to trace the text origins.

- **ChatLog: Recording and Analyzing ChatGPT Across Time.** [[paper]](https://arxiv.org/pdf/2304.14106) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.04-blue)

  *Shangqing Tu, Chunyang Li, Jifan Yu, Xiaozhi Wang, Lei Hou and Juanzi Li.*
  > Collect a coarse-to-fine temporal dataset called ChatLog, consisting of two parts that update monthly and daily. In section 5, explore the application of ChatGPT unchanged features on ChatLog-Daily dataset. Show a preliminary use case: improving the ChatGPT detection model’s robustness.

- **Perception, performance, and detectability of conversational artificial intelligence across 32 university courses.** [[paper]](https://arxiv.org/pdf/2305.13934) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.05-blue)

  <details><summary>Show Authors</summary><i>Hazem Ibrahim, Fengyuan Liu, Rohail Asim, Balaraju Battu, Sidahmed Benabderrahmane, Bashar Alhafni, Wifag Adnan, Tuka Alhanai, Bedoor AlShebli, Riyadh Baghdadi, Jocelyn J. Bélanger, Elena Beretta, Kemal Celik, Moumena Chaqfeh, Mohammed F. Daqaq, Zaynab El Bernoussi, Daryl Fougnie, Borja Garcia de Soto, Alberto Gandolfi, Andras Gyorgy, Nizar Habash, J. Andrew Harris, Aaron Kaufman, Lefteris Kirousis, Korhan Kocak, Kangsan Lee, Seungah S. Lee, Samreen Malik, Michail Maniatakos, David Melcher, Azzam Mourad, Minsu Park, Mahmoud Rasras, Alicja Reuben, Dania Zantout, Nancy W. Gleason, Kinga Makovi, Talal Rahwan and Yasir Zaki</i></details>

  > Compare the performance of ChatGPT against students on 32 university-level courses. Current AI-text classifiers cannot reliably detect ChatGPT’s use in school work, due to their propensity to classify human-written answers as AI-generated, as well as the ease with which AI-generated text can be edited to evade detection.

- **GPT-Sentinel: Distinguishing Human and ChatGPT Generated Content.** [[paper]](https://arxiv.org/pdf/2305.07969) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Yutian Chen, Hao Kang, Vivian Zhai, Liangze Li, Rita Singh and Bhiksha Raj.*
  > Collecte and release a pre-processed dataset named OpenGPTText, which consists of rephrased content generated using ChatGPT. Design, implement, and train two different models for text classification, using RoBERTa and T5, respectively. These models achieve remarkable results, with an accuracy of over 97% on the test dataset, as evaluated through various metrics.

- **Machine-Made Media: Monitoring the Mobilization of Machine-Generated Articles on Misinformation and Mainstream News Websites.** [[paper]](https://arxiv.org/pdf/2305.09820) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Hans W. A. Hanley and Zakir Durumeric.*
  > Train a DeBERTa-based synthetic news detector and classify over 12.91 million articles from 3,074 misinformation and mainstream news websites. Find that between January 1, 2022 and April 1, 2023, the relative number of synthetic news articles increased by 79.4% on mainstream websites while increasing by 342% on misinformation sites.

- **Smaller Language Models are Better Black-box Machine-Generated Text Detectors.** [[paper]](https://arxiv.org/pdf/2305.09859) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Fatemehsadat Mireshghallah, Justus Mattern, Sicun Gao, Reza Shokri and Taylor Berg-Kirkpatrick.*
  > Explore whether models other than the generator can be used to differentiate between machinegenerated and human-written text. Find that overall, smaller and partially-trained models are better universal text detectors. Interestingly, we find that whether the detector and generator were trained on the same data is not critically important to the detection success.

- **GPT Paternity Test: GPT Generated Text Detection with GPT Genetic Inheritance.** [[paper]](https://arxiv.org/pdf/2305.12519) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Xiao Yu, Yuang Qi, Kejiang Chen, Guoqiang Chen, Xi Yang, Pengyuan Zhu, Weiming Zhang and Nenghai Yu.*
  > Introduce GPT Paternity Test (GPT-Pat), which reliably detects machine-generated text across varied datasets. Given a text under scrutiny, we leverage ChatGPT to generate a corresponding question and provide a re-answer to the question. By comparing the similarity between the original text and the generated re-answered text, it can be determined whether the text is machine-generated.

- **G3Detector: General GPT-Generated Text Detector.** [[paper]](https://arxiv.org/pdf/2305.12680) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Haolan Zhan, Xuanli He, Qiongkai Xu, Yuxiang Wu and Pontus Stenetorp.*
  > Introduce an unpretentious yet potent detection approach proficient in identifying synthetic text across a wide array of fields. The detector demonstrates outstanding performance uniformly across various model architectures and decoding strategies. It also possesses the capability to identify text generated utilizing a potent detectionevasion technique.

- **Deepfake Text Detection in the Wild.** [[paper]](https://arxiv.org/pdf/2305.13242) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Yafu Li, Qintong Li, Leyang Cui, Wei Bi, Longyue Wang, Linyi Yang, Shuming Shi and Yue Zhang.*
  > Construct a wild testbed for deepfake text detection, by gathering texts from various writing tasks and deepfake texts generated by different LLMs. Find that supervised PLM-based methods were the best-performing detection methods across all testbeds. Out-of-distribution posed an even greater challenge for a detector to be employed in realistic application scenarios.

- **DetectLLM: Leveraging Log Rank Information for Zero-Shot Detection of Machine-Generated Text.** [[paper]](https://arxiv.org/pdf/2306.05540) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Jinyan Su, Terry Yue Zhuo, Di Wang and Preslav Nakov.*
  > Introduce two novel zero-shot methods for detecting machinegenerated text by leveraging the log rank information. One is called DetectLLM-LRR, which is fast and efficient, and the other is called DetectLLM-NPR, which is more accurate, but slower due to the need for perturbations.

- **LLMDet: A Third Party Large Language Models Generated Text Detection Tool.** [[paper]](https://arxiv.org/pdf/2305.15004) ![](https://img.shields.io/badge/EMNLP%202023%20Findings-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Kangxi Wu, Liang Pang, Huawei Shen, Xueqi Cheng and Tat-Seng Chua.*
  > Propose an efficient, secure, and scalable detection tool called LLMDet, which calculates the proxy perplexity of text by utilizing the prior information of the model’s next-token probabilities, obtained through pre-training. Subsequently, use the self-watermarking information of the model, as measured by proxy perplexity, to detect the source of the text.

- **Ghostbuster: Detecting Text Ghostwritten by Large Language Models.** [[paper]](https://arxiv.org/pdf/2305.15047) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Vivek Verma, Eve Fleisig, Nicholas Tomlin and Dan Klein.*
  > Introduce Ghostbuster, works by passing documents through a series of weaker language models and running a structured search over possible combinations of their features, then training a classifier on the selected features to determine if the target document was AI-generated. Release three new datasets of human and AI-generated text as detection benchmarks that cover multiple domains and task setups.

- **HowkGPT: Investigating the Detection of ChatGPT-generated University Student Homework through Context-Aware Perplexity Analysis.** [[paper]](https://arxiv.org/pdf/2305.18226) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Christoforos Vasilatos, Manaar Alam, Talal Rahwan, Yasir Zaki and Michail Maniatakos.*
  > Propose a novel multi-level approach to detect AIgenerated text focusing on university student homework. Utilize metadata categorization from an academic dataset to enhance the perplexity metric used to detect whether a given assignment has been studentauthored or AI-generated.

- **DNA-GPT: Divergent N-Gram Analysis for Training-Free Detection of GPT-Generated Text.** [[paper]](https://arxiv.org/pdf/2305.17359) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Xianjun Yang, Wei Cheng, Linda Petzold, William Yang Wang and Haifeng Chen.*
  > Given a text, we first truncate it in the middle and then use only the preceding portion as input to the LLMs to regenerate the new remaining parts. By analyzing the differences between the original and new remaining parts through N-gram analysis in black-box or probability divergence in white-box, we can clearly illustrate significant discrepancies between machine-generated and human-written text.

- **Efficient Detection of LLM-generated Texts with a Bayesian Surrogate Model.** [[paper]](https://arxiv.org/pdf/2305.16617) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Zhijie Deng, Hongcheng Gao, Yibo Miao and Hao Zhang.*
  > DetectGPT suffers from significant inefficiency issues, as detecting a single candidate requires scoring hundreds of its perturbations with the source LLM. This paper aims to bridge this gap. Technically, propose to incorporate a Bayesian surrogate model, which allows us to select typical samples based on Bayesian uncertainty and interpolate scores from typical samples to other ones, to improve query efficiency.

- **Distinguishing Human Generated Text From ChatGPT Generated Text Using Machine Learning.** [[paper]](https://arxiv.org/pdf/2306.01761) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Niful Islam, Debopom Sutradhar, Humaira Noor, Jarin Tasnim Raya, Monowara Tabassum Maisha and Dewan Md Farid.*
  > Present a machine learning-based solution that can identify the ChatGPT delivered text from the human written text along with the comparative analysis of a total of 11 machine learning and deep learning algorithms in the classification process.

- **Multiscale Positive-Unlabeled Detection of AI-Generated Texts.** [[paper]](https://arxiv.org/pdf/2305.18149) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Yuchuan Tian, Hanting Chen, Xutao Wang, Zheyuan Bai, Qinghua Zhang, Ruifeng Li, Chao Xu and Yunhe Wang.*
  > Mainstream detectors are formulated without considering the factor of corpus length: shorter corpuses are harder to detect compared with longer ones for shortage of informative features. In this paper, a Multiscale Positive-Unlabeled (MPU) training framework is proposed to address the challenge of multiscale text detection.

- **Intrinsic Dimension Estimation for Robust Detection of AI-Generated Texts.** [[paper]](https://arxiv.org/pdf/2306.04723) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.06-blue)

  *Eduard Tulchinskii, Kristian Kuznetsov, Laida Kushnareva, Daniil Cherniavskii, Serguei Barannikov, Irina Piontkovskaya, Sergey Nikolenko and Evgeny Burnaev.*
  > Propose an invariant of human texts, namely the intrinsic dimensionality of the manifold underlying the set of embeddings of a given text sample. We show a clear statistical separation between human-generated and AI-generated distributions. This property allows us to build a score-based artificial text detector, which outperforming SOTA detectors in model-agnostic and cross-domain scenarios by a significant margin.

- **Distinguishing academic science writing from humans or ChatGPT with over 99% accuracy using off-the-shelf machine learning tools.** [[paper]](https://www.cell.com/cell-reports-physical-science/pdf/S2666-3864(23)00200-X.pdf) ![](https://img.shields.io/badge/Cell%20Reports%20Physical%20Science-orange) ![](https://img.shields.io/badge/2023.06-blue)

  *Heather Desaire, Aleesa E. Chua, Madeline Isom, Romana Jarosova and David Hua.*
  > Report a method for discriminating text generated by ChatGPT from (human) academic scientists, relying on prevalent and accessible supervised classification methods. The approach uses new features for discriminating (these) humans from AI.

- **Long-form analogies generated by chatGPT lack human-like psycholinguistic properties.** [[paper]](https://arxiv.org/pdf/2306.04537) ![](https://img.shields.io/badge/CogSci%202023-orange) ![](https://img.shields.io/badge/2023.06-blue)

  *S. M. Seals and Valerie L. Shalin.*
  > Apply psycholinguistic methods to evaluate individual sentences from long-form analogies about biochemical concepts. Perform a supervised classification analysis using 78 features extracted from Coh-metrix that analyze text cohesion, language, and readability. Results illustrate high performance for classifying student-generated and chatGPT-generated analogies.

- **Check Me If You Can: Detecting ChatGPT-Generated Academic Writing using CheckGPT.** [[paper]](https://arxiv.org/pdf/2306.05524) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.06-blue)

  *Zeyan Liu, Zijun Yao, Fengjun Li and Bo Luo.*
  > Present GPABenchmark, a benchmarking dataset of 600,000 samples of human-written, GPT-written, GPT-completed, and GPT-polished abstracts of research papers in CS, physics, and humanities and social sciences (HSS). Present CheckGPT, a novel LLM-content detector consisting of a general representation module and an attentive-BiLSTM classification module, which is accurate, transferable, and interpretable.

- Stanford CS224N Custom Projects

  - **Check Me If You Can: Detecting ChatGPT-Generated Academic Writing using CheckGPT.** [[paper]](http://web.stanford.edu/class/cs224n/final-reports/final-report-169358982.pdf) ![](https://img.shields.io/badge/2023.06-blue)

    *Jeffrey Heo and Simon Kim.*

  - **Looking Under the Hood of DetectGPT.** [[paper]](http://web.stanford.edu/class/cs224n/final-reports/final-report-169403912.pdf) ![](https://img.shields.io/badge/2023.06-blue)

    *Maximilian Du, Ryan Lian and Kaien Yang.*

  - **GPTNo: A Deep Learning LLM to Beat the Turing Test.** [[paper]](http://web.stanford.edu/class/cs224n/final-reports/final-report-169508272.pdf) ![](https://img.shields.io/badge/2023.06-blue)

    *Sri Jaladi, William Li and Abhinav Sinha.*

  - **Human Writing is as Uniform as Machine Writing.** [[paper]](http://web.stanford.edu/class/cs224n/final-reports/final-report-169508494.pdf) ![](https://img.shields.io/badge/2023.06-blue)

    *Ryan Tan, Raghav Garg and Jacob Stavrianos.*

  - **DetectChatGPT: Black-Box Zero-Shot Detection of LLM-Generated Text.** [[paper]](http://web.stanford.edu/class/cs224n/final-reports/final-report-170049587.pdf) ![](https://img.shields.io/badge/2023.06-blue)

    *Julia Park and Armaan Rashid.*

- **La détection de textes générés par des modèles de langue: une tâche complexe? Une étude sur des textes académiques.** [[paper]](https://arts2023.sciencesconf.org/data/pages/proceedings_ARTS_2.pdf#page=79) ![](https://img.shields.io/badge/CORIA--TALN%202023-orange) ![](https://img.shields.io/badge/2023.06-blue)

  *Vijini Liyanage and Davide Buscaldi.*

- **Towards a Robust Detection of Language Model Generated Text: Is ChatGPT that Easy to Detect?** [[paper]](https://coria-taln-2023.sciencesconf.org/461938/document) ![](https://img.shields.io/badge/CORIA--TALN%202023-orange) ![](https://img.shields.io/badge/2023.06-blue)

  *Wissam Antoun, Virginie Mouilleron, Benoît Sagot and Djamé Seddah.*
  > Proposes a methodology for developing and evaluating ChatGPT detectors for French text, with a focus on investigating their robustness on outof-domain data and against common attack schemes. The proposed method involves translating an English dataset into French and training a classifier on the translated data.

- **Implementing BERT and fine-tuned RobertA to detect AI generated news by ChatGPT.** [[paper]](https://arxiv.org/pdf/2306.07401) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.06-blue)

  *Zecong Wang, Jiaxi Cheng, Chen Cui and Chenhao Yu.*
  > Demonstrate that the BERT and RobertA models with fine-tuning had the best success in detecting AI generated news. With a score of 98%, tweaked RobertA in particular showed excellent precision.

- **Beyond Black Box AI-Generated Plagiarism Detection: From Sentence to Document Level.** [[paper]](https://arxiv.org/pdf/2306.08122) ![](https://img.shields.io/badge/ACL%202023%20Workshop-orange) ![](https://img.shields.io/badge/2023.06-blue)

  *Mujahid Ali Quidwai, Chunhui Li and Parijat Dube.*
  > Propose a novel approach offering quantifiable metrics at both sentence. Employs a multi-faceted approach, generating multiple paraphrased versions of a given question and inputting them into the LLM to generate answers. By using a contrastive loss function based on cosine similarity, match generated sentences with those from the student’s response.

- **Detecting Artificially Generated Academic Text: The Importance of Mimicking Human Utilization of Large Language Models.** [[paper]](https://link.springer.com/content/pdf/10.1007/978-3-031-35320-8_42.pdf?pdf=inline%20link) ![](https://img.shields.io/badge/NLDB%202023-orange) ![](https://img.shields.io/badge/2023.06-blue)

  *Vijini Liyanage and Davide Buscaldi.*
  > Examine the detectability of the generated text using DetectGPT and GLTR, and utilize state-of-the-art classification models like SciBERT, RoBERTa, DEBERTa, XLNet, and ELECTRA. Experiments show that the generated text is difficult to detect using existing models when created using a LLM fine-tuned on the remainder of a paper.

- **Testing of Detection Tools for AI-Generated Text.** [[paper]](https://arxiv.org/pdf/2306.15666) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.06-blue)

  *Debora Weber-Wulff, Alla Anohina-Naumeca, Sonja Bjelobaba, Tomáš Foltýnek, Jean Guerrero-Dib, Olumide Popoola, Petr Šigut and Lorna Waddington.*
  > The study seeks to answer research questions about whether existing detection tools can reliably differentiate between human-written text and ChatGPT-generated text, and whether machine translation and content obfuscation techniques affect the detection of AIgenerated text. The research covers 12 publicly available tools and two commercial systems (Turnitin and PlagiarismCheck) that are widely used in the academic setting.

- **Discriminating Human-authored from ChatGPT-Generated Code Via Discernable Feature Analysis.** [[paper]](https://arxiv.org/pdf/2306.14397) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.06-blue)

  *Li Ke, Hong Sheng, Fu Cai, Zhang Yunhe and Liu Ming.*
  > Propose a discriminative feature set yielding high accuracy in differentiating ChatGPT-generated code from human-authored code in binary classification tasks; Devise methods for generating extensive ChatGPT-generated codes; Introduce a dataset cleansing strategy.

- **RADAR: Robust AI-Text Detection via Adversarial Learning.** [[paper]](https://arxiv.org/pdf/2307.03838) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.07-blue)

  *Xiaomeng Hu, Pin-Yu Chen and Tsung-Yi Ho.*
  > Existing works show that current AI-text detectors are not robust to LLM-based paraphrasing, this paper aims to bridge this gap by proposing a new framework called RADAR. RADAR is based on adversarial training of a paraphraser and a detector. The paraphraser’s goal is to generate realistic contents to evade AI-text detection. RADAR uses the feedback from the detector to update the paraphraser, and vice versa.

- **Detecting LLM-Generated Text in Computing Education: A Comparative Study for ChatGPT Cases.** [[paper]](https://arxiv.org/pdf/2307.07411) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.07-blue)

  *Michael Sheinman Orenstrakh, Oscar Karnalim, Carlos Anibal Suarez and Michael Liut.*
  > Collect 124 submissions from computer science students before the creation of ChatGPT, then generate 40 ChatGPT submissions. Use this data to evaluate eight publicly-available LLM-generated text detectors through the measures of accuracy, false positives, and resilience.

- **Is ChatGPT Involved in Texts? Measure the Polish Ratio to Detect ChatGPT-Generated Text.** [[paper]](https://arxiv.org/pdf/2307.11380) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.07-blue)

  *Lingyi Yang, Feng Jiang and Haizhou Li.*
  > Introduce a novel dataset termed HPPT (ChatGPT-polished academic abstracts), facilitating the construction of more robust detectors. Propose the "Polish Ratio" method, an innovative measure of ChatGPT’s involvement in text generation based on editing distance. It provides a mechanism to measure the degree of human originality in the resulting text.

- **OUTFOX: LLM-generated Essay Detection through In-context Learning with Adversarially Generated Examples.** [[paper]](https://arxiv.org/pdf/2307.11729) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.07-blue)

  *Ryuto Koike, Masahiro Kaneko and Naoaki Okazaki.*
  > Propose OUTFOX, a novel framework that improves the robustness of LLM-generated-text detectors by allowing both the detector and the attacker to consider each other’s output and apply this to the domain of student essays.

- **The Looming Threat of Fake and LLM-generated LinkedIn Profiles: Challenges and Opportunities for Detection and Prevention.** [[paper]](https://arxiv.org/pdf/2307.11864) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.07-blue)

  *Navid Ayoobi, Sadat Shahriar and Arjun Mukherjee.*
  > Present a novel method for detecting fake and Large Language Model (LLM)-generated profiles in the LinkedIn Online Social Network immediately upon registration and before establishing connections.

- **The Imitation Game: Detecting Human and AI-Generated Texts in the Era of Large Language Models.** [[paper]](https://arxiv.org/pdf/2307.12166) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.07-blue)

  *Kadhim Hayawi, Sakib Shahriar and Sujith Samuel Mathew.*
  > Introduce a novel dataset of human-written and LLM-generated texts in different genres: essays, stories, poetry, and Python code. Employ several machine learning models to classify the texts.

- **Towards Automatic Boundary Detection for Human-AI Collaborative Hybrid Essay in Education.** [[paper]](https://arxiv.org/pdf/2307.12267) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.07-blue)

  *Zijie Zeng, Lele Sha, Yuheng Li, Kaixun Yang, Dragan Gašević and Guanliang Chen.*
  > Construct a hybrid essay dataset. Propose a two-step detection approach where we (1) separate AI-generated content from human-written content during the encoder training process; and (2) calculate the distances between every two adjacent prototypes and assume that the boundaries exist between the two adjacent prototypes that have the furthest distance from each other.

- **Fighting Fire with Fire: Can ChatGPT Detect AI-generated Text?** [[paper]](https://arxiv.org/pdf/2308.01284) ![](https://img.shields.io/badge/SIGKDD%20Explorations%202023-orange) ![](https://img.shields.io/badge/2023.08-blue)

  *Amrita Bhattacharjee and Huan Liu.*
  > Empirically investigate if ChatGPT is symmetrically effective in detecting AI-generated or human-written text. Provide insight on how ChatGPT and similar LLMs may be leveraged in automated detection pipelines by simply focusing on solving a specific aspect of the problem and deriving the rest from that solution.

- **A Deep Fusion Model for Human vs. Machine-Generated Essay Classification.** [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10191322) ![](https://img.shields.io/badge/IJCNN%202023-orange) ![](https://img.shields.io/badge/2023.08-blue)

  *Roberto Corizzo and Sebastian Leal-Arenas.*
  > Propose a deep neural network-based model that combines text modeling and linguistic features via data fusion, with the aim to provide robust classification capabilities. Experiments show that it is possible to accurately perform essay classification, and that our model is competitive, even when compared to popular feature-based and neural network-based approaches.

- **MFD: Multi-Feature Detection of LLM-Generated Text.** [[paper]](https://www.researchsquare.com/article/rs-3226684/v1.pdf?c=1691560657000) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.08-blue)

  *Zhendong Wu and Hui Xiang.*
  > Introduce Multi-Feature Detection (MFD), a new zero-shot method. MFD comprehensively considers log-likelihood, log-rank, entropy, and LLM-Deviation. LLM-Deviation is a new statistical feature proposed in this paper and has a clear distribution difference between texts generated by LLMs and those written by humans. Experiments show MFD is more effective than the existing zero-shot method.

- **Classification of Human- and AI-Generated Texts: Investigating Features for ChatGPT.** [[paper]](https://arxiv.org/pdf/2308.05341) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.08-blue)

  *Lorenz Mindner, Tim Schlippe and Kristina Schaaff.*
  > Explore traditional and new features to (1) detect text generated by AI from scratch and (2) text rephrased by AI. Results show that the new features substantially help to improve the performance of many classifiers. 

- **Separating the Human Touch from AI-Generated Text using Higher Criticism: An Information-Theoretic Approach.** [[paper]](https://arxiv.org/pdf/2308.12747) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.08-blue)

  *Alon Kipnis.*
  > Propose a method to determine whether a given article was entirely written by a generative language model. The process involves many perplexity tests for the origin of individual sentences or other text atoms, combining these multiple tests using Higher Criticism (HC).

- **人工智能生成语言与人类语言对比研究——以ChatGPT为例.** [[paper]](https://aclanthology.org/2023.ccl-1.46.pdf) ![](https://img.shields.io/badge/CCL%202023-orange) ![](https://img.shields.io/badge/2023.08-blue)

  *朱君辉, 王梦焰, 杨尔弘, 聂锦燃, 王誉杰, 岳岩 and 杨麟儿.*
  > Explore the differences between the language used in human-generated responses and responses generated by ChatGPT. Extract and compute the distribution of 159 language features in real human text and ChatGPT-generated text. Employ three machine learning algo-rithms: Random Forest, Logistic Regression, and SVM. The result reveals that the two texts differ significantly in three dimensions: descriptive features, word commonness, and word diversity.

- **HC3 Plus: A Semantic-Invariant Human ChatGPT Comparison Corpus.** [[paper]](https://arxiv.org/pdf/2309.02731) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.09-blue)

  *Zhenpeng Su, Xing Wu, Wei Zhou, Guangyuan Ma and Songlin Hu.*
  > Introduce a more extensive and comprehensive dataset that considers more types of tasks than previous work, including semantic-invariant tasks. Further instruct fine-tuning Tk-instruct and build a more powerful detection system. Experimental results show that the proposed detector outperforms the previous state-of-the-art RoBERTa-based detector.

- **J-Guard: Journalism Guided Adversarially Robust Detection of AI-generated News.** [[paper]](https://arxiv.org/pdf/2309.03164) ![](https://img.shields.io/badge/IJCNLP--AACL%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

  *Tharindu Kumarage, Amrita Bhattacharjee, Djordje Padejski, Kristy Roschke, Dan Gillmor, Scott Ruston, Huan Liu and Joshua Garland.*
  > Develop a framework, J-Guard, capable of steering existing supervised AI text detectors for detecting AI-generated news while boosting adversarial robustness. By incorporating stylistic cues inspired by the unique journalistic attributes, J-Guard effectively distinguishes between real-world journalism and AIgenerated news articles.

- **Overview of AuTexTification at IberLEF 2023: Detection and Attribution of Machine-Generated Text in Multiple Domains.** [[paper]](http://journal.sepln.org/sepln/ojs/ojs/index.php/pln/article/view/6559/3959) ![](https://img.shields.io/badge/Procesamiento%20del%20Lenguaje%20Natural%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

  *Areg Mikael Sarvazyan, José Ángel González, Marc Franco-Salvador, Francisco Rangel, Berta Chulvi and Paolo Rosso.*
  > This paper presents the overview of the AuTexTification shared task as part of the IberLEF 2023 Workshop. AuTexTification consists of two subtasks: for Subtask 1, participants had to determine whether a text is human-authored or has been generated by a large language model. For Subtask 2, participants had to attribute a machine-generated text to one of six different text generation models. In this overview, present the AuTexTification dataset and task, the submitted participating systems, and the results.

- **ConDA: Contrastive Domain Adaptation for AI-generated Text Detection.** [[paper]](https://arxiv.org/pdf/2309.03992.pdf) ![](https://img.shields.io/badge/IJCNLP--AACL%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

  *Amrita Bhattacharjee, Tharindu Kumarage, Raha Moraffah and Huan Liu.*
  > Address the problem of AIgenerated text detection in the absence of labeled target data. Propose a contrastive domain adaptation framework that leverages the power of both unsupervised domain adaptation and selfsupervised representation learning, in order to tackle the task of AI-generated text detection.

- **Supervised Machine-Generated Text Detectors: Family and Scale Matters.** [[paper]](https://link.springer.com/content/pdf/10.1007/978-3-031-42448-9_11.pdf?pdf=inline%20link) ![](https://img.shields.io/badge/CLEF%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

  *Areg Mikael Sarvazyan, José Ángel González, Paolo Rosso and Marc Franco-Salvador.*
  > This work studies the generalization capabilities of supervised Machine-Generated Text (MGT) detectors across model families and parameter scales of text generation models. In addition, explore the feasibility of identifying the family and scale of the generator behind an MGT, instead of attributing the text to a particular language model.

- **Use prompt to differentiate text generated by ChatGPT and humans.** [[paper]](https://www.sciencedirect.com/science/article/pii/S2666827023000506/pdfft?md5=eb0d84ba25f407e6267636d94235ef81&pid=1-s2.0-S2666827023000506-main.pdf) ![](https://img.shields.io/badge/MLWA%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

  *Ruopeng An, Yuyi Yang, Fan Yang and Shanshan Wang.*
  > Introduce a method that uses both prompts and essays to differentiate between machine-generated and human-written text. Validate its effectiveness in distinguishing between machine-generated and human-written essays and shows that it outperforms existing approaches based solely on text passages.

- **A Statistical Turing Test for Generative Models.** [[paper]](https://arxiv.org/pdf/2309.08913.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.09-blue)

  *Hayden Helm, Carey E. Priebe and Weiwei Yang.*
  > Provide a framework in the language of statistical pattern recognition that quantifies the difference between the distributions of human and machinegenerated content conditioned on an evaluation context. Describe current methods in the context of the framework and demonstrate how to use the framework to evaluate the progression of generative models towards human-like capabilities, among many axes of analysis.

- **TopRoBERTa: Topology-Aware Authorship Attribution of Deepfake Texts.** [[paper]](https://arxiv.org/pdf/2309.12934.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.09-blue)

  *Adaku Uchendu, Thai Le and Dongwon Lee.*
  > Propose TopRoBERTa to improve existing AA solutions by capturing more linguistic patterns in deepfake texts by including a Topological Data Analysis (TDA) layer in the RoBERTa model. Use RoBERTa to capture contextual representations (i.e., semantic and syntactic linguistic features), while using TDA to capture the shape and structure of data (i.e., linguistic structures). Finally, TopRoBERTa, outperforms the vanilla RoBERTa in 2/3 datasets, achieving up to 7% increase in Macro F1 score.

- **From Text to Source: Results in Detecting Large Language Model-Generated Content.** [[paper]](https://arxiv.org/pdf/2309.13322.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.09-blue)

  *Wissam Antoun, Benoît Sagot and Djamé Seddah.*
  > Investigate "Cross-Model Detection," evaluating whether a classifier trained to distinguish between source LLM-generated and humanwritten text can also detect text from a target LLM without further training. The study comprehensively explores various LLM sizes and families, and assesses the impact of conversational fine-tuning techniques on classifier generalization. The research also delves into Model Attribution, encompassing source model identification, model family classification, and model size classification.

- **Can LLM-Generated Misinformation Be Detected?** [[paper]](https://arxiv.org/pdf/2309.13788.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.09-blue)

  *Canyu Chen and Kai Shu.*
  > Build a taxonomy of LLM-generated misinformation. Categorize and validate the potential real-world methods for generating misinformation with LLMs. Discover that LLM-generated misinformation can be harder to detect for humans and detectors compared to human-written misinformation with the same semantics.

- **A Framework for Detecting AI-Generated Text in Research Publications.** [[paper]](https://proceedings.icatsconf.org/conf/index.php/ICAT/article/view/36/21) ![](https://img.shields.io/badge/ICAT%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

  *Paria Sarzaeim, Arya Doshi and Qusay Mahmoud.*
  > Present a framework for AI-generated text. The prototype implementation of the proposed approach is to train a model using predefined datasets and deploy this model on a cloud-based service to predict whether a text was created by a human or AI. This approach is specifically focused on assessing the accuracy of scientific writings and research papers rather than general text.

- **Supervised Machine Generated Text Detection Using LLM Encoders In Various Data Resource Scenarios.** [[paper]](https://digital.wpi.edu/downloads/hh63t0231?locale=en) ![](https://img.shields.io/badge/Dissertation-orange) ![](https://img.shields.io/badge/2023.09-blue)

  *Marc Capobianco, Matthew Reynolds, Charles Phelan, Krish Shah-Nathwani and Duong Luong.*
  > Explore the effectiveness of BERT and RoBERTa-based machine generated text detection in a supervised setting. Created several models for both BERT and RoBERTa, trained with 5%, 10%, 15%, 20%, and 100% of the dataset. Conduct these experiments with frozen and unfrozen parameter variations.

- **Machine-Generated Text Detection and Attribution.** [[paper]](https://riunet.upv.es/bitstream/handle/10251/197189/Sarvazyan%20-%20Machine-Generated%20Text%20Detection%20and%20Attribution.pdf?sequence=2&isAllowed=y) ![](https://img.shields.io/badge/Dissertation-orange) ![](https://img.shields.io/badge/2023.09-blue)

  *Sarvazyan and Areg Mikael.*
  > (i) study the MGT detection and attribution models that achieve high performance under various settings, (ii) explore their generalization capabilities to different scenarios, analyzing their applicability to unseen types of data, and (iii) successfully organize an evaluation campaign for MGT detection and attribution.

- Automated Text Identification Shared Task (AuTexTification)

  - **Automated Text Identification Using CNN and Training Dynamics.** [[paper]](https://ceur-ws.org/Vol-3496/autextification-paper1.pdf) ![](https://img.shields.io/badge/IberLEF%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

    *Claudiu Creanga and Liviu Petrisor Dinu.*

  - **Do Origin and Facts Identify Automatically Generated Text?** [[paper]](https://ceur-ws.org/Vol-3496/autextification-paper2.pdf) ![](https://img.shields.io/badge/IberLEF%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

    *Judita Preiss and Monica Lestari Paramita.*

  - **Syntax-based Contrastive Learning for Automated Text Identification.** [[paper]](https://ceur-ws.org/Vol-3496/autextification-paper3.pdf) ![](https://img.shields.io/badge/IberLEF%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

    *Hongyan Wu, Nankai Lin and Shengyi Jiang.*

  - **A Method for Identifying Bot Generated Text : Notebook for IberLEF 2023.** [[paper]](https://ceur-ws.org/Vol-3496/autextification-paper4.pdf) ![](https://img.shields.io/badge/IberLEF%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

    *Maryam Elamine, Asma Mekki and Lamia Hadrich Belguith.*

  - **Artificial Intelligence-Based Text Classification: Separating Human Writing from Computer Generated Writing.** [[paper]](https://ceur-ws.org/Vol-3496/autextification-paper5.pdf) ![](https://img.shields.io/badge/IberLEF%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

    *Luis Enrique Morales-Márquez, Erick Barrios-González and David Eduardo Pinto-Avendaño.*

  - **SINAI at AuTexTification in IberLEF 2023: Combining All Layer Embeddings for Automatically Generated Texts.** [[paper]](https://ceur-ws.org/Vol-3496/autextification-paper6.pdf) ![](https://img.shields.io/badge/IberLEF%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

    *César Espin-Riofrio, Jenny Ortiz-Zambrano and Arturo Montejo-Ráez.*

  - **I’ve Seen Things You Machines Wouldn’t Believe: Measuring Content Predictability to Identify Automatically-Generated Text.** [[paper]](https://ceur-ws.org/Vol-3496/autextification-paper7.pdf) ![](https://img.shields.io/badge/IberLEF%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

    *Piotr Przybyła, Nicolau Duran-Silva and Santiago Egea-Gómez.*

  - **Detecting Generated Text and Attributing Language Model Source with Fine-tuned Models and Semantic Understanding.** [[paper]](https://ceur-ws.org/Vol-3496/autextification-paper8.pdf) ![](https://img.shields.io/badge/IberLEF%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

    *Margherita Gambini, Marco Avvenuti, Fabrizio Falchi, Maurizio Tesconi and Tiziano Fagni.*

  - **AI-Writing Detection Using an Ensemble of Transformers and Stylometric Features.** [[paper]](https://ceur-ws.org/Vol-3496/autextification-paper9.pdf) ![](https://img.shields.io/badge/IberLEF%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

    *George Mikros, Athanasios Koursaris, Dimitrios Bilianos and George Markopoulos.*

  - **Exploring Text Representations for Detecting Automatically Generated Text.** [[paper]](https://ceur-ws.org/Vol-3496/autextification-paper10.pdf) ![](https://img.shields.io/badge/IberLEF%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

    *Zayra Villegas-Trejo, Helena Gómez-Adorno and Sergio-Luis Ojeda-Trueba.*

  - **GPT-2 versus GPT-3 and Bloom: LLMs for LLMs Generative Text Detection.** [[paper]](https://ceur-ws.org/Vol-3496/autextification-paper11.pdf) ![](https://img.shields.io/badge/IberLEF%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

    *Fernando Aguilar-Canto, Marco Cardoso-Moreno, Diana Jiménez and Hiram Calvo.*

  - **Taming the Turing Test: Exploring Machine Learning Approaches to Discriminate Human vs. AI-Generated Texts.** [[paper]](https://ceur-ws.org/Vol-3496/autextification-paper12.pdf) ![](https://img.shields.io/badge/IberLEF%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

    *Alberto Fernández-Hernández, Juan Luis Arboledas-Márquez, Julián Ariza-Merino and Salud María Jiménez-Zafra.*

  - **Team GPLSI at AuTexTification Shared Task: Determining the Authorship of a Text.** [[paper]](https://ceur-ws.org/Vol-3496/autextification-paper13.pdf) ![](https://img.shields.io/badge/IberLEF%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

    *Iván Martínez-Murillo, Robiert Sepúlveda-Torres, Estela Saquete, Elena LLoret and Manuel Palomar.*

  - **Generative AI Text Classification using Ensemble LLM Approaches.** [[paper]](https://ceur-ws.org/Vol-3496/autextification-paper14.pdf) ![](https://img.shields.io/badge/IberLEF%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

    *Harika Abburi, Michael Suesserman, Nirmala Pudota, Balaji Veeramani, Edward Bowen and Sanmitra Bhattacharya.*

  - **Automated Text Identification: Multilingual Transformer-based Models Approach.** [[paper]](https://ceur-ws.org/Vol-3496/autextification-paper15.pdf) ![](https://img.shields.io/badge/IberLEF%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

    *German Gritsay, Andrey Grabovoy, Aleksandr Kildyakov and Yury Chekhovich.*

  - **IberLEF 2023 AuTexTification: Automated Text Identification Shared Task – Team OD-21.** [[paper]](https://ceur-ws.org/Vol-3496/autextification-paper16.pdf) ![](https://img.shields.io/badge/IberLEF%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

    *Rinaldo Gagiano, Haytham Fayek, Maria Myung-Hee Kim, Jennifer Biggs and Xiuzhen Zhang.*

  - **Using Linguistic Knowledge for Automated Text Identification.** [[paper]](https://ceur-ws.org/Vol-3496/autextification-paper17.pdf) ![](https://img.shields.io/badge/IberLEF%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

    *Lara Alonso Simón, José Antonio Gonzalo Gimeno, Ana María Fernández-Pampillón Cesteros, Marianela Fernández Trinidad and María Victoria Escandell Vidal.*

  - **Univ. of Hildesheim at AuTexTification 2023: Detection of Automatically Generated Texts.** [[paper]](https://ceur-ws.org/Vol-3496/autextification-paper18.pdf) ![](https://img.shields.io/badge/IberLEF%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

    *Tatjana Scheibe and Thomas Mandl.*

  - **UPB at IberLEF-2023 AuTexTification: Detection of Machine-Generated Text using Transformer Ensembles.** [[paper]](https://ceur-ws.org/Vol-3496/autextification-paper19.pdf) ![](https://img.shields.io/badge/IberLEF%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

    *Andrei-Alexandru Preda, Dumitru-Clementin Cercel, Traian Rebedea and Costin-Gabriel Chiru.*

  - **Exploring the Distinction: Investigating the Recognition of Automatic Text Generation Systems and Differentiating Human Text from Language Models.** [[paper]](https://ceur-ws.org/Vol-3496/autextification-paper20.pdf) ![](https://img.shields.io/badge/IberLEF%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

    *Manex Agirrezabal.*

- **Looking for Traces of Textual Deepfakes in Bulgarian on Social Media.** [[paper]](https://aclanthology.org/2023.ranlp-1.122.pdf) ![](https://img.shields.io/badge/RANLP%202023-orange) ![](https://img.shields.io/badge/2023.09-blue)

  *Irina Temnikova, Iva Marinova, Silvia Gargova, Ruslana Margova and Ivan Koychev.*
  > Create a new Bulgarian-language dataset with real social media messages and those generated by two language models. Conclude that combining LM text detection with fact-checking is the most appropriate method for this task, and that identifying Bulgarian textual deepfakes is indeed possible.

- **On the Generalization of Training-based ChatGPT Detection Methods.** [[paper]](https://arxiv.org/pdf/2310.01307.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Han Xu, Jie Ren, Pengfei He, Shenglai Zeng, Yingqian Cui, Amy Liu, Hui Liu and Jiliang Tang.*
  > Aim to have a comprehensive investigation on existing methods’ generalization behaviors under distribution shift caused by a wide range of factors, including prompts, text lengths, topics, and language tasks. Collect a new dataset with human and ChatGPT texts, and then conduct extensive studies on the collected dataset.

- **Counter Turing Test CT^2: AI-Generated Text Detection is Not as Easy as You May Think -- Introducing AI Detectability Index.** [[paper]](https://arxiv.org/pdf/2310.05030.pdf) ![](https://img.shields.io/badge/EMNLP%202023-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Megha Chakraborty, S.M Towhidul Islam Tonmoy, S M Mehedi Zaman, Krish Sharma, Niyar R Barman, Chandan Gupta, Shreya Gautam, Tanay Kumar, Vinija Jain, Aman Chadha, Amit P. Sheth and Amitava Das.*
  > Introduce the Counter Turing Test (CT2), a benchmark consisting of techniques aiming to offer a comprehensive evaluation of the robustness of existing AGTD techniques. Establish a quantifiable spectrum facilitating the evaluation and ranking of LLMs according to their detectability levels, we propose the AI Detectability Index (ADI).

- **Fast-DetectGPT: Efficient Zero-Shot Detection of Machine-Generated Text via Conditional Probability Curvature.** [[paper]](https://arxiv.org/pdf/2310.05130.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Guangsheng Bao, Yanbin Zhao, Zhiyang Teng, Linyi Yang and Yue Zhang.*
  > Present Fast-DetectGPT, an optimized zero-shot detector, which substitutes DetectGPT’s perturbation step with a more efficient sampling step. The evaluations on various datasets, source models, and test conditions indicate that Fast-DetectGPT not only outperforms DetectGPT in both the whitebox and black-box settings but also accelerates the detection process by a factor of 340.

- **Zero-Shot Detection of Machine-Generated Codes.** [[paper]](https://arxiv.org/pdf/2310.05103.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Xianjun Yang, Kexun Zhang, Haifeng Chen, Linda Petzold, William Yang Wang and Wei Cheng.*
  > Propose a training-free approach for the detection of LLMs-generated codes, mitigating the risks associated with their indiscriminate usage. Modify the previous zero-shot text detection method, DetectGPT by utilizing a surrogate white-box model to estimate the probability of the rightmost tokens, allowing us to identify code snippets generated by language models.

- **How Reliable Are AI-Generated-Text Detectors? An Assessment Framework Using Evasive Soft Prompts.** [[paper]](https://arxiv.org/pdf/2310.05095.pdf) ![](https://img.shields.io/badge/EMNLP%202023%20Findings-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Tharindu Kumarage, Paras Sheth, Raha Moraffah, Joshua Garland and Huan Liu.*
  > Suggest a universal evasive prompt, a novel type of soft prompt, which guides PLMs in producing "human-like" text that can mislead the detectors. The novel universal evasive prompt is achieved in two steps: First, create an evasive soft prompt tailored to a specific PLM through prompt tuning; and then, leverage the transferability of soft prompts to transfer the learned evasive soft prompt from one PLM to another.

- **On the Zero-Shot Generalization of Machine-Generated Text Detectors.** [[paper]](https://arxiv.org/pdf/2310.05165.pdf) ![](https://img.shields.io/badge/EMNLP%202023%20Findings-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Xiao Pu, Jingyu Zhang, Xiaochuang Han, Yulia Tsvetkov and Tianxing He.*
  > Collect generation data from a wide range of LLMs, and train neural detectors on data from each generator and test its performance on heldout generators. Demonstrate that robust detectors can be built on an ensemble of training data from medium-sized models.

- **GPT-who: An Information Density-based Machine-Generated Text Detector.** [[paper]](https://arxiv.org/pdf/2310.06202.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Saranya Venkatraman, Adaku Uchendu and Dongwon Lee.*
  > Propose GPT-who, the first psycholinguistically-aware multi-class domainagnostic statistical-based detector. This detector employs UID-based features to model the unique statistical signature of each LLM and human author for accurate authorship attribution.

- **SeqXGPT: Sentence-Level AI-Generated Text Detection.** [[paper]](https://arxiv.org/pdf/2310.08903.pdf) ![](https://img.shields.io/badge/EMNLP%202023-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Pengyu Wang, Linyang Li, Ke Ren, Botian Jiang, Dong Zhang and Xipeng Qiu.*
  > Propose Sequence X (Check) GPT, a novel method that utilizes log probability lists from white-box LLMs as features for sentence-level AIGT detection. These features are composed like waves in speech processing and cannot be studied by LLMs. Build SeqXGPT based on convolution and self-attention networks.

- **Detecting Generated Text via Rewriting.** [[paper]](https://openreview.net/attachment?id=bQWE2UqXmf&name=pdf) ![](https://img.shields.io/badge/ICLR%202024%20Submission-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Anonymous authors.*
  > Find that large language models (LLMs) are more likely to modify human-written text than AI-generated text when tasked with rewriting. Introduce a method to detect AI-generated content by prompting LLMs to rewrite text and calculating the editing distance of the output.

- **Spotting LLMs With Binoculars: Zero-Shot Detection of Machine-Generated Text.** [[paper]](https://openreview.net/attachment?id=iARAKITHTH&name=pdf) ![](https://img.shields.io/badge/ICLR%202024%20Submission-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Anonymous authors.*
  > Propose a novel LLM detector that only requires simple calculations using pre-trained LLMs.  The method, called Binoculars, achieves state-of-the-art accuracy without any training data.

- **On the Possibilities of AI-Generated Text Detection: A Sample Complexity Analysis.** [[paper]](https://openreview.net/attachment?id=oxEER3kZ9M&name=pdf) ![](https://img.shields.io/badge/ICLR%202024%20Submission-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Anonymous authors.*
  > Establish precise sample complexity bounds for detecting AI-generated text. The empirical evaluations across multiple datasets confirm the viability of enhanced detection methods.

- **Human-in-the-loop Detection of AI-generated Text via Grammatical Patterns.** [[paper]](https://openreview.net/attachment?id=UZS6D7GfP1&name=pdf) ![](https://img.shields.io/badge/ICLR%202024%20Submission-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Anonymous authors.*
  > Focus on the problem of detecting AI-generated text in a domain where a training dataset of human-written samples is readily available. Our key insight is to learn interpretable grammatical patterns that are highly indicative of human or AI written text. The most useful of these patterns can then be given to humans as part of a human-in-the-loop approach.

- **Few-Shot Detection of Machine-Generated Text using Style Representations.** [[paper]](https://openreview.net/attachment?id=cWiEN1plhJ&name=pdf) ![](https://img.shields.io/badge/ICLR%202024%20Submission-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Anonymous authors.*
  > Pursue a approach not relying on samples from language models of concern at training time. Propose to leverage representations of writing style estimated from human-authored text. Find that features effective at distinguishing among human authors are also effective at distinguishing human from machine authors.

- **Metric Learning for Detection of Large Language Model Generated Texts.** [[paper]](https://openreview.net/attachment?id=LKx4rubqkO&name=pdf) ![](https://img.shields.io/badge/ICLR%202024%20Submission-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Anonymous authors.*
  > Present a new paradigm of metric-based detection for LLM-generated texts that is able to balance among computational costs, accessibility, and performances. Specifically, the detection is performed through evaluating the similarity between a given text to an equivalent example generated by LLMs and through that determining the former's origination.

- **Detecting Machine-Generated Texts by Multi-Population Aware Optimization for Maximum Mean Discrepancy.** [[paper]](https://openreview.net/attachment?id=3fEKavFsnv&name=pdf) ![](https://img.shields.io/badge/ICLR%202024%20Submission-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Anonymous authors.*
  > Propose a novel multi-population aware optimization method for MMD called MMD-MP, which can avoid variance increases and thus improve the stability to measure the distributional discrepancy. Relying on MMD-MP, develop two methods for paragraph-based and sentence-based detection, respectively.

- **Using AI-based detectors to control AI-assisted plagiarism in ESL writing: “The Terminator Versus the Machines”.** [[paper]](https://languagetestingasia.springeropen.com/counter/pdf/10.1186/s40468-023-00260-2.pdf) ![](https://img.shields.io/badge/Language%20Testing%20in%20Asia%202023-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Karim Ibrahim.*
  > To address the challenge of AI-assisted plagiarism in ESL contexts, the present cross-disciplinary descriptive study examined the potential of two RoBERTa-based classifiers to control AI-assisted plagiarism on a dataset of 240 human-written and ChatGPT-generated essays. Data analysis revealed that both platforms could identify AI-generated texts, but their detection accuracy was inconsistent across the dataset.

- **An Ensemble-Based Approach for Generative Language Model Attribution.** [[paper]](https://link.springer.com/chapter/10.1007/978-981-99-7254-8_54) ![](https://img.shields.io/badge/WISE%202023-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Harika Abburi, Michael Suesserman, Nirmala Pudota, Balaji Veeramani, Edward Bowen and Sanmitra Bhattacharya.*
  > Propose an ensemble neural model that generates probabilities from multiple pre-trained LLMs, which are then used as features for a traditional machine learning classifier.

- **DetectGPT-SC: Improving Detection of Text Generated by Large Language Models through Self-Consistency with Masked Predictions.** [[paper]](https://arxiv.org/pdf/2310.14479.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Rongsheng Wang, Qi Li and Sihong Xie.*
  > Find that large language models such as ChatGPT exhibit strong self-consistency in text generation and continuation. Propose DetectGPT-SC for AI-generated texts detection based on self-consistency with masked predictions to determine whether a text is generated by LLMs.

- **Do Stochastic Parrots have Feelings Too? Improving Neural Detection of Synthetic Text via Emotion Recognition.** [[paper]](https://arxiv.org/pdf/2310.15904.pdf) ![](https://img.shields.io/badge/EMNLP%202023%20Findings-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Alan Cowap, Yvette Graham and Jennifer Foster.*
  > Hypothesize that pretrained language models (PLMs) have an affective deficit because of lacking the kind of emotional coherence present in human-authored text. Develop an emotionally aware detector by fine-tuning a PLM on emotion.

- **How well can machine-generated texts be identified and can language models be trained to avoid identification?** [[paper]](https://arxiv.org/pdf/2310.16992.pdf) ![](https://img.shields.io/badge/HICSS%202024-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Sinclair Schneider, Florian Steuber, Joao A. G. Schneider and Gabi Dreo Rodosek.*
  > Highlight the significance of sampling techniques and the essential role of employing advanced models like transformers to detect generated texts accurately. Demonstrate how a malicious actor could adapt generative models to evade a detector if accessible.

- **An Ensemble Method Based on the Combination of Transformers with Convolutional Neural Networks to Detect Artificially Generated Text.** [[paper]](https://arxiv.org/pdf/2310.17312.pdf) ![](https://img.shields.io/badge/ALTA%202023-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Vijini Liyanage and Davide Buscaldi.*
  > Present some classification models constructed by ensembling transformer models such as SciBERT, DeBERTa and XLNet, with Convolutional Neural Networks (CNNs). The experiments demonstrate that the considered ensemble architectures surpass the performance of the individual transformer models for classification.

- **Detection of news written by the ChatGPT through authorship attribution performed by a Bidirectional LSTM model.** [[paper]](https://arxiv.org/pdf/2310.16685.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Amanda Ferrari Iaquinta and Gustavo Voltani von Atzingen.*
  > A dataset containing equal amounts of human and ChatGPT written news was assembled and different natural processing language techniques were used to extract features from it that were used to train, validate and test three models built with different techniques. The best performance was produced by the Bidirectional Long Short Term Memory (LSTM) Neural Network model.

- **Stacking the Odds: Transformer-Based Ensemble for AI-Generated Text Detection.** [[paper]](https://arxiv.org/pdf/2310.18906.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Duke Nguyen, Khaing Myat Noe Naing and Aditya Joshi.*
  > Use a stacking ensemble of Transformers for the task of AI-generated text detection. The approach is novel in terms of its choice of models in that we use accessible and lightweight models in the ensemble.

- **A Simple yet Efficient Ensemble Approach for AI-generated Text Detection.** [[paper]](https://arxiv.org/pdf/2311.03084.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.11-blue)

  *Harika Abburi, Kalyani Roy, Michael Suesserman, Nirmala Pudota, Balaji Veeramani, Edward Bowen and Sanmitra Bhattacharya.*
  > Propose a simple yet efficient solution to this problem by ensembling predictions from multiple constituent LLMs. Study the influence that the training data from individual LLMs have on model performance. Find that substituting commercially-restrictive GPT data with data generated from other open language models is a feasible alternative when developing generative text detectors.

- **Detecting and Unmasking AI-Generated Texts through Explainable Artificial Intelligence using Stylistic Features.** [[paper]](https://thesai.org/Downloads/Volume14No10/Paper_110-Detecting_and_Unmasking_AI_Generated_Texts.pdf) ![](https://img.shields.io/badge/IJACSA%202023-orange) ![](https://img.shields.io/badge/2023.11-blue)

  *Aditya Shah, Prateek Ranka, Urmi Dedhia, Shruti Prasad, Siddhi Muni and Kiran Bhowmick.*
  > The research delves into parameters such as syllable count, word length, sentence structure, functional word usage, and punctuation ratios to detect AI-generated text. Furthermore, the research integrates Explainable AI (xAI) techniques—LIME and SHAP—to enhance the interpretability of machine learning model predictions.

- **DEMASQ: Unmasking the ChatGPT Wordsmith.** [[paper]](https://arxiv.org/pdf/2311.05019.pdf) ![](https://img.shields.io/badge/NDSS%202024-orange) ![](https://img.shields.io/badge/2023.11-blue)

  *Kavita Kumari, Alessandro Pegoraro, Hossein Fereidooni and Ahmad-Reza Sadeghi.*
  > Propose an effective ChatGPT detector named DEMASQ, which accurately identifies ChatGPT-generated content. The method addresses two critical factors: (i) the distinct biases in text composition observed in human- and machinegenerated content and (ii) the alterations made by humans to evade previous detection methods.

- **AuthentiGPT: Detecting Machine-Generated Text via Black-Box Language Models Denoising.** [[paper]](https://arxiv.org/pdf/2311.07700.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.11-blue)

  *Zhen Guo and Shangdi Yu.*
  > Present AuthentiGPT, an efficient classifier that distinguishes between machine-generated and human-written texts. Under the assumption that humanwritten text resides outside the distribution of machine-generated text, AuthentiGPT leverages a black-box LLM to denoise input text with artificially added noise, and then semantically compares the denoised text with the original to determine if the content is machine-generated.

- **How You Prompt Matters! Even Task-Oriented Constraints in Instructions Affect LLM-Generated Text Detection.** [[paper]](https://arxiv.org/pdf/2311.08369.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.11-blue)

  *Ryuto Koike, Masahiro Kaneko and Naoaki Okazaki.*
  > Discover that even a task-oriented constraint in instruction can cause the inconsistent performance of current detectors to the generated texts. Show that the detection performance variance of the current detector on texts generated by instruction with each task-oriented constraint is up to 20 times larger than the variance caused by generating texts multiple times and paraphrasing the instruction.

#### Detector Attack
- **Attacking Neural Text Detectors.** [[paper]](https://trustworthyiclr20.github.io/wolff.pdf) ![](https://img.shields.io/badge/ICLR%202020%20Workshop-orange) ![](https://img.shields.io/badge/2020.02-blue)

  *Max Wolff, Stuart Wolff.*
  > Present two classes of black-box attacks on neural text detectors, one which randomly replaces characters with homoglyphs, and the other a simple scheme to purposefully misspell words. The homoglyph and misspelling attacks decrease a popular neural text detector's recall on neural text from 97.44% to 0.26% and 22.68%, respectively.

- **Adversarial Robustness of Neural-Statistical Features in Detection of Generative Transformers.** [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9892269) ![](https://img.shields.io/badge/IJCNN%202022-orange) ![](https://img.shields.io/badge/2022.03-blue)

  *Evan Crothers, Nathalie Japkowicz, Herna Viktor and Paula Branco.*
  > Assess each model’s relative performance at classifying computer-generated text. Evaluat models for robustness in the presence of text adversarial attacks. Find that statistical features are considerably more robust to adversarial attack than Transformer-derived features.

- **Exploring Semantic Perturbations on Grover.** [[paper]](https://arxiv.org/pdf/2302.00509) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.02-blue)

  *Pranav Kulkarni, Ziqing Ji, Yan Xu, Marko Neskovic and Kevin Nolan.*
  > Find that Grover-generated substitution, GPT2-generated substitution, length changing, and perturbations informed with the model’s embedding table were all effective to some degree in fooling Grover’s detection.

- **Can AI-Generated Text be Reliably Detected?** [[paper]](https://arxiv.org/pdf/2303.11156) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.03-blue)

  *Vinu Sankar Sadasivan, Aounon Kumar, Sriram Balasubramanian, Wenxiao Wang and Soheil Feizi.*
  > Show that paraphrasing attacks can break detectors using the watermarking schemes as well as neural network-based detectors and zero-shot classifiers. Even LLMs protected by watermarking schemes can be vulnerable against spoofing attacks.

- **Paraphrasing evades detectors of AI-generated text, but retrieval is an effective defense.** [[paper]](https://arxiv.org/pdf/2303.13408) ![](https://img.shields.io/badge/NeurIPS%202023-orange) ![](https://img.shields.io/badge/2023.03-blue)

  *Kalpesh Krishna, Yixiao Song, Marzena Karpinska, John Wieting and Mohit Iyyer.*
  > Present DIPPER, a discourse paraphrase generation model. DIPPER paraphrases easily evade these detectors while approximately preserving input semantics. Propose a retrieval-based mechanism to defend against such paraphrase attacks. Experiments show that this retrieval defense significantly outperforms baseline detectors on paraphrased text, and is effective at scale.

- **GPT detectors are biased against non-native English writers.** [[paper]](https://arxiv.org/pdf/2304.02819) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.04-blue)

  *Weixin Liang, Mert Yuksekgonul, Yining Mao, Eric Wu and James Zou.*
  > Find that several widely-used GPT detectors consistently misclassify non-native English writing samples as AI-generated, whereas native writing samples are accurately identified. Demonstrate that simple prompting strategies can not only mitigate this bias but also effectively bypass GPT detectors.

- **Stochastic Parrots Looking for Stochastic Parrots: LLMs are Easy to Fine-Tune and Hard to Detect with other LLMs.** [[paper]](https://arxiv.org/pdf/2304.08968) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.04-blue)

  *Da Silva Gameiro Henrique, Andrei Kucharavy and Rachid Guerraoui.*
  > Show that generative LLM detection with a discriminator LLM is impossible if the attacker has access to the reference "human" dataset used to train the discriminator LLM. Simply fine-tuning the dataset and using prompts from it leads to a complete failure of the discriminator to learn the difference between machine and human-generated texts, even in a setting where all LLM outputs are correctly labeled.

- **Large Language Models can be Guided to Evade AI-Generated Text Detection.** [[paper]](https://arxiv.org/pdf/2305.10847) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Ning Lu, Shengcai Liu, Rui He, Qi Wang and Ke Tang.*
  > Reveal that with the aid of carefully crafted prompts, LLMs can effectively evade detection systems. Propose a novel Substitution-based In-Context example Optimization method (SICO) to automatically generate such prompts. On three real-world tasks where LLMs can be misused, SICO successfully enables ChatGPT to evade six existing detectors, causing a significant 0.54 AUC drop on average.

- **Red Teaming Language Model Detectors with Language Models.** [[paper]](https://arxiv.org/pdf/2305.19713) ![](https://img.shields.io/badge/TACL%202023-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Zhouxing Shi, Yihan Wang, Fan Yin, Xiangning Chen, Kai-Wei Chang and Cho-Jui Hsieh.*
  > Systematically test the reliability of the existing detectors, by designing two types of attack strategies to fool the detectors: 1) replacing words with their synonyms based on the context; 2) altering the writing style of generated text. Reveal that these attacks effectively compromise the performance of all tested detectors.

- **Evade ChatGPT Detectors via A Single Space.** [[paper]](https://arxiv.org/pdf/2307.02599) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.07-blue)

  *Shuyang Cai and Wanyun Cui.*
  > Find that detectors do not effectively discriminate the semantic and stylistic gaps between human-generated and AI-generated conten. Instead, the “subtle differences”, such as an extra space, become crucial for detection. Based on this discovery, propose the SpaceInfi strategy to evade detection.

#### Benchmark
- **TURINGBENCH: A Benchmark Environment for Turing Test in the Age of Neural Text Generation.** [[paper]](https://aclanthology.org/2021.findings-emnlp.172.pdf) ![](https://img.shields.io/badge/EMNLP%202021%20Findings-orange) ![](https://img.shields.io/badge/2021.09-blue)

  *Adaku Uchendu, Zeyu Ma, Thai Le, Rui Zhang and Dongwon Lee.*
  > TuringBench is a benchmark environment that contains: (1)Benchmark tasks- Turing Test (i.e., human vs. machine) and Authorship Attribution: (i.e., who is the author of this texts?) (2) Datasets (Binary and Multi-class settings) (3) Website with leaderboard.

- **A Benchmark Corpus for the Detection of Automatically Generated Text in Academic Publications.** [[paper]](http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.501.pdf) ![](https://img.shields.io/badge/LREC%202022-orange) ![](https://img.shields.io/badge/2022.02-blue)

  *Vijini Liyanage, Davide Buscaldi and Adeline Nazarenko.*
  > Propose two datasets comprised of artificially generated research content: a completely synthetic dataset and a partial text substitution dataset.

- **MGTBench: Benchmarking Machine-Generated Text Detection.** [[paper]](https://arxiv.org/pdf/2303.14822) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.03-blue)

  *Xinlei He, Xinyue Shen, Zeyuan Chen, Michael Backes and Yang Zhang.*
  > Consider 6 metric-based detection methods and 2 model-based detection methods under ChatGPT. And integrate the detection methods as well as datasets into a modular-designed framework named MGTBench.

- **M4: Multi-generator, Multi-domain, and Multi-lingual Black-Box Machine-Generated Text Detection.** [[paper]](https://arxiv.org/pdf/2305.14902) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Yuxia Wang, Jonibek Mansurov, Petar Ivanov, Jinyan Su, Artem Shelmanov, Akim Tsvigun, Chenxi Whitehouse, Osama Mohammed Afzal, Tarek Mahmoud, Alham Fikri Aji and Preslav Nakov.*
  > Introduce a large-scale benchmark M4, which is multigenerator, multi-domain, and multi-lingual corpus for machine-generated text detection. Using the dataset, experiment with a number of methods and show that it is challenging for detectors to generalize well on unseen examples if they are either from different domains or are generated by different large language models.

- **Distinguishing Fact from Fiction: A Benchmark Dataset for Identifying Machine-Generated Scientific Papers in the LLM Era.** [[paper]](https://aclanthology.org/2023.trustnlp-1.17.pdf) ![](https://img.shields.io/badge/TrustNLP%202023-orange) ![](https://img.shields.io/badge/2023.07-blue)

  *Edoardo Mosca, Mohamed Hesham Ibrahim Abdalla, Paolo Basso, Margherita Musumeci and Georg Groh.*
  > Introduce a novel benchmark dataset, containing human-written and machine-generated scientific papers from SCIgen, GPT-2, GPT-3, ChatGPT, and Galactica. Experiment with four distinct classifiers as a baseline for detecting the authorship of scientific text.

- **Med-MMHL: A Multi-Modal Dataset for Detecting Human- and LLM-Generated Misinformation in the Medical Domain.** [[paper]](https://arxiv.org/pdf/2306.08871) ![](https://img.shields.io/badge/Preprint%202023-orange) ![](https://img.shields.io/badge/2023.07-blue)

  *Yanshen Sun, Jianfeng He, Shuo Lei, Limeng Cui and Chang-Tien Lu.*
  > Present Med-MMHL, a novel multi-modal misinformation detection dataset in a general medical domain encompassing multiple diseases. Med-MMHL not only incorporates human-generated misinformation but also includes misinformation generated by LLMs like ChatGPT.

- **An Empirical Study of AI Generated Text Detection Tools.** [[paper]](https://arxiv.org/pdf/2310.01423.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.09-blue)

  *Arslan Akram.*
  > Create a multidomain dataset for testing the state-of-the-art APIs and tools for detecting artificially generated information used by universities and other research institutions. Six different artificial intelligence (AI) text identification systems, including "GPTkit," "GPTZero," "Originality," "Sapling," "Writer," and "Zylalab," have accuracy rates between 55.29 and 97.0%.

- **Who Said That? Benchmarking Social Media AI Detection.** [[paper]](https://arxiv.org/pdf/2310.08240.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Wanyun Cui, Linqiu Zhang, Qianle Wang and Shuyang Cai.*
  > Introduce SAID (Social media AI Detection), a novel benchmark developed to assess AI-text detection models' capabilities in real social media platforms. It incorporates real AI-generate text from popular social media platforms like Zhihu and Quora. Present a new user-oriented AI-text detection challenge focusing on the practicality and effectiveness of identifying AI-generated text based on user information and multiple responses.

- **MULTITuDE: Large-Scale Multilingual Machine-Generated Text Detection Benchmark.** [[paper]](https://arxiv.org/pdf/2310.13606.pdf) ![](https://img.shields.io/badge/EMNLP%202023-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Dominik Macko, Robert Moro, Adaku Uchendu, Jason Samuel Lucas, Michiharu Yamashita, Matúš Pikuliak, Ivan Srba, Thai Le, Dongwon Lee, Jakub Simko and Maria Bielikova.*
  > Introduce MULTITuDE, a novel benchmarking dataset for multilingual machine-generated text detection comprising of 74,081 authentic and machine-generated texts in 11 languages (ar, ca, cs, de, en, es, nl, pt, ru, uk, and zh) generated by 8 multilingual LLMs.

- **HANSEN: Human and AI Spoken Text Benchmark for Authorship Analysis.** [[paper]](https://arxiv.org/pdf/2310.16746.pdf) ![](https://img.shields.io/badge/EMNLP%202023%20Findings-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Nafis Tripto, Adaku Uchendu, Thai Le, Mattia Setzu, Fosca Giannotti and Dongwon Lee.*
  > Introduce the largest benchmark for spoken texts - HANSEN (Human ANd ai Spoken tExt beNchmark). HANSEN encompasses meticulous curation of existing speech datasets accompanied by transcripts, alongside the creation of novel AI-generated spoken text datasets. Together, it comprises 17 human datasets, and AI-generated spoken texts created using 3 prominent LLMs: ChatGPT, PaLM2, and Vicuna13B.

#### Tracing Text Provenance & Watermarking
- **Adversarial Watermarking Transformer: Towards Tracing Text Provenance with Data Hiding.** [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9519400) ![](https://img.shields.io/badge/S&P%202021-orange) ![](https://img.shields.io/badge/2020.09-blue)

  *Sahar Abdelnabi and Mario Fritz.*

- **Tracing Text Provenance via Context-Aware Lexical Substitution.** [[paper]](https://ojs.aaai.org/index.php/AAAI/article/download/21415/21164) ![](https://img.shields.io/badge/AAAI%202022-orange) ![](https://img.shields.io/badge/2021.12-blue)

  *Xi Yang, Jie Zhang, Kejiang Chen, Weiming Zhang, Zehua Ma, Feng Wang and Nenghai Yu.*

- **On Information Hiding in Natural Language Systems.** [[paper]](https://journals.flvc.org/FLAIRS/article/download/130602/133919/233024) ![](https://img.shields.io/badge/FLAIRS%202022-orange) ![](https://img.shields.io/badge/2022.03-blue)

  *Geetanjali Bihani, Julia Taylor Rayz.*

- **Protecting Intellectual Property of Language Generation APIs with Lexical Watermark.** [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/21321/21070) ![](https://img.shields.io/badge/AAAI%202022-orange) ![](https://img.shields.io/badge/2022.06-blue)

  *Xuanli He, Qiongkai Xu, Lingjuan Lyu, Fangzhao Wu and Chenguang Wang.*

- **DeepHider: A Covert NLP Watermarking Framework Based on Multi-task Learning.** [[paper]](https://arxiv.org/pdf/2208.04676) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2022.08-blue)

  *Long Dai, Jiarong Mao, Xuefeng Fan and Xiaoyi Zhou.*

- **CATER: Intellectual Property Protection on Text Generation APIs via Conditional Watermarks.** [[paper]](https://openreview.net/pdf?id=L7P3IvsoUXY) ![](https://img.shields.io/badge/NeurIPS%202022-orange) ![](https://img.shields.io/badge/2022.09-blue)

  *Xuanli He, Qiongkai Xu, Yi Zeng, Lingjuan Lyu, Fangzhao Wu, Jiwei Li and Ruoxi Jia.*

- **A Watermark for Large Language Models.** [[paper]](https://arxiv.org/pdf/2301.10226) ![](https://img.shields.io/badge/ICML%202023-orange) ![](https://img.shields.io/badge/2023.01-blue)

  *John Kirchenbauer, Jonas Geiping, Yuxin Wen, Jonathan Katz, Ian Miers and Tom Goldstein.*

- **Protecting Language Generation Models via Invisible Watermarking.** [[paper]](https://arxiv.org/pdf/2302.03162) ![](https://img.shields.io/badge/ICML%202023-orange) ![](https://img.shields.io/badge/2023.02-blue)

  *Xuandong Zhao, Yu-Xiang Wang and Lei Li.*

- **Robust Natural Language Watermarking through Invariant Features.** [[paper]](https://arxiv.org/pdf/2305.01904) ![](https://img.shields.io/badge/ACL%202023-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *KiYoon Yoo, Wonhyuk Ahn, Jiho Jang and Nojun Kwak.*

- **Watermarking Text Generated by Black-Box Language Models.** [[paper]](https://arxiv.org/pdf/2305.08883) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Xi Yang, Kejiang Chen, Weiming Zhang, Chang Liu, Yuang Qi, Jie Zhang, Han Fang and Nenghai Yu.*

- **Are You Copying My Model? Protecting the Copyright of Large Language Models for EaaS via Backdoor Watermark.** [[paper]](https://arxiv.org/pdf/2305.10036) ![](https://img.shields.io/badge/ACL%202023-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Wenjun Peng, Jingwei Yi, Fangzhao Wu, Shangxi Wu, Bin Zhu, Lingjuan Lyu, Binxing Jiao, Tong Xu, Guangzhong Sun and Xing Xie.*

- **Watermarking Text Data on Large Language Models for Dataset Copyright Protection.** [[paper]](https://arxiv.org/pdf/2305.13257) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Yixin Liu, Hongsheng Hu, Xuyun Zhang and Lichao Sun.*

- **Who Wrote this Code? Watermarking for Code Generation.** [[paper]](https://arxiv.org/pdf/2305.15060) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Taehyun Lee, Seokhee Hong, Jaewoo Ahn, Ilgee Hong, Hwaran Lee, Sangdoo Yun, Jamin Shin and Gunhee Kim.*

- **Undetectable Watermarks for Language Models.** [[paper]](https://eprint.iacr.org/2023/763.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Miranda Christ, Sam Gunn and Or Zamir.*

- **Baselines for Identifying Watermarked Large Language Models.** [[paper]](https://arxiv.org/pdf/2305.18456) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Leonard Tang, Gavin Uberti and Tom Shlomi.*

- **On the Reliability of Watermarks for Large Language Models.** [[paper]](https://arxiv.org/pdf/2306.04634) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *John Kirchenbauer, Jonas Geiping, Yuxin Wen, Manli Shu, Khalid Saifullah, Kezhi Kong, Kasun Fernando, Aniruddha Saha, Micah Goldblum and Tom Goldstein.*

- **Provable Robust Watermarking for AI-Generated Text.** [[paper]](https://openreview.net/pdf?id=Bwz0fy9Hc9) ![](https://img.shields.io/badge/ICML%202023%20Workshop-orange) ![](https://img.shields.io/badge/2023.06-blue)

  *Xuandong Zhao, Prabhanjan Vijendra Ananth, Lei Li and Yu-Xiang Wang.*

- **Watermarking Conditional Text Generation for AI Detection: Unveiling Challenges and a Semantic-Aware Watermark Remedy.** [[paper]](https://arxiv.org/pdf/2307.13808) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.07-blue)

  *Yu Fu, Deyi Xiong and Yue Dong.*

- **Robust Distortion-free Watermarks for Language Models.** [[paper]](https://arxiv.org/pdf/2307.15593) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.07-blue)

  *Rohith Kuditipudi, John Thickstun, Tatsunori Hashimoto and Percy Liang.*

- **Three Bricks to Consolidate Watermarks for Large Language Models.** [[paper]](https://arxiv.org/pdf/2308.00113) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.07-blue)

  *Pierre Fernandez, Antoine Chaffin, Karim Tit, Vivien Chappelier and Teddy Furon.*

- **Towards Codable Text Watermarking for Large Language Models.** [[paper]](https://arxiv.org/pdf/2307.15992) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.07-blue)

  *Lean Wang, Wenkai Yang, Deli Chen, Hao Zhou, Yankai Lin, Fandong Meng, Jie Zhou and Xu Sun.*

- **A Private Watermark for Large Language Models.** [[paper]](https://arxiv.org/pdf/2307.16230) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.07-blue)

  *Aiwei Liu, Leyi Pan, Xuming Hu, Shu'ang Li, Lijie Wen, Irwin King and Philip S. Yu.*

- **Advancing Beyond Identification: Multi-bit Watermark for Large Language Models.** [[paper]](https://arxiv.org/pdf/2308.00221) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.08-blue)

  *KiYoon Yoo, Wonhyuk Ahn and Nojun Kwak.*

- **Unbiased Watermark for Large Language Models.** [[paper]](https://arxiv.org/pdf/2310.10669.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.09-blue)

  *Zhengmian Hu, Lichang Chen, Xidong Wu, Yihan Wu, Hongyang Zhang and Heng Huang.*

- **Necessary and Sufficient Watermark for Large Language Models.** [[paper]](https://arxiv.org/pdf/2310.00833) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Yuki Takezawa, Ryoma Sato, Han Bao, Kenta Niwa and Makoto Yamada.*

- **SemStamp: A Semantic Watermark with Paraphrastic Robustness for Text Generation.** [[paper]](https://arxiv.org/pdf/2310.03991.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Abe Bohan Hou, Jingyu Zhang, Tianxing He, Yichen Wang, Yung-Sung Chuang, Hongwei Wang, Lingfeng Shen, Benjamin Van Durme, Daniel Khashabi and Yulia Tsvetkov.*

- **A Semantic Invariant Robust Watermark for Large Language Models.** [[paper]](https://arxiv.org/pdf/2310.06356.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Aiwei Liu, Leyi Pan, Xuming Hu, Shiao Meng and Lijie Wen.*

- **DiPmark: A Stealthy, Efficient and Resilient Watermark for Large Language Models.** [[paper]](https://arxiv.org/pdf/2310.07710.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Yihan Wu, Zhengmian Hu, Hongyang Zhang and Heng Huang.*

- **WASA: WAtermark-based Source Attribution for Large Language Model-Generated Data.** [[paper]](https://arxiv.org/pdf/2310.00646.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Jingtan Wang, Xinyang Lu, Zitong Zhao, Zhongxiang Dai, Chuan-Sheng Foo, See-Kiong Ng and Bryan Kian Hsiang Low.*

- **On the Learnability of Watermarks for Language Models.** [[paper]](https://openreview.net/attachment?id=9k0krNzvlV&name=pdf) ![](https://img.shields.io/badge/ICLR%202024%20Submission-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Anonymous authors.*

- **Double-I Watermark: Protecting Model Copyright for LLM Fine-tuning.** [[paper]](https://openreview.net/attachment?id=ecbRyZZmKG&name=pdf) ![](https://img.shields.io/badge/ICLR%202024%20Submission-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Anonymous authors.*

- **I Know You Did Not Write That! A Sampling Based Watermarking Method for Identifying Machine Generated Text.** [[paper]](https://openreview.net/attachment?id=eKGEsFdpin&name=pdf) ![](https://img.shields.io/badge/ICLR%202024%20Submission-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Anonymous authors.*

- **Watermarking LLMs with Weight Quantization.** [[paper]](https://arxiv.org/pdf/2310.11237.pdf) ![](https://img.shields.io/badge/EMNLP%202023%20Findings-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Linyang Li, Botian Jiang, Pengyu Wang, Ke Ren, Hang Yan and Xipeng Qiu.*

- **Embarrassingly Simple Text Watermarks.** [[paper]](https://arxiv.org/pdf/2310.08920.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Ryoma Sato, Yuki Takezawa, Han Bao, Kenta Niwa and Makoto Yamada.*

- **REMARK-LLM: A Robust and Efficient Watermarking Framework for Generative Large Language Models.** [[paper]](https://arxiv.org/pdf/2310.12362.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Ruisi Zhang, Shehzeen Samarah Hussain, Paarth Neekhara and Farinaz Koushanfar.*

- **Publicly Detectable Watermarking for Language Models.** [[paper]](https://eprint.iacr.org/2023/1661.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.10-blue)

  *Jaiden Fairoze, Sanjam Garg, Somesh Jha, Saeed Mahloujifar, Mohammad Mahmoody and Mingyuan Wang.*

- **Watermarks in the Sand: Impossibility of Strong Watermarking for Generative Models.** [[paper]](https://arxiv.org/pdf/2311.04378.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.11-blue)

  *Hanlin Zhang, Benjamin L. Edelman, Danilo Francati, Daniele Venturi, Giuseppe Ateniese and Boaz Barak.*

- **WaterBench: Towards Holistic Evaluation of Watermarks for Large Language Models.** [[paper]](https://arxiv.org/pdf/2311.07138.pdf) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.11-blue)

  *Shangqing Tu, Yuliang Sun, Yushi Bai, Jifan Yu, Lei Hou and Juanzi Li.*

#### Other Related Work
- **MAUVE: Measuring the Gap Between Neural Text and Human Text using Divergence Frontiers.** [[paper]](https://proceedings.neurips.cc/paper/2021/file/260c2432a0eecc28ce03c10dadc078a4-Paper.pdf) ![](https://img.shields.io/badge/NeurIPS%202021-orange) ![](https://img.shields.io/badge/2021.02-blue)

  *Krishna Pillutla, Swabha Swayamdipta, Rowan Zellers, John Thickstun, Sean Welleck, Yejin Choi and Zaid Harchaoui.*
  > Develop MAUVE, a comparison measure for open-ended text generation, which directly compares the learnt distribution from a text generation model to the distribution of human-written text using divergence frontiers.

- **Is GPT-3 Text Indistinguishable from Human Text? Scarecrow: A Framework for Scrutinizing Machine Text.** [[paper]](https://aclanthology.org/2022.acl-long.501.pdf) ![](https://img.shields.io/badge/ACL%202022-orange) ![](https://img.shields.io/badge/2021.07-blue)

  *Yao Dou, Maxwell Forbes, Rik Koncel-Kedziorski, Noah A. Smith and Yejin Choi.*
  > Develop Scarecrow, a methodology for eliciting categorical judgements of errors in machine-generated text from crowd workers. Quantify measurable gaps between human authored text and generations from models of several sizes.

- **Automatic Detection of Entity-Manipulated Text using Factual Knowledge.** [[paper]](https://aclanthology.org/2022.acl-short.10.pdf) ![](https://img.shields.io/badge/ACL%202022-orange) ![](https://img.shields.io/badge/2022.03-blue)

  *Ganesh Jawahar, Muhammad Abdul-Mageed and Laks Lakshmanan.*
  > Present an approach that can detect entity-manipulated text articles. The proposed detector exploits explicit factual knowledge from a knowledge base to overcome the limitations of relying only on stylometric signals. Constructed challenging manipulated datasets by considering various entity replacement strategies, including with random selection and GPT-2 generation.

- **Unraveling the Mystery of Artifacts in Machine Generated Text.** [[paper]](http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.744.pdf) ![](https://img.shields.io/badge/LREC%202022-orange) ![](https://img.shields.io/badge/2022.06-blue)

  *Jiashu Pu, Ziyi Huang, Yadong Xi, Guandan Chen, Weijie Chen and Rongsheng Zhang.*
  > Reveal characteristics and possible manifestations of artifacts. Locate artifacts mainly based on the performance variation of the classifier against different corruptions.

- **On the Possibilities of AI-Generated Text Detection.** [[paper]](https://arxiv.org/pdf/2304.04736) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.04-blue)

  *Souradip Chakraborty, Amrit Singh Bedi, Sicheng Zhu, Bang An, Dinesh Manocha and Furong Huang.*
  > Provide evidence that it should almost always be possible to detect the AI-generated text unless the distributions of human and machine generated texts are exactly the same over the entire support.

- **Towards an Understanding and Explanation for Mixed-Initiative Artificial Scientific Text Detection.** [[paper]](https://arxiv.org/pdf/2304.05011) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.04-blue)

  *Luoxuan Weng, Minfeng Zhu, Kam Kwai Wong, Shi Liu, Jiashun Sun, Hang Zhu, Dongming Han and Wei Chen.*
  >  A formative study that identifies critical distinctions and summarizes design requirements for artificial scientific text detection. Propose a novel workflow and a prototype system that combines human intelligence with machine learning techniques to facilitate artificial text detection.

- **AI, write an essay for me: A large-scale comparison of human-written versus ChatGPT-generated essays.** [[paper]](https://arxiv.org/pdf/2304.14276) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.04-blue)

  *Steffen Herbold, Annette Hautli-Janisz, Ute Heuer, Zlata Kikteva and Alexander Trautsch.*
  >  Compare human-written versus ChatGPT-generated argumentative student essays. The results demonstrate that ChatGPT generates essays that are rated higher for quality than human-written essays. The writing style of the AI models exhibits linguistic characteristics that are different from those of the human-written essays.

- **Bot or Human? Detecting ChatGPT Imposters with A Single Question.** [[paper]](https://arxiv.org/pdf/2305.06424) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Hong Wang, Xuan Luo, Weizhi Wang and Xifeng Yan.*
  > Propose a framework named FLAIR, Finding Large Language Model Authenticity via a Single Inquiry and Response, to detect conversational bots in an online manner. The questions that can effectively differentiate human users from bots are divided into two categories: those that are easy for humans but difficult for bots, and those that are easy for bots but difficult for humans.

- **On the Risk of Misinformation Pollution with Large Language Models.** [[paper]](https://arxiv.org/pdf/2305.13661) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.05-blue)

  *Yikang Pan, Liangming Pan, Wenhu Chen, Preslav Nakov, Min-Yen Kan and William Yang Wang.*
  > To mitigate the harm caused by LLM-generated misinformation, explore three defense strategies: prompting, misinformation detection, and majority voting. Initial results show promising trends for these defensive strategies.

- **Social bot detection in the age of ChatGPT: Challenges and opportunities.** [[paper]](https://firstmonday.org/ojs/index.php/fm/article/view/13185/11042) ![](https://img.shields.io/badge/First%20Monday%202023-orange) ![](https://img.shields.io/badge/2023.06-blue)

  *Emilio Ferrara.*
  > Suggest potentially promising opportunities and research directions in social bot detection, including the use of generative agents for synthetic data generation, testing and evaluation.

- **Are you in a Masquerade? Exploring the Behavior and Impact of Large Language Model Driven Social Bots in Online Social Networks.** [[paper]](https://arxiv.org/pdf/2307.10337) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.07-blue)

  *Siyu Li, Jin Yang and Kui Zhao.*
  > Provide a comprehensive analysis of LLMs-driven social bots. Collect and publicly release the first activity behavior dataset of LLMs-driven social bots, named Masquerade-23.

- **"I Slept Like a Baby": Using Human Traits To Characterize Deceptive ChatGPT and Human Text.** [[paper]](https://sjgiorgi.github.io/publications/giorgi2023islept.pdf) ![](https://img.shields.io/badge/SIGIR%202023%20Workshop-orange) ![](https://img.shields.io/badge/2023.07-blue)

  *Salvatore Giorgi, David M. Markowitz, Nikita Soni, Vasudha Varadarajan, Siddharth Mangalik and H. Andrew Schwartz.*
  > Characterize differences between (a) truthful text written by humans, (b) intentionally deceptive text written by humans, and (c) inherently deceptive text written by state-of-the-art language models (ChatGPT). Building on these differences, train a classifier using only the thirteen human traits to automatically discriminate between truthful and deceptive language, with a classification AUC of up to 0.966.

- **Anatomy of an AI-powered malicious social botnet.** [[paper]](https://arxiv.org/pdf/2307.16336) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.07-blue)

  *Kai-Cheng Yang and Filippo Menczer.*
  > Unveil the emergence of LLM-powered social bots. Combine the 1,140 bot accounts with the 1,140 human ones results in a benchmark dataset: the fox8-23 dataset. Apply state-of-the-art LLM-content detectors and find they cannot effectively distinguish between human and LLM-powered bots in the wild.

- **Detecting The Corruption Of Online Questionnaires By Artificial Intelligence.** [[paper]](https://arxiv.org/pdf/2308.07499) ![](https://img.shields.io/badge/Preprint-orange) ![](https://img.shields.io/badge/2023.08-blue)

  *Benjamin Lebrun, Sharon Temtsin, Andrew Vonasch and Christoph Bartneck.*
  > This study tested if text generated by an AI for the purpose of an online study can be detected by both humans and automatic AI detection systems. While humans were able to correctly identify authorship of text above chance level (76 percent accuracy), their performance was still below what would be required to ensure satisfactory data quality. Researchers currently have to rely on the disinterest of bad actors to successfully use open-ended responses as a useful tool for ensuring data quality.

### Demos & Products
- Grover [[demo]](https://grover.allenai.org/detect) [[repo]](https://github.com/rowanz/grover) ![](https://img.shields.io/badge/2019.05-blue)
- Giant Language model Test Room [[demo]](http://gltr.io/dist/index.html) ![](https://img.shields.io/badge/2019.06-blue)
- OpenAI GPT-2 Output Detector [[demo]](https://openai-openai-detector.hf.space/) [[repo]](https://github.com/openai/gpt-2-output-dataset/tree/master/detector) ![](https://img.shields.io/badge/2019.11-blue)
- Writer.com AI Content Detector [[demo]](https://writer.com/ai-content-detector/) ![](https://img.shields.io/badge/2022.10-blue)
- Originality.AI [[home]](https://originality.ai/) [[blog]](https://originality.ai/can-gpt-3-5-chatgpt-be-detected/) ![](https://img.shields.io/badge/2022.12-blue)
- Crossplag AI Content Detector [[demo]](https://crossplag.com/ai-content-detector/) ![](https://img.shields.io/badge/2022.12-blue)
- Copyleaks AI Content Detector [[demo]](https://copyleaks.com/features/ai-content-detector) ![](https://img.shields.io/badge/2023.01-blue)
- GPTZero [[demo]](https://gptzero.me/) ![](https://img.shields.io/badge/2023.01-blue)
- ZeroGPT [[demo]](https://www.zerogpt.com/) ![](https://img.shields.io/badge/2023.01-blue)
- AI Text Classifier [[demo]](https://platform.openai.com/ai-text-classifier) [[blog]](https://openai.com/blog/new-ai-classifier-for-indicating-ai-written-text/) ![](https://img.shields.io/badge/2023.01-blue)
- DetectGPT [[demo]](https://detectgpt.ericmitchell.ai/) [[repo]](https://github.com/eric-mitchell/detect-gpt) ![](https://img.shields.io/badge/2023.01-blue)
- ChatGPT-Comparison-Detection Project [[demo]](https://huggingface.co/Hello-SimpleAI) [[repo]](https://github.com/Hello-SimpleAI/chatgpt-comparison-detection) ![](https://img.shields.io/badge/2023.01-blue)
- Percent Human [[home]](https://percenthuman.app/) ![](https://img.shields.io/badge/2023.01-blue)
- AICheatCheck [[home]](https://www.aicheatcheck.com/) ![](https://img.shields.io/badge/2023.01-blue)
- C@S AI Detector [[demo]](https://contentatscale.ai/ai-content-detector/) ![](https://img.shields.io/badge/2023.02-blue)
- Winston AI Content Detection [[demo]](https://gowinston.ai/) ![](https://img.shields.io/badge/2023.02-blue)
- AI Content Detector [[demo]](https://ai-content-detector.online/) ![](https://img.shields.io/badge/2023.03-blue)
- Paraphrasing Tool AI Content Detector  [[demo]](https://paraphrasingtool.ai/ai-content-detector/)
- GPTKit [[demo]](https://gptkit.ai/)
- Sapling AI Content Detector [[demo]](https://sapling.ai/ai-content-detector) 
- Hive Moderation AI-Generated Content Detection [[demo]](https://hivemoderation.com/ai-generated-content-detection)
- Smodin Multi-lingual AI Content Detector [[demo]](https://smodin.io/ai-content-detector) 
- Content at Scale AI Content Detector [[demo]](https://contentatscale.ai/ai-content-detector/) 
- Writefull GPT Detector [[demo]](https://x.writefull.com/gpt-detector) 



### Datasets
| Dateset | Reference | Release Time | Description | Generation Model | Link |
| :-: | :-: | :-: | :-: | :-: | :-: |
| gpt-2-output-dataset | [[paper]](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) | 2019 | 250K random samples and 250K samples generated with Top-K 40 truncation | GPT-2 | [[repo]](https://github.com/openai/gpt-2-output-dataset) |
| Grover generation | [[paper]](https://proceedings.neurips.cc/paper/2019/file/3e9f0fc9b2f89e043bc6233994dfcf76-Paper.pdf) | 2019 | 15,000 human-written and 10,000 generated news article | Grover | [[repo]](https://github.com/rowanz/grover/tree/master/generation_examples) |
| fakenews machine data | [[paper]](https://direct.mit.edu/coli/article-pdf/46/2/499/1847559/coli_a_00380.pdf) | 2019 | 2000 newsQA answers generated by Grover and 2000 news articles edited by GPT-2 | Grover, GPT-2 | [[home]](https://people.csail.mit.edu/tals/publication/are_we_safe/) [[file]](https://github.com/TalSchuster/talschuster.github.io/raw/master/static/fakenews_machine_data.zip) |
| Deepfake bot submissions | [[paper]](https://techscience.org/a/2019121801/download) | 2019 | 795 human-written comments and 1,001 generated comments  | GPT-2 | [[home]](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/OQCPOT) |
| NeuralNews | [[paper]](https://aclanthology.org/2020.emnlp-main.163.pdf) | 2020 | 128k articles, 27% of which are generated text | Grover | [[home]](https://cs-people.bu.edu/rxtan/projects/didan/) [[file]](https://drive.google.com/file/d/1yttGOSGvKQtPuLrJMJPByBlRfVQYisG1/view?usp=sharing) |
| TweepFake | [[paper]](https://journals.plos.org/plosone/article/file?id=10.1371/journal.pone.0251415&type=printable) | 2020 | 25,572 tweets half human and half bots generated | varied | [[home]](https://www.kaggle.com/datasets/mtesconi/twitter-deep-fake-text) |
| Mixed NLG | [[paper]](https://aclanthology.org/2020.emnlp-main.673.pdf) | 2020 | 8 different Transformer-based LM, 1066 texts from each of the models and 1066 human-written texts | varied | [[repo]](https://github.com/AdaUchendu/Authorship-Attribution-for-Neural-Text-Generation) |
| Generated Headlines | [[paper]](https://aclanthology.org/2021.nlp4if-1.1.pdf) | 2020 | 72,401 real and 414,373 generated headlines in "defender" set, 179, 880 real and 517, 932 generated in “attacker" set | GPT-2 | [[repo]](https://github.com/antmarakis/generated_headline_detection) |
| TuringBench | [[paper]](https://aclanthology.org/2021.findings-emnlp.172.pdf) | 2021 | 168,612 articles from 19 machine text-generators and 1 human | varied | [[repo]](https://huggingface.co/datasets/turingbench/TuringBench/tree/main) |
| GeneratedTextDetection | [[paper]](http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.501.pdf) | 2022 | 100 artificially generated research papers aligned to the original abstract and 100 combinations of original content and machine generated sentences | GPT-2 | [[repo]](https://github.com/vijini/GeneratedTextDetection) |
| COVID Generated Data | [[paper]](https://aclanthology.org/2022.coling-1.106.pdf) | 2022 | 50k examples from GPT-3, about 60k examples each from 4 sizes of GPT-2 and GPT-NEO and 3 decoding technique | GPT-2, GPT-NEO, GPT-3 (`davinci`) | [[repo]](https://github.com/artidoro/detect-gentext) [[file]](https://drive.google.com/drive/folders/1E3YLoIWxBgAtvq2mu5CDugEVByLxZP9M?usp=share_link) |
| In-The-Wild | [[paper]](https://arxiv.org/pdf/2210.09421) | 2022 | 3,887 human-written articles and 3,887 synthetic articles from AI-Writer, ArticleForge, Kafkai and RedditBot | varied | [[repo]](https://github.com/jmpu/DeepfakeTextDetection) |
| RoFT Dataset | [[paper]](https://arxiv.org/pdf/2212.12672) | 2022 | 21,646 annotations for human to find the boundary between human-written text and machine-generated text | GPT-3 (`davinci`) | [[repo]](https://github.com/liamdugan/human-detection/tree/main/data) |
| Self-Instruct | [[paper]](https://arxiv.org/pdf/2212.10560) | 2022 | 52k instructions, paired with 82K instance inputs and outputs | GPT-3 (`davinci`) | [[repo]](https://github.com/yizhongw/self-instruct) |
| ChatGPT Generated Text Detection Corpus | [[paper]](https://www.researchgate.net/profile/Ercan-Canhasi/publication/366898047_ChatGPT_Generated_Text_Detection/links/63b76718097c7832ca932473/ChatGPT-Generated-Text-Detection.pdf) | 2023 | 126 humans essays and 126 nonhumans essays | ChatGPT | [[repo]](https://github.com/rexshijaku/chatgpt-generated-text-detection-corpus) |
| Human ChatGPT Comparison Corpus (HC3) | [[paper]](https://arxiv.org/pdf/2301.07597) | 2023 | 58,546 human answers and 26,903 ChatGPT answrers in English, 22,259 human answers and 17,522 ChatGPT answrers in Chinese | ChatGPT | [[repo]](https://github.com/Hello-SimpleAI/chatgpt-comparison-detection) |
| MGTBench | [[paper]](https://arxiv.org/pdf/2303.14822) | 2023 | Human and ChatGPT answers of 817 questions from TruthfulQA, 1,000 questions from SQuAD1 and 1,000 questions from NarrativeQA | ChatGPT | [[repo]](https://github.com/xinleihe/MGTBench) |
| Alpaca | | 2023 | 52K instruction-following data generated by `text-davinci-003` | GPT-3.5 (`text-davinci-003`) | [[home]](https://crfm.stanford.edu/2023/03/13/alpaca.html) [[repo]](https://github.com/tatsu-lab/stanford_alpaca) |
| Cleaned Alpaca | | 2023 | A cleaned version of the original Alpaca Dataset | GPT-3.5 (`text-davinci-003`) | [[repo]](https://github.com/gururise/AlpacaDataCleaned) [[repo]](https://huggingface.co/datasets/yahma/alpaca-cleaned) |
| GPT4All | [[paper]](https://s3.amazonaws.com/static.nomic.ai/gpt4all/2023_GPT4All_Technical_Report.pdf) | 2023 |  437,605 prompt-generation pairs | GPT-3.5 (`gpt-3.5-turbo`) | [[repo]](https://github.com/nomic-ai/gpt4all) [[repo]](https://huggingface.co/datasets/nomic-ai/gpt4all_prompt_generations) |
| Instruction Tuning with GPT-4 | [[paper]](https://arxiv.org/pdf/2304.03277) | 2023 | 52K instruction-following data generated by GPT-4 | GPT-4 | [[home]](https://instruction-tuning-with-gpt-4.github.io/) [[repo]](https://github.com/Instruction-Tuning-with-GPT-4/GPT-4-LLM) |
| ArguGPT | [[paper]](https://arxiv.org/pdf/2304.07666) | 2023 | 4,115 human-written essays and 4,038 machine-generated essays produced by 7 GPT models | varied | [[repo]](https://github.com/huhailinguist/ArguGPT) |
| DeepfakeTextDetect | [[paper]](https://arxiv.org/pdf/2305.13242) | 2023 | 154,078 human-written texts and 294,381 machine-generated texts produced by 27 LLMs | varied | [[repo]](https://github.com/yafuly/DeepfakeTextDetect) |
| M4 | [[paper]](https://arxiv.org/pdf/2305.14902) | 2023 | 122k human–machine parallel data and over 10M non-parallel human-written texts | varied | [[repo]](https://github.com/mbzuai-nlp/M4) |
| Ghostbuster | [[paper]](https://arxiv.org/abs/2305.15047) | 2023 | All datasets were generated using `gpt-3.5-turbo`, with the exception of the paragraph-level data, which was generated using `text-davinci-003`’s insert feature | GPT-3.5 (`gpt-3.5-turbo`, `text-davinci-003`) | [[repo]](https://github.com/vivek3141/ghostbuster) |
| SnifferBench | [[paper]](https://arxiv.org/pdf/2304.14072) | 2023 | 6k human written texts, and every 6k texts from GPT2, GPT-Neo, GPT-J, and 12k texts from GPT3 models, which is 36k texts in total | varied | [[repo]](https://github.com/OpenLMLab/Sniffer/tree/main/SnifferBench) |
| HPPT | [[paper]](https://arxiv.org/pdf/2307.11380) | 2023 | 6050 pairs of abstracts and corresponding polished versions from ACL anthology | ChatGPT | [[repo]](https://github.com/Clement1290/ChatGPT-Detection-PR-HPPT/tree/main/Dataset/HPPT) |
| IDMGSP | [[paper]](https://aclanthology.org/2023.trustnlp-1.17.pdf) | 2023 | 16k human-written texts and 13k machine-generated scientific papers | varied | [[repo]](https://huggingface.co/datasets/tum-nlp/IDMGSP) |
| Med-MMHL | [[paper]](https://arxiv.org/pdf/2306.08871) | 2023 | 41,365 human-written sentences and 17,608 LLM-generated scentences from the medical domain | GPT-3.5 (`gpt-3.5-turbo`) | [[repo]](https://github.com/styxsys0927/Med-MMHL) |
| OpenGPTText | [[paper]](https://arxiv.org/pdf/2305.07969) | 2023 | A high quality dataset with approximately 30,000 text sample rephrased by gpt-3.5-turbo. | GPT-3.5 (`gpt-3.5-turbo`) | [[repo]](https://github.com/Hao-Kang/GPT-Sentinel-public) [[file]](https://drive.google.com/drive/folders/1Vnr-_nJWT4VXE-1wK38YSsCD4GcP6mk_) |
| HC-Var | [[paper]](https://arxiv.org/pdf/2310.01307.pdf) | 2023 | Contains 4 different types of language tasks, each task covers 1 to 4 different topics. | GPT-3.5 (`gpt-3.5-turbo`) | [[repo]](https://huggingface.co/datasets/hannxu/hc_var) |
| SAID | [[paper]](https://arxiv.org/pdf/2310.08240.pdf) | 2023 | 87,215 human-written responses and 131,546 AI-generated responses from Zhihu and Quora | Unknown | [[repo]](https://github.com/SLAM-group/SAID) |
| SeqXGPT-Bench | [[paper]](https://arxiv.org/pdf/2310.08903.pdf) | 2023 | 30,000 documents generated by GPT-2, GPT-J, GPT-Neo, LLaMA, GPT-3.5-turbo and human. | varied | [[repo]](https://github.com/Jihuai-wpy/SeqXGPT) |
| MULTITuDE | [[paper]](https://arxiv.org/pdf/2310.13606.pdf) | 2023 | 7992 human-written news texts in 11 languages, accompanied by 66089 texts generated by 8 large language models. | varied | [[repo]](https://zenodo.org/records/10013755) |
| HANSEN | [[paper]](https://pike.psu.edu/publications/emnlp23-hansen.pdf) | 2023 | Encompass existing speech datasets accompanied by transcripts, alongside the creation of novel AI-generated spoken text datasets. | GPT-3.5 (`gpt-3.5-turbo`), PaLM 2 (`chat-bison@001`), Vicuna 13B | [[repo]](https://huggingface.co/datasets/HANSEN-REPO/HANSEN) |

### Shared Tasks
- RuATD: Russian Artificial Text Detection [[paper]](https://arxiv.org/abs/2206.01583) [[repo]](https://github.com/dialogue-evaluation/RuATD)
- AuTexTification: Automated Text Identification shared task [[home]](https://sites.google.com/view/autextification/home)
- CLIN33 Shared Task [[home]](https://sites.google.com/view/shared-task-clin33/home)
- ALTA Shared Task 2023 [[home]](https://www.alta.asn.au/events/sharedtask2023/description.html) [[home]](https://codalab.lisn.upsaclay.fr/competitions/14327)
