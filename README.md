# Low-Light-Image-Enhancement-with-a-Pretrained-SID-Model

# Low-Light Enhancement Demo

This MATLAB script runs a pretrained **Learning to See in the Dark** model without downloading the SID dataset. It simulates a dark/noisy image and enhances it using the pretrained network.

## Features
- Automatically downloads and loads the pretrained model  
- Builds a simple 4-channel fake RAW input  
- Runs inference and shows original, degraded, and enhanced images

## Requirements
- MATLAB + Deep Learning Toolbox  
- (Optional) GPU support

## Usage
Run the script. The model downloads on first use, and you can replace the sample image with any RGB file.
