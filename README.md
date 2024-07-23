# Igor

Just made some adaptations for numpy > 1.20.

See the [original repo](https://github.com/wking/igor) for more information.

# Installation
```shell
pip install git+https://github.com/Ficere/igor
```
# Usage

In my case, this package is mainly used for reading the .ibw files from OxInst AFM.

```python
from igor.binarywave import load
wave = load(path_to_ibw)
print(wave)
```
