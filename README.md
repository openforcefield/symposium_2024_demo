This is where I'm assembling OpenFF's live demo for the 2024 OSMF Symposium.

Magic words for [colab](https://colab.research.google.com/github/openforcefield/symposium_2024_demo/blob/main/symposium_demo.ipynb):

```python
!pip install -U https://github.com/conda-incubator/condacolab/archive/cuda-version-12.tar.gz
import condacolab
condacolab.install_mambaforge()
!wget -q https://raw.githubusercontent.com/openforcefield/symposium_2024_demo/main/colab-environment.yml
!wget -q https://raw.githubusercontent.com/openforcefield/symposium_2024_demo/main/last_frame_lig.pdb
!mamba env update -q --name=base --file=colab-environment.yml
```

```
from google.colab import output
output.enable_custom_widget_manager()
```

This repo has a corresponding Zenodo artifact at https://zenodo.org/records/12628105
