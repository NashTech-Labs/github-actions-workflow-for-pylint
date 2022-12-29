## GitHub Actions Workflow For Linting through Pylint

Official Pylint Python package: https://pypi.org/project/pylint/

### Example To Check For Wildcard Imports

```
      - name: Error out on wildcard imports
        run: pylint --disable=all --enable=wildcard-import folder1 folder2
```

### Example To Check For Unused Imports

```
      - name: Error out on wildcard imports
        run: pylint --disable=all --enable=unused-import folder1 folder2
```

For more Pylint rules: https://pylint.pycqa.org/en/latest/user_guide/configuration/all-options.html