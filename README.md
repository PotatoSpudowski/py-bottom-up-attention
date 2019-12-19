# Bottom-up Attention with Detectron2 

**Previewing**

The detectron2 system with *exact same* weight as the Caffe VG detection.

## Installation
```
git clone https://github.com/facebookresearch/detectron2.git
cd detectron2

# Install python libraries
pip install -r requirements.txt
pip install 'git+https://github.com/cocodataset/cocoapi.git#subdirectory=PythonAPI'

# Install detectron2
python setup.py build develop

# or if you are on macOS
# MACOSX_DEPLOYMENT_TARGET=10.9 CC=clang CXX=clang++ python setup.py build develop

# or, as an alternative to `setup.py`, do
# pip install [--editable] .
```

## Demos
### Detection
[demo vg detection](demo/demo_vg_detection.ipynb)

### Feature Extraction
1. Single image: [demo extraction](demo/demo_feature_extraction.ipynb)
2. Batchwise extraction: [demo batchwise extraction](demo/demo_batchwise_feature_extraction.ipynb)
3. Extract features for given boxes: [demo batchwise extraction](demo/demo_batchwise_feature_extraction.ipynb)

## Feature Extraction Scripts for LXMERT

## Citing

Detectron2:
```BibTeX
@misc{wu2019detectron2,
  author =       {Yuxin Wu and Alexander Kirillov and Francisco Massa and
                  Wan-Yen Lo and Ross Girshick},
  title =        {Detectron2},
  howpublished = {\url{https://github.com/facebookresearch/detectron2}},
  year =         {2019}
}
```

Bottom-up Attention:
```BibTeX
@inproceedings{Anderson2017up-down,
  author = {Peter Anderson and Xiaodong He and Chris Buehler and Damien Teney and Mark Johnson and Stephen Gould and Lei Zhang},
  title = {Bottom-Up and Top-Down Attention for Image Captioning and Visual Question Answering},
  booktitle={CVPR},
  year = {2018}
}
```
