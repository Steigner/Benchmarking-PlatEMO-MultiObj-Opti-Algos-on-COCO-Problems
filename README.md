# PlatEMO — Data-Driven Characterization of Multiobjective Optimization Algorithms

Benchmarking and visualization of multiobjective optimization algorithms using the [COCO](https://github.com/numbbo/coco) / BBOB bi-objective test suite.

**Live site:** [GitHub Pages](https://steigner.github.io/PlatEMO-Data-Driven-Characterization-Multiobjective-Optimization-Algorithms/)

## Algorithms

| Algorithm | Description |
|-----------|-------------|
| **RMMED** | Regularized multiobjective covariance matrix estimation descent |
| **MOCMA** | Multi-Objective Covariance Matrix Adaptation Evolution Strategy |
| **DRLOS** | Data-driven reference-line optimization with low-overhead surrogates |
| **best2** | Virtual best-of-two reference from COCO archive |

## Benchmark Scope

- **481** bi-objective BBOB test functions
- **6** problem dimensions: 2D, 3D, 5D, 10D, 20D, 40D
- ERT-based performance profiles with bootstrap confidence intervals
- Bonferroni-corrected significance testing (p < 0.01)

## Report Views

| View | Description |
|------|-------------|
| [Interactive Runtime Profiles](biobj_best2_RMMED_MOCMA_DRLOS_041602h3003/pprldflex.html) | Navigate all functions with keyboard or buttons |
| [Per-Function Profiles](biobj_best2_RMMED_MOCMA_DRLOS_041602h3003/pprldmany-single-functions/pprldmany.html#20) | Detailed per-function ERT distributions |
| [Summary & Groups](biobj_best2_RMMED_MOCMA_DRLOS_041602h3003/pprldmany.html#20) | Aggregated profiles by function group |
| [Scaling with Dimension](biobj_best2_RMMED_MOCMA_DRLOS_041602h3003/ppfigs.html) | ERT vs. dimension scaling plots |
| [Performance Tables](biobj_best2_RMMED_MOCMA_DRLOS_041602h3003/pptables.html) | Tabulated ERT for selected targets |

## License

MIT License © 2026 Martin Juříček
