# Deblur blurry image

Input: one blurry image
Output: sharpen image

## Setup

Python 2.7
Install packages in `requirements.txt` (pip install -r requirements.txt)

## Download model

```
cd checkpoints
sh download_model.sh
```

## Run

```
cd SRN-Deblur
python run_model.py --input_path=./path/to/image --output_path=./output [--gpu]
```
The processed image will be saved in `output_path`
It will take time to process an image in CPU, consider using GPU to speed up.