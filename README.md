
# diffusion2D

## Project description

This code simulates the diffusion equation in 2D over a square domain, where the entire domain starts at a certain temperature, except for a circular disc at the center with a higher temperature. The simulation uses the Finite Difference Method to solve the diffusion equation. Users can modify the thermal diffusivity and initial conditions of the system. The code generates four plots showing the diffusion process at different time points, allowing for a clear visualization of the temperature distribution over time.

## Installing the package

### Using pip3 to install from PyPI
```bash
pip install -i https://test.pypi.org/simple/ gilvv-diffusion2d-1==0.0.1
```

### Required dependencies

The required dependencies are Numpy and Matplotlib which are automatically installed.
The python version required is also >= 3.6

## Running this package

Use the provided `solve()` function in python:

```python
from gilvv_diffusion2d_1.diffusion2d import solve
solve(dx = 0.1, dy = 0.1, D = 4)
```

It contains three parameter, which can be adjusted:

- `dx` intervals in x-direction
- `dy` intervals in y-direction
- `D` thermal diffusivity

## Citing

This is a student project from Software simulation Engineering at University of Stuttgart.
[https://github.com/Simulation-Software-Engineering/diffusion2D]