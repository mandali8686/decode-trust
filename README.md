<h1>DECODINGTRUST: A Comprehensive Assessment of Trustworthiness in GPT Models</h1>

This repository contains overview, experiment and result of DECODINGTRUST as outlined in the official paper: https://arxiv.org/abs/2306.11698

Boxin Wang, Weixin Chen, Hengzhi Pei, Chulin Xie, Mintong Kang, Chenhui Zhang, Chejian Xu, Zidi Xiong, Ritik Dutta, Rylan Schaeffer, Sang T. Truong, Simran Arora, Mantas Mazeika, Dan Hendrycks, Zinan Lin, Yu Cheng, Sanmi Koyejo, Dawn Song, Bo Li


__Introduction__

This paper extensive evaluation of the trustworthiness of the latest large language models, particularly GPT-3.5 and GPT-42. The study aims to assess their capabilities and limitations by using a range of benchmarks to measure performance and test resilience against adversarial conditions. Key areas of evaluation include the models' ability to avoid generating toxic content, perpetuation of stereotypes, robustness against adversarial and out-of-distribution data, and their capacity to maintain privacy, ethics, and fairness. The methodology incorporates standard benchmarks, custom datasets, and adversarially crafted prompts. Through rigorous testing, the paper seeks to produce reproducible results that reveal the strengths and weaknesses of these models, contributing to the advancement of reliable, unbiased, and transparent language models that uphold high standards of trustworthiness.

__Capacities__


<img width="800" alt="Screen Shot 2023-11-05 at 6 38 09 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/631ee10f-1f26-476b-9edb-c1fbe113e525">

<img width="800" alt="Screen Shot 2023-11-05 at 6 39 15 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/734f9d02-a368-45bc-b179-87f766fffb22">

**Disucussion Questions**

Questions 1: Why is trustworthiness-focused evaluation crucial for LLMs?

**Toxicity**






**Toxicity Result**

1) **Standard Benchmark**


<img width="800" alt="Screen Shot 2023-11-05 at 7 08 28 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/bad90fc4-fc8a-4837-b93f-fcf3b44173c2">

**Comparison to GPT3**

<img width="800" alt="Screen Shot 2023-11-05 at 7 05 09 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/b948e089-c2e8-4509-9acf-ab0c89d0eae4">
<img width="675" alt="Screen Shot 2023-11-05 at 7 05 39 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/ff0c1b50-613c-4cb6-b7b5-27c193205474">

2) **Diverse System**
<img width="900" alt="Screen Shot 2023-11-05 at 7 33 45 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/59346089-2f37-4721-a0bb-ffc98dedb7d0">

**Comparison between GPT-3.5 and GPT-4**

<img width="900" alt="Screen Shot 2023-11-05 at 7 34 08 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/24885998-dd68-469a-a973-9cd4c30b09d4">

<img width="674" alt="Screen Shot 2023-11-05 at 7 39 35 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/fdfc604d-0cf7-452b-91a6-2d3d4cc5f587">

3)**Design of challenging user prompts**

<img width="677" alt="Screen Shot 2023-11-05 at 7 42 53 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/c559c0a5-b5fe-400b-88ed-0dc492d6b077">

<img width="665" alt="Screen Shot 2023-11-05 at 7 43 17 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/f27308f2-6ab1-4d0f-807a-7e7fdec5a160">

<img width="689" alt="Screen Shot 2023-11-05 at 7 43 34 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/fc6cfe21-a211-4e0b-9ea0-656f3fc540b0">

<img width="634" alt="Screen Shot 2023-11-05 at 7 44 58 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/2450c5b2-d0d8-41ee-8a5d-d2e06536c54b">



**Stereotypes Bias**

<img width="673" alt="Screen Shot 2023-11-05 at 7 45 25 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/f0379215-1cc1-4e27-85ad-89126c0d8b57">


<img width="872" alt="Screen Shot 2023-11-05 at 7 46 45 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/73e59e09-1bf1-4a48-8b9d-330c5919c44a">


<img width="849" alt="Screen Shot 2023-11-05 at 7 47 12 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/f0dfe5c1-b596-46b1-837d-52ad1fe90d36">

<img width="684" alt="Screen Shot 2023-11-05 at 7 47 33 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/fa923ac1-c8b5-43db-a292-099bc5ea5062">

**Adversial Robustness**

**Robustness evaluation on standard benchmark AdvGLUE**

<img width="711" alt="Screen Shot 2023-11-05 at 8 21 32 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/95964d9c-afb9-4f55-9f20-0332d9705ada">

**Result**

<img width="681" alt="Screen Shot 2023-11-05 at 8 21 59 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/c94191ff-d119-4bf2-acd8-51ea73c24ea0">



