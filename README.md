# acmiel-demo-package

<https://pypi.org/project/acmiel-demo-package/>

A python package that executes arbitrary code (non-malicious) when installed via `pip`.

```bash
pip install acmiel-demo-package
```

This raises an error and creates a file in the tmpdir (or prints the content directly
if the file already exists, to be extra safe and avoid overwriting anything important).
