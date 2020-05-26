---
id: project_structure
title: Project Structure and Templates
sidebar_label: Project Structure
---

### The following folder structure should be used for projects:


* :file_folder: Project Root:
    - :memo: pyproject.toml (can be requirements.txt and setup.py)
    - :file_folder: docs
        * Your documentation
    - :file_folder: data
        * Data for project.
    - :file_folder: {PROJECT_NAME}
        + :file_folder: utils
        + :file_folder: service
        + :file_folder: config
    - :file_folder: tests
        + test of projects
    - :memo: LICENSE (**OPTIONAL**)
    - :memo: README (can be `md` or `rst`)
    - Other configurable from third parties (**OPTIONAL**) such as tox.ini



##### Template Generation: 
* Look into [cookiecutter](https://cookiecutter.readthedocs.io/en/1.7.2/) tool for template generation.
    - [List of templates for cookiecutter](http://cookiecutter-templates.sebastianruml.name/)