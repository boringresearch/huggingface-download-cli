# Huggingface Download Cli

Download Huggingface given `repo_id/filename`

## Install package

```
pip install huggingface-download-cli
```

## Usage

```
hf_download distilbert-base-uncased-distilled-squad pytorch_model.bin --save-dir model_path
```


## PyPI publish

```
python3 setup.py sdist
twine upload dist/huggingface-download-cli-1.0.3.tar.gz # pip install twine
```
