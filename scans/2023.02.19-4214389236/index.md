---
layout: default
---

## Scan date: 2023.02.19
[All results (tar.gz)](./all-results.tar.gz) [Repo list (JSON)](./filtered-repos.json) [Bug breakdown (JSON)](./bug_breakdown.json) [Score vs Bugs (CSV)](./score_vs_bugs.csv)

***

---
## Repositories matching search query 'archived:false language:c language:c++ org:intel stars:>=1000': 3
## Repositories with supported build systems: 3
Github Actions Run ID: [4213655855](https://github.com/intel/srs/actions/runs/4213655855)

### Breakdown
| #    | Repo        | Bugs       | OSSF score | High cognitive complexity functions / Total functions   |
| ---- | ----------- | ---------- | ---------- | ------------------------------------------------------- |

***

### Repositories built with scan-build: 2
### Repositories scored with OSSF scorecard: 3

***

### Total number of bugs found: 12
### Total number of high cognitivite complexity functions found: 208

***

#### Bug categories
##### API: 2
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/linux-sgx | 2 |

***

##### Logic error: 3
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/pcm | 2 |
| intel/linux-sgx | 1 |

***

##### Memory error: 3
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/linux-sgx | 3 |

***

##### Readability: 208
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/linux-sgx | 126 |
| intel/pcm | 82 |

***

##### Security: 4
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/pcm | 2 |
| intel/linux-sgx | 2 |

***

#### Bug types
##### Argument with 'nonnull' attribute passed null: 2
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/linux-sgx | 2 |

***

##### Cognitive complexity: 208
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/linux-sgx | 126 |
| intel/pcm | 82 |

***

##### Dereference of null pointer: 1
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/linux-sgx | 1 |

***

##### Memory leak: 3
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/linux-sgx | 3 |

***

##### Potential insecure memory buffer bounds restriction in call 'strcat': 2
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/pcm | 1 |
| intel/linux-sgx | 1 |

***

##### Potential insecure memory buffer bounds restriction in call 'strcpy': 2
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/pcm | 1 |
| intel/linux-sgx | 1 |

***

##### Uninitialized argument value: 2
| Repo        | Bug count   |
| ----------- | ----------- |
| intel/pcm | 2 |

***


***

### Repositories with no bugs: 0

| Repo |
| ---- |
[back](../..)
