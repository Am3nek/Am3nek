Vedansh Kumar

Computer Vision | Multimodal AI | Vision-Language Learning | Generative Models

I am a Computer Science graduate and researcher interested in developing intelligent vision-language systems that can reason across modalities, establish fine-grained semantic correspondences, and solve challenging problems in biomedical imaging and multimedia analysis.

My work spans multimodal representation learning, contrastive learning, image generation, retrieval-augmented generation, and deep learning. I am particularly interested in bridging the gap between visual perception and semantic understanding through robust representation learning and grounded generation.

I have contributed to peer-reviewed publications, developed custom datasets for multimedia research, and built end-to-end deep learning systems with quantitative evaluation and reproducible experimental pipelines.

* 🔬 Research Interests: Computer Vision, Multimodal Learning, Vision-Language Models, Biomedical AI, Generative Models.
* 🧠 Core Focus: Multimodal representation alignment, fine-grained concept grounding, and retrieval-augmented generation.
* 📄 Publications: Three research publications, including work on multilingual audio censoring and blockchain systems in aerospace engineering.
* 🛠️ Research Stack: PyTorch, Hugging Face Transformers, FAISS, SWIN Transformer, PubMedBERT, BioT5, and Weights & Biases.
* 🎯 Research Goal: Developing robust, interpretable, and computationally efficient multimodal AI systems for complex real-world problems.

⸻

🔬 Research Highlights

1. Medical Image Captioning through Contrastive Vision-Language Learning

Research Focus: Biomedical Vision-Language Models · Multimodal Alignment · Retrieval-Augmented Generation

Developed a two-stage medical image captioning framework that combines global multimodal representation learning with fine-grained visual concept grounding.

Key Contributions

* Designed a tri-modal contrastive learning framework aligning medical images, textual captions, and biomedical concepts.
* Used a SWIN Transformer image encoder and PubMedBERT text embeddings to learn aligned representations.
* Introduced patch-level concept grounding alongside global contrastive alignment to improve correspondence between image regions and biomedical concepts.
* Developed a second-stage generation pipeline using BioT5, projected image patch representations, learned visual tokens, and top-k biomedical concepts retrieved through FAISS.
* Evaluated the system using language-generation metrics and experiment tracking through Weights & Biases.

Reported Results

Metric	Score
Validation Loss	2.4709
Perplexity	11.8258
BERTScore (F1)	0.8608
ROUGE-L	0.2194
BLEU	0.0251

Technologies: Python, PyTorch, SWIN Transformer, PubMedBERT, BioT5, FAISS, Hugging Face Transformers, Weights & Biases.

⸻

2. AudioCensorNet: Multilingual Audio Censoring and Multimedia Analysis

Research Focus: Audio-Visual Processing · Speech Recognition · Multilingual NLP · Dataset Engineering

Developed a multilingual audio censoring pipeline based on OpenAI Whisper for identifying and censoring offensive language in video content.

A major component of this research was the creation and annotation of a custom dataset containing 707 multilingual videos, designed to support systematic evaluation across languages.

Key Contributions

* Built an end-to-end pipeline for audio extraction, speech transcription, foul-language detection, audio censoring, and video reconstruction.
* Developed and structured a multilingual dataset for model evaluation.
* Evaluated the system across English, German, Italian, and Spanish.
* Investigated multilingual speech processing and censorship as a multimedia analysis problem.

Reported Accuracy

Language	Accuracy
English	91.44%
German	89.21%
Italian	85.20%
Spanish	68.13%

Publication: AudioCensorNet: A Multilingual Audio Censoring Model Based on Whisper for Generating Censored Video (2025).

Technologies: Python, OpenAI Whisper, Speech Processing, NLP, FFmpeg, Multimedia Processing.

⸻

3. Aerial Image Denoising using Wasserstein GANs

Research Focus: Generative Models · Image Restoration · Adversarial Learning

Developed a GAN-based image denoising framework using a U-Net-based architecture to investigate restoration of noisy aerial and remote-sensing imagery.

Key Contributions

* Implemented a generative adversarial learning pipeline for image denoising.
* Evaluated restoration under multiplicative, Gaussian, and random noise models.
* Curated a multi-source dataset using UC-Merced, WHU-RS19, RSSCN7, and AID.
* Established quantitative evaluation using structural similarity and peak signal-to-noise ratio.

Reported Results

Metric	Score
SSIM	0.9172
PSNR	33.04 dB
Output Resolution	224 × 224

Technologies: Python, PyTorch, U-Net, Wasserstein GANs, Image Processing.

⸻

📚 Publications

My research contributions span multilingual multimedia processing and emerging computing systems.

1. AudioCensorNet: A Multilingual Audio Censoring Model Based on Whisper for Generating Censored Video — May 2025.
2. Foul Language Censored Social Media Video Generation Using Audio Censoring Model — March 2025.
3. Blockchain Systems in Aerospace Engineering: Review and Research Challenges — January 2024.

My research interests continue to evolve toward multimodal representation learning, biomedical vision-language models, and grounded generative AI.

⸻

🧪 Additional Projects

InspireIt — Research Ideation Assistant

Built a retrieval-augmented research assistant using arXiv data and generative AI to produce literature-grounded research ideas, summaries, citations, and innovation scores.

Technologies: Python, Vertex AI, Google Cloud Platform, Mistral, RAG.

Smart Attendance System

Designed a dual-verification attendance platform combining facial recognition and RFID authentication, integrating embedded hardware, a backend service, and a relational database.

Technologies: Django REST Framework, ESP32-CAM, RFID, JavaScript, SQLite.

Adaptive Traffic Signal Control

Contributed to a patented traffic management system involving traffic-state representation, predictive analysis, anomaly detection, and coordinated signal scheduling using a federated meta-reinforcement learning approach.

Patent Application: Indian Patent Application No. 202641082856, published July 2026.

⸻

🛠️ Research Toolkit

Area	Technologies
Deep Learning	PyTorch, TensorFlow
Computer Vision	SWIN Transformer, Image Processing, Image Restoration
Vision-Language Learning	Contrastive Learning, Multimodal Alignment, Concept Grounding
Language Models	PubMedBERT, BioT5, Hugging Face Transformers
Retrieval Systems	FAISS, Retrieval-Augmented Generation
Generative AI	GANs, Wasserstein GANs, Generative Models
Speech & Multimedia	OpenAI Whisper, Audio Processing
Experiment Tracking	Weights & Biases
Programming	Python, C, C++

⸻

🎯 Research Interests

I am particularly interested in exploring the following directions:

* Multimodal Representation Learning: Learning shared representations across visual, textual, and structured modalities.
* Fine-Grained Vision-Language Grounding: Connecting local visual regions with meaningful semantic and biomedical concepts.
* Biomedical Vision-Language Models: Developing systems that combine medical image understanding, domain-specific knowledge, and grounded text generation.
* Generative Models: Investigating generative approaches for image restoration, synthesis, and representation learning.
* Efficient and Reliable AI: Building computationally practical models with rigorous evaluation and reproducible experiments.

⸻

🤝 Collaboration

I am interested in collaborating on research involving computer vision, multimodal learning, biomedical AI, and generative models.

I welcome discussions around research ideas, experimental methodologies, model architectures, and opportunities to contribute to meaningful open-source research.

📧 Email: vedansh.kr31@gmail.com
💻 GitHub: @am3nek
🔗 LinkedIn: Vedansh Kumar

⸻

Building multimodal AI systems that connect perception, semantics, and grounded generation.
