- We implement GPU-based N-W density estimation after extracting features from all images. The probability density information is then used to reweight the adjacency matrix. Since the density estimation is orthogonal to the training procedure, it can be conveniently integrated into other algorithms

You can start training process by typing

```sh
python train.py -c config/lassl_cifar10.yaml
```