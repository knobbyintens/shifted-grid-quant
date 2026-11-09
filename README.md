# Shifted-Grid Quant

Reference implementation of **Shifted-Grid Quantization (SGQ)**.
The toolkit covers calibration, shifted rounding-grid construction and
packing for 4-bit weights.

- Language: Python
- License: Apache-2.0
- Status: active
- Implements: Shifted-Grid Quantization (SGQ)
- Benchmark (WQ-4 4-bit accuracy retention): 89.2

## Notes

See `sgq/core.py` for the quantizer and `eval/wq4.py` for the benchmark
harness.
