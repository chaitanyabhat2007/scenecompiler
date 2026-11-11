# SceneCompiler

**A workload-aware, hardware-conscious GPU compiler for real-time robotic perception.**

SceneCompiler explores compiler optimizations for irregular, data-dependent
geometric workloads in RGB-D robotic perception pipelines.

## Research Focus

The project investigates how workload-aware compilation can improve
GPU execution efficiency for operations such as:

- Depth unprojection
- Coordinate transformations
- Geometric filtering
- Voxel coordinate computation
- Voxel aggregation

The central research question is:

> Can workload-aware compilation jointly optimize operator fusion and
> irregular aggregation strategies under GPU resource constraints?

## Objectives

- Reduce perception pipeline latency.
- Improve GPU memory efficiency.
- Adapt execution plans to runtime workload characteristics.
- Maintain correctness across different input distributions.

## Status

Research and system design phase. Implementation and experimental results
will be documented as the project develops.

## License

TBD
