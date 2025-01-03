# Depth Estimation Using UNet with EfficientNet Backbone

This repository contains the code and resources for depth estimation tasks using UNet models with EfficientNet as the backbone. The project explores multiple variants and includes performance comparisons with InceptionResNetv2.

## Features
- Implementation of UNet with EfficientNet and InceptionResNetv2 backbones
- Evaluation of accuracy and efficiency metrics (FLOPS, ARE, RMSE, etc.)
- Support for freezing and non-freezing variants

## Prerequisites
- Python >= 3.8
- TensorFlow >= 2.6
- Jupyter Notebook

## Notebooks
All code is provided in Jupyter Notebook format (`.ipynb`). Notebooks for model training, evaluation, and performance analysis are included:
- `evaluate_cv_model_256.ipynb`: Evaluates efficientnet-unet model performance on test datasets.
- `IRv2_evaluate_cv_model.ipynb`: Evaluates IRv2 model performance on test datasets.
- `eff-unet-expand-activation.ipynb`: Contains the training pipeline for efficientnet unet.

## Usage
1. Clone this repository:
```bash
git clone https://github.com/fachrinnk4869/effUnetDepthEstimation
```

2. Navigate to the project directory:
```bash
cd effUnetDepthEstimation
```

3. Run the notebooks in Jupyter:
```bash
jupyter notebook
```

## Trained Models
Download the trained models from the link below:
- [All Model](https://drive.google.com/drive/folders/1ev2VBGLnbm5Kou1fBSkKvXlNtGyGM-oN)


## Citation
If you use this code or find it helpful in your research, please cite:
```
@article{yourname2024,
  title={Optimizing Depth Estimation Using EfficientNet as a Backbone Encoder},
  author={Your Name},
  journal={GitHub},
  year={2025},
  url={https://github.com/fachrinnk4869/effUnetDepthEstimation}
}
```

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments
Special thanks to colleagues, professors, and the Computer Vision course at [Your University Name] for their guidance and support in this project.
