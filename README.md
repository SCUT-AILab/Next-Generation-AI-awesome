# Next-Generation AI

We would like to maintain an up-to-date list of progress (papers, blogs, codes, and *etc.*) made in **Next-Generation AI** (GPT-4, ChatGPT and other AGI), and provide a guide for some of the papers that have received wide interest.
Please feel free to [open an issue](SCUT-AILab/Next-Generation-AI-awesome) to add papers.

## <a name="toc">Table of Contents</a>

- <a href="#for-beginner">For Beginners</a>

## <a name="for-beginner">For Beginners</a>

In this section, we present various resources in the form of **papers, blogs, and videos** that are designed to aid **beginners** in acquiring a **rapid comprehension** of Transformer (include BERT and GPT families), Instruct-GPT, ChatGPT and GPT-4. It is **not advised** to initially **refer to the original paper** as its technical content may be hard to follow **for beginners**.

- **Groundbreaking Work (Transformer)**.

  - **Video**: A Detailed Reading of the Transformer Paper by *LiMu* [![bilibili](https://img.shields.io/badge/dynamic/json?label=views&style=social&logo=bilibili&query=data.stat.view&url=https%3A%2F%2Fapi.bilibili.com%2Fx%2Fweb-interface%2Fview%3Fbvid%3DBV1pu411o7BE)](https://www.bilibili.com/video/BV1pu411o7BE/) [![Youtube](https://img.shields.io/youtube/views/nzqlFIcCSWQ?style=social)](https://youtu.be/nzqlFIcCSWQ)
  - **Blog**: [*Details of Transformer*](https://zhuanlan.zhihu.com/p/338817680).
  - **Paper**: [*Attention Is All You Need*](https://proceedings.neurips.cc/paper_files/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf).
  
- **Evolution with Pretraining and Finetuning (BERT)**.
  - **Video**: A Detailed Reading of the BERT Paper by *LiMu* [![bilibili](https://img.shields.io/badge/dynamic/json?label=views&style=social&logo=bilibili&query=data.stat.view&url=https%3A%2F%2Fapi.bilibili.com%2Fx%2Fweb-interface%2Fview%3Fbvid%3DBV1PL411M7eQ)](https://www.bilibili.com/video/BV1PL411M7eQ/) [![](https://img.shields.io/youtube/views/ULD3uIb2MHQ?style=social)](https://youtu.be/ULD3uIb2MHQ)
  - **Blog**: [*Illustration of BERT*](https://zhuanlan.zhihu.com/p/364966458).
  - **Paper**: [*BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding*](https://arxiv.org/pdf/1810.04805.pdf)


- **Zero-shot Predictions with Pretraining at Scales (GPT1, GPT2, GPT3, GPT4)**.
  - **Video**: A Detailed Reading of the GPT-1,2&3 Paper by *LiMu* [![bilibili](https://img.shields.io/badge/dynamic/json?label=views&style=social&logo=bilibili&query=data.stat.view&url=https%3A%2F%2Fapi.bilibili.com%2Fx%2Fweb-interface%2Fview%3Fbvid%3DBV1AF411b7xQ)](https://www.bilibili.com/video/BV1AF411b7xQ/) [![](https://img.shields.io/youtube/views/t70Bl3w7bxY?style=social)](https://youtu.be/t70Bl3w7bxY)
  - **Blog**: [*The Evolution of GPT Series*](https://zhuanlan.zhihu.com/p/609716668)
  - **Paper**: GPT-1, 2, and 3 have been accompanied by academic publications, while GPT-4 is currently only documented in a technical report without any model or training details.
    - [*Improving Language Understanding by Generative Pre-Training (GPT-1)*](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf)
    - [*Language Models are Unsupervised Multitask Learners (GPT-2)*](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)
    - [*Language Models are Few-Shot Learners (GPT-3)*](https://proceedings.neurips.cc/paper/2020/file/1457c0d6bfcb4967418bfb8ac142f64a-Paper.pdf)
    - [*GPT-4 Technical Report*](https://arxiv.org/pdf/2303.08774)

- **Learning with Human Feedbacks (Instruct-GPT, ChatGPT)**.
  - **Video**: A Detailed Reading of the Instruct-GPT Paper by *LiMu* [![bilibili](https://img.shields.io/badge/dynamic/json?label=views&style=social&logo=bilibili&query=data.stat.view&url=https%3A%2F%2Fapi.bilibili.com%2Fx%2Fweb-interface%2Fview%3Fbvid%3DBV1hd4y187CR)](https://www.bilibili.com/video/BV1hd4y187CR) [![](https://img.shields.io/youtube/views/zfIGAwD1jOQ?style=social)](https://youtu.be/zfIGAwD1jOQ)
  - **Blog**: [*Details of Instruct-GPT/ChatGPT*](https://www.bilibili.com/opus/749177592393760805). We also provide some meterials about the background knowledge: [*Details of RLHF*](https://mp.weixin.qq.com/s/hm_bbVebSF4JudctCsiRcA) and [*Details of PPO*](https://www.jianshu.com/p/9f113adc0c50).
  - **Paper**: [*InstructGPT: Training Language Models to Follow Instructions With Human Feedback*](https://proceedings.neurips.cc/paper_files/paper/2022/file/b1efde53be364a73914f58805a001731-Paper-Conference.pdf)

- **Applying GPT to Various Tasks**.
    - **Prompt Engineering.** To query speficied information from GPT, you need to design a proper question (prompt) to ask GPT. The research about how to design these prompts is referred to prompt engineering [[Blog](https://zhuanlan.zhihu.com/p/613197867), [Paper](https://openreview.net/pdf?id=e2TBb5y0yFf)]. 
    - **GPT for Embodied AI.** We can use GPT for emboedied AI, including Robotics [[Blog](https://zhuanlan.zhihu.com/p/612137768), [Paper](https://www.microsoft.com/en-us/research/uploads/prod/2023/02/ChatGPT___Robotics.pdf)], Object-Goal Navigation [[Paper](https://arxiv.org/pdf/2301.13166.pdf)] and Task Planning [[Blog](https://zhuanlan.zhihu.com/p/501856356), [Paper](https://arxiv.org/pdf/2204.01691.pdf)].
    - **GPT for CV.** We can also use GPT for CV, including VQA [[Paper](https://arxiv.org/abs/2207.12101)] and video [[Paper](https://arxiv.org/abs/2212.04501)].
