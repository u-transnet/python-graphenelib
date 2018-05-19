[![English](https://thumb.ibb.co/jDrVkd/gb.png)](README.md) [![Russian](https://thumb.ibb.co/cjYMrJ/ru.png)](README.ru.md)

# python-graphenelib
Python 3 library for Graphene 2.0!

## Manual installation:

    $ git clone https://github.com/u-transnet/python-graphenelib/
    $ cd python-graphenelib
    $ python3 setup.py install --user

## Dependencies:

Some dependencies are not required for parts of the library to run
properly. However these modules require some additional libraries to be
present:

* `graphenebase.bip38`
   * `pycrypto==2.6.1`
   * `scrypt==0.7.1` (to speedup scrypt hashing)
* `graphenebase.memo`
   * `pycrypto==2.6.1`

## Documentation

Thanks to readthedocs.io, the documentation can be viewed
[online](http://python-graphenelib.readthedocs.io/en/latest/)

Documentation is written with the help of sphinx and can be compile to
html with:

    cd docs
    make html

## Contributing
We'd love to have your helping hand on our project! See [CONTRIBUTING.md](CONTRIBUTING.md) for more information on what we're looking for and how to get started.

## License
Project is under the MIT license. See [LICENSE](LICENSE) for more information.

