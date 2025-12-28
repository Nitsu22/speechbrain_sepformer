conda env create -f env_sepformer_whamr_py39.yml
conda activate sepformer-whamr
pip install --no-deps -e .
pip uninstall -y torchvision
