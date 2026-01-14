ggml_cuda_init: found 1 ROCm devices:
  Device 0: AMD Instinct MI50/MI60, gfx906:sramecc+:xnack- (0x906), VMM: no, Wave Size: 64
llama-bench: benchmark 1/2: starting
main: error: failed to load model '/home/iacoppbk/Downloads/Kimi-Linear-48B-A3B-Instruct.q4_k_s.gguf'
| model                          |       size |     params | backend    | ngl | threads | type_k | fa |            test |                  t/s |
| ------------------------------ | ---------: | ---------: | ---------- | --: | ------: | -----: | -: | --------------: | -------------------: |
ggml_cuda_init: found 1 ROCm devices:
  Device 0: AMD Instinct MI50/MI60, gfx906:sramecc+:xnack- (0x906), VMM: no, Wave Size: 64
llama-bench: benchmark 1/2: starting
main: error: failed to load model '/media/iacoppbk/80F42C9BF42C96061/llms/Qwen3-VL-30B-A3B-Thinking-Q4_1.gguf'
| model                          |       size |     params | backend    | ngl | threads | n_ubatch | type_k | fa |            test |                  t/s |
| ------------------------------ | ---------: | ---------: | ---------- | --: | ------: | -------: | -----: | -: | --------------: | -------------------: |
ggml_cuda_init: found 1 ROCm devices:
  Device 0: AMD Instinct MI50/MI60, gfx906:sramecc+:xnack- (0x906), VMM: no, Wave Size: 64
llama-bench: benchmark 1/2: starting
llama-bench: benchmark 1/2: warmup prompt run
llama-bench: benchmark 1/2: prompt run 1/1
| model                          |       size |     params | backend    | ngl | threads | n_ubatch | type_k | fa |            test |                  t/s |
| ------------------------------ | ---------: | ---------: | ---------- | --: | ------: | -------: | -----: | -: | --------------: | -------------------: |
| qwen3vlmoe 30B.A3B Q4_1        |  17.87 GiB |    30.53 B | ROCm       |  99 |      12 |     1800 |   q8_0 |  1 |          pp2048 |       1758.66 ± 0.00 |
llama-bench: benchmark 2/2: starting
llama-bench: benchmark 2/2: warmup generation run
llama-bench: benchmark 2/2: generation run 1/1
| qwen3vlmoe 30B.A3B Q4_1        |  17.87 GiB |    30.53 B | ROCm       |  99 |      12 |     1800 |   q8_0 |  1 |           tg128 |        125.52 ± 0.00 |

build: fb7e6eed (7775)
ggml_cuda_init: found 1 ROCm devices:
  Device 0: AMD Instinct MI50/MI60, gfx906:sramecc+:xnack- (0x906), VMM: no, Wave Size: 64
llama-bench: benchmark 1/2: starting
llama-bench: benchmark 1/2: warmup prompt run
llama-bench: benchmark 1/2: prompt run 1/1
| model                          |       size |     params | backend    | ngl | threads | type_k | fa |            test |                  t/s |
| ------------------------------ | ---------: | ---------: | ---------- | --: | ------: | -----: | -: | --------------: | -------------------: |
| qwen3vlmoe 30B.A3B Q4_1        |  17.87 GiB |    30.53 B | ROCm       |  99 |      12 |   q8_0 |  1 |           pp512 |       1504.58 ± 0.00 |
llama-bench: benchmark 2/2: starting
llama-bench: benchmark 2/2: warmup generation run
llama-bench: benchmark 2/2: generation run 1/1
| qwen3vlmoe 30B.A3B Q4_1        |  17.87 GiB |    30.53 B | ROCm       |  99 |      12 |   q8_0 |  1 |           tg128 |        124.43 ± 0.00 |

build: fb7e6eed (7775)
ggml_cuda_init: found 1 ROCm devices:
  Device 0: AMD Instinct MI50/MI60, gfx906:sramecc+:xnack- (0x906), VMM: no, Wave Size: 64
llama-bench: benchmark 1/2: starting
llama-bench: benchmark 1/2: warmup prompt run
llama-bench: benchmark 1/2: prompt run 1/1
| model                          |       size |     params | backend    | ngl | threads | type_k | fa |            test |                  t/s |
| ------------------------------ | ---------: | ---------: | ---------- | --: | ------: | -----: | -: | --------------: | -------------------: |
| qwen3vlmoe 30B.A3B Q4_1        |  17.87 GiB |    30.53 B | ROCm       |  99 |      12 |   q8_0 |  1 |           pp512 |       1541.04 ± 0.00 |
llama-bench: benchmark 2/2: starting
llama-bench: benchmark 2/2: warmup generation run
llama-bench: benchmark 2/2: generation run 1/1
| qwen3vlmoe 30B.A3B Q4_1        |  17.87 GiB |    30.53 B | ROCm       |  99 |      12 |   q8_0 |  1 |           tg128 |        125.98 ± 0.00 |

build: fb7e6eed (7775)
ggml_cuda_init: found 1 ROCm devices:
  Device 0: AMD Instinct MI50/MI60, gfx906:sramecc+:xnack- (0x906), VMM: no, Wave Size: 64
