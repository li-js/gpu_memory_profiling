# gpu_memory_profiling
Profile the GPU memory usage of every line in a pytorch code

## Example Usage
```bash
python example_mnist.py
```

## Dependency
This code depends on [py3nvml](https://github.com/fbcotter/py3nvml). Pip install is available here: 
```
pip install py3nvml
```

### Acknowledgement
The gpu_profile.py is a modified version of [this script](https://gist.github.com/MInner/8968b3b120c95d3f50b8a22a74bf66bc).

The example_mnist.py is modified from [this script](https://github.com/pytorch/examples/blob/master/mnist/main.py).
