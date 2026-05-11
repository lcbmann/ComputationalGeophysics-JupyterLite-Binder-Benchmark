# Computational Geophysics Animation Benchmark

This repository compares MyBinder and JupyterLite for two computational geophysics animation notebooks.

The notebooks are small standalone benchmarks adapted from finite-difference wave examples:

- `notebooks/01_simple_fd_acoustic_1d_animation.ipynb`: simple 1D acoustic wave animation
- `notebooks/02_complex_fd_acoustic_2d_animation.ipynb`: heavier 2D acoustic wave animation

Each notebook prints timing values for the simulation, animation setup, and JavaScript/HTML animation rendering.

## JupyterLite
- JupyterLite site: https://lcbmann.github.io/ComputationalGeophysics-JupyterLite-Binder-Benchmark/lab/index.html
- Simple notebook: https://lcbmann.github.io/ComputationalGeophysics-JupyterLite-Binder-Benchmark/lab/index.html?path=notebooks/01_simple_fd_acoustic_1d_animation.ipynb
- Complex notebook: https://lcbmann.github.io/ComputationalGeophysics-JupyterLite-Binder-Benchmark/lab/index.html?path=notebooks/02_complex_fd_acoustic_2d_animation.ipynb

## MyBinder
- Binder launcher: https://mybinder.org/v2/gh/lcbmann/ComputationalGeophysics-JupyterLite-Binder-Benchmark/HEAD?urlpath=lab
- Simple notebook: https://mybinder.org/v2/gh/lcbmann/ComputationalGeophysics-JupyterLite-Binder-Benchmark/HEAD?urlpath=lab/tree/notebooks/01_simple_fd_acoustic_1d_animation.ipynb
- Complex notebook: https://mybinder.org/v2/gh/lcbmann/ComputationalGeophysics-JupyterLite-Binder-Benchmark/HEAD?urlpath=lab/tree/notebooks/02_complex_fd_acoustic_2d_animation.ipynb

## What To Record

- page load time
- kernel ready time
- `simulation_seconds`
- `animation_creation_seconds`
- `jshtml_render_seconds`
- `html_size_mb`

Use a fresh private browser window for each test if you want to reduce cache effects.
