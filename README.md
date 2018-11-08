# Quick-Draw---Recognition-and-Generation
The Course Project of  CE7454

#### Set Up Environment
0. conda create -n course pip python=2.7
1. conda install pytorch=0.4 torchvision cuda90 -c pytorch 
2. bash install_package.sh

#### Download Dataset: Quick Draw
0. pip install gsutil
1. Go to ./data/simplify/ 
2. gsutil -m cp gs://quickdraw_dataset/full/simplified/*.ndjson .
3. Go to ./data/numpy/
4. gsutil -m cp gs://quickdraw_dataset/full/numpy_bitmap/*.npy .

#### Prepare Dataset
1. run preprocessing.ipynb

## Two Types of Model
Change Model Type from config.ipynb
e.g.
IMAGE_MODE = False
SEQUENCE_MODE = True
assert IMAGE_MODE + SEQUENCE_MODE == 1
#### 28*28 Image Model
Under image_model.ipynb
#### Length*(x,y) Stroke Sequence Model 
Under sequence_model.ipynb

#### Start Training
Run train.ipynb


