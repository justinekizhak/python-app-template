# {{cookiecutter.project_name}}

## Run project

```sh
python3 {{cookiecutter.project_root}}
```

## Testing

### Isolated testing

```sh
tox
```

### Testing once

```sh
pytest
```

### TDD

```sh
pytest-watch
```

### Type checking

```sh
mypy
```

### Linting, typechecking all at once

```sh
tox -e check
```
