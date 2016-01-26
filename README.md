# Jupyter with Tensorflow

## How to use it?

```
$ docker pull satoshun/tensorflow
$ docker run --rm -it -p 8888:8888 -v "$HOME/notebooks:/notebooks" satoshun/tensorflow
```

`$HOME/notebooks` is your notebook direcotry of local.


## Specs

- Tensorflow 0.6.0
- Ubuntu 15.10
- Python3.4
- Including Scipy, matplotlib, sklearn, pandas
