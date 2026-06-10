# solve — sinew-mocap

A hexagon cluster (`core/` + `ports/` + `adapters/`) of the Sinew mocap stack:
the body solve — FK + linear-blend skinning of the ANNY body (Lean->Slang kernels).

## Build

```
cmake -B build && cmake --build build
# tests: cmake -B build -DSINEW_TESTS=ON && cmake --build build && ctest --test-dir build
```

## Dependencies

See `ports/sibling-repos.txt` — clone the listed `sinew-mocap` repos side-by-side in `~/`.
