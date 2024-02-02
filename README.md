# numpydantic

[![PyPI - Version](https://img.shields.io/pypi/v/numpydantic)](https://pypi.org/project/numpydantic)
[![Documentation Status](https://readthedocs.org/projects/numpydantic/badge/?version=latest)](https://numpydantic.readthedocs.io/en/latest/?badge=latest)
[![Coverage Status](https://coveralls.io/repos/github/p2p-ld/numpydantic/badge.svg)](https://coveralls.io/github/p2p-ld/numpydantic)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

Type and shape validation and serialization for numpy arrays in pydantic models

This package was picked out of [nwb-linkml](https://github.com/p2p-ld/nwb-linkml/), a 
translation of the [NWB](https://www.nwb.org/) schema language and data format to
linkML and pydantic models.

It does two primary things:
- **Provide types** - Annotations (based on [npytyping](https://github.com/ramonhagenaars/nptyping))
  for specifying numpy arrays in pydantic models, and
- **Generate models from LinkML** - extend the LinkML pydantic generator to create models that 
  that use the [linkml-arrays](https://github.com/linkml/linkml-arrays) syntax

