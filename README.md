**ASTROALIGN** is a python module that will try to align two stellar astronomical images, especially when there is no WCS information available.

**This is a hasty port of astroalign** to use photutils instead of sep for source extraction (sep is not compatible with recent versions of numpy). Original repo: [https://github.com/quatrope/astroalign/tree/master](https://github.com/quatrope/astroalign/tree/master).

# Citation

If you use astroalign in a scientific publication, the original authors would appreciate citations to the following [paper](https://www.sciencedirect.com/science/article/pii/S221313372030038X):

    Astroalign: A Python module for astronomical image registration.
    Beroiz, M., Cabral, J. B., & Sanchez, B.
    Astronomy & Computing, Volume 32, July 2020, 100384.