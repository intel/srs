---
layout: default
---

## Scan date: 2023.03.02
[All results (tar.gz)](./all-results.tar.gz) [Repo list (JSON)](./filtered-repos.json) [Bug breakdown (JSON)](./bug_breakdown.json) [Score vs Bugs (CSV)](./score_vs_bugs.csv)

***

---
## Repositories matching search query 'archived:false language:c language:c++ org:intel stars:>=1': 169
## Repositories with supported build systems: 116
Github Actions Run ID: [4315143687](https://github.com/intel/srs/actions/runs/4315143687)

### Breakdown
| #    | Repo        | Bugs       | OSSF score | High cognitive complexity functions / Total functions   |
| ---- | ----------- | ---------- | ---------- | ------------------------------------------------------- |
| 1 | [intel/intel-ipsec-mb](https://github.com/intel/intel-ipsec-mb) | 11 | 5 | 77 / 545 |
| 2 | [intel/gna](https://github.com/intel/gna) | 0 | 4.4 | 0 / 5 |
| 3 | [intel/compute-benchmarks](https://github.com/intel/compute-benchmarks) | 0 | 4.6 | 127 / 356 |
| 4 | [intel/aubstream](https://github.com/intel/aubstream) | 0 | 4.8 | 4 / 126 |
| 5 | [intel/Intel-Vector-Data-Streaming-Library](https://github.com/intel/Intel-Vector-Data-Streaming-Library) | 0 | 4.1 | 5 / 130 |
| 6 | [intel/BDTK](https://github.com/intel/BDTK) | 0 | 6.5 | 0 / 9 |

***

### Repositories built with scan-build: 25
### Repositories scored with OSSF scorecard: 31

***

### Total number of bugs found: 260
### Total number of high cognitivite complexity functions found: 1108

***

#### Bug categories
##### API: 4
| #   | Repo        | Bug count   |
| --- | ----------- | ----------- |
| 1 | intel/gdb | 4 |

***

##### C++ move semantics: 4
| #   | Repo        | Bug count   |
| --- | ----------- | ----------- |
| 1 | intel/hexl | 4 |

***

##### Logic error: 67
| #   | Repo        | Bug count   |
| --- | ----------- | ----------- |
| 1 | intel/gdb | 37 |
| 2 | intel/gmmlib | 8 |
| 3 | intel/intel-ipsec-mb | 7 |
| 4 | intel/ideep | 3 |
| 5 | intel/dptf | 3 |
| 6 | intel/intel-cpu-frequency-library | 2 |
| 7 | intel/hexl | 2 |
| 8 | intel/DML | 2 |
| 9 | intel/intel-device-resource-mgt-lib | 1 |
| 10 | intel/cm-cpu-emulation | 1 |
| 11 | intel/cloud-client-ai-service-framework | 1 |

***

##### Memory error: 25
| #   | Repo        | Bug count   |
| --- | ----------- | ----------- |
| 1 | intel/gdb | 18 |
| 2 | intel/gmmlib | 5 |
| 3 | intel/cm-cpu-emulation | 2 |

***

##### Readability: 1108
| #   | Repo        | Bug count   |
| --- | ----------- | ----------- |
| 1 | intel/ideep | 302 |
| 2 | intel/gdb | 195 |
| 3 | intel/gmmlib | 170 |
| 4 | intel/compute-benchmarks | 127 |
| 5 | intel/intel-ipsec-mb | 77 |
| 6 | intel/DML | 68 |
| 7 | intel/dptf | 46 |
| 8 | intel/igsc | 25 |
| 9 | intel/intel-device-resource-mgt-lib | 24 |
| 10 | intel/intel-qs | 21 |
| 11 | intel/intel-graphics-compiler | 16 |
| 12 | intel/hexl | 13 |
| 13 | intel/Intel-Vector-Data-Streaming-Library | 5 |
| 14 | intel/crypto-api-toolkit | 4 |
| 15 | intel/cm-cpu-emulation | 4 |
| 16 | intel/aubstream | 4 |
| 17 | intel/IA-Hardware-Composer | 4 |
| 18 | intel/hexl-fpga | 2 |
| 19 | intel/cloud-client-ai-service-framework | 1 |

***

##### Security: 160
| #   | Repo        | Bug count   |
| --- | ----------- | ----------- |
| 1 | intel/gdb | 144 |
| 2 | intel/IA-Hardware-Composer | 6 |
| 3 | intel/intel-ipsec-mb | 4 |
| 4 | intel/ideep | 2 |
| 5 | intel/dptf | 2 |
| 6 | intel/DML | 2 |

***

#### Bug types
##### Argument with 'nonnull' attribute passed null: 4
| #   | Repo        | Bug count   |
| --- | ----------- | ----------- |
| 1 | intel/gdb | 4 |

***

##### Assigned value is garbage or undefined: 17
| #   | Repo        | Bug count   |
| --- | ----------- | ----------- |
| 1 | intel/gdb | 9 |
| 2 | intel/intel-ipsec-mb | 5 |
| 3 | intel/gmmlib | 3 |

***

##### Called C++ object pointer is null: 2
| #   | Repo        | Bug count   |
| --- | ----------- | ----------- |
| 1 | intel/intel-device-resource-mgt-lib | 1 |
| 2 | intel/gmmlib | 1 |

***

##### Cognitive complexity: 1108
| #   | Repo        | Bug count   |
| --- | ----------- | ----------- |
| 1 | intel/ideep | 302 |
| 2 | intel/gdb | 195 |
| 3 | intel/gmmlib | 170 |
| 4 | intel/compute-benchmarks | 127 |
| 5 | intel/intel-ipsec-mb | 77 |
| 6 | intel/DML | 68 |
| 7 | intel/dptf | 46 |
| 8 | intel/igsc | 25 |
| 9 | intel/intel-device-resource-mgt-lib | 24 |
| 10 | intel/intel-qs | 21 |
| 11 | intel/intel-graphics-compiler | 16 |
| 12 | intel/hexl | 13 |
| 13 | intel/Intel-Vector-Data-Streaming-Library | 5 |
| 14 | intel/crypto-api-toolkit | 4 |
| 15 | intel/cm-cpu-emulation | 4 |
| 16 | intel/aubstream | 4 |
| 17 | intel/IA-Hardware-Composer | 4 |
| 18 | intel/hexl-fpga | 2 |
| 19 | intel/cloud-client-ai-service-framework | 1 |

***

##### Dangerous construct in a vforked process: 1
| #   | Repo        | Bug count   |
| --- | ----------- | ----------- |
| 1 | intel/gdb | 1 |

***

##### Dereference of null pointer: 22
| #   | Repo        | Bug count   |
| --- | ----------- | ----------- |
| 1 | intel/gdb | 21 |
| 2 | intel/dptf | 1 |

***

##### Division by zero: 1
| #   | Repo        | Bug count   |
| --- | ----------- | ----------- |
| 1 | intel/gmmlib | 1 |

***

##### Garbage return value: 2
| #   | Repo        | Bug count   |
| --- | ----------- | ----------- |
| 1 | intel/gdb | 1 |
| 2 | intel/cm-cpu-emulation | 1 |

***

##### Memory leak: 6
| #   | Repo        | Bug count   |
| --- | ----------- | ----------- |
| 1 | intel/gmmlib | 5 |
| 2 | intel/gdb | 1 |

***

##### Potential insecure implementation-specific behavior in call 'vfork': 1
| #   | Repo        | Bug count   |
| --- | ----------- | ----------- |
| 1 | intel/gdb | 1 |

***

##### Potential insecure memory buffer bounds restriction in call 'strcat': 15
| #   | Repo        | Bug count   |
| --- | ----------- | ----------- |
| 1 | intel/gdb | 8 |
| 2 | intel/intel-ipsec-mb | 3 |
| 3 | intel/ideep | 1 |
| 4 | intel/dptf | 1 |
| 5 | intel/IA-Hardware-Composer | 1 |
| 6 | intel/DML | 1 |

***

##### Potential insecure memory buffer bounds restriction in call 'strcpy': 143
| #   | Repo        | Bug count   |
| --- | ----------- | ----------- |
| 1 | intel/gdb | 134 |
| 2 | intel/IA-Hardware-Composer | 5 |
| 3 | intel/intel-ipsec-mb | 1 |
| 4 | intel/ideep | 1 |
| 5 | intel/dptf | 1 |
| 6 | intel/DML | 1 |

***

##### Potential insecure temporary file in call 'mktemp': 1
| #   | Repo        | Bug count   |
| --- | ----------- | ----------- |
| 1 | intel/gdb | 1 |

***

##### Result of operation is garbage or undefined: 10
| #   | Repo        | Bug count   |
| --- | ----------- | ----------- |
| 1 | intel/gdb | 5 |
| 2 | intel/ideep | 3 |
| 3 | intel/gmmlib | 1 |
| 4 | intel/cloud-client-ai-service-framework | 1 |

***

##### Uninitialized argument value: 12
| #   | Repo        | Bug count   |
| --- | ----------- | ----------- |
| 1 | intel/intel-ipsec-mb | 2 |
| 2 | intel/intel-cpu-frequency-library | 2 |
| 3 | intel/hexl | 2 |
| 4 | intel/gmmlib | 2 |
| 5 | intel/dptf | 2 |
| 6 | intel/DML | 2 |

***

##### Use-after-free: 19
| #   | Repo        | Bug count   |
| --- | ----------- | ----------- |
| 1 | intel/gdb | 17 |
| 2 | intel/cm-cpu-emulation | 2 |

***

##### Use-after-move: 4
| #   | Repo        | Bug count   |
| --- | ----------- | ----------- |
| 1 | intel/hexl | 4 |

***


***

### Repositories with no bugs: 5

| Repo |
| ---- |
| intel/BDTK |
| intel/gna |
| intel/eth-mpi-apps |
| intel/cm-compiler |
| intel/intel-extension-for-pytorch |
[back](../..)
