# DeepECG

## Usage [WIP]
* To generat image from csv:
```
./gnuplot -e "fileIn='<input csv>'; fileOut='<output image>'" csv2img.gnuplot
Eg: gnuplot -e "fileIn='csv/04015.csv'; fileOut='uploads/04015.png'" csv2img.gnuplot
```
* To convert all raw data to csv and image (include above step already):
```
./raws2img
```

* To convert single file to csv and image:
```
./raw2img <filename without extension>
Eg: ./raw2img 04015
```

* To convert image to csv:
```
python img2csv.py '<full path to file>'
Eg: python img2csv.py '/Users/macbook/Desktop/data/uploads/04015.png'
```

#Install
b1:
-wfdb
https://physionet.org/physiotools/wfdb-darwin-quick-start.shtml
b2:
-	anaconda
https://www.anaconda.com/download/#macos
-	tensorflow
https://www.tensorflow.org/install/install_mac
b3:
source activate tensorflow
b4:
conda install jupyter notebook
b5:
-	Scipy
pip install scipy
b6:
-	CardIO
pip  install git+https://github.com/analysiscenter/cardio.git
-	Dicom
pip install dicom
-	Keras
sudo pip3 install keras
b7:
-	Run jupyter notebook 
jupyter notebook
b8:
run file test.ipynb
http://localhost:8888/notebooks/test.ipynb
b9:
-openCV
https://anaconda.org/conda-forge/opencv
b10:
Edit đường dẫn trong checkpoin && test.ipynb