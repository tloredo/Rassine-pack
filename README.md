# rassine

This package is being developed using a `conda` environment named `eprv10` (using Python 3.10), defined as follows:
```
$ conda create --name eprv10 -c conda-forge -c defaults python=3.10 ipython jupyter scipy matplotlib \
  h5py beautifulsoup4 html5lib bleach pandas sortedcontainers \
  pytz setuptools mpmath bottleneck jplephem asdf pyarrow colorcet hypothesis astropy gsl
```

Currently the package requires linking to data in the `spectra_library` directory in the original Rassine project, which can be clone from here: [MichaelCretignier/Rassine_public: RASSINE is a code using alpha shape to normalise 1d spectra](https://github.com/MichaelCretignier/Rassine_public).

This project's packaging uses the LINCC Python project template.  For information about the template see its [documentation](https://lincc-ppt.readthedocs.io/en/latest/).
