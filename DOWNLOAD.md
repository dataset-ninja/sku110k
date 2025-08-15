Dataset **SKU110K** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogInMzOi8vc3VwZXJ2aXNlbHktZGF0YXNldHMvMzEzN19TS1UxMTBLL3NrdTExMGstRGF0YXNldE5pbmphLnRhciIsICJzaWciOiAiVE55elkvTm1rbE4vZzh3a1drS2piQ3o4L1lDVnFHQjY5NFA0d053cWJwOD0ifQ==?response-content-disposition=attachment%3B%20filename%3D%22sku110k-DatasetNinja.tar%22)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='SKU110K', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://drive.google.com/file/d/1iq93lCdhaPUN0fWbLieMtzfB1850pKwd).