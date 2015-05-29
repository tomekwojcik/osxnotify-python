# osxnotify

No nonsense OS X notifications for Python scripts (native wrapper).

## Installing

```sh
$ python setup.py install
```

## Usage

```python
import osxnotify

osnotify.notify('Title', subtitle='Subtitle', informative_text='Informative text')
```

## Issues and limitations

Currently, only UTF-8 is supported.
