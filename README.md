# Computational Geophysics Animation Benchmark

This small repository compares MyBinder and JupyterLite for running animation-heavy computational geophysics notebooks.

It contains two notebooks adapted from the finite-difference wave-animation material in the Computational Geophysics short course:

- `notebooks/01_simple_fd_acoustic_1d_animation.ipynb`: a small 1D acoustic wave animation
- `notebooks/02_complex_fd_acoustic_2d_animation.ipynb`: a larger 2D acoustic wave animation

Each notebook measures:

- simulation time
- animation object creation time
- JavaScript/HTML animation rendering time

The goal is to compare practical startup and runtime behavior:

- MyBinder has a full server-side Python environment, but startup can be slow.
- JupyterLite starts from static GitHub Pages, but the Python kernel runs in the browser.

## Links

Replace the repository owner/name if you publish this under a different GitHub repository.

### JupyterLite

- JupyterLite site: https://lcbmann.github.io/ComputationalGeophysics_JupyterLite_Binder_Benchmark/lab/index.html
- Simple notebook: https://lcbmann.github.io/ComputationalGeophysics_JupyterLite_Binder_Benchmark/lab/index.html?path=notebooks/01_simple_fd_acoustic_1d_animation.ipynb
- Complex notebook: https://lcbmann.github.io/ComputationalGeophysics_JupyterLite_Binder_Benchmark/lab/index.html?path=notebooks/02_complex_fd_acoustic_2d_animation.ipynb

### MyBinder

- Binder launcher: https://mybinder.org/v2/gh/lcbmann/ComputationalGeophysics_JupyterLite_Binder_Benchmark/HEAD?urlpath=lab
- Simple notebook: https://mybinder.org/v2/gh/lcbmann/ComputationalGeophysics_JupyterLite_Binder_Benchmark/HEAD?urlpath=lab/tree/notebooks/01_simple_fd_acoustic_1d_animation.ipynb
- Complex notebook: https://mybinder.org/v2/gh/lcbmann/ComputationalGeophysics_JupyterLite_Binder_Benchmark/HEAD?urlpath=lab/tree/notebooks/02_complex_fd_acoustic_2d_animation.ipynb

## Suggested Test

For each platform, record:

- time from clicking the link to seeing the notebook UI
- time until the Python kernel is ready
- time for the simulation cell
- time for the animation rendering cell

Use a fresh private browser window for each test if you want to reduce cache effects.
