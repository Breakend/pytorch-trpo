# PyTorch implementation of TRPO

This is a PyTorch implementation of ["Trust Region Policy Optimization (TRPO)"](https://arxiv.org/abs/1502.05477).

This is code mostly ported from [original implementation by John Schulman](https://github.com/joschu/modular_rl). In contrast to [another implementation of TRPO in PyTorch](https://github.com/mjacar/pytorch-trpo), this implementation uses exact Hessian-vector product instead of finite differences approximation.

## Contributions

Contributions are very welcome. If you know how to make this code better, don't hesitate to send a pull request.

## Usage

```
python main.py --env-name "Reacher-v1"
```

## Results

More or less similar to the original code. Coming soon.

## Todo

- [ ] Plots.
- [ ] Collect data in multiple threads.
