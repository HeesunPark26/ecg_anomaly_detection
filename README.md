# ecg_anomaly_detection
A repo for trying ecg anomaly detection (practice!).

## Set up tensorflow in macOS Monterey (12.2.1)
### 1. install Xcode

```bash
xcode-select --install
```

### 2. install miniforge
  - Download miniforge: [here](https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-MacOSX-arm64.sh)
  ```bash
  bash ~/Downloads/Miniforge3-MacOSX-arm64.sh
  source ~/miniforge3/bin/activate
  ```

For using this repo, 
### 3. create virtual env using .yaml
```bash
conda env create -n tf -f tf_env.yaml
```

### 4. activate the env
```bash
conda activate tf
```

To deactivate, 
```bash
conda deactivate
```

* reference
  * tf and conda: https://suwani.tistory.com/14
  * conda virtual env: https://teddylee777.github.io/python/anaconda-%EA%B0%80%EC%83%81%ED%99%98%EA%B2%BD%EC%84%A4%EC%A0%95-%ED%8C%81-%EA%B0%95%EC%A2%8C
