ggml_cuda_init: found 1 ROCm devices:
  Device 0: AMD Instinct MI50/MI60, gfx906:sramecc+:xnack- (0x906), VMM: no, Wave Size: 64
llama-bench: benchmark 1/2: starting
main: error: failed to load model '/path/...'
| model                          |       size |     params | backend    | ngl | threads | type_k | fa |            test |                  t/s |
| ------------------------------ | ---------: | ---------: | ---------- | --: | ------: | -----: | -: | --------------: | -------------------: |
ggml_cuda_init: found 1 ROCm devices:
  Device 0: AMD Instinct MI50/MI60, gfx906:sramecc+:xnack- (0x906), VMM: no, Wave Size: 64
llama-bench: benchmark 1/2: starting
llama-bench: benchmark 1/2: warmup prompt run
llama-bench: benchmark 1/2: depth run 1/1
llama-bench: benchmark 1/2: prompt run 1/1
| model                          |       size |     params | backend    | ngl | threads | type_k | fa |            test |                  t/s |
| ------------------------------ | ---------: | ---------: | ---------- | --: | ------: | -----: | -: | --------------: | -------------------: |
| qwen3moe 30B.A3B Q8_0          |  24.64 GiB |    24.87 B | ROCm       |  99 |      12 |   q8_0 |  1 |   pp512 @ d8192 |        655.33 ± 0.00 |
llama-bench: benchmark 2/2: starting
llama-bench: benchmark 2/2: warmup generation run
llama-bench: benchmark 2/2: depth run 1/1 (cached)
llama-bench: benchmark 2/2: generation run 1/1
| qwen3moe 30B.A3B Q8_0          |  24.64 GiB |    24.87 B | ROCm       |  99 |      12 |   q8_0 |  1 |   tg128 @ d8192 |         84.81 ± 0.00 |

build: 269b919ba (7673)
ggml_cuda_init: found 1 ROCm devices:
  Device 0: AMD Instinct MI50/MI60, gfx906:sramecc+:xnack- (0x906), VMM: no, Wave Size: 64
llama-bench: benchmark 1/2: starting
llama-bench: benchmark 1/2: warmup prompt run
llama-bench: benchmark 1/2: depth run 1/1
llama-bench: benchmark 1/2: prompt run 1/1
| model                          |       size |     params | backend    | ngl | threads | type_k | fa |            test |                  t/s |
| ------------------------------ | ---------: | ---------: | ---------- | --: | ------: | -----: | -: | --------------: | -------------------: |
| qwen3moe 30B.A3B Q8_0          |  24.64 GiB |    24.87 B | ROCm       |  99 |      12 |   q8_0 |  1 |   pp512 @ d8192 |        603.50 ± 0.00 |
llama-bench: benchmark 2/2: starting
llama-bench: benchmark 2/2: warmup generation run
llama-bench: benchmark 2/2: depth run 1/1 (cached)
llama-bench: benchmark 2/2: generation run 1/1
| qwen3moe 30B.A3B Q8_0          |  24.64 GiB |    24.87 B | ROCm       |  99 |      12 |   q8_0 |  1 |   tg128 @ d8192 |         75.86 ± 0.00 |

build: 3343e1943 (7675)
ggml_cuda_init: found 1 ROCm devices:
  Device 0: AMD Instinct MI50/MI60, gfx906:sramecc+:xnack- (0x906), VMM: no, Wave Size: 64
llama-bench: benchmark 1/2: starting
llama-bench: benchmark 1/2: warmup prompt run
llama-bench: benchmark 1/2: depth run 1/1
llama-bench: benchmark 1/2: prompt run 1/1
| model                          |       size |     params | backend    | ngl | threads | type_k | fa |            test |                  t/s |
| ------------------------------ | ---------: | ---------: | ---------- | --: | ------: | -----: | -: | --------------: | -------------------: |
| qwen3moe 30B.A3B Q8_0          |  24.64 GiB |    24.87 B | ROCm       |  99 |      12 |   q8_0 |  1 |   pp512 @ d8192 |        646.01 ± 0.00 |
llama-bench: benchmark 2/2: starting
llama-bench: benchmark 2/2: warmup generation run
llama-bench: benchmark 2/2: depth run 1/1 (cached)
llama-bench: benchmark 2/2: generation run 1/1
| qwen3moe 30B.A3B Q8_0          |  24.64 GiB |    24.87 B | ROCm       |  99 |      12 |   q8_0 |  1 |   tg128 @ d8192 |         85.19 ± 0.00 |

build: 3343e1943 (7675)
