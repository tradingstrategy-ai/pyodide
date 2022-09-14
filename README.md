Patched Pyodide to include pyarrow

- No clean patchset available, so probably not 

- Forked from pyodide-build 0.22.0.dev0

- For any question [pop in to our Discord server](https://tradingstrategy.ai/co])
# Building

Start Docker builder container:

```shell
./run_docker
```

To build pyarrow:

```shell
pip install ./pyodide-build
python -m pyodide_build buildall --only 'pyarrow' packages dist
```

# Kudos

Thank you for [Joe Marshall](github.com/joemarshall/) for setting this up.