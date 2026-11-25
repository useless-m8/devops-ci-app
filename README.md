# \# devops-ci-app

# 

# Учебное Flask-приложение для практической работы № 10.

# 

# CI: Pylint → pytest → Docker build → smoke-test → GHCR.

# 

# Публикация образа выполняется только из `main`.

# В Pull Request выполняются проверки без push.

# 

# \- Health endpoint: `/health`

# \- Образ: `ghcr.io/useless-m8/devops-ci-app`

# \- Основной workflow: `.github/workflows/ci.yml`

