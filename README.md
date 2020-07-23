Reproducing my issue:

1. Create a brand new virtual environment
2. Update pip to latest version
3. `pip install . --no-cache-dir`

snowflake-connector-python version 2.2.9 is installed, and requests version 2.24.0 is installed, creating a conflict:

```
ERROR: snowflake-connector-python 2.2.9 has requirement requests<2.24.0, but you'll have requests 2.24.0 which is incompatible.
```
