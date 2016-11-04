cyberoam-candy
==============

A basic python cyberoam login script. It uses Command Line Interface as of now. It was written to automatically log in through whichever cyberoam account had data bandwidth left.

You have to input host url in the `config_file`. The lines following that can have multiple accounts in the format `<username>:<password>`.
Cyberoam candy automatically tries to log in through the next account if the data bandwidth of previous one is expired.
