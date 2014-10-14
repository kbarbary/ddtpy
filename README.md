DDTPy
=====

Python implementation of the spectral data cube modeling code DDT

The name DDTPy is mostly a placeholder to distinguish this from the
original DDT implementation, during development.

Alternative name: SNIFit - "SuperNova IFU Fit"?

Dependencies
------------

Currently written for Python 2.7.

* numpy
* scipy (for optimization)
* fitsio - https://github.com/esheldon/fitsio


**FFT libraries** - Currently we're just using `numpy.fft`. Note that
PyFFTW is a wrapper for `fftw` while `numpy.fft` or `scipy.fftpack`
are wrappers for other FFT libraries. FFTW is supposedly the
fastest. We're The original Yorick code uses a FFTW wrapper and we may
want to switch at some point.

Documentation
-------------

http://ddtpy.readthedocs.org

License
-------

MIT