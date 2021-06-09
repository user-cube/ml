# Machine Learning

## Tensorflow Metal on MacOS

To use Tensorflow Metal on Mac M1 Chip:

- [Download](https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-MacOSX-arm64.sh) Miniforge
- Run:

```shell
$ chmod +x ~/Downloads/Miniforge3-MacOSX-arm64.sh
$ sh ~/Downloads/Miniforge3-MacOSX-arm64.sh
$ source ~/miniforge3/bin/activate
```

- Instal tensorflow dependencies

```shell
$ conda install -c apple tensorflow-deps
```

- Install base tensorflow

```shell
$ python -m pip install tensorflow-macos
```

- Install metal plugin

```shell
$ python -m pip install tensorflow-metal
```