<img width="677" alt="Screen Shot 2023-11-05 at 8 22 24 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/58a57d8a-5787-49b6-8db6-586a2c7d3cc4">

**Robustness evaluation on generated adversarial texts AdvGLUE++**

<img width="676" alt="Screen Shot 2023-11-05 at 8 23 39 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/1f2cfd79-7982-4d17-a2af-f1f16282fe1b">

<img width="684" alt="Screen Shot 2023-11-05 at 8 23 54 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/dccd27e3-ab9f-473d-be7e-f3d86131c9a9">

<img width="687" alt="Screen Shot 2023-11-05 at 8 24 11 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/c0f3e7fb-1d28-47e2-9c8c-4d5b59b5cbb9">

<img width="683" alt="Screen Shot 2023-11-05 at 8 24 35 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/60fc1036-9eb3-463c-8d3f-ce8eb0f7f198">


<img width="711" alt="Screen Shot 2023-11-05 at 8 24 54 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/e1dfe410-75aa-4d3a-acb4-338bf6f72aa0">

**Out-of-distribution robustness**

**OOD Style**


<img width="702" alt="Screen Shot 2023-11-05 at 8 31 26 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/25481c26-23e1-4825-948e-12fac96d6bcb">


<img width="555" alt="Screen Shot 2023-11-05 at 8 31 57 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/3994aa57-9a73-4aed-9090-20e6c0667a02">


<img width="698" alt="Screen Shot 2023-11-05 at 8 32 46 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/55d6ae6c-7087-4902-9397-ffcaef93a5a1">

**OOD Knowledge**


<img width="686" alt="Screen Shot 2023-11-05 at 8 33 06 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/81311677-5f83-4a2d-9eb0-690e17df1167">

<img width="693" alt="Screen Shot 2023-11-05 at 8 33 23 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/0a7f48c0-1b31-4231-8475-7081c6ba504e">

<img width="664" alt="Screen Shot 2023-11-05 at 8 33 38 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/72a0da55-ef9c-4212-82fe-5c02203b1579">

<img width="669" alt="Screen Shot 2023-11-05 at 8 34 08 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/68fdb28b-7b38-4f56-a6ce-9343392d14eb">

**Robustness on OOD demonstrations via in-context learning**

<img width="682" alt="Screen Shot 2023-11-05 at 8 34 51 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/80537315-03c0-4937-aaa9-ca0dba3a2659">

<img width="704" alt="Screen Shot 2023-11-05 at 8 35 10 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/04b4117b-148d-49c0-99ef-2b8e15786cae">


**Robustness against adversarial demonstrations**

1) **Robustness against counterfactual demonstrations**

<img width="670" alt="Screen Shot 2023-11-05 at 8 37 46 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/e5976b2c-1108-48b7-84c4-f718612cf7e4">



<img width="629" alt="Screen Shot 2023-11-05 at 8 38 03 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/0585072c-b972-4091-81ae-c8cce60c864a">



<img width="736" alt="Screen Shot 2023-11-05 at 8 38 39 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/2c6366d1-23ae-4994-a0c7-cfa91705b088">


<img width="674" alt="Screen Shot 2023-11-05 at 8 38 57 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/9de14128-2a09-4849-94d9-756aace21b06">

2) **Robustness against spurious correlations in demonstrations**


<img width="273" alt="Screen Shot 2023-11-05 at 8 39 30 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/4376bfe6-6d4f-461b-a723-6627fa0d1470">



<img width="679" alt="Screen Shot 2023-11-05 at 8 39 48 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/cf683cf3-c93e-410b-bf1f-d717c6b814e9">

3)  **Robustness against backdoors in demonstrations**

<img width="676" alt="Screen Shot 2023-11-05 at 8 40 33 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/d7580a7a-978d-48f8-bebb-eb6c4255e792">

<img width="704" alt="Screen Shot 2023-11-05 at 8 41 06 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/a2cca8b6-eaff-413d-883f-79a294ecc06c">

<img width="670" alt="Screen Shot 2023-11-05 at 8 41 24 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/2f17618f-0b3e-4cbb-913f-716fe7e09d56">

<img width="703" alt="Screen Shot 2023-11-05 at 8 41 42 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/059d4968-ba0d-4d02-9d62-723ad762e004">

<img width="674" alt="Screen Shot 2023-11-05 at 8 42 16 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/2de6fd2e-92f6-4617-8a7d-37e757b698ea">

**Privacy**

<img width="569" alt="Screen Shot 2023-11-05 at 8 42 43 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/9375c56c-2e42-495a-9220-8500b240dabe">

1) **Privacy leakage of training data**

