# Medical-Image-Caption-Generator

This project provides a medical image captioning pipeline using LLaMA 3 with vision capabilities, applied to the ROCO dataset (Radiology Objects in COntext). It includes notebooks for generating image captions and running inference.

## Features

- Uses LLaMA 3 Vision model for multimodal image captioning
- Fine-tuned on the ROCO dataset (radiological images)
- Includes interactive notebooks for:
  - Training / prompting with medical images
  - Caption generation and inference
- Outputs can be evaluated against ground truth or used for downstream tasks

## Notebooks

- `roco-caption-inference.ipynb`: Run inference on medical images and generate captions using a pretrained LLaMA 3 Vision model.
- `roco-caption-llama-3-2-vision.ipynb`: Core logic for preparing and prompting the LLaMA 3 Vision model with ROCO data.

## Installation

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/roco-captioning.git
   cd roco-captioning
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

   _Note: You may need access to LLaMA 3 Vision weights, which may require registration or API access._

3. Launch the notebooks:
   ```bash
   jupyter notebook
   ```

## Dataset

- **ROCO Dataset**: [https://huggingface.co/datasets/eltorio/ROCOv2-radiology]
- You must download and preprocess the dataset according to your system and storage.

## License

This project is licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).  
See the [LICENSE](LICENSE) file for more details.

## Disclaimer

This tool is intended for **research purposes only**. It does not provide medical advice or diagnosis.
