# Third-Party Licenses

This project includes several third-party open-source libraries, each with its own license. This file lists the licenses of the dependencies we use.

## Python Dependencies

### Development and Utilities
- **black**: MIT License
  - https://github.com/psf/black/blob/main/LICENSE
- **ipykernel**: BSD 3-Clause License
  - https://github.com/ipython/ipykernel/blob/main/LICENSE
- **python-dotenv**: BSD 3-Clause License
  - https://github.com/theskumar/python-dotenv/blob/main/LICENSE
- **tqdm**: MIT License / MPL-2.0
  - https://github.com/tqdm/tqdm/blob/master/LICENCE
- **pytest**: MIT License
  - https://github.com/pytest-dev/pytest/blob/main/LICENSE

### Scientific Computing and Data Processing
- **scikit-learn**: BSD 3-Clause License
  - https://github.com/scikit-learn/scikit-learn/blob/main/COPYING
- **scikit-image**: BSD 3-Clause License
  - https://github.com/scikit-image/scikit-image/blob/main/LICENSE.txt
- **openpyxl**: MIT License
  - https://github.com/theorchard/openpyxl/blob/master/LICENCE.rst
- **duckdb**: MIT License
  - https://github.com/duckdb/duckdb/blob/main/LICENSE

### Geospatial Libraries
- **torchgeo**: MIT License
  - https://github.com/microsoft/torchgeo/blob/main/LICENSE
- **geopandas**: BSD 3-Clause License
  - https://github.com/geopandas/geopandas/blob/main/LICENSE.txt
- **feather-format**: Apache License 2.0
  - https://github.com/wesm/feather/blob/master/LICENSE.txt
- **pyproj**: MIT License
  - https://github.com/pyproj4/pyproj/blob/main/LICENSE

### Deep Learning and Machine Learning
- **kornia**: Apache License 2.0
  - https://github.com/kornia/kornia/blob/main/LICENSE
- **tensorboard**: Apache License 2.0
  - https://github.com/tensorflow/tensorboard/blob/master/LICENSE
- **optuna**: MIT License
  - https://github.com/optuna/optuna/blob/master/LICENSE

### Cloud Services and Storage
- **azure-storage-blob**: MIT License
  - https://github.com/Azure/azure-sdk-for-python/blob/main/sdk/storage/azure-storage-blob/LICENSE
- **azure-ai-ml**: MIT License
  - https://github.com/Azure/azure-sdk-for-python/blob/main/sdk/ml/azure-ai-ml/LICENSE
- **azureml-core**: Proprietary / Microsoft Software License
  - https://github.com/Azure/MachineLearningNotebooks/blob/master/LICENSE.txt
  - Note: Usage subject to Microsoft Azure terms
- **google-cloud-storage**: Apache License 2.0
  - https://github.com/googleapis/python-storage/blob/main/LICENSE

## License Summaries

### MIT License
Permissive license that allows commercial use, modification, distribution, and private use. Requires preservation of copyright and license notices.

**Packages**: black, tqdm, pytest, openpyxl, duckdb, torchgeo, pyproj, optuna, azure-storage-blob, azure-ai-ml

### BSD 3-Clause License
Permissive license similar to MIT but with an additional non-endorsement clause. Allows commercial use, modification, distribution, and private use.

**Packages**: ipykernel, python-dotenv, scikit-learn, scikit-image, geopandas

### Apache License 2.0
Permissive license that allows commercial use, modification, distribution, and patent use. Requires preservation of copyright, license, and state changes.

**Packages**: feather-format, kornia, tensorboard, google-cloud-storage

### Proprietary / Microsoft Software License
Usage subject to Microsoft's terms and conditions for Azure services.

**Packages**: azureml-core

## Notes

- This project uses **kornia v0.7.3** specifically, which is licensed under Apache License 2.0
- **duckdb** requires version 1.1.0 or higher
- Some packages may have transitive dependencies with their own licenses
- Always verify license compatibility for your specific use case
- Refer to each package's repository for the most current license information
