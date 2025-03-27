# HumanGEMlib usage

HumanGEMlib is a Python library to perform genome-scale analysis on HumanGEM.

```bash
pip install humangemlib
```

Tested in Jupyter Notebook.

```bash
pip install jupyter
```

Before first run of humangemlib, GTF database needs to be created to convert Ensembl genes to gene IDs

```pyensembl install --release 111 --species homo_sapiens```

PyPI package contains HumanGEM XML file but GitHub repository does not (25 MB upload limit). It can be downloaded [here](https://github.com/SysBioChalmers/Human-GEM/blob/main/model/Human-GEM.xml).

```usage.ipynb``` is an example on diabetic metabolic dysregulation due to genetic knockouts.

 Publication draft: [Subtypes of type 2 diabetes from genetic knockouts in HumanGEM genome-scale model show 5 signature metabolic states](diabetes_sysbio_draft_publication.pdf)

Dependencies:

- cobra==0.29.0
- importlib_resources==6.4.0
- numpy==1.26.4
- pandas==2.2.2
- pyensembl==2.3.13

## License

This project is released under the Creative Commons Zero license.
