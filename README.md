# BK21
BK21 is... inefficient.

I wish [this short notebook](https://nbviewer.jupyter.org/github/ysBach/BK21/blob/master/BK2020_survey_topublic.ipynb) can help you save your precious time from stupid administrative work.



## Requirements

* tqdm
* astroquery
* pandas

```
$ conda install conda-forge tqdm pandas
```

For astroquery, I recommend developer's bleeding edge version:

```
$ cd <your_github_download_directory>
$ git clone https://github.com/astropy/astroquery.git
$ cd astroquery
$ python setup.py install
```

Alternatively (not recommended), you can do ``conda install -c astropy astroquery``. 

