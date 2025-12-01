# NeuralDeRain

A deep learning approach for single-image deraining using neural networks.

> **Note**: This is my initial attempt at building an image deraining system. Feedback and contributions are welcome!

## 📋 Overview

NeuralDeRain removes rain streaks from images using a pre-trained deep learning model. The model is ready to use - no training required.

## 🚀 Quick Start

### Prerequisites

- Python 3.x
- PyTorch
- NumPy, Scipy (for .mat file handling)

### Usage

1. Run inference on your rainy image:
```bash
python inference2.py
```

2. The derained image will be automatically saved in the `results/` folder

## 📁 Project Structure

```
NeuralDeRain/
├── results/              # Output derained images
├── Train_Model.py        # Model training script
├── inference2.py         # Inference script for deraining
├── best_model.pth        # Pre-trained model weights
├── test12_chunks.mat     # Sample test image
├── Rain200L_val_chunks.zip  # Validation dataset
└── README.md
```

## 💡 Input Format

- Default input: `test12_chunks.mat`
- Format: MATLAB .mat file containing image data

## 🎯 Future Improvements

- [ ] Support for JPG/PNG formats
- [ ] Batch processing
- [ ] Performance optimization
- [ ] Better model architecture

## 🤝 Contributing

This is an early-stage project and I'm learning! Contributions, bug reports, and suggestions are highly appreciated.

## 📄 License

MIT License

---

⭐ If you find this helpful, please consider giving it a star!
