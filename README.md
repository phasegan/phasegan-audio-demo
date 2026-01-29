# audio-demo
PhaseGAN: High-Fidelity Vocoder via Decoupled Amplitude and GAN-Driven Phase Reconstruction

We present our audio samples as follows:

​​LJSpeech​​: Demonstrates the performance of our method and baseline models on the LJSpeech test set.

​​VCTK​​: Evaluates our method and baseline models (trained on LJSpeech) on unseen speakers without fine-tuning.

​​Opencpop​​: Tests our method and baseline models (trained on LJSpeech) on singing voice data without fine-tuning.

TTS: Without any fine-tuning, the experimental results of our method and the benchmark model (trained on LJSpeech data) in end-to-end speech synthesis.

​​Ablation Study​​: Features ablation samples from LJSpeech, including:

Results without the adversarial loss module.

Results without MRSTFT components.

Results without Zero-Centered Gradient Penalty (zgp) components.
