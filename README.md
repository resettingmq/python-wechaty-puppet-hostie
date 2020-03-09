# wechaty-puppet-hostie [![Python 3.7](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-370/) [![PyPI GitHub Actions](https://github.com/wechaty/python-wechaty-puppet-hostie/workflows/PyPI/badge.svg)](https://github.com/wechaty/python-wechaty-puppet/actions?query=workflow%3APyPI)

[![Powered by Wechaty](https://img.shields.io/badge/Powered%20By-Wechaty-brightgreen.svg)](https://github.com/wechaty/wechaty)

![Hostie](https://wechaty.github.io/wechaty-puppet-hostie/images/hostie.png)

[![PyPI Version](https://img.shields.io/pypi/v/wechaty-puppet-hostie?color=blue)](https://pypi.org/project/wechaty-puppet-hostie)
![PyPI - Downloads](https://img.shields.io/pypi/dm/wechaty-puppet-hostie?color=blue)

Python Hostie Puppet for Wechaty

## Features

1. Consume hostie service

## Usage

```python
import asyncio
from wechaty import Wechaty

bot = new Wechaty({
  puppet: 'wechaty-puppet-hostie',
  puppetOptions: {
    token: 'secret'
  }
})

asyncio.run(wechaty.start())
```

## Environment Variables

### 1 `WECHATY_PUPPET_HOSTIE_TOKEN`

The token set to this environment variable will become the default value of `puppetOptions.token`

```sh
WECHATY_PUPPET_HOSTIE_TOKEN=secret python bot.py
```

## History

### master

### v0.0.1 (Mar 10, 2020)

1. Init Python version
1. Published to PyPI

## Author

[Huan LI](https://github.com/huan) ([李卓桓](http://linkedin.com/in/zixia)) zixia@zixia.net

[![Profile of Huan LI (李卓桓) on StackOverflow](https://stackexchange.com/users/flair/265499.png)](https://stackexchange.com/users/265499)

## Copyright & License

* Code & Docs © 2020-now Huan LI \<zixia@zixia.net\>
* Code released under the Apache-2.0 License
* Docs released under Creative Commons
