# Python for DevOps: CI/CD for Python Projects

This repository contains the complete CI/CD implementation for the CI/CD 


## ✅ What I have done in this repository

- [x] **Implement the project (code files)** - Complete Python package with proper structure
- [x] **Add a simple GHA workflow** - Basic GitHub Actions setup and execution
- [x] **Add linting (ruff) and format checks (black)** - Code quality automation
- [x] **Add typing (mypy) and security checks (bandit)** - Static analysis and security scanning
- [x] **Add test automation** - Comprehensive test suite with pytest
- [x] **Build our Python project** - Automated package building
- [x] **Publish the project to both TestPyPI and PyPI** - Automated package publishing on releases


usefull commmands: 
#check-urls https://github.com https://google.com --timeout 10 -v


#python -m venv .venv
#.venv/Scripts/activate
#pip install -e. 
#pip install ".[dev]"
#black --check .  
#black .
#ruff check .
#bandit -c .\pyproject.toml -r . 