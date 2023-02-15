---
layout: default
---

## Scan date: 2023.02.15
[All results (tar.gz)](./all-results.tar.gz) [Repo list (JSON)](./filtered-repos.json) [Bug breakdown (JSON)](./bug_breakdown.json) [Score vs Bugs (CSV)](./score_vs_bugs.csv)

***

---
## Repositories matching search query 'archived:false language:c language:c++ org:intel stars:>=200': 30
## Repositories with supported build systems: 26
Github Actions Run ID: [4185519691](https://github.com/intel/srs/actions/runs/4185519691)

***

### Repositories built with scan-build: 14
### Repositories scored with OSSF scorecard: 23

***

### Total number of bugs found: 58
### Total number of high cognitivite complexity functions found: 923

***

#### Bug categories
##### API: 2
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/linux-sgx | 2 |

***

##### C++ move semantics: 3
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/compile-time-init-build | 3 |

***

##### Logic error: 27
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/intel-graphics-compiler | 10 |
| intel/intel-ipsec-mb | 7 |
| intel/isa-l | 3 |
| intel/pcm | 2 |
| intel/opencl-intercept-layer | 2 |
| intel/ipp-crypto | 2 |
| intel/linux-sgx | 1 |

***

##### Memory error: 6
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/linux-sgx | 3 |
| intel/libva | 2 |
| intel/compile-time-init-build | 1 |

***

##### Readability: 923
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/opencl-intercept-layer | 222 |
| intel/intel-graphics-compiler | 156 |
| intel/pcm | 155 |
| intel/linux-sgx | 130 |
| intel/intel-ipsec-mb | 76 |
| intel/compile-time-init-build | 31 |
| intel/yarpgen | 30 |
| intel/thermal_daemon | 30 |
| intel/isa-l | 23 |
| intel/libva | 21 |
| intel/safestringlib | 19 |
| intel/libipt | 14 |
| intel/media-driver | 13 |
| intel/ipp-crypto | 3 |

***

##### Security: 20
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/media-driver | 7 |
| intel/opencl-intercept-layer | 6 |
| intel/pcm | 2 |
| intel/linux-sgx | 2 |
| intel/intel-ipsec-mb | 2 |
| intel/libva | 1 |

***

#### Bug types
##### Argument with 'nonnull' attribute passed null: 2
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/linux-sgx | 2 |

***

##### Assigned value is garbage or undefined: 8
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/intel-ipsec-mb | 5 |
| intel/intel-graphics-compiler | 2 |
| intel/isa-l | 1 |

***

##### Called C++ object pointer is null: 1
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/intel-graphics-compiler | 1 |

***

##### Cognitive complexity: 923
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/opencl-intercept-layer | 222 |
| intel/intel-graphics-compiler | 156 |
| intel/pcm | 155 |
| intel/linux-sgx | 130 |
| intel/intel-ipsec-mb | 76 |
| intel/compile-time-init-build | 31 |
| intel/yarpgen | 30 |
| intel/thermal_daemon | 30 |
| intel/isa-l | 23 |
| intel/libva | 21 |
| intel/safestringlib | 19 |
| intel/libipt | 14 |
| intel/media-driver | 13 |
| intel/ipp-crypto | 3 |

***

##### Dereference of null pointer: 3
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/opencl-intercept-layer | 2 |
| intel/linux-sgx | 1 |

***

##### Division by zero: 2
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/intel-graphics-compiler | 2 |

***

##### Double free: 2
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/libva | 1 |
| intel/compile-time-init-build | 1 |

***

##### Garbage return value: 1
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/intel-graphics-compiler | 1 |

***

##### Memory leak: 3
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/linux-sgx | 3 |

***

##### Potential insecure memory buffer bounds restriction in call 'strcat': 12
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/opencl-intercept-layer | 4 |
| intel/media-driver | 4 |
| intel/pcm | 1 |
| intel/linux-sgx | 1 |
| intel/libva | 1 |
| intel/intel-ipsec-mb | 1 |

***

##### Potential insecure memory buffer bounds restriction in call 'strcpy': 8
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/media-driver | 3 |
| intel/opencl-intercept-layer | 2 |
| intel/pcm | 1 |
| intel/linux-sgx | 1 |
| intel/intel-ipsec-mb | 1 |

***

##### Result of operation is garbage or undefined: 4
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/intel-graphics-compiler | 4 |

***

##### Uninitialized argument value: 8
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/pcm | 2 |
| intel/isa-l | 2 |
| intel/ipp-crypto | 2 |
| intel/intel-ipsec-mb | 2 |

***

##### Use-after-free: 1
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/libva | 1 |

***

##### Use-after-move: 3
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/compile-time-init-build | 3 |

***


***

### Repositories with no bugs: 0

| Repo |
| ---- |

### Breakdown
| #    | Repo        | Bugs       | OSSF score | High cognitive complexity functions / Total functions   |
| ---- | ----------- | ---------- | ---------- | ------------------------------------------------------- |
| 1 | intel/intel-graphics-compiler | 10 | 4.3 | 156 / 1170 |
| 2 | intel/intel-ipsec-mb | 9 | 4.3 | 76 / 531 |
| 3 | intel/opencl-intercept-layer | 8 | 4.3 | 222 / 408 |
| 4 | intel/linux-sgx | 8 | 4.3 | 130 / 992 |
| 5 | intel/media-driver | 7 | 4.3 | 13 / 101 |
| 6 | intel/pcm | 4 | 4.3 | 155 / 781 |
| 7 | intel/compile-time-init-build | 4 | 4.3 | 31 / 460 |
| 8 | intel/libva | 3 | 4.3 | 21 / 328 |
| 9 | intel/isa-l | 3 | 4.3 | 23 / 158 |
| 10 | intel/compile-time-init-build | 3 |  |  /  |
| 11 | intel/ipp-crypto | 2 | 4.3 | 3 / 252 |
| 12 | intel/yarpgen | 0 | 4.3 | 30 / 228 |
| 13 | intel/thermal_daemon | 0 | 4.3 | 30 / 335 |
| 14 | intel/safestringlib | 0 | 4.3 | 19 / 84 |
| 15 | intel/libipt | 0 | 4.3 | 14 / 475 |
[back](../..)
