# Hyperband
Hyperband based on zygmuntz's repository

Disclaimer: most of the code in this repo has been forked from zygmuntz's excellent repository: 
https://github.com/zygmuntz/hyperband

I have included some modifications which make it easier to use as well as new functionalities:

Current implementations
- Added possibility to set parameters max_iter and eta from the creation of the Hyperband object (defaults to paper's default: 81 and 3).
- Added argument in hb.run to pass the data (before it was necessary to store it in some arbitrary folder).

To be implemented:
- Support for LSTM's in tensorflow.
