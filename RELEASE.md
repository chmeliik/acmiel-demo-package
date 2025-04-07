# Releasing

```bash
pip install build twine
BUILDING_RELEASE=1 python -m build
# Upload only the sdist, wheels do not cause arbitrary code execution
python -m twine upload dist/*.tar.gz
```
