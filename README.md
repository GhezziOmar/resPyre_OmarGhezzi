# resPyre_depth

## Procedure to install resPyre (featured with depth model)
- Install DINOv2:
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
- Manually install pyVHR:
1. Install numba using conda:
  ```bash
    conda install numba
  ```
2. Install cupy:
  ```bash
    conda install -c conda-forge cupy cuda-version=11.7
  ```
3. Install cusignal (do not specify the cuda version):
  ```bash
    conda install -c rapidsai -c conda-forge -c nvidia \
    cusignal python=3.9
  ```
4. Install kaleido:
  ```bash
    conda install -c conda-forge python-kaleido
  ```
5. conda pytables:
  ```bash
    conda install -c anaconda pytables
  ```
6. Install pyVHR:
  ```bash
    cd pyVHR
  ```
  ```bash
    python setup.py install
  ```
- Use pip to install the following dependencies:
  ```bash
    pip install autorank
  ```
  ```bash
    pip install asposestorage
  ```
  ```bash
    pip install biosppy
  ```
- Use conda to install the following pakages:
  ```bash
    conda install -c anaconda ipython
  ```
  ```bash
    conda install -c anaconda ipywidgets
  ```
  ```bash
    conda install -c conda-forge lmfit
  ```
- Installa mediapipe:
```bash
    pip install mediapipe==0.9.0.1
  ```
- mediapipe installa protobuf 3.20.3 mentre cu11 (di dinov2) richiede protobuf >=4.21, <5, la soluzione è reinstallare protobuf con conda:
  ```bash
    conda install -c conda-forge protobuf
  ```
  oppure aggiornare protobuf alla versione più recente:
  ```bash
    pip install --upgrade protobuf
  ```
  o alla versione protobuf==4.22.0:
  ```bash
    pip install protobuf==4.21
  ```
- Use conda and pip to install the following pakages:
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
- Install tensorflow:
  ```bash
    conda install -c conda-forge tensorflow
  ```




 
   
