# Count_cells
Fast ai based project to count cells from microscopy images

## Objective
The aim of this project is to facilitate life of those researcher who have to spend hours counting cells on a microscope

## How??
To achieve this objective a machine learning algorithm is going to do all the hard work for yourself. The algorithm is a pytorch/Fastai python script that enables a resnet archtecture to learn how to count cells in an image

## datasets
The dataset used to train both neural networks is a kaggle dataset called Broad Bioimage Benchmark Collection under the accesion number [BBBC038](https://data.broadinstitute.org/bbbc/BBBC038)

## Notebooks
The notebook entitled count_cells 2 is a first approach to the problem. it uses a resnet 50 to learn how to segmentate images and a resnet38 with some changes in the layers to learn how to count the number of the cells. The changes in the layers were based on [a notebook that creates an image regression model based on Fastai library ](https://github.com/abhikjha/Image-Regression---Age-Prediction---Fastai)
