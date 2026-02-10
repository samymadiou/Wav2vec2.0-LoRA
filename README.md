# Wav2vec2.0-LoRA
## Fine tuning of the Wav2Vec 2.0 model for an audio classification task with low-rank adaptation techniques

In this work, we adapt a LLM originally designed for speech-related tasks, namely Wav2Vec 2.0, to a music genre classification task on the GTZAN dataset using LoRA fine-tuning techniques. This approach achieved an overall accuracy of approximately 78%, demonstrating that fine-tuning with LoRA outperforms the approach without fine-tuning, while training only 8.99% of the original number of parameters. The results highlight the critical importance of hyperparameter optimization, particularly the LoRA rank and strategic layer selection.
