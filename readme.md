Run tests without Coverage
- > poetry run pytest
Run tests with Coverage
- > poetry run pytest --cov
Run nox
- > nox
Run nox without install everything
- > nox -r


Setup pyenv
```
export PATH="~/.pyenv/bin:$PATH"
eval "$(pyenv init -)"
eval "$(pyenv virtualenv-init -)"
source ~/.bashrc
source ~/.poetry/env
