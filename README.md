pytype mirror
=============

Mirror of pytype package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For pytype: see https://github.com/google/pytype


### Using pytype with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: https://github.com/ZlatyChlapec/mirrors-pytype
        rev: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: pytype
