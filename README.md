# Mohanad Almahjoub

I’m an Electrical and Electronics Engineering student at Ankara Medipol University, graduating in 2028. I study digital signal processing and statistical estimation, with a particular interest in neural signals and radar sensing.

## Featured benchmark

**[When Noise Calibration Drifts — MUSIC Source Counting](https://github.com/MohanadAlmahjoub/music-source-counting-benchmark)**

A reproducible signal-processing benchmark with synthetic array data, paired noise-whitening experiments, and CPU and GPU measurements. It documents when a 12-bit counting heuristic fails under calibration drift and what the results imply for an FPGA implementation.

[Reproduce the experiments](https://github.com/MohanadAlmahjoub/music-source-counting-benchmark#run-it) · [Inspect the performance report](https://github.com/MohanadAlmahjoub/music-source-counting-benchmark/blob/main/docs/performance.md)

One question runs through my work: when a sensor gets noisy, how much can we still trust the estimate?

In Python, I built a closed-loop EEG simulation using synthetic signals. I tracked how noise affected the decoder’s output and how much delay the feedback loop introduced. In my EEG research, I also care about whether a result holds up on a participant or recording session the model has never seen.

My next step is to take a DSP algorithm from a floating-point reference to a fixed-point FPGA implementation. I want to measure how many bits the estimate needs, how long each decision takes, and what it costs in hardware resources and power.
