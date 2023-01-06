# What's in here
This package serves as a practice for packaging python libraries.  
1. Package for python
2. Uploading it to pypi

# Build the python package
https://packaging.python.org/en/latest/tutorials/packaging-projects/

# Uploading to artifactory cloud pypi
configure .pypirc so that it points to the right pypi repo
`twine upload -r local dist/* --config-file .pypirc`


# Installing through artifactory cloud pypi
`pip3 install map-runner -i http://seanwutest.jfrog.io/artifactory/api/pypi/default-pypi-local/simple --trusted-host XYZ.jfrog.io`

`pip3 install map-runner -i http://seanwutest.jfrog.io/artifactory/api/pypi/default-pypi-local/simple --trusted-host seanwutest.jfrog.io `