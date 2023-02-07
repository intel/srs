---
layout: default
---

## Scan date: 2023.02.07
[All results (tar.gz)](./all-results.tar.gz) [Repo list (JSON)](./filtered-repos.json) [Bug breakdown (JSON)](./bug_breakdown.json) [Score vs Bugs (CSV)](./score_vs_bugs.csv)

***

---
## Repositories matching search query 'archived:false language:c language:c++ org:intel stars:>=1': 163
## Repositories with supported build systems: 125
Github Actions Run ID: [4114208664](https://github.com/intel/srs/actions/runs/4114208664)

***

### Repositories built with scan-build: 55
### Repositories scored with OSSF scorecard: 111

***

### Total number of bugs found: 574
### Total number of high cognitivite complexity functions found: 5934

***

#### Bug categories
##### API: 19
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/fineibt_llvm | 1 |
| intel/gdb | 6 |
| intel/intel-device-resource-mgt-lib | 6 |
| intel/linux-sgx | 2 |
| intel/qatlib | 4 |

***

##### C++ move semantics: 7
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/compile-time-init-build | 3 |
| intel/hexl | 4 |

***

##### Logic error: 216
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/DML | 2 |
| intel/MTMC-Temporal-Profiler | 2 |
| intel/cloud-client-ai-service-framework | 1 |
| intel/cm-cpu-emulation | 1 |
| intel/compute-aggregation-layer | 1 |
| intel/dptf | 3 |
| intel/fineibt_llvm | 32 |
| intel/gdb | 43 |
| intel/gmmlib | 16 |
| intel/hexl | 2 |
| intel/ideep | 3 |
| intel/intel-device-resource-mgt-lib | 29 |
| intel/intel-extension-for-transformers | 4 |
| intel/intel-graphics-compiler | 10 |
| intel/iotg-lin-gfx-libva | 1 |
| intel/ipp-crypto | 2 |
| intel/isa-l | 3 |
| intel/linux-sgx | 1 |
| intel/opencl-intercept-layer | 2 |
| intel/pcm | 2 |
| intel/qatlib | 25 |
| intel/qpl | 8 |
| intel/systemc-compiler | 1 |
| intel/xpumanager | 20 |
| intel/zlib | 2 |

***

##### Memory error: 86
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/cm-cpu-emulation | 2 |
| intel/compile-time-init-build | 1 |
| intel/fineibt_llvm | 9 |
| intel/gdb | 30 |
| intel/gmmlib | 10 |
| intel/intel-device-resource-mgt-lib | 5 |
| intel/intel-extension-for-transformers | 2 |
| intel/libva | 2 |
| intel/linux-sgx | 3 |
| intel/qatlib | 5 |
| intel/systemc-compiler | 2 |
| intel/xpumanager | 15 |

***

##### Readability: 5934
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/DML | 80 |
| intel/IA-Hardware-Composer | 4 |
| intel/Intel-Vector-Data-Streaming-Library | 5 |
| intel/MTMC-Temporal-Profiler | 2 |
| intel/SGXDataCenterAttestationPrimitives | 18 |
| intel/aubstream | 7 |
| intel/cloud-client-ai-service-framework | 1 |
| intel/cm-cpu-emulation | 7 |
| intel/compile-time-init-build | 32 |
| intel/compute-aggregation-layer | 76 |
| intel/compute-benchmarks | 129 |
| intel/crypto-api-toolkit | 4 |
| intel/dptf | 32 |
| intel/fineibt_llvm | 555 |
| intel/gdb | 266 |
| intel/gmmlib | 340 |
| intel/hexl-fpga | 2 |
| intel/hexl | 24 |
| intel/ideep | 588 |
| intel/igsc | 25 |
| intel/intel-device-resource-mgt-lib | 226 |
| intel/intel-extension-for-transformers | 1451 |
| intel/intel-graphics-compiler | 156 |
| intel/intel-ipsec-mb | 76 |
| intel/intel-qs | 21 |
| intel/iotg-lin-gfx-libva | 15 |
| intel/iotg_tsn_ref_sw | 4 |
| intel/ipmctl | 2 |
| intel/ipp-crypto | 3 |
| intel/isa-l | 23 |
| intel/libipt | 14 |
| intel/libva | 21 |
| intel/linux-sgx | 130 |
| intel/linux-vpu-driver | 37 |
| intel/media-driver | 13 |
| intel/metee | 3 |
| intel/oneAPI-Ultrasound-Beamforming-Library | 3 |
| intel/opencl-intercept-layer | 222 |
| intel/pcm | 154 |
| intel/qatlib | 390 |
| intel/qemu-tdx | 10 |
| intel/qpl | 206 |
| intel/safe-arithmetic | 1 |
| intel/safestringlib | 19 |
| intel/systemc-compiler | 32 |
| intel/thermal_daemon | 30 |
| intel/xpumanager | 414 |
| intel/yarpgen | 30 |
| intel/zlib | 31 |

***

##### Security: 245
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/DML | 2 |
| intel/IA-Hardware-Composer | 6 |
| intel/dptf | 2 |
| intel/fineibt_llvm | 3 |
| intel/gdb | 144 |
| intel/ideep | 2 |
| intel/intel-device-resource-mgt-lib | 27 |
| intel/iotg-lin-gfx-libva | 1 |
| intel/iotg_tsn_ref_sw | 2 |
| intel/libva | 1 |
| intel/linux-sgx | 2 |
| intel/media-driver | 7 |
| intel/metee | 2 |
| intel/opencl-intercept-layer | 6 |
| intel/pcm | 2 |
| intel/qatlib | 2 |
| intel/systemc-compiler | 18 |
| intel/uintr-ipc-bench | 2 |
| intel/xpumanager | 8 |
| intel/zlib | 6 |

***

##### Unix API: 1
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/qatlib | 1 |

***

#### Bug types
##### Allocator sizeof operand mismatch: 1
| Repo        | Bug count   |
|:-----------:|:-----------:|
| intel/qatlib | 1 |

***

##### Argument with 'nonnull' attribute passed null: 19
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/fineibt_llvm | 1 |
| intel/gdb | 6 |
| intel/intel-device-resource-mgt-lib | 6 |
| intel/linux-sgx | 2 |
| intel/qatlib | 4 |

***

##### Assigned value is garbage or undefined: 25
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/fineibt_llvm | 1 |
| intel/gdb | 9 |
| intel/gmmlib | 6 |
| intel/intel-device-resource-mgt-lib | 2 |
| intel/intel-graphics-compiler | 2 |
| intel/isa-l | 1 |
| intel/qatlib | 1 |
| intel/qpl | 2 |
| intel/xpumanager | 1 |

***

##### Bad align storage for placement new: 1
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/fineibt_llvm | 1 |

***

##### Bad deallocator: 1
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/intel-extension-for-transformers | 1 |

***

##### Branch condition evaluates to a garbage value: 6
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/intel-device-resource-mgt-lib | 4 |
| intel/iotg-lin-gfx-libva | 1 |
| intel/xpumanager | 1 |

***

##### Called C++ object pointer is null: 14
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/fineibt_llvm | 4 |
| intel/gdb | 4 |
| intel/gmmlib | 2 |
| intel/intel-device-resource-mgt-lib | 2 |
| intel/intel-graphics-compiler | 1 |
| intel/xpumanager | 1 |

***

##### Called function pointer is null (null dereference): 3
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/fineibt_llvm | 1 |
| intel/intel-extension-for-transformers | 2 |

***

##### Cognitive complexity: 5934
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/DML | 80 |
| intel/IA-Hardware-Composer | 4 |
| intel/Intel-Vector-Data-Streaming-Library | 5 |
| intel/MTMC-Temporal-Profiler | 2 |
| intel/SGXDataCenterAttestationPrimitives | 18 |
| intel/aubstream | 7 |
| intel/cloud-client-ai-service-framework | 1 |
| intel/cm-cpu-emulation | 7 |
| intel/compile-time-init-build | 32 |
| intel/compute-aggregation-layer | 76 |
| intel/compute-benchmarks | 129 |
| intel/crypto-api-toolkit | 4 |
| intel/dptf | 32 |
| intel/fineibt_llvm | 555 |
| intel/gdb | 266 |
| intel/gmmlib | 340 |
| intel/hexl-fpga | 2 |
| intel/hexl | 24 |
| intel/ideep | 588 |
| intel/igsc | 25 |
| intel/intel-device-resource-mgt-lib | 226 |
| intel/intel-extension-for-transformers | 1451 |
| intel/intel-graphics-compiler | 156 |
| intel/intel-ipsec-mb | 76 |
| intel/intel-qs | 21 |
| intel/iotg-lin-gfx-libva | 15 |
| intel/iotg_tsn_ref_sw | 4 |
| intel/ipmctl | 2 |
| intel/ipp-crypto | 3 |
| intel/isa-l | 23 |
| intel/libipt | 14 |
| intel/libva | 21 |
| intel/linux-sgx | 130 |
| intel/linux-vpu-driver | 37 |
| intel/media-driver | 13 |
| intel/metee | 3 |
| intel/oneAPI-Ultrasound-Beamforming-Library | 3 |
| intel/opencl-intercept-layer | 222 |
| intel/pcm | 154 |
| intel/qatlib | 390 |
| intel/qemu-tdx | 10 |
| intel/qpl | 206 |
| intel/safe-arithmetic | 1 |
| intel/safestringlib | 19 |
| intel/systemc-compiler | 32 |
| intel/thermal_daemon | 30 |
| intel/xpumanager | 414 |
| intel/yarpgen | 30 |
| intel/zlib | 31 |

***

##### Dangerous construct in a vforked process: 1
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/gdb | 1 |

***

##### Dereference of null pointer: 77
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/compute-aggregation-layer | 1 |
| intel/dptf | 1 |
| intel/fineibt_llvm | 15 |
| intel/gdb | 23 |
| intel/intel-device-resource-mgt-lib | 16 |
| intel/linux-sgx | 1 |
| intel/opencl-intercept-layer | 2 |
| intel/qatlib | 16 |
| intel/xpumanager | 2 |

***

##### Division by zero: 17
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/fineibt_llvm | 1 |
| intel/gmmlib | 2 |
| intel/intel-extension-for-transformers | 2 |
| intel/intel-graphics-compiler | 2 |
| intel/qatlib | 5 |
| intel/systemc-compiler | 1 |
| intel/xpumanager | 4 |

***

##### Double free: 6
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/compile-time-init-build | 1 |
| intel/fineibt_llvm | 2 |
| intel/intel-extension-for-transformers | 1 |
| intel/libva | 1 |
| intel/xpumanager | 1 |

***

##### Garbage return value: 4
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/cm-cpu-emulation | 1 |
| intel/fineibt_llvm | 1 |
| intel/gdb | 1 |
| intel/intel-graphics-compiler | 1 |

***

##### Memory leak: 40
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/fineibt_llvm | 2 |
| intel/gdb | 9 |
| intel/gmmlib | 10 |
| intel/intel-device-resource-mgt-lib | 5 |
| intel/linux-sgx | 3 |
| intel/qatlib | 5 |
| intel/xpumanager | 6 |

***

##### Potential insecure implementation-specific behavior in call 'vfork': 1
| Repo        | Bug count   |
|:-----------:|:-----------:|
| intel/gdb | 1 |

***

##### Potential insecure memory buffer bounds restriction in call 'strcat': 35
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/DML | 1 |
| intel/IA-Hardware-Composer | 1 |
| intel/dptf | 1 |
| intel/gdb | 8 |
| intel/ideep | 1 |
| intel/intel-device-resource-mgt-lib | 8 |
| intel/iotg-lin-gfx-libva | 1 |
| intel/iotg_tsn_ref_sw | 1 |
| intel/libva | 1 |
| intel/linux-sgx | 1 |
| intel/media-driver | 4 |
| intel/metee | 1 |
| intel/opencl-intercept-layer | 4 |
| intel/pcm | 1 |
| intel/qatlib | 1 |

***

##### Potential insecure memory buffer bounds restriction in call 'strcpy': 208
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/DML | 1 |
| intel/IA-Hardware-Composer | 5 |
| intel/dptf | 1 |
| intel/fineibt_llvm | 3 |
| intel/gdb | 134 |
| intel/ideep | 1 |
| intel/intel-device-resource-mgt-lib | 19 |
| intel/iotg_tsn_ref_sw | 1 |
| intel/linux-sgx | 1 |
| intel/media-driver | 3 |
| intel/metee | 1 |
| intel/opencl-intercept-layer | 2 |
| intel/pcm | 1 |
| intel/qatlib | 1 |
| intel/systemc-compiler | 18 |
| intel/uintr-ipc-bench | 2 |
| intel/xpumanager | 8 |
| intel/zlib | 6 |

***

##### Potential insecure temporary file in call 'mktemp': 1
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/gdb | 1 |

***

##### Result of operation is garbage or undefined: 31
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/cloud-client-ai-service-framework | 1 |
| intel/fineibt_llvm | 3 |
| intel/gdb | 5 |
| intel/gmmlib | 2 |
| intel/ideep | 3 |
| intel/intel-device-resource-mgt-lib | 2 |
| intel/intel-graphics-compiler | 4 |
| intel/qatlib | 1 |
| intel/qpl | 3 |
| intel/xpumanager | 7 |

***

##### Return of address to stack-allocated memory: 2
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/intel-device-resource-mgt-lib | 2 |

***

##### Returning null reference: 2
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/fineibt_llvm | 2 |

***

##### Uninitialized argument value: 34
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/DML | 2 |
| intel/MTMC-Temporal-Profiler | 2 |
| intel/dptf | 2 |
| intel/fineibt_llvm | 4 |
| intel/gmmlib | 4 |
| intel/hexl | 2 |
| intel/intel-device-resource-mgt-lib | 1 |
| intel/ipp-crypto | 2 |
| intel/isa-l | 2 |
| intel/pcm | 2 |
| intel/qatlib | 2 |
| intel/qpl | 3 |
| intel/xpumanager | 4 |
| intel/zlib | 2 |

***

##### Use of zero allocated: 6
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/gdb | 3 |
| intel/xpumanager | 3 |

***

##### Use-after-free: 32
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/cm-cpu-emulation | 2 |
| intel/fineibt_llvm | 4 |
| intel/gdb | 18 |
| intel/libva | 1 |
| intel/systemc-compiler | 2 |
| intel/xpumanager | 5 |

***

##### Use-after-move: 7
| Repo        | Bug count   |
|:-----------:|:-----------:|

| intel/compile-time-init-build | 3 |
| intel/hexl | 4 |

***


***

### Repositories with no bugs: 5
| Repo        |
|:---:|

| intel/pailliercryptolib |
| intel/gna |
| intel/BDTK |
| intel/eth-mpi-apps |
| intel/cm-compiler |

### Breakdown
| Repo        | OSSF score  | Bugs      | High cognitive complexity functions / Total functions   |
|:-----------:|:-----------:|:---------:|:-------------------------------------------------------:|

| intel/media-driver | 5.3 | 7 | 13 / 101 |
| intel/linux-vpu-driver | 4.3 | 0 | 37 / 2074 |
| intel/aubstream | 4.3 | 0 | 7 / 126 |
| intel/intel-qs | 5.3 | 0 | 21 / 180 |
| intel/pailliercryptolib | 5.3 | 0 | 0 / 66 |
| intel/intel-ipsec-mb | 5.3 | 0 | 76 / 485 |
| intel/oneAPI-Ultrasound-Beamforming-Library | 4.3 | 0 | 3 / 23 |
| intel/hexl-fpga | 4.9 | 0 | 2 / 69 |
| intel/dptf | 5.3 | 5 | 32 / 1969 |
| intel/intel-extension-for-transformers | 5.3 | 6 | 1451 / 4482 |
| intel/xpumanager | 5.3 | 43 | 414 / 2818 |
| intel/ipmctl | 4.3 | 0 | 2 / 11 |
| intel/MTMC-Temporal-Profiler | 5.3 | 2 | 2 / 37 |
| intel/compute-aggregation-layer | 4.3 | 1 | 76 / 296 |
| intel/hexl | 4.3 | 6 | 24 / 236 |
| intel/qpl | 4.3 | 8 | 206 / 1391 |
| intel/zlib | 5.3 | 8 | 31 / 221 |
| intel/DML | 5.3 | 4 | 80 / 391 |
| intel/gdb | 5.3 | 223 | 266 / 2450 |
| intel/systemc-compiler | 4.9 | 21 | 32 / 1099 |
| intel/pcm | 5.3 | 4 | 154 / 776 |
| intel/compile-time-init-build | 4.3 | 4 | 32 / 455 |
| intel/cloud-client-ai-service-framework | 4.9 | 1 | 1 / 15 |
| intel/thermal_daemon | 5.3 | 0 | 30 / 335 |
| intel/gna | 4.3 | 0 | 0 / 5 |
| intel/SGXDataCenterAttestationPrimitives | 4.3 | 0 | 18 / 273 |
| intel/uintr-ipc-bench | 4.3 | 2 | 0 / 104 |
| intel/igsc | 5.3 | 0 | 25 / 92 |
| intel/ideep | 4.3 | 5 | 588 / 1375 |
| intel/gmmlib | 4.3 | 26 | 340 / 1410 |
| intel/safe-arithmetic | 4.3 | 0 | 1 / 7 |
| intel/qemu-tdx | 5.3 | 0 | 10 / 91 |
| intel/compute-benchmarks | 5.3 | 0 | 129 / 353 |
| intel/BDTK | 4.3 | 0 | 0 / 4 |
| intel/IA-Hardware-Composer | 4.9 | 6 | 4 / 117 |
| intel/yarpgen | 5.3 | 0 | 30 / 228 |
| intel/qatlib | 4.5 | 37 | 390 / 1371 |
| intel/crypto-api-toolkit | 4.9 | 0 | 4 / 219 |
| intel/Intel-Vector-Data-Streaming-Library | 4.9 | 0 | 5 / 130 |
| intel/metee | 4.7 | 2 | 3 / 65 |
| intel/iotg-lin-gfx-libva | 4.7 | 2 | 15 / 303 |
| intel/safestringlib | 4.9 | 0 | 19 / 84 |
| intel/eth-mpi-apps | 5.3 | 0 | 0 / 0 |
| intel/linux-sgx | 4.3 | 8 | 130 / 992 |
| intel/fineibt_llvm | 5.3 | 45 | 555 / 6468 |
| intel/libipt | 5.3 | 0 | 14 / 475 |
| intel/cm-cpu-emulation | 4.3 | 3 | 7 / 109 |
| intel/intel-device-resource-mgt-lib | 5.3 | 67 | 226 / 1970 |
| intel/libva | 4.9 | 3 | 21 / 328 |
| intel/iotg_tsn_ref_sw | 4.3 | 2 | 4 / 19 |
| intel/isa-l | 4.3 | 3 | 23 / 158 |
| intel/ipp-crypto | 5.3 | 2 | 3 / 252 |
| intel/cm-compiler | 5.3 | 0 | 0 / 28 |
| intel/opencl-intercept-layer | 5.3 | 8 | 222 / 408 |
| intel/intel-graphics-compiler | 5.3 | 10 | 156 / 1170 |

[back](../..)
