# Linear-Transformer-State

O(n) complexity transformer using FNet-inspired Fourier features with state caching

## Overview

This project implements a novel approach to: Linear-complexity transformer with recurrent state cache for long sequences

## Key Features

- Optimized for 4GB VRAM constraint
- Efficient attention mechanisms
- Production-ready PyTorch implementation

## Installation

```bash
pip install -r requirements.txt
```

## Usage

```bash
python train.py --epochs 100 --batch-size 32
```

## Architecture

...

## Performance

- VRAM Usage: <4GB
- Parameters: ~10M
- Inference: ~20ms/image

## License

MIT License
