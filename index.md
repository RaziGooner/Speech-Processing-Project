# Graduate Speech Processing – Final Project

This project presents a deep-learning–based speech enhancement system designed to separate clean speech from
noisy inputs across diverse acoustic conditions. The system uses a Bidirectional Long Short-Term Memory 
with Phase-Sensitive Approximation (BLSTM-PSA) model trained on mixtures of clean utterances from the 
LibriSpeech corpus and noise samples from the DEMAND dataset spanning a wide range of signal to-noise ratios. 

## Code
You can view the main Jupyter notebook here:

- [Speech Enhancement Notebook](https://github.com/RaziGooner/Speech-Processing-Project/blob/main/Speech%20Denoiser.ipynb)


<h2>Project Report</h2>
<p>
  You can download or view the full report here:
  <a href="project%20report.pdf" target="_blank">Open PDF in new tab</a>
</p>

<iframe
  src="project%20report.pdf"
  width="100%"
  height="600px"
  style="border:none;">
</iframe>


## Audio Examples

### Noisy Input
<audio controls>
  <source src="Denoised%20example/noisy.wav" type="audio/wav">
  Your browser does not support the audio element.
</audio>

### Denoised Output
<audio controls>
  <source src="Denoised%20example/denoised.wav" type="audio/wav">
  Your browser does not support the audio element.
</audio>

### Clean Reference
<audio controls>
  <source src="Denoised%20example/clean.wav" type="audio/wav">
  Your browser does not support the audio element.
</audio>

