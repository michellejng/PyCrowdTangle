# Develop Tools
Tools used to build this package and project

## github Workflow
https://www.atlassian.com/es/git/tutorials/comparing-workflows/gitflow-workflow

Work will be done in the develop branch, and the releases in the master branch

## CD/CI Github actions
https://github.com/features/actions

## IDE
VSCODE

## StyleGuide
http://google.github.io/styleguide/pyguide.html

## Considerations
API keys safe (You can store your API key in an environment variable)
avoid hitting rate limits.

## Build package
Compile package
`python setup.py bdist_wheel`

Upload to pip
`twine upload dist/*`

## References
- first examples https://www.geeksforgeeks.org/get-post-requests-using-python/
- API reference https://github.com/CrowdTangle/API/wiki
- https://semaphoreci.com/community/tutorials/building-and-testing-an-api-wrapper-in-python
- cookiecutter https://github.com/AllenCellModeling/cookiecutter-pypackage
- build a python package simple https://towardsdatascience.com/build-your-first-open-source-python-project-53471c9942a7
- https://medium.com/@joel.barmettler/how-to-upload-your-python-package-to-pypi-65edc5fe9c56
- https://dzone.com/articles/executable-package-pip-install
- create documentation spinx https://jackmckew.dev/automatically-generate-documentation-with-sphinx.html