llama-bench: benchmark 1/2: starting
main: error: failed to load model '/media/iacoppbk/80F42C9BF42C96061/llms//mnt/data/openai_gpt-oss-20b-MXFP4.gguf'
| model                          |       size |     params | backend    | ngl | threads | type_k | fa |            test |                  t/s |
| ------------------------------ | ---------: | ---------: | ---------- | --: | ------: | -----: | -: | --------------: | -------------------: |
ggml_cuda_init: found 1 ROCm devices:
  Device 0: AMD Instinct MI50/MI60, gfx906:sramecc+:xnack- (0x906), VMM: no, Wave Size: 64
llama-bench: benchmark 1/2: starting
llama-bench: benchmark 1/2: warmup prompt run
llama-bench: benchmark 1/2: prompt run 1/1
| model                          |       size |     params | backend    | ngl | threads | type_k | fa |            test |                  t/s |
| ------------------------------ | ---------: | ---------: | ---------- | --: | ------: | -----: | -: | --------------: | -------------------: |
| gpt-oss 20B MXFP4 MoE          |  11.27 GiB |    20.91 B | ROCm       |  99 |      12 |   q8_0 |  1 |           pp512 |       1325.58 ± 0.00 |
llama-bench: benchmark 2/2: starting
llama-bench: benchmark 2/2: warmup generation run
llama-bench: benchmark 2/2: generation run 1/1
| gpt-oss 20B MXFP4 MoE          |  11.27 GiB |    20.91 B | ROCm       |  99 |      12 |   q8_0 |  1 |           tg128 |        146.08 ± 0.00 |

build: fb7e6eed (7775)
ggml_cuda_init: found 1 ROCm devices:
  Device 0: AMD Instinct MI50/MI60, gfx906:sramecc+:xnack- (0x906), VMM: no, Wave Size: 64
llama-bench: benchmark 1/2: starting
llama-bench: benchmark 1/2: warmup prompt run
llama-bench: benchmark 1/2: prompt run 1/1
| model                          |       size |     params | backend    | ngl | threads | type_k | fa |            test |                  t/s |
| ------------------------------ | ---------: | ---------: | ---------- | --: | ------: | -----: | -: | --------------: | -------------------: |
| gpt-oss 20B MXFP4 MoE          |  11.27 GiB |    20.91 B | ROCm       |  99 |      12 |   q8_0 |  1 |           pp512 |       1328.14 ± 0.00 |
llama-bench: benchmark 2/2: starting
llama-bench: benchmark 2/2: warmup generation run
llama-bench: benchmark 2/2: generation run 1/1
| gpt-oss 20B MXFP4 MoE          |  11.27 GiB |    20.91 B | ROCm       |  99 |      12 |   q8_0 |  1 |           tg128 |        147.52 ± 0.00 |

build: fb7e6eed (7775)
ggml_cuda_init: found 1 ROCm devices:
  Device 0: AMD Instinct MI50/MI60, gfx906:sramecc+:xnack- (0x906), VMM: no, Wave Size: 64
llama-bench: benchmark 1/2: starting
llama-bench: benchmark 1/2: warmup prompt run
llama-bench: benchmark 1/2: prompt run 1/1
| model                          |       size |     params | backend    | ngl | threads | type_k | fa |            test |                  t/s |
| ------------------------------ | ---------: | ---------: | ---------- | --: | ------: | -----: | -: | --------------: | -------------------: |
| kimi-linear 48B.A3B MXFP4 MoE  |  25.33 GiB |    49.12 B | ROCm       |  99 |      12 |   q8_0 |  1 |           pp512 |        330.97 ± 0.00 |
llama-bench: benchmark 2/2: starting
llama-bench: benchmark 2/2: warmup generation run
llama-bench: benchmark 2/2: generation run 1/1
| kimi-linear 48B.A3B MXFP4 MoE  |  25.33 GiB |    49.12 B | ROCm       |  99 |      12 |   q8_0 |  1 |           tg128 |         54.38 ± 0.00 |

build: fb7e6eed (7775)
ggml_cuda_init: found 1 ROCm devices:
  Device 0: AMD Instinct MI50/MI60, gfx906:sramecc+:xnack- (0x906), VMM: no, Wave Size: 64
llama-bench: benchmark 1/2: starting
llama-bench: benchmark 1/2: warmup prompt run
llama-bench: benchmark 1/2: depth run 1/1
llama-bench: benchmark 1/2: prompt run 1/1
| model                          |       size |     params | backend    | ngl | threads | type_k | fa |            test |                  t/s |
| ------------------------------ | ---------: | ---------: | ---------- | --: | ------: | -----: | -: | --------------: | -------------------: |
| kimi-linear 48B.A3B MXFP4 MoE  |  25.33 GiB |    49.12 B | ROCm       |  99 |      12 |   q8_0 |  1 |   pp512 @ d8192 |        155.96 ± 0.00 |
llama-bench: benchmark 2/2: starting
llama-bench: benchmark 2/2: warmup generation run
llama-bench: benchmark 2/2: depth run 1/1 (cached)
llama-bench: benchmark 2/2: generation run 1/1
| kimi-linear 48B.A3B MXFP4 MoE  |  25.33 GiB |    49.12 B | ROCm       |  99 |      12 |   q8_0 |  1 |   tg128 @ d8192 |         45.13 ± 0.00 |

build: fb7e6eed (7775)
