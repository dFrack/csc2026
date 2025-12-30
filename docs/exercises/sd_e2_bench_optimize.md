# SD-E2 Benchmark and Optimise

Goal: measure first, then change one thing that improves performance.

## Success criteria

- `bench_layout` runs and prints benchmark results
- You record **baseline** vs **improved** results
- Correctness is preserved (same numeric output within tolerance)

## Build + run (starter)

```bash
cd exercises/SD-E2-benchmark-and-optimize/starter

cmake -B build -G Ninja -DCMAKE_BUILD_TYPE=Release
cmake --build build -j"$(nproc)"

./build/bench_layout --benchmark_format=console
```

## Stretch
* Add a second benchmark case (different data size)
* Add a correctness check alongside the benchmark
