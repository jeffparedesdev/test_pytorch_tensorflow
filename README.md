# test_pytorch_tensorflow

## Pytorch

```
import torch as T 

if T.cuda.is_available():
    print("GPU habilitada")
else:
    print("No GPU")
```
## Tensorflow
```
import tensorflow as tf 

if tf.test.is_gpu_available():
    print("GPU habilitada")
else:
    print("No GPU")
```
