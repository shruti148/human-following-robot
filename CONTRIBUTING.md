# Contributing to Human Following Robot

Thank you for your interest in contributing! Please follow these steps:

1. **Fork** the repository and clone your fork locally.
2. Create a feature branch: `git checkout -b feature/your-feature-name`.
3. Write code following the [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html) and [PEP8](https://peps.python.org/pep-0008/) for Python.
4. Add or update **unit tests** (`tests/unit_tests.cpp`) and **integration tests** (`tests/integration_tests.py`).
5. Ensure all tests pass locally:
   ```bash
   # C++ tests
   mkdir -p build && cd build
   cmake .. && make && ctest
   
   # Python tests
   pytest tests/integration_tests.py
