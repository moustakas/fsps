# C3K_R10K

This directory contains custom C3K spectra generated using the scripts in
  https://github.com/moustakas/c3k

Like the C3K models that ship with FSPS, they have been downsampled
from the full C3K resolution and interpolated onto the BaSeL logg-logt
grid.

However, in the optical spectral range, the models have much higher
spectral resolution; they are critically sampled with the following
resolution


| wave_low (AA) | wave_high (AA) | R (lambda/FWHM) |
|---------------|----------------|-----------------|
| 100           | 1000           | 250             |
| 1000          | 3500           | 1000            |
| 3500          | 9800           | 10000           |
| 9800          | 24000          | 500             |
| 240000        | 10000000       | 50              |