<img width="702" alt="Screen Shot 2023-11-05 at 8 43 25 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/9549b4f1-6cb8-41dc-8792-f155ad326183">

<img width="671" alt="Screen Shot 2023-11-05 at 8 44 18 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/40783e52-d66d-4f80-a504-22437a810719">


<img width="695" alt="Screen Shot 2023-11-05 at 8 43 49 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/b5e51b7b-71e6-4083-a645-25673ed87993">

2) **Privacy leakage during conversations**

<img width="679" alt="Screen Shot 2023-11-05 at 8 55 15 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/2c922d94-bbde-4adb-bb40-089e33cef9df">

3)**Understanding of privacy-related words and privacy events**

<img width="623" alt="Screen Shot 2023-11-05 at 8 55 59 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/b99b7c7b-0b07-4afc-ac57-f2f78303da64">

<img width="608" alt="Screen Shot 2023-11-05 at 8 56 42 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/2976c444-95e5-47b2-8cfd-1079cb59d214">


<img width="602" alt="Screen Shot 2023-11-05 at 8 56 59 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/a5622d2d-079c-4a75-999d-be99cac46764">

<img width="606" alt="Screen Shot 2023-11-05 at 8 57 25 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/fb0ea74f-e747-42bc-a41f-e98b11800860">

<img width="606" alt="Screen Shot 2023-11-05 at 8 57 45 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/585cdf70-de87-46d6-be9c-a5e4fe837344">


**Machine Ethics**

1) **Evaluation on standard machine ethics benchmarks**

<img width="611" alt="Screen Shot 2023-11-05 at 8 59 03 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/1f873f4e-6e72-47aa-a523-181cb5d91dc5">

<img width="595" alt="Screen Shot 2023-11-05 at 9 02 02 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/bd374b35-152d-4e22-a6dd-7987f169aad4">

<img width="594" alt="Screen Shot 2023-11-05 at 9 02 22 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/8ab60756-afd0-41e7-92a5-5059f7e2f253">

<img width="603" alt="Screen Shot 2023-11-05 at 9 18 27 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/717dc1d5-dab1-4e05-a9df-5ff776cc3edd">

2) **Evaluation on jailbreaking prompts**

<img width="607" alt="Screen Shot 2023-11-05 at 9 19 09 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/a537a2f0-1924-4ee4-8ac3-63af9beef23d">

3) **Evaluation on evasive sentences**

<img width="599" alt="Screen Shot 2023-11-05 at 9 19 44 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/b7ac027b-95c7-442c-8122-6aaefe0d4be5">

<img width="597" alt="Screen Shot 2023-11-05 at 9 20 00 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/d708121e-0ed9-4ee1-9e57-ef545769d9e5">

4) **Evaluation on conditional action**


<img width="229" alt="Screen Shot 2023-11-05 at 9 20 43 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/6584d375-c3c6-44af-adeb-4838190470cb">




<img width="592" alt="Screen Shot 2023-11-05 at 9 20 56 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/a5321fd9-c94c-416b-b48b-67dd95554481">

**Evaluation on Fairness**


<img width="605" alt="Screen Shot 2023-11-05 at 9 21 24 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/134c8141-0810-43bb-b30c-17a6b1c05a3f">

<img width="600" alt="Screen Shot 2023-11-05 at 9 21 41 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/78cc737b-ed8c-43cd-88ea-b1a02c2cb033">



<img width="603" alt="Screen Shot 2023-11-05 at 9 22 03 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/c0df3e9a-0896-4480-9784-aaaed4a76776">

<img width="605" alt="Screen Shot 2023-11-05 at 9 22 33 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/ac2d59af-bac3-44be-af09-889040e93451">


<img width="615" alt="Screen Shot 2023-11-05 at 9 22 18 PM" src="https://github.com/mandali8686/decode-trust/assets/100242191/04127cf5-12ab-4407-a746-c64fd4a4bc6a">

**Discussion**

Question 1: Why is trustworthiness-focused evaluation crucial for LLMs?

Question 2: What other concerns you may have for LLMs? 

**Conclusion**

While GPT-4 generally outperforms GPT-3.5 across various trustworthiness metrics, it is more susceptible to manipulation through precise instructions or adversarial prompts due to its advanced instruction-following capabilities. The study reveals that numerous input factors significantly influence trustworthiness, meriting further investigation. Future work is recommended to focus on multi-turn interactive evaluations, exploring the models' responses to misleading contexts, assessing their vulnerability to coordinated adversarial attacks, and domain-specific trustworthiness. There's an emphasis on developing verification methods to provide safety guarantees for LLMs, enhancing models with domain knowledge and reasoning, using game theory to ensure consistent and context-aware responses, and auditing models against specific user requirements for safety and trustworthiness.

