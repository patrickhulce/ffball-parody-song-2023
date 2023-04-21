# Instructions

## Setting up Faceswap

```bash
brew install --cask miniconda
conda create --name faceswap python=3.9
conda init zsh
git clone --depth 1 https://github.com/deepfakes/faceswap.git

conda activate faceswap
python setup.py
```
