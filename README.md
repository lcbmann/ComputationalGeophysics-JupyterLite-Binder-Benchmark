# Computational Geophysics Animation Benchmark

This repository compares MyBinder and JupyterLite for three animation notebooks derived from the Computational Geophysics short course.

The notebooks keep the course-style plotting and finite-difference parameters:

- `notebooks/01_simple_fd_acoustic_1d_animation.ipynb`: based on `fd_acoustic_1D.ipynb`, with `nx=10000`, `nt=1001`, `idisp=5`
- `notebooks/02_complex_fd_acoustic_2d_animation.ipynb`: based on `fd_acoustic_2D_homogeneous.ipynb`, with `nx=500`, `nz=500`, `nt=502`, `idisp=5`
- `notebooks/03_original_fe_elastic_waves_1d_animation.ipynb`: based on the original `fe_elastic_waves_1D.ipynb`, with `nx=1000`, `nt=2000`, `idisp=20`

Each notebook prints timing values for the simulation, animation setup, and JavaScript/HTML animation rendering.

## JupyterLite
- JupyterLite site: https://lcbmann.github.io/ComputationalGeophysics-JupyterLite-Binder-Benchmark/lab/index.html
- Simple notebook: https://lcbmann.github.io/ComputationalGeophysics-JupyterLite-Binder-Benchmark/lab/index.html?path=notebooks/01_simple_fd_acoustic_1d_animation.ipynb
- Complex notebook: https://lcbmann.github.io/ComputationalGeophysics-JupyterLite-Binder-Benchmark/lab/index.html?path=notebooks/02_complex_fd_acoustic_2d_animation.ipynb
- Original FE notebook: https://lcbmann.github.io/ComputationalGeophysics-JupyterLite-Binder-Benchmark/lab/index.html?path=notebooks/03_original_fe_elastic_waves_1d_animation.ipynb

## MyBinder
- Binder launcher: https://mybinder.org/v2/gh/lcbmann/ComputationalGeophysics-JupyterLite-Binder-Benchmark/HEAD?urlpath=lab
- Simple notebook: https://mybinder.org/v2/gh/lcbmann/ComputationalGeophysics-JupyterLite-Binder-Benchmark/HEAD?urlpath=lab/tree/notebooks/01_simple_fd_acoustic_1d_animation.ipynb
- Complex notebook: https://mybinder.org/v2/gh/lcbmann/ComputationalGeophysics-JupyterLite-Binder-Benchmark/HEAD?urlpath=lab/tree/notebooks/02_complex_fd_acoustic_2d_animation.ipynb
- Original FE notebook: https://mybinder.org/v2/gh/lcbmann/ComputationalGeophysics-JupyterLite-Binder-Benchmark/HEAD?urlpath=lab/tree/notebooks/03_original_fe_elastic_waves_1d_animation.ipynb

## What To Record

- page load time
- kernel ready time
- `simulation_seconds`
- `animation_creation_seconds`
- `jshtml_render_seconds`
- `html_size_mb`

Use a fresh private browser window for each test if you want to reduce cache effects.
