*Check [CM MLPerf docs](https://docs.mlcommons.org/inference) for more details.*

## Host platform

* OS version: Linux-6.8.0-60-generic-x86_64-with-glibc2.29
* CPU version: x86_64
* Python version: 3.8.10 (default, Feb  4 2025, 15:02:54) 
[GCC 9.4.0]
* MLC version: unknown

## CM Run Command

See [CM installation guide](https://docs.mlcommons.org/inference/install/).

```bash
pip install -U mlcflow

mlc rm cache -f

mlc pull repo mlcommons@mlperf-automations --checkout=cc1d43d1d5eeebee7efa08a1aa0f1cc62fcb1560


```
*Note that if you want to use the [latest automation recipes](https://docs.mlcommons.org/inference) for MLPerf,
 you should simply reload mlcommons@mlperf-automations without checkout and clean MLC cache as follows:*

```bash
mlc rm repo mlcommons@mlperf-automations
mlc pull repo mlcommons@mlperf-automations
mlc rm cache -f

```

## Results

Platform: RTX4090x1-nvidia-gpu-TensorRT-default_config

Model Precision: fp16

### Accuracy Results 
`F1`: `90.15279`, Required accuracy for closed division `>= 89.96526`

### Performance Results 
`Samples per second`: `4094.16`
