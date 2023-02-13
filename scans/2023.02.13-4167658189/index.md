---
layout: default
---

## Scan date: 2023.02.13
[All results (tar.gz)](./all-results.tar.gz) [Repo list (JSON)](./filtered-repos.json) [Bug breakdown (JSON)](./bug_breakdown.json) [Score vs Bugs (CSV)](./score_vs_bugs.csv)

***

---
## Repositories matching search query 'archived:false language:c language:c++ org:intel stars:>=1': 164
## Repositories with supported build systems: 126
Github Actions Run ID: [4167658189](https://github.com/intel/srs/actions/runs/4167658189)

***

### Repositories built with scan-build: 58
### Repositories scored with OSSF scorecard: 112

***

### Total number of bugs found: 607
### Total number of high cognitivite complexity functions found: 6958

***

#### Bug categories
##### API: 19
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/intel-device-resource-mgt-lib | 6 |
| intel/gdb | 6 |
| intel/qatlib | 4 |
| intel/linux-sgx | 2 |
| intel/fineibt_llvm | 1 |

***

##### C++ move semantics: 7
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/hexl | 4 |
| intel/compile-time-init-build | 3 |

***

##### Logic error: 229
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/gdb | 43 |
| intel/fineibt_llvm | 39 |
| intel/intel-device-resource-mgt-lib | 29 |
| intel/qatlib | 25 |
| intel/xpumanager | 20 |
| intel/gmmlib | 16 |
| intel/intel-graphics-compiler | 10 |
| intel/intel-ipsec-mb | 7 |
| intel/qpl | 6 |
| intel/intel-extension-for-transformers | 4 |
| intel/isa-l | 3 |
| intel/ideep | 3 |
| intel/dptf | 3 |
| intel/zlib | 2 |
| intel/systemc-compiler | 2 |
| intel/pcm | 2 |
| intel/opencl-intercept-layer | 2 |
| intel/ipp-crypto | 2 |
| intel/hexl | 2 |
| intel/MTMC-Temporal-Profiler | 2 |
| intel/DML | 2 |
| intel/linux-sgx | 1 |
| intel/iotg-lin-gfx-libva | 1 |
| intel/compute-aggregation-layer | 1 |
| intel/cm-cpu-emulation | 1 |
| intel/cloud-client-ai-service-framework | 1 |

***

##### Memory error: 96
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/gdb | 30 |
| intel/fineibt_llvm | 19 |
| intel/xpumanager | 15 |
| intel/gmmlib | 10 |
| intel/qatlib | 5 |
| intel/intel-device-resource-mgt-lib | 5 |
| intel/linux-sgx | 3 |
| intel/systemc-compiler | 2 |
| intel/libva | 2 |
| intel/intel-extension-for-transformers | 2 |
| intel/cm-cpu-emulation | 2 |
| intel/compile-time-init-build | 1 |

***

##### Readability: 6958
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/libvirt-tdx | 1311 |
| intel/intel-extension-for-transformers | 922 |
| intel/fineibt_llvm | 793 |
| intel/ideep | 588 |
| intel/xpumanager | 453 |
| intel/qatlib | 390 |
| intel/gmmlib | 340 |
| intel/gdb | 254 |
| intel/intel-device-resource-mgt-lib | 226 |
| intel/opencl-intercept-layer | 222 |
| intel/intel-graphics-compiler | 156 |
| intel/pcm | 155 |
| intel/qpl | 153 |
| intel/linux-sgx | 130 |
| intel/compute-benchmarks | 129 |
| intel/DML | 80 |
| intel/intel-ipsec-mb | 76 |
| intel/compute-aggregation-layer | 51 |
| intel/dptf | 46 |
| intel/linux-vpu-driver | 37 |
| intel/systemc-compiler | 32 |
| intel/compile-time-init-build | 32 |
| intel/zlib | 31 |
| intel/idxd-config | 31 |
| intel/yarpgen | 30 |
| intel/thermal_daemon | 30 |
| intel/igsc | 25 |
| intel/hexl | 24 |
| intel/isa-l | 23 |
| intel/SGXDataCenterAttestationPrimitives | 23 |
| intel/libva | 21 |
| intel/intel-qs | 21 |
| intel/safestringlib | 19 |
| intel/iotg-lin-gfx-libva | 15 |
| intel/libipt | 14 |
| intel/media-driver | 13 |
| intel/qemu-tdx | 10 |
| intel/cm-cpu-emulation | 7 |
| intel/aubstream | 7 |
| intel/Intel-Vector-Data-Streaming-Library | 5 |
| intel/pti-gpu | 4 |
| intel/iotg_tsn_ref_sw | 4 |
| intel/crypto-api-toolkit | 4 |
| intel/IA-Hardware-Composer | 4 |
| intel/oneAPI-Ultrasound-Beamforming-Library | 3 |
| intel/metee | 3 |
| intel/ipp-crypto | 3 |
| intel/ipmctl | 2 |
| intel/hexl-fpga | 2 |
| intel/MTMC-Temporal-Profiler | 2 |
| intel/safe-arithmetic | 1 |
| intel/cloud-client-ai-service-framework | 1 |

***

##### Security: 255
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/gdb | 144 |
| intel/intel-device-resource-mgt-lib | 27 |
| intel/systemc-compiler | 18 |
| intel/xpumanager | 8 |
| intel/idxd-config | 8 |
| intel/media-driver | 7 |
| intel/zlib | 6 |
| intel/opencl-intercept-layer | 6 |
| intel/IA-Hardware-Composer | 6 |
| intel/fineibt_llvm | 3 |
| intel/uintr-ipc-bench | 2 |
| intel/qatlib | 2 |
| intel/pcm | 2 |
| intel/metee | 2 |
| intel/linux-sgx | 2 |
| intel/iotg_tsn_ref_sw | 2 |
| intel/intel-ipsec-mb | 2 |
| intel/ideep | 2 |
| intel/dptf | 2 |
| intel/DML | 2 |
| intel/libva | 1 |
| intel/iotg-lin-gfx-libva | 1 |

***

##### Unix API: 1
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/qatlib | 1 |

***

#### Bug types
##### Allocator sizeof operand mismatch: 1
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/qatlib | 1 |

***

##### Argument with 'nonnull' attribute passed null: 19
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/intel-device-resource-mgt-lib | 6 |
| intel/gdb | 6 |
| intel/qatlib | 4 |
| intel/linux-sgx | 2 |
| intel/fineibt_llvm | 1 |

***

##### Assigned value is garbage or undefined: 30
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/gdb | 9 |
| intel/gmmlib | 6 |
| intel/intel-ipsec-mb | 5 |
| intel/qpl | 2 |
| intel/intel-graphics-compiler | 2 |
| intel/intel-device-resource-mgt-lib | 2 |
| intel/xpumanager | 1 |
| intel/qatlib | 1 |
| intel/isa-l | 1 |
| intel/fineibt_llvm | 1 |

***

##### Bad align storage for placement new: 1
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/fineibt_llvm | 1 |

***

##### Bad deallocator: 1
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/intel-extension-for-transformers | 1 |

***

##### Branch condition evaluates to a garbage value: 6
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/intel-device-resource-mgt-lib | 4 |
| intel/xpumanager | 1 |
| intel/iotg-lin-gfx-libva | 1 |

***

##### Called C++ object pointer is null: 14
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/gdb | 4 |
| intel/fineibt_llvm | 4 |
| intel/intel-device-resource-mgt-lib | 2 |
| intel/gmmlib | 2 |
| intel/xpumanager | 1 |
| intel/intel-graphics-compiler | 1 |

***

##### Called function pointer is null (null dereference): 3
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/intel-extension-for-transformers | 2 |
| intel/fineibt_llvm | 1 |

***

##### Cognitive complexity: 6958
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/libvirt-tdx | 1311 |
| intel/intel-extension-for-transformers | 922 |
| intel/fineibt_llvm | 793 |
| intel/ideep | 588 |
| intel/xpumanager | 453 |
| intel/qatlib | 390 |
| intel/gmmlib | 340 |
| intel/gdb | 254 |
| intel/intel-device-resource-mgt-lib | 226 |
| intel/opencl-intercept-layer | 222 |
| intel/intel-graphics-compiler | 156 |
| intel/pcm | 155 |
| intel/qpl | 153 |
| intel/linux-sgx | 130 |
| intel/compute-benchmarks | 129 |
| intel/DML | 80 |
| intel/intel-ipsec-mb | 76 |
| intel/compute-aggregation-layer | 51 |
| intel/dptf | 46 |
| intel/linux-vpu-driver | 37 |
| intel/systemc-compiler | 32 |
| intel/compile-time-init-build | 32 |
| intel/zlib | 31 |
| intel/idxd-config | 31 |
| intel/yarpgen | 30 |
| intel/thermal_daemon | 30 |
| intel/igsc | 25 |
| intel/hexl | 24 |
| intel/isa-l | 23 |
| intel/SGXDataCenterAttestationPrimitives | 23 |
| intel/libva | 21 |
| intel/intel-qs | 21 |
| intel/safestringlib | 19 |
| intel/iotg-lin-gfx-libva | 15 |
| intel/libipt | 14 |
| intel/media-driver | 13 |
| intel/qemu-tdx | 10 |
| intel/cm-cpu-emulation | 7 |
| intel/aubstream | 7 |
| intel/Intel-Vector-Data-Streaming-Library | 5 |
| intel/pti-gpu | 4 |
| intel/iotg_tsn_ref_sw | 4 |
| intel/crypto-api-toolkit | 4 |
| intel/IA-Hardware-Composer | 4 |
| intel/oneAPI-Ultrasound-Beamforming-Library | 3 |
| intel/metee | 3 |
| intel/ipp-crypto | 3 |
| intel/ipmctl | 2 |
| intel/hexl-fpga | 2 |
| intel/MTMC-Temporal-Profiler | 2 |
| intel/safe-arithmetic | 1 |
| intel/cloud-client-ai-service-framework | 1 |

***

##### Dangerous construct in a vforked process: 1
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/gdb | 1 |

***

##### Dereference of null pointer: 77
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/gdb | 23 |
| intel/qatlib | 16 |
| intel/intel-device-resource-mgt-lib | 16 |
| intel/fineibt_llvm | 15 |
| intel/xpumanager | 2 |
| intel/opencl-intercept-layer | 2 |
| intel/linux-sgx | 1 |
| intel/dptf | 1 |
| intel/compute-aggregation-layer | 1 |

***

##### Division by zero: 17
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/qatlib | 5 |
| intel/xpumanager | 4 |
| intel/intel-graphics-compiler | 2 |
| intel/intel-extension-for-transformers | 2 |
| intel/gmmlib | 2 |
| intel/systemc-compiler | 1 |
| intel/fineibt_llvm | 1 |

***

##### Double free: 6
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/fineibt_llvm | 2 |
| intel/xpumanager | 1 |
| intel/libva | 1 |
| intel/intel-extension-for-transformers | 1 |
| intel/compile-time-init-build | 1 |

***

##### Garbage return value: 6
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/fineibt_llvm | 3 |
| intel/intel-graphics-compiler | 1 |
| intel/gdb | 1 |
| intel/cm-cpu-emulation | 1 |

***

##### Memory leak: 50
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/fineibt_llvm | 12 |
| intel/gmmlib | 10 |
| intel/gdb | 9 |
| intel/xpumanager | 6 |
| intel/qatlib | 5 |
| intel/intel-device-resource-mgt-lib | 5 |
| intel/linux-sgx | 3 |

***

##### Potential insecure implementation-specific behavior in call 'vfork': 1
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/gdb | 1 |

***

##### Potential insecure memory buffer bounds restriction in call 'strcat': 37
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/intel-device-resource-mgt-lib | 8 |
| intel/gdb | 8 |
| intel/opencl-intercept-layer | 4 |
| intel/media-driver | 4 |
| intel/qatlib | 1 |
| intel/pcm | 1 |
| intel/metee | 1 |
| intel/linux-sgx | 1 |
| intel/libva | 1 |
| intel/iotg_tsn_ref_sw | 1 |
| intel/iotg-lin-gfx-libva | 1 |
| intel/intel-ipsec-mb | 1 |
| intel/idxd-config | 1 |
| intel/ideep | 1 |
| intel/dptf | 1 |
| intel/IA-Hardware-Composer | 1 |
| intel/DML | 1 |

***

##### Potential insecure memory buffer bounds restriction in call 'strcpy': 216
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/gdb | 134 |
| intel/intel-device-resource-mgt-lib | 19 |
| intel/systemc-compiler | 18 |
| intel/xpumanager | 8 |
| intel/idxd-config | 7 |
| intel/zlib | 6 |
| intel/IA-Hardware-Composer | 5 |
| intel/media-driver | 3 |
| intel/fineibt_llvm | 3 |
| intel/uintr-ipc-bench | 2 |
| intel/opencl-intercept-layer | 2 |
| intel/qatlib | 1 |
| intel/pcm | 1 |
| intel/metee | 1 |
| intel/linux-sgx | 1 |
| intel/iotg_tsn_ref_sw | 1 |
| intel/intel-ipsec-mb | 1 |
| intel/ideep | 1 |
| intel/dptf | 1 |
| intel/DML | 1 |

***

##### Potential insecure temporary file in call 'mktemp': 1
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/gdb | 1 |

***

##### Result of operation is garbage or undefined: 33
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/xpumanager | 7 |
| intel/gdb | 5 |
| intel/fineibt_llvm | 5 |
| intel/intel-graphics-compiler | 4 |
| intel/ideep | 3 |
| intel/qpl | 2 |
| intel/intel-device-resource-mgt-lib | 2 |
| intel/gmmlib | 2 |
| intel/systemc-compiler | 1 |
| intel/qatlib | 1 |
| intel/cloud-client-ai-service-framework | 1 |

***

##### Return of address to stack-allocated memory: 2
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/intel-device-resource-mgt-lib | 2 |

***

##### Returning null reference: 2
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/fineibt_llvm | 2 |

***

##### Stack address stored into global variable: 1
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/fineibt_llvm | 1 |

***

##### Uninitialized argument value: 37
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/fineibt_llvm | 6 |
| intel/xpumanager | 4 |
| intel/gmmlib | 4 |
| intel/zlib | 2 |
| intel/qpl | 2 |
| intel/qatlib | 2 |
| intel/pcm | 2 |
| intel/isa-l | 2 |
| intel/ipp-crypto | 2 |
| intel/intel-ipsec-mb | 2 |
| intel/hexl | 2 |
| intel/dptf | 2 |
| intel/MTMC-Temporal-Profiler | 2 |
| intel/DML | 2 |
| intel/intel-device-resource-mgt-lib | 1 |

***

##### Use of zero allocated: 6
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/xpumanager | 3 |
| intel/gdb | 3 |

***

##### Use-after-free: 32
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/gdb | 18 |
| intel/xpumanager | 5 |
| intel/fineibt_llvm | 4 |
| intel/systemc-compiler | 2 |
| intel/cm-cpu-emulation | 2 |
| intel/libva | 1 |

***

##### Use-after-move: 7
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/hexl | 4 |
| intel/compile-time-init-build | 3 |

***


***

### Repositories with no bugs: 5

| Repo |
| ---- |
| intel/pailliercryptolib |
| intel/gna |
| intel/BDTK |
| intel/eth-mpi-apps |
| intel/cm-compiler |

### Breakdown
| #    | Repo        | Bugs       | OSSF score | High cognitive complexity functions / Total functions   |
| ---- | ----------- | ---------- | -------------------------------------------------------------------- |
| 1 | intel/gdb | 223 | 4.3 | 254 / 2531 |
| 2 | intel/intel-device-resource-mgt-lib | 67 | 4.3 | 226 / 1970 |
| 3 | intel/fineibt_llvm | 62 | 4.3 | 793 / 8731 |
| 4 | intel/xpumanager | 43 | 4.3 | 453 / 3096 |
| 5 | intel/qatlib | 37 | 4.3 | 390 / 1371 |
| 6 | intel/gmmlib | 26 | 5.3 | 340 / 1410 |
| 7 | intel/systemc-compiler | 22 | 5.3 | 32 / 1099 |
| 8 | intel/intel-graphics-compiler | 10 | 4.3 | 156 / 1170 |
| 9 | intel/intel-ipsec-mb | 9 | 4.3 | 76 / 531 |
| 10 | intel/zlib | 8 | 4.3 | 31 / 221 |
| 11 | intel/opencl-intercept-layer | 8 | 4.3 | 222 / 408 |
| 12 | intel/linux-sgx | 8 | 5.3 | 130 / 992 |
| 13 | intel/idxd-config | 8 | 4.3 | 31 / 205 |
| 14 | intel/media-driver | 7 | 4.7 | 13 / 101 |
| 15 | intel/qpl | 6 | 4.3 | 153 / 1131 |
| 16 | intel/intel-extension-for-transformers | 6 | 4.3 | 922 / 3071 |
| 17 | intel/hexl | 6 | 4.3 | 24 / 236 |
| 18 | intel/IA-Hardware-Composer | 6 | 4.7 | 4 / 117 |
| 19 | intel/ideep | 5 | 5.3 | 588 / 1375 |
| 20 | intel/dptf | 5 | 4.3 | 46 / 2248 |
| 21 | intel/pcm | 4 | 5.3 | 155 / 781 |
| 22 | intel/hexl | 4 |  |  /  |
| 23 | intel/compile-time-init-build | 4 | 5.3 | 32 / 455 |
| 24 | intel/DML | 4 | 4.3 | 80 / 391 |
| 25 | intel/libva | 3 | 4.7 | 21 / 328 |
| 26 | intel/isa-l | 3 | 4.3 | 23 / 158 |
| 27 | intel/compile-time-init-build | 3 |  |  /  |
| 28 | intel/cm-cpu-emulation | 3 | 5.3 | 7 / 110 |
| 29 | intel/uintr-ipc-bench | 2 | 5.3 | 0 / 104 |
| 30 | intel/metee | 2 | 5.3 | 3 / 65 |
| 31 | intel/ipp-crypto | 2 | 5.3 | 3 / 252 |
| 32 | intel/iotg_tsn_ref_sw | 2 | 4.7 | 4 / 19 |
| 33 | intel/iotg-lin-gfx-libva | 2 | 5.3 | 15 / 303 |
| 34 | intel/MTMC-Temporal-Profiler | 2 | 5.3 | 2 / 37 |
| 35 | intel/compute-aggregation-layer | 1 | 5.3 | 51 / 621 |
| 36 | intel/cloud-client-ai-service-framework | 1 | 5.3 | 1 / 15 |
| 37 | intel/yarpgen | 0 | 4.3 | 30 / 228 |
| 38 | intel/thermal_daemon | 0 | 5.3 | 30 / 335 |
| 39 | intel/safestringlib | 0 | 4.3 | 19 / 84 |
| 40 | intel/safe-arithmetic | 0 | 4.7 | 1 / 7 |
| 41 | intel/qemu-tdx | 0 | 4.3 | 10 / 91 |
| 42 | intel/pti-gpu | 0 | 5.3 | 4 / 63 |
| 43 | intel/pailliercryptolib | 0 | 4.7 | 0 / 66 |
| 44 | intel/oneAPI-Ultrasound-Beamforming-Library | 0 | 4.3 | 3 / 23 |
| 45 | intel/linux-vpu-driver | 0 | 4.3 | 37 / 2074 |
| 46 | intel/libvirt-tdx | 0 | 5.3 | 1311 / 12759 |
| 47 | intel/libipt | 0 | 4.3 | 14 / 475 |
| 48 | intel/ipmctl | 0 | 5.3 | 2 / 11 |
| 49 | intel/intel-qs | 0 | 4.3 | 21 / 180 |
| 50 | intel/igsc | 0 | 5.3 | 25 / 92 |
| 51 | intel/hexl-fpga | 0 | 4.3 | 2 / 69 |
| 52 | intel/gna | 0 | 5.3 | 0 / 5 |
| 53 | intel/crypto-api-toolkit | 0 | 4.3 | 4 / 219 |
| 54 | intel/compute-benchmarks | 0 | 5.3 | 129 / 354 |
| 55 | intel/cm-compiler | 0 | 5.3 | 0 / 28 |
| 56 | intel/aubstream | 0 | 5.3 | 7 / 126 |
| 57 | intel/SGXDataCenterAttestationPrimitives | 0 | 5.3 | 23 / 335 |
| 58 | intel/Intel-Vector-Data-Streaming-Library | 0 | 5.3 | 5 / 130 |
| 59 | intel/BDTK | 0 | 4.7 | 0 / 4 |
[back](../..)
