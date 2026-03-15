# mohu-compute

SIMD-accelerated compute kernels for the [mohu](https://github.com/mohu-org/mohu) array library.

Usable standalone — no dependency on mohu's array types.

## Features

- `simd` — portable SIMD via `std::simd`
- `avx512` — opt-in AVX-512 (implies `simd`)

## License

MIT
