# Futuristic Car GAN

This repository contains code and resources for generating futuristic car images using a Generative Adversarial Network (GAN). The project uses the **StudioGAN** framework and focuses on training a **SNGAN** model for car image generation and segmentation tasks.

## Key Features
- **Car Segmentation Masking**: Implements car segmentation for training the GAN.
- **Latent Code Prediction**: Uses a ResNet model to predict latent codes for GAN training.
- **Model Training**: The training setup for SNGAN, including the configuration and hyperparameters, is provided.
- **Generated Results**: Includes results from the GAN's output at various training stages.

## Project Structure
- `Car_Masking.ipynb`: Notebook for car segmentation masking.
- `Latent_Code_ResNet.ipynb`: Notebook for training the ResNet model to predict latent codes.
- `SNGAN_cars-train-2022_03_01_19_04_26.log`: Training log with model architecture and hyperparameters.
- `SNGAN_cars.json`: Configuration file for the SNGAN model.
- `generated_canvas_*`: Images showing results from different training stages.

## Requirements
To run the project, you need the following dependencies:
- Python 3.x
- PyTorch
- StudioGAN 0.2.0

You can install the necessary dependencies by running:
```bash
pip install -r requirements.txt
```

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/akshit619/Futuristic-Car-GAN.git
   ```
2. Navigate to the project directory and run the Jupyter Notebooks to explore the models.

## Contributing
Feel free to fork this repository, make changes, and submit pull requests.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- The GAN framework used is based on **StudioGAN** ([GitHub link](https://github.com/POSTECH-CVLab/PyTorch-StudioGAN)).
