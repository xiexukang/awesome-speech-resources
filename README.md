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
| Russian asr | 俄语识别推理代码 | [GitHub](https://github.com/salute-developers/gigaam) |

### 数据集

| 名称 | 描述 | 链接 |
|------|------|------|
| LibriSpeech | 英文语音数据集 | [官网](http://www.openslr.org/12/) |
| AISHELL-1 | 中文语音数据集 | [官网](http://www.openslr.org/33/) |
| AISHELL-3 | 中文语音数据集 | [官网](http://www.openslr.org/68/) |
| voice_datasets |  open source voice and music datasets | [GitHub](https://github.com/jim-schwoebel/voice_datasets) |
| Common Voice | 开源语音数据集 | [官网](https://commonvoice.mozilla.org/en) |
| Emilia | 多语种开源语音数据集 | [官网](https://huggingface.co/datasets/amphion/Emilia-Dataset) |
| LibriVox | 英文语音数据集 | [官网](https://librivox.org/) |
| Mosel | 欧洲多语言语音数据集 | [huggingface](https://huggingface.co/datasets/FBK-MT/mosel) |
| ReazonSpeech | 日語语音数据集 | [huggingface](https://huggingface.co/datasets/reazon-research/reazonspeech) |

### 论文

- **[Attention Is All You Need (2017)]**  
  Transformer 架构奠基性论文 [[arXiv](https://arxiv.org/abs/1706.03762)]
- **[AST: Audio Spectrogram Transformer (2021)]**  
  AST [[arXiv](https://arxiv.org/pdf/2104.01778)]
- **[Whisper (2022)]**  
  大规模弱监督语音识别 [[arXiv](https://arxiv.org/abs/2212.04356)]
- **[PSEUDO-LABELING FOR MASSIVELY MULTILINGUAL SPEECH RECOGNITION (2022)]**  
  大规模多语言语音识别 [[arXiv](https://arxiv.org/abs/2209.03143)]
- **[WavLM: Large-Scale Self-Supervised Pre-Training for Full Stack Speech Processing (2022)]**  
  WavLM 大规模自监督预训练 [[arXiv](https://arxiv.org/pdf/2111.00161)]
- **[ZIPFORMER: A FASTER AND BETTER ENCODER FOR AUTOMATIC SPEECH RECOGNITION (2023)]**  
  一种更快更好的自动语音识别编码器 [[arXiv](https://arxiv.org/pdf/2310.11230)]
- **[FAST CONFORMER WITH LINEARLY SCALABLE ATTENTION FOR EFFICIENT SPEECH RECOGNITION (2023)]**  
  Fastconformer一种用于高效语音识别 [[arXiv](https://arxiv.org/pdf/2305.05084)]
- **[An Embarrassingly Simple Approach for LLM with Strong ASR Capacity (2024)]**  
  LLM 强大的语音识别能力 [[arXiv](https://arxiv.org/abs/2402.08846)]
- **[: 950,000 Hours of Speech Data for Open-Source Speech Foundation Model Training on EU Languages (2024)]**
  欧盟语言的开放式语音基础模型训练的 950,000 小时语音数据 [[arXiv](https://arxiv.org/pdf/2410.01036)]
- **[Retrieval Augmented Correction of Named Entity Speech Recognition Errors (2024)]**  
  检索增强的命名实体语音识别错误校正 [[arXiv](https://arxiv.org/pdf/2409.06062)]
- **[Dynamic Language Group-based MoE: Enhancing Code-Switching Speech Recognition with Hierarchical Routing (2024)]**  
  基于动态语言组的分层路由 MoE：增强CS语音识别 [[arXiv](https://arxiv.org/pdf/2407.18581)]
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
- **[Qwen vs. Gemma Integration with Whisper: A Comparative Study in Multilingual SpeechLLM Systems (2025)]**  
  Qwen vs. Gemma 集成 Whisper：多语言语音LLM系统比较研究 [[arXiv](https://arxiv.org/pdf/2506.13596.pdf)]
- **[SHNU Multilingual Conversational Speech Recognition System for INTERSPEECH 2025 MLC-SLM Challenge (2025)]**  
  上海师范大学 2025年Interspeech MLC-SLM 挑战赛论文 [[arXiv](https://arxiv.org/pdf/2507.03343.pdf)]
- **[CMT-LLM: Contextual Multi-Talker ASR Utilizing Large Language Models (2025)]**  
  利用大型语言模型的上下文多说话人语音识别 [[arXiv](https://arxiv.org/pdf/2506.12059v1.pdf)]
- **[Whale: Large-Scale multilingual ASR model with w2v-BERT and E-Branchformer with large speech data (2025)]**
  基于w2v-BERT和E-Branchformer的大型多语言ASR模型 [[arXiv](https://arxiv.org/pdf/2506.01439v1.pdf)]
- **[Improving Multilingual Speech Models on ML-SUPERB 2.0: Fine-tuning with Data Augmentation and LID-Aware CTC (2025)]**  
  改进ML-SUPERB 2.0上的多语言语音模型：数据增强和LID感知CTC微调 [[arXiv](https://arxiv.org/pdf/2505.24200v2.pdf)]
- **[Delayed-KD: Delayed Knowledge Distillation based CTC for Low-Latency Streaming ASR (2025)]**  
  延迟知识蒸馏的低延迟流式ASR [[arXiv](https://arxiv.org/pdf/2505.22069.pdf)]
- **[GigaAM: Efficient Self-Supervised Learner for Speech Recognition (2025)]**  
  俄语语音识别：高效的自监督学习者用于语音识别 [[arXiv](https://arxiv.org/pdf/2505.21999v1.pdf)]
- **[Exploring Generative Error Correction for Dysarthric Speech Recognition (2025)]**
  探索生成式错误纠正以改善发音障碍语音识别 [[arXiv](https://arxiv.org/pdf/2505.20163v1.pdf)]
- **[ILT: Iterative LoRA Training through Focus–Feedback–Fix for Multilingual Speech Recognition (2025)]**  
  迭代LoRA训练：聚焦-反馈-修复用于多语言语音识别 [[arXiv](https://arxiv.org/pdf/2507.08477.pdf)]
- **[GigaSpeech 2: An Evolving, Large-Scale and Multi-domain ASR Corpus for Low-Resource Languages with Automated Crawling, Transcription and Refinement (2025)]**  
  2025年GigaSpeech 2：用于低资源语言的自动爬取、转录和改进的大型多领域ASR语料库 [[arXiv](https://arxiv.org/pdf/2406.11546.pdf)]
- **[Enabling Auditory Large Language Models for Automatic Speech Quality Evaluation (2025)]**  
  用于自动语音质量评估的听觉大型语言模型 [[arXiv](https://arxiv.org/pdf/2505.19967v1.pdf)]
- **[Performance Evaluation of SLAM-ASR: The Good, the Bad, the Ugly, and the Way Forward (2025)]**  
  SLAM-ASR的性能评估：好、坏、丑陋和前进方向 [[arXiv](https://arxiv.org/pdf/2411.03866.pdf)]
- **[Speech Prefix-Tuning with RNNT Loss for Improving LLM Predictions (2025)]**  
  使用RNNT损失进行语音前缀调优以提高LLM预测 [[arXiv](https://arxiv.org/pdf/2406.14701.pdf)]
- **[Low-Rank and Sparse Model Merging for Multi-Lingual Speech Recognition and Translation (2025)]**  
  多语言语音识别和翻译的低秩和稀疏模型合并 [[arXiv](https://arxiv.org/pdf/2505.19893v1.pdf)]
- **[Emilia: A Large-Scale, Extensive, Multilingual, and Diverse Dataset for Speech Generation (2025)]**  
  用于语音生成的Emilia：大规模、广泛、多语言和多样化的数据集 [[arXiv](https://arxiv.org/pdf/2501.15907.pdf)]
- **[Language-Aware Prompt Tuning for Parameter-Efficient Seamless Language Expansion in Multilingual ASR (2025)]**  
  用于多语言ASR中参数高效无缝语言扩展的语言感知提示调优 [[arXiv](https://arxiv.org/pdf/2506.21577.pdf)]
- **[Efficient Multilingual ASR Finetuning via LoRA Language Experts (2025)]**  
  通过LoRA语言专家进行高效多语言ASR微调 [[arXiv](https://arxiv.org/pdf/2506.21555.pdf)]
- **[OWSM v4: Improving Open Whisper-Style Speech Models via Data Scaling and Cleaning (2025)]**  
  通过数据缩放和清理改进开放式Whisper风格语音模型 [[arXiv](https://arxiv.org/pdf/2506.00338.pdf)]
- **[Phi-4-Mini Technical Report: Compact yet Powerful Multimodal Language Models via Mixture-of-LoRAs (2025)]**  
  通过混合LoRA进行紧凑而强大的多模态语言模型 [[arXiv](https://arxiv.org/pdf/2503.01743.pdf)]
- **[Voxtral (2025)]**  
  Voxtral 模型 [[arXiv](https://arxiv.org/pdf/2507.13264.pdf)]
- **[Granite-speech: open-source speech-aware LLMs with strong English ASR capabilities (2025)]**  
  具有强大英语ASR能力的开源语音感知LLMs [[arXiv](https://arxiv.org/pdf/2505.08699.pdf)]
- **[: The First Large-Scale Open-Science Speech Foundation Model for English and Italian (2025)]**  
  英语和意大利语的第一大数据集开源语音基础模型 [[arXiv](https://arxiv.org/pdf/2505.22759.pdf)]
- **[From Tens of Hours to Tens of Thousands: Scaling Back-Translation for Speech Recognition (2025)]**  
  从数十小时到数万小时：通过回译扩展语音识别 [[arXiv](https://arxiv.org/pdf/2505.16972.pdf)]
- **[The TEA-ASLP System for Multilingual Conversational Speech Recognition and Speech Diarization in MLC-SLM 2025 Challenge (2025)]**  
  MLC-SLM 2025挑战中的多语言对话语音识别和语音分离系统 [[arXiv](https://arxiv.org/pdf/2507.18051.pdf)]
- **[SpecASR: Accelerating LLM-based Automatic Speech Recognition via Speculative Decoding (2025)]**  
  通过推测解码加速基于LLM的自动语音识别 [[arXiv](https://arxiv.org/pdf/2507.18181.pdf)]
- **[An approach to measuring the performance of Automatic Speech Recognition(ASR) models in the context of Large Language Model(LLM) powered applications (2025)]**  
  在基于大型语言模型（LLM）驱动的应用程序的上下文中衡量自动语音识别（ASR）模型的性能的方法 [[arXiv](https://arxiv.org/pdf/2507.16456.pdf)]
- **[Code-Switching in End-to-End Automatic Speech Recognition: A Systematic Literature Review (2025)]**  
  端到端自动语音识别中的代码切换：系统文献综述 [[arXiv](https://arxiv.org/pdf/2507.07741.pdf)]
- **[The Eloquence team submission for task 1 of MLC-SLM challenge (2025)]**  
  MLC-SLM挑战任务1的Eloquence团队提交 [[arXiv](https://arxiv.org/pdf/2507.19308.pdf)]
- **[Boosting CTC-Based ASR Using LLM-Based Intermediate Loss Regularization (2025)]**  
  使用基于LLM的中间损失正则化增强CTC ASR [[arXiv](https://arxiv.org/pdf/2506.22846.pdf)]
- **[Unifying Streaming and Non-streaming Zipformer-based ASR (2025)]**  
  统一流式和非流式Zipformer ASR [[arXiv](https://www.arxiv.org/pdf/2506.14434.pdf)]
- **[Omni-Router: Sharing Routing Decisions in Sparse Mixture-of-Experts for Speech Recognition (2025)]**  
  在稀疏混合专家中统一路由决策以进行语音识别 [[arXiv](https://arxiv.org/pdf/2507.05724.pdf)]
- **[Granary: Speech Recognition and Translation Dataset in 25 European Languages (2025)]**  
  25种欧洲语言的语音识别和翻译数据集 [[arXiv](https://arxiv.org/pdf/2505.13404.pdf)]
- **[Switch Conformer with Universal Phonetic Experts for Multilingual ASR (2025)]**  
  用于多语言ASR的通用音素专家切换Conformer [[arXiv](https://www.isca-archive.org/interspeech_2025/mimura25_interspeech.pdf)]
- **[Improving Generalization of End-to-End ASR through Diversity and Independence Regularization (2025)]**  
  通过多样性和独立性正则化提高端到端ASR的泛化性 [[arXiv](https://www.isca-archive.org/interspeech_2025/ko25_interspeech.pdf)]
- **[Towards Efficiently Whisper Fine-tuning with Monotonic Alignments (2025)]**  
  通过单调对齐实现高效的Whisper微调 [[arXiv](https://www.isca-archive.org/interspeech_2025/zhuang25_interspeech.pdf)]
- **[REB-former: RWKV-enhanced E-branchformer for Speech Recognition (2025)]**  
  基于RWKV增强的E-branchformer用于语音识别 [[arXiv](https://www.isca-archive.org/interspeech_2025/song25b_interspeech.pdf)]
- **[AISHELL-5: The First Open-Source In-Car Multi-Channel Multi-Speaker Speech Dataset for Automatic Speech Diarization and Recognition (2025)]**  
  AISHELL-5：第一个用于自动语音分离和识别的开放式车内多通道多说话人语音数据集 [[arXiv](https://www.isca-archive.org/interspeech_2025/dai25c_interspeech.pdf)]
- **[Better Semi-supervised Learning for Multi-domain ASR Through Incremental Retraining and Data Filtering (2025)]**  
  通过增量再训练和数据过滤提高Multi-domain ASR的半监督学习 [[arXiv](https://www.isca-archive.org/interspeech_2025/carofilis25_interspeech.pdf)]
- **[ReazonSpeech: A Free and Massive Corpus for Japanese ASR (2025)]**  
  ReazonSpeech：用于日语ASR的免费且庞大的语料库 [[arXiv](https://research.reazon.jp/_static/reazonspeech_nlp2023.pdf)]
- **[ASR Error Correction using Large Language Models (2025)]**  
  使用大型语言模型进行ASR错误纠正 [[arXiv](https://arxiv.org/pdf/2409.09554.pdf)]
- **[Chain-of-Thought Prompting for Speech Translation (2025)]**  
  基于思维链提示的语音翻译 [[arXiv](https://arxiv.org/pdf/2409.11538?)]
- **[Investigation of Whisper ASR Hallucinations Induced by Non-Speech Audio (2025)]**  
  非语音音频引起的Whisper ASR幻觉研究 [[arXiv](https://arxiv.org/pdf/2501.11378?)]
- **[CR-CTC: CONSISTENCY REGULARIZATION ON CTC FOR IMPROVED SPEECH RECOGNITION (2025)]**  
  CTC一致性正则化用于改进语音识别 [[arXiv](https://arxiv.org/pdf/2410.05101)]
- **[WenetSpeech-Yue: A Large-scale Cantonese Speech Corpus with Multi-dimensional Annotation (2025)]**  
  WenetSpeech-Yue：具有多维注释的大规模粤语语音语料库 [[arXiv](https://arxiv.org/pdf/2509.03959)]
- **[SpeechLLM: Unified Speech and Language Model for Enhanced Multi-Task Understanding in Low Resource Settings (2025)]**  
  SpeechLLM：用于低资源设置中多任务理解的统一语音和语言模型 [[arXiv](https://arxiv.org/pdf/2509.04473)]
- **[Streaming Sequence-to-Sequence Learning with Delayed Streams Modeling (2025)]**  
  延迟流建模的流式序列到序列学习 [[arXiv](https://arxiv.org/pdf/2509.08753)]
- **[Denoising GER: A Noise-Robust Generative Error Correction with LLM for Speech Recognition (2025)]**  
  基于LLM的噪声鲁棒生成错误纠正（Denoising GER）用于语音识别 [[arXiv](https://arxiv.org/pdf/2509.08753)]

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
| index-tts | 基于LLM的工业可控中英文合成 | [GitHub](https://github.com/index-tts/index-tts) |

### 论文

- **[Deep Voice: Real-time Neural Text-to-Speech (2017)]**  
  实时神经文本到语音 [[arXiv](https://arxiv.org/abs/1702.07825v2.pdf)]
- **[Deep Voice 2: Multi-Speaker Neural Text-to-Speech (2017)]**  
  Deep Voice 2 多说话人神经文本到语音 [[arXiv](https://arxiv.org/abs/1705.08947v2.pdf)]
- **[TACOTRON: TOWARDS END-TO-END SPEECH SYNTHESIS (2017)]**  
  TACOTRON走向端到端语音合成 [[arXiv](https://arxiv.org/abs/1703.10135v2.pdf)]
- **[VITS (2021)]**  
  对抗学习端到端TTS [[arXiv](https://arxiv.org/abs/2106.06103)]
- **[One TTS Alignment To Rule Them All (2021)]**  
  一种TTS对齐 [[arXiv](https://arxiv.org/abs/2108.10447v1.pdf)]
- **[ON PROSODY MODELING FOR ASR+TTS BASED VOICE CONVERSION (2021)]**  
  基于ASR+TTS的语音转换的韵律建模 [[arXiv](https://arxiv.org/abs/2107.09477v1.pdf)]
- **[ISTFTNET: FAST AND LIGHTWEIGHT MEL-SPECTROGRAM VOCODER INCORPORATING INVERSE SHORT-TIME FOURIER TRANSFORM (2022)]**  
  ISTFTNET：快速且轻量级的包含逆短时傅里叶变换的梅尔频谱波形合成器 [[arXiv](https://arxiv.org/abs/2203.02395v1.pdf)]
- **[NaturalSpeech 3: Zero-Shot Speech Synthesis with Factorized Codec and Diffusion Models (2024)]**  
  NaturalSpeech3：具有因子编解码器和扩散模型的零样本语音合成 [[arXiv](https://arxiv.org/pdf/2403.03100.pdf)]
- **[Simple and Controllable Music Generation (2024)]**  
  简单且可控的音乐生成 [[arXiv](https://arxiv.org/pdf/2306.05284)]
- **[GENERATIVE PRE-TRAINING FOR SPEECH WITH FLOW MATCHING (2024)]**  
  基于流匹配的生成预训练 [[arXiv](https://arxiv.org/pdf/2310.16338.pdf)]
- **[ZipVoice: Fast and High-Quality Zero-Shot Text-to-Speech with Flow Matching (2025)]**  
  小米团队基于流匹配的零样本文本到语音 [[arXiv](https://arxiv.org/abs/2506.13053v2.pdf)]
- **[Comparative Analysis of Fast and High-Fidelity Neural Vocoders for Low-Latency Streaming Synthesis in Resource-Constrained Environments (2025)]**  
  资源受限环境下的低延迟流式合成比较分析 [[arXiv](https://arxiv.org/abs/2506.03554v1.pdf)]
- **[CosyVoice: A Scalable Multilingual Zero-shot Text-to-speech Synthesizer based on Supervised Semantic Tokens (2024)]**  
  阿里通义CosyVoice 1：基于监督语义标记的可扩展多语言零样本文本到语音合成器 [[arXiv](https://arxiv.org/abs/2407.05407.pdf)]
- **[CosyVoice2: A Scalable Multilingual Zero-shot Text-to-speech Synthesizer based on Supervised Semantic Tokens (2024)]**  
  阿里通义CosyVoice 2：基于监督语义标记的可扩展多语言零样本文本到语音合成器 [[arXiv](https://arxiv.org/abs/2412.10117.pdf)]
- **[CosyVoice 3: Towards In-the-wild Speech Generation via Scaling-up and Post-training (2025)]**  
  阿里通义CosyVoice 3 [[arXiv](https://arxiv.org/abs/2505.17589v2.pdf)]
- **[SlimSpeech: Lightweight and Efficient Text-to-Speech with Slim Rectified Flow (2025)]**  
  轻量级高效文本到语音 [[arXiv](https://arxiv.org/abs/2504.07776v2.pdf)]
- **[IndexTTS: An Industrial-Level Controllable and Efficient Zero-Shot Text-To-Speech System (2025)]**  
  b站：工业级可控高效零样本文本到语音系统 [[arXiv](https://arxiv.org/abs/2502.05512.pdf)]
- **[IndexTTS2: A Breakthrough in Emotionally Expressive and Duration-Controlled Auto-Regressive Zero-Shot Text-to-Speech (2025)]**  
  b站：情感表达和持续时间控制的自动回归零样本文本到语音突破 [[arXiv](https://arxiv.org/abs/2506.21619.pdf)]
- **[Spark-TTS An Efficient LLM-Based Text-to-Speech Model with Single-Stream Decoupled Speech Tokens (2025)]**  
  Spark-TTS 基于单流解耦语音标记的LLM文本到语音模型 [[arXiv](https://arxiv.org/abs/2503.01710v1.pdf)]
- **[ZipVoice-Dialog: Non-Autoregressive Spoken Dialogue Generation with Flow Matching (2025)]**  
  ZipVoice-Dialog 基于流匹配的非自回归对话生成 [[arXiv](https://arxiv.org/pdf/2507.09318.pdf)]
- **[MoonCast: High-Quality Zero-Shot Podcast Generation (2025)]**  
  MoonCast 高质量零样本播客生成 [[arXiv](https://arxiv.org/pdf/2503.14345.pdf)]

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
| LLaMA-Factory | LLM sft tool | [GitHub](https://github.com/hiyouga/LLaMA-Factory) |
| Megatron-LM | Megatron-LM | [GitHub](https://github.com/NVIDIA/Megatron-LM.git) |
| verl | LLM强化学习工具 | [GitHub](https://github.com/volcengine/verl.git) |
| VeOmni | LLM训练工具 | [GitHub](https://github.com/ByteDance-Seed/VeOmni) |

### 论文

- **[LLaMA: Open and Efficient Foundation Language Models (2023)]**
  LLaMA：开源高效的基础语言模型 [[arXiv](https://arxiv.org/abs/2302.13971)]
- **[Qwen2-Audio Technical Report (2024)]**  
  阿里云Qwen2-Audio技术报告 [[arXiv](https://arxiv.org/abs/2407.10759)]
- **[Gemma 2: Improving Open Language Models at a Practical Size (2024)]**  
  Gemma 2技术报告 [[arXiv](https://storage.googleapis.com/deepmind-media/gemma/gemma-2-report.pdf)]
- **[Uni-MoE: Scaling Unified Multimodal LLMs with Mixture of Experts (2024)]**
  Uni-MoE：通过专家混合实现统一多模态LLM的扩展 [[arXiv](https://arxiv.org/pdf/2405.11273?)]
- **[Making LLMs Better Many-to-Many Speech-to-Text Translators with Curriculum Learning (2024)]**  
  通过课程学习使LLMs成为更好的多对多语音到文本翻译者 [[arXiv](https://arxiv.org/pdf/2409.19510)]
- **[GAMA: A Large Audio-Language Model with Advanced Audio Understanding and Complex Reasoning Abilities (2023)]**  
  GAMA：具有高级音频理解和复杂推理能力的音频语言模型 [[arXiv](https://arxiv.org/pdf/2406.11768)]
- **[Audio Flamingo: A Novel Audio Language Model with Few-Shot Learning and Dialogue Abilities (2024)]**  
  Audio Flamingo：具有少样本学习和对话能力的音频语言模型 [[arXiv](https://arxiv.org/pdf/2402.01831)]
- **[Audio Flamingo 2: An Audio-Language Model with Long-Audio Understanding and Expert Reasoning Abilities (2025)]**  
  Audio Flamingo 2：具有长音频理解和专家推理能力的音频语言模型 [[arXiv](https://arxiv.org/pdf/2503.03983)]
- **[Audio Flamingo 3: Advancing Audio Intelligence with Fully Open Large Audio Language Models (2025)]**  
  Audio Flamingo 3：推进音频智能 [[arXiv](https://arxiv.org/pdf/2507.08128)]
- **[Step-Audio (2025)]**  
  Step-Audio Team 语音对话 [[arXiv](https://arxiv.org/abs/2502.11946)]
- **[Seed LiveInterpret 2.0: End-to-end Simultaneous Speech-to-speech Translation with Your Voice (2025)]**  
  Seed LiveInterpret 2.0：端到端同时语音到语音翻译 [[arXiv](https://arxiv.org/abs/2507.17527)]
- **[Gemma 3 Technical Report (2025)]**  
  Gemma 3技术报告 [[Gemma3Report](https://storage.googleapis.com/deepmind-media/gemma/Gemma3Report.pdf)]
- **[Large Language Models: A Survey (2025)]**  
  大型语言模型综述 [[arXiv](https://arxiv.org/pdf/2402.06196)]
- **[Recent Advances in Speech Language Models: A Survey (2025)]**  
  语音语言模型最新进展综述 [[arXiv](https://arxiv.org/pdf/2410.03751)]
- **[Step-Audio 2 Technical Report (2025)]**  
  Step-Audio 2技术报告 [[arXiv](https://arxiv.org/pdf/2507.16632)]  
- **[Seed-X: Building Strong Multilingual Translation LLM with 7B Parameters (2025)]**  
  Seed-X：构建7B参数的强大多语言翻译LLM [[arXiv](https://arxiv.org/pdf/2507.13618)]
- **[MiDashengLM: Efficient Audio Understanding with General Audio Captions (2025)]**  
  MiDashengLM：基于通用音频字幕的音频理解 [[arXiv](https://arxiv.org/pdf/2508.03983)]
- **[VeOmni: Scaling Any Modality Model Training with Model-Centric Distributed Recipe Zoo (2025)]**  
  VeOmni [[arXiv](https://arxiv.org/pdf/2508.02317)]
- **[VIBEVOICE Technical Report (2025)]**  
  VIBEVOICE技术报告 [[arXiv](https://arxiv.org/pdf/2508.19205)]
- **[SEAL: Speech Embedding Alignment Learning for Speech Large Language Model with Retrieval-Augmented Generation (2025)]**  
  SEAL：基于检索增强生成的语音语言模型 [[arXiv](https://arxiv.org/pdf/2502.02603)]
- **[LLaMA-Omni 2: LLM-based Real-time Spoken Chatbot with Autoregressive Streaming Speech Synthesis (2025)]**  
  LLaMA-Omni 2：基于LLM的实时语音聊天机器人 [[arXiv](https://arxiv.org/pdf/2505.02625?)]
- **[Qwen2.5-Omni Technical Report (2025)]**  
  Qwen2.5-Omni技术报告 [[arXiv](https://arxiv.org/pdf/2503.20215)]
- **[ESPnet-SpeechLM: An Open Speech Language Model Toolkit (2025)]**  
  ESPnet-SpeechLM：开源语音语言模型工具包 [[arXiv](https://arxiv.org/pdf/2502.15218)]

</details>

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
