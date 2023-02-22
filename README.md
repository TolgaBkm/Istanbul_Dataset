# Istanbul Dataset

This repo contains weights of Unet++ model with SE-ResNeXt101 encoder trained with Istanbul, Inria and Massachusetts datasets seperately.
Trainings have been realized using PyTorch and segmentation models library (https://github.com/qubvel/segmentation_models.pytorch)
We also provide an inference notebook to run prediction on GeoTiff images. This notebook also outputs prediction images as GeoTiff.

# Update:
We have addeed more weights of different architectures trained with Istanbul dataset.

You can use the following links to download weights files:
- Unet++ trained with Istanbul Dataset: [Download](https://drive.google.com/file/d/1ue3w5UqLgd3e0nKfNIl4QmgswzA2wtRt/view?usp=sharing)
- Unet++ trained with Inria Dataset: [Download](https://drive.google.com/file/d/17SClh43guLZACAVOgnN4huhm7FCA0-OB/view?usp=sharing)
- Unet++ trained with Massachusetts Dataset: [Download](https://drive.google.com/file/d/1ZJfTTU92vPgKPUD0CT_93e3_vuohEhSp/view?usp=sharing)

New Weights trained with Istanbul Dataset:
- Unet++ with InceptionResNetv2 encoder: [Download](https://drive.google.com/file/d/1Fnegirgyhh9kuMGzXsBVCWLUavSOvYd7/view?usp=sharing)
- Unet++ with EfficientNet-b6 encoder: [Download](https://drive.google.com/file/d/1gPJkQjnVTr-4R8dwi6RdTDFbhB2UtcJJ/view?usp=sharing)
- UNet with SE-ResNeXt101 encoder: [Download](https://drive.google.com/file/d/1TUBiFYq_BI4N6iNtMcLuIK0GsGtyAw6f/view?usp=sharing)
- UNet with InceptionResNetv2 encoder: [Download](https://drive.google.com/file/d/14p0XaGcnqi45_yL1OgTzNSNsK7Y4Mwr-/view?usp=sharing)
- UNet with EfficientNet-b6 encoder: [Download](https://drive.google.com/file/d/1zkHMfWW07qrr_jLSyztrFR0kd-GKGIr7/view?usp=sharing)
- DeepLabv3+ with SE-ResNeXt101 encoder: [Download](https://drive.google.com/file/d/1Rh65zOo26Eilkeb_Zf_ZoSFfBEuuIhtx/view?usp=sharing)

To run the notebook, following libraries are required:
- torch == 1.7.1
- segmentation-models-pytorch == 0.1.3
- scikit-image == 0.18.1
- GDAL == 3.2.1
- tifffile == 2021.2.1

# Citation

Please cite the following study if you make use of our weights: [Paper](https://doi.org/10.1016/j.eswa.2022.117346)
