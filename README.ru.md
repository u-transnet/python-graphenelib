[![English](https://thumb.ibb.co/jDrVkd/gb.png)](README.md) [![Russian](https://thumb.ibb.co/cjYMrJ/ru.png)](README.ru.md)

# python-graphenelib
Python 3 библиотека для Graphene 2.0!

## Установка из репозитория:

    $ git clone https://github.com/u-transnet/python-graphenelib/
    $ cd python-graphenelib
    $ python3 setup.py install --user

## Зависимости:

Some dependencies are not required for parts of the library to run
properly. However these modules require some additional libraries to be
present:

* `graphenebase.bip38`
   * `pycrypto==2.6.1`
   * `scrypt==0.7.1` (to speedup scrypt hashing)
* `graphenebase.memo`
   * `pycrypto==2.6.1`

## Документация

Thanks to readthedocs.io, the documentation can be viewed
[online](http://python-graphenelib.readthedocs.io/en/latest/)

Documentation is written with the help of sphinx and can be compile to
html with:

    cd docs
    make html

## Сотрудничество
Мы будем рады вашей помощи в развитии проекта! Откройте [CONTRIBUTING.ru.md](CONTRIBUTING.ru.md) для того, чтобы узнать чем Вы можете поможете помочь проекту и как присоединиться

## Лицензия
Проект использует MIT лицензию. Откройте [LICENSE](LICENSE) для подробностей

