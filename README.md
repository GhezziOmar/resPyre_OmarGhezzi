# resPyre_depth

### Procedure to install resPyre (DINOv2)
- Firstly it is needed to create the virtual environment to allow the intallation of DINOv2, pyVHR and the specific resPyre dependencies, the conda-extras.yaml in ./dinov2 provides the DINOv2 dependecies for the monocular depth estimation :
  
  1) creating the virtual conda environment by running:
  ```bash
  conda env create -f dinov2_/conda-extras.yaml
  ```
  2) go to ./dinov2 and use pip to install DINOv2:
  ```bash
    cd dinov2
  ```
  ```bash
    python setup.py install
  ```
### Procedure to install resPyre (pyVHR)
- Manually install pyVHR:
  1). Install numba using conda:
  ```bash
    conda install numba
  ```
  2). Install cupy:
  ```bash
    conda install -c conda-forge cupy cuda-version=11.7
  ```
  3). Install cusignal (do not specify the cuda version):
  ```bash
    conda install -c rapidsai -c conda-forge -c nvidia \
    cusignal python=3.9
  ```
  4). Install kaleido:
  ```bash
    conda install -c conda-forge python-kaleido
  ```
  5). conda pytables:
  ```bash
    conda install -c anaconda pytables
  ```
  6). Install pyVHR:
  ```bash
    cd pyVHR
  ```
  ```bash
    python setup.py install
  ```
- Use pip or conda to install the remaining dependencies (ignore the protobuf incompatibility while installing mediapipe): 
  ```bash
    pip install autorank
  ```
  ```bash
    pip install asposestorage
  ```
  ```bash
    pip install biosppy
  ```
  ```bash
    conda install -c anaconda ipython
  ```
  ```bash
    conda install -c anaconda ipywidgets
  ```
  ```bash
    conda install -c conda-forge lmfit
  ```
  ```bash
    pip install mediapipe
  ```
  ```bash
    conda install -c conda-forge plotly
  ```
  ```bash
    pip install pybdf
  ```
  ```bash
    conda install -c conda-forge pysimplegui
  ```
  ```bash
    conda install -c conda-forge scikit-posthocs
  ```
  ```bash
    conda install -c conda-forge scikit-image
  ```
  ```bash
    conda install -c conda-forge tqdm
  ```
  ```bash
    pip install tensorflow==2.11.0
  ```
  ```bash
    pip install common==0.1.2
  ```
  ```bash
    pip install emd==0.6.2
  ```
  ```bash
    pip install opencv-python==4.7.0.72
  ```
  ```bash
    pip install opencv-contrib-python==4.7.0.68
  ```
  ```bash
    pip install tvm==1.0.0
  ```
  



 
   
