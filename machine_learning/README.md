# Data Science course - Machine Learning


This will be a short introduction to machine learning for data scientist to understand the key concepts.


For the introduction, we will follow David Kirkby's online course:

```
git clone https://github.com/Asterics2020-Obelics/School2018.git
```

```
cd School2018
conda env update -f environment.yml
conda activate school18
conda install -c astropy emcee
conda install pytables
cd machinelearning
python setup.py install
```

Check that the install worked:
```
python
import mls
```

We will work on the following notebooks:
- Intro
- Clustering
- Dimensionality Reduction (if time allows)
- Supervised
- Deep Learning (if time allows)
- Hands-On 2

Notes:
- you need to run `Data.ipynb` to generate the dataset
- there is bug lately with pandas, fixed with `pip install numpy==1.15.4`
