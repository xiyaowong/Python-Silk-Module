# pysilk

## Installation

### Linux

```bash
pip install git+https://github.com/xiyaowong/Python-Silk-Module
```

### windows

`pip install python-silk`

如果安装不成功，就也使用第一种`pip install git+https://github.com/xiyaowong/Python-Silk-Module`

If you get some issues with building, check documentation of [pybind11](https://pybind11.readthedocs.io)

## Usage

```python
from pysilk import async_decode, async_encode, decode, encode
```

Only four functions: `encode`, `decode`, `async_encode`, `async_decode`

It's very easy to use. Just follow the IDE/editor typing intergration and check out the docs of these functions

**NOTE**:

The first argument `input` can be a `str`, `pathlib.Path`, `bytes`, `BytesIO` or `BinaryIO` liked object.

`str` and `pathlib.Path` are both meaning local file path

**The source data of input and returned data must be the original PCM coded data**

## Author

Due to some reasons, these changes can't be merged into upstream, I have contacted the original author and kept the fork version as a separate project

[DCZYewen](https://github.com/DCZYewen/Python-Silk-Module)

## License

All the licenses are in the LICENSE file. This project is also released under BSD lisence.
