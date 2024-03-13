note:
xformers error -   
ERROR: Failed building wheel for xformers
  Running setup.py clean for xformers
Failed to build xformers
ERROR: Could not build wheels for xformers, which is required to install pyproject.toml-based projects

due to gcc incompatibility, fix:
    brew install gcc@7
    gcc-7 --version
    CC=gcc-7 CXX=g++-7 pip install xformer


