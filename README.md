# Istanbul Dataset

This repo contains weights of Unet++ model with SE-ResNeXt101 encoder trained with Istanbul, Inria and Massachusetts datasets seperately.
Trainings have been realized using PyTorch and segmentation models library (https://github.com/qubvel/segmentation_models.pytorch)
We also provide an inference notebook to run prediction on GeoTiff images. This notebook also outputs prediction images as GeoTiff.

You can use the following links to download weights files:
- Unet++ trained with Istanbul Dataset: [Download](https://drive.google.com/file/d/1ue3w5UqLgd3e0nKfNIl4QmgswzA2wtRt/view?usp=sharing)
- Unet++ trained with Inria Dataset: [Download](https://drive.google.com/file/d/17SClh43guLZACAVOgnN4huhm7FCA0-OB/view?usp=sharing)
- Unet++ trained with Massachusetts Dataset: [Download](https://drive.google.com/file/d/1ZJfTTU92vPgKPUD0CT_93e3_vuohEhSp/view?usp=sharing)

To run the notebook, following libraries are required:
- torch == 1.7.1
- segmentation-models-pytorch == 0.1.3
- scikit-image = 0.18.1
- GDAL == 3.2.1
- tifffile == 2021.2.1
