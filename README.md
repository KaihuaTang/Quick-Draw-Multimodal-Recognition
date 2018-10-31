# Quick-Draw---Recognition-and-Generation
The Course Project of  CE7454

#### Download Dataset: Quick Draw
0. pip install gsutil
1. Go to ./data/simplify/ 
2. gsutil -m cp gs://quickdraw_dataset/full/simplified/*.ndjson .
3. Go to ./data/numpy/
4. gsutil -m cp gs://quickdraw_dataset/full/numpy_bitmap/*.npy .

#### Prepare Dataset
1. run preprocessing.ipynb

#### Classification Model
Under model.ipynb

#### Start Training
Run train.ipynb
