# Awesome Speech Resources

🗣️ A curated list of speech-related tools, papers, and datasets.  
*点击下方分类展开详细资源列表*

---

<details>
<summary><b>🔊 语音识别 (ASR)</b></summary>

### 工具
| 名称 | 描述 | 链接 |
|------|------|------|
| Whisper | OpenAI 开源的多语言语音识别模型 | [GitHub](https://github.com/openai/whisper) |
| PaddleSpeech | 百度开源的语音识别工具包 | [GitHub](https://github.com/PaddlePaddle/PaddleSpeech) |
| awesome-whisper | whisper 的一些应用和优化 | [GitHub](https://github.com/sindresorhus/awesome-whisper) |
| Kaldi | 基于WFST的经典ASR工具包 | [官网](https://kaldi-asr.org/) |
| ESPnet | 端到端语音处理工具包 | [GitHub](https://github.com/espnet/espnet) |
| wenet | 新手中文语音识别工具包 | [GitHub](https://github.com/wenet-e2e/wenet) |
| funasr | 新手中文语音识别工具包 | [GitHub](https://github.com/modelscope/FunASR) |
| WeTextProcessor | 语音识别TN工具包 | [GitHub](https://github.com/wenet-e2e/WeTextProcessing) |
| NeMo | Nvidia端到端语音处理工具包 | [GitHub](https://github.com/NVIDIA/NeMo) |

### 数据集
| 名称 | 描述 | 链接 |
|------|------|------|
| LibriSpeech | 英文语音数据集 | [官网](http://www.openslr.org/12/) |
| AISHELL-1 | 中文语音数据集 | [官网](http://www.openslr.org/33/) |
| AISHELL-3 | 中文语音数据集 | [官网](http://www.openslr.org/68/) |
| voice_datasets |  open source voice and music datasets | [GitHub](https://github.com/jim-schwoebel/voice_datasets) |


### 论文
- **[Attention Is All You Need (2017)]**  
  Transformer 架构奠基性论文 [[arXiv](https://arxiv.org/abs/1706.03762)]
- **[Whisper (2022)]**  
  大规模弱监督语音识别 [[arXiv](https://arxiv.org/abs/2212.04356)]
- **[Efficient Streaming LLM for Speech Recognition (2025)]**
  Meta流式LLM 语音识别 [[arXiv](https://arxiv.org/abs/2410.03752)]
- **[Adapting Whisper for Streaming Speech Recognition via Two-Pass Decoding (2025)]**
  U2 whisper 流式语音识别 [[arXiv](https://www.arxiv.org/abs/2506.12154)]
- **[Adaptability of ASR Models on Low-Resource Language: A Comparative Study of Whisper and Wav2Vec-BERT on Bangla (2025)]**
  低资源语言 ASR 模型适应性研究：Whisper 与 Wav2Vec-BERT 在孟加拉语上的对比分析 [[arXiv](https://arxiv.org/pdf/2507.01931)]
- **[What do self-supervised speech models know about Dutch? Analyzing advantages of language-specific pre-training (2025)]**
  自监督语音模型对荷兰语语言信息的编码能力，以及语言特定预训练的优势 [[arXiv](https://arxiv.org/pdf/2506.00981v1.pdf)]
- **[BUT System for the MLC-SLM Challenge (2025)]**
  2025年Interspeech MLC-SLM 挑战赛论文 [[arXiv](https://arxiv.org/pdf/2506.13414v1.pdf)]
- **[Bi-directional Context-Enhanced Speech Large Language Models for Multilingual Conversational ASR (2025)]**
  Alibaba-NTU 2025年Interspeech MLC-SLM 挑战赛论文 [[arXiv](https://arxiv.org/pdf/2506.13396v1.pdf)]
- **[NTU Speechlab LLM-Based Multilingual ASR System for Interspeech MLC-SLM Challenge 2025]**
  NTU 2025年Interspeech MLC-SLM 挑战赛论文 [[arXiv](https://arxiv.org/pdf/2506.13339v1.pdf)]
- **[Seewo’s Submission to MLC-SLM: Lessons learned from Speech Reasoning Language Models (2025)]**
  Seewo 2025年Interspeech MLC-SLM 挑战赛论文,可验证奖励的强化学习 [[arXiv](https://arxiv.org/pdf/2506.13300v3.pdf)]
  
</details>

---

<details>
<summary><b>🎵 语音合成 (TTS)</b></summary>

### 工具
| 名称 | 描述 | 链接 |
|------|------|------|
| VITS | 基于VAE的端到端TTS模型 | [GitHub](https://github.com/jaywalnut310/vits) |
| Tacotron 2 | Google 神经TTS架构 | [GitHub](https://github.com/NVIDIA/tacotron2) |
| FastSpeech | 非自回归快速合成 | [GitHub](https://github.com/ming024/FastSpeech) |
| wetts | 中文TTS工具包 | [GitHub](https://github.com/wenet-e2e/wetts) |

### 论文
- **[VITS (2021)]**  
  对抗学习端到端TTS [[arXiv](https://arxiv.org/abs/2106.06103)]
- **[FastSpeech (2019)]**  
  非自回归快速合成 [[arXiv](https://arxiv.org/abs/1905.09263)]
- **[ZipVoice: Fast and High-Quality Zero-Shot Text-to-Speech with Flow Matching (2025)]**
  小米团队基于流匹配的零样本文本到语音 [[arXiv](https://arxiv.org/abs/2506.13053v2.pdf)]


</details>

---

<details>
<summary><b>🔉 语音增强</b></summary>

### 工具
| 名称 | 描述 | 链接 |
|------|------|------|
| Demucs | 语音/音乐分离工具 | [GitHub](https://github.com/facebookresearch/demucs) |
| RNNoise | 实时噪声抑制 | [GitHub](https://github.com/xiph/rnnoise) |

### 论文
- **[SEGAN (2017)]**  
  首个基于GAN的语音增强 [[arXiv](https://arxiv.org/abs/1703.09452)]

</details>

---

<details>
<summary><b>🤖 LLM及多模态LLM</b></summary>

### 工具
| 名称 | 描述 | 链接 |
|------|------|------|
| SpeechGPT | 支持语音交互的LLM | [GitHub](https://github.com/0nutation/SpeechGPT) |
| Step-Audio | 语音对话大模型 | [GitHub](https://github.com/stepfun-ai/Step-Audio) |

### 论文
- **[Step-Audio (2025)]**  
  Step-Audio Team 语音对话 [[arXiv](https://arxiv.org/abs/2502.11946)]

</details>

---

---

<details>
<summary><b>🆔 声纹识别 (Speaker Recognition)</b></summary>

### 工具
| 名称 | 描述 | 链接 |
|------|------|------|
| Resemblyzer | 基于神经网络的声纹特征提取 | [GitHub](https://github.com/resemble-ai/Resemblyzer) |
| PyAnnote | 说话人日志分析工具包 | [GitHub](https://github.com/pyannote/pyannote-audio) |
| ECAPA-TDNN | 当前最优声纹模型实现 | [GitHub](https://github.com/TaoRuijie/ECAPA-TDNN) |
| 3D-Speaker | 阿里的声纹工具包 | [GitHub](https://github.com/modelscope/3D-Speaker) |

### 论文
- **[ECAPA-TDNN (2020)]**  
  通道注意力机制改进的声纹模型 [[arXiv](https://arxiv.org/abs/2005.07143)]
- **[GE2E (2018)]**  
  谷歌端到端声纹识别 [[arXiv](https://arxiv.org/abs/1710.10467)]

</details>

---

<details>
<summary><b>⏰ 语音唤醒 (Wake Word Detection)</b></summary>

### 工具
| 名称 | 描述 | 链接 |
|------|------|------|
| Porcupine | 离线唤醒词引擎（支持自定义热词） | [GitHub](https://github.com/Picovoice/porcupine) |
| Snowboy | 轻量级唤醒词检测（已归档） | [GitHub](https://github.com/Kitt-AI/snowboy) |
| HeyFriender | 开源多语言唤醒词训练框架 | [GitHub](https://github.com/HeyFriender/heyfriender) |

### 论文
- **[Keyword Transformer (2021)]**  
  基于Transformer的唤醒词检测 [[arXiv](https://arxiv.org/abs/2104.00769)]
- **[MatchboxNet (2020)]**  
  端到端低延迟唤醒模型 [[arXiv](https://arxiv.org/abs/2004.03706)]

</details>

---
## 贡献
欢迎提交 Pull Request 补充资源！  
⚠️ 要求：  
- 按分类添加  
- 提供官方链接  
- 论文需附arXiv/DOI链接
