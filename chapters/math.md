# 📐 数学

行列の計算問題を [NumPy](https://numpy.org/) で解く例。

## Docker

Anaconda の Docker image でローカル環境を構築します。

Docker Hub: https://hub.docker.com/r/continuumio/anaconda3

```sh
# Download Docker image
docker pull continuumio/anaconda3

# Start a Jupyter Notebook server and interact with Anaconda via your browser
docker run -i -t -p 8888:8888 continuumio/anaconda3 /bin/bash -c "/opt/conda/bin/conda install jupyter -y --quiet && mkdir /opt/notebooks && /opt/conda/bin/jupyter notebook --notebook-dir=/opt/notebooks --ip='*' --port=8888 --no-browser --allow-root"
```

## 計算

Numpy: https://numpy.org/

```python
import numpy as np
```

### 足し算

```python
a = np.matrix([-1, 2])
b = np.matrix([0, 5])

a + b
matrix([[-1,  7]])

a - b
matrix([[-1, -3]])

a + b * 2
matrix([[-1, 12]])
```

### 掛け算

```python
a = np.matrix([
    [1, -1, 1],
    [0, 1, 1]
])
b = np.matrix([
    [1, 1],
    [-1, 1],
    [1, 1]
])

a * b
matrix([[3, 1],
        [0, 2]])
```

### 掛け算2

```python
a = np.matrix([
    [1, 2],
    [2, 1]
])
b = np.matrix([
    [1, 2],
    [3, -4]
])

a * b
matrix([[ 7, -6],
        [ 5,  0]])

b * a
matrix([[ 5,  4],
        [-5,  2]])
```
