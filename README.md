# WCT2
This repository contains PyTorch implementation of the paper [Photorealistic Style Transfer via Wavelet Transforms](https://arxiv.org/abs/1903.09760) and [Presentation on Photorealistic style transfer via WCT2](https://docs.google.com/document/d/1XXqfoJc23DFYfQnyIVZVKkxQ1gebP0vDyRa0_sZizDI/edit).
- Aditi Tiwari - 04301032019
- Rhythm- 05701032019
 


### Dependency
- PyTorch >= 0.4.1
- Check the requirements.txt
```bash
pip install -r requirements.txt
```
### Installation
- Clone this repo:
```bash
git clone https://github.com/Adititiwari02/Photorealistic-Style-Transfer-AI-College.git
cd https://github.com/Adititiwari02/Photorealistic-Style-Transfer-AI-College.git
```

## How to run the code
```python
cd WCT2/src/
python main.py
```
### Dataset
  - Images can be found in [DPST repo](https://github.com/luanfujun/deep-photo-styletransfer)
  
### Arguments
- `--content`: FOLDER-PATH-TO-CONTENT-IMAGES
- `--content_segment`: FOLDER-PATH-TO-CONTENT-SEGMENT-LABEL-IMAGES
- `--style`: FOLDER-PATH-TO-STYLE-IMAGES
- `--style_segment`: FOLDER-PATH-TO-STYLE-SEGMENT-LABEL-IMAGES
- `--output`: FOLDER-PATH-TO-OUTPUT-IMAGES
- `--image_size`: output image size
- `--alpha`: alpha determines the blending ratio between content and stylized features

