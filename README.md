# rassine-pack

`Rassine-pack` is a revision of the `RASSINE` 1-D spectrum smoothing software shared in Michael Cretignier's  [Rassine_public](https://github.com/MichaelCretignier/Rassine_public) repo. `Rassine-pack` modifies the original collection of scripts and module to comprise a pip-installable Python package with a more Pythonic user interface.

This package is being developed using a `conda` environment named `eprv10` (using Python 3.10), defined as follows:

```
$ conda create --name eprv10 -c conda-forge -c defaults python=3.10 ipython jupyter scipy matplotlib \
  pooch tqdm h5py beautifulsoup4 html5lib bleach pandas sortedcontainers \
  pytz setuptools mpmath bottleneck jplephem asdf pyarrow colorcet hypothesis astropy copier gsl
```

Currently the package requires linking to data in the `spectra_library` directory in the original Rassine project, which can be clone from here: [MichaelCretignier/Rassine_public: RASSINE is a code using alpha shape to normalise 1d spectra](https://github.com/MichaelCretignier/Rassine_public).

This project's packaging is maintained using the `copier`-based LINCC Frameworks Python project template.  For information about the template see the [LINCC Frameworks Python project template documentation](https://lincc-ppt.readthedocs.io/en/latest/).

