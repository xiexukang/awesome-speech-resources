# awesome-speech-resources


## Paper List
- [Text-to-Audio](#Text-to-Audio)
- [Automatic Speech Recognition(ASR)](#Automatic-Speech-Recognition)
- [Speaker Verification](#Speaker-Verification)
- [Voice Conversion(VC)](#Voice-Conversion)
- [Speech Synthesis(TTS)](#Speech-Synthesis)
- [Language Modelling](#Language-Modelling)
- [Confidence Estimates](#Confidence-Estimates)
- [Music Modelling](#Music-Modelling)
- [Interesting papers](#Interesting-papers)


<details>
<summary><b>Text to Audio</b> (Click to expand)</summary>

- **AudioLM: a Language Modeling Approach to Audio Generation**(2022), Zalán Borsos et al. [[pdf]](https://arxiv.org/pdf/2209.03143)
- **AudioLDM: Text-to-Audio Generation with Latent Diffusion Models**(2023), Haohe Liu et al. [[pdf]](https://arxiv.org/pdf/2301.12503)
- **MusicLM: Generating Music From Text**(2023), Andrea Agostinelli et al. [[pdf]](https://arxiv.org/pdf/2301.11325)
- **Moûsai: Text-to-Music Generation with Long-Context Latent Diffusion**(2023), Flavio Schneider et al. [[pdf]](https://arxiv.org/pdf/2301.11757)
- **Noise2Music: Text-conditioned Music Generation with Diffusion Models**(2023), Qingqing Huang et al. [[pdf]](https://arxiv.org/pdf/2302.03917)

</details>

# **模型概述**
- 基于AISHELL+wav2vec2预训练用于语音识别
- 采用Transformer和wav2vec2技术
# **模型性能**
- 发布时开发集错误率为5.19%
- 发布时测试集错误率为5.58%
# **系统组成**
- 基于单字的分词器处理文本
- 含wav2vec2编码器的声学模型
# **安装与使用**
- 使用pip命令安装SpeechBrain
- 提供英文音频转录代码示例
# **训练方法**
- 克隆SpeechBrain代码库
- 按步骤执行训练命令
# **模型局限性**
- 换数据集性能无保障
# **关于SpeechBrain**
- 提供官网、代码库链接
- 给出HuggingFace页面链接
# **引用规范**
- 用于研究或商业需引用
- 提供具体引用格式示例
