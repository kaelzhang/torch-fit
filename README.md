[![](https://travis-ci.org/kaelzhang/torch-fit.svg?branch=master)](https://travis-ci.org/kaelzhang/torch-fit)
[![](https://codecov.io/gh/kaelzhang/torch-fit/branch/master/graph/badge.svg)](https://codecov.io/gh/kaelzhang/torch-fit)
[![](https://img.shields.io/pypi/v/torch-fit.svg)](https://pypi.org/project/torch-fit/)
[![](https://img.shields.io/pypi/l/torch-fit.svg)](https://github.com/kaelzhang/torch-fit)

ARCHIVED, because there is already one for you:

https://github.com/ncullen93/torchsample

****

# torch-fit

`Keras.Model::fit`-like torch fit implementation

## Install

```sh
$ pip install torch-fit
```

## Usage

```py
from torch_fit import fit

model = MyPyTorchModule()

history = fit(
    model,
    loss='mse',
    metrics='mae',
    epochs=100
)
```

## License

[MIT](LICENSE)
