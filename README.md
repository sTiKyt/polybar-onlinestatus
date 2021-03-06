# polybar-onlinestatus
<p align="center">
    <a href="https://badge.fury.io/py/polybar-onlinestatus"><img src="https://badge.fury.io/py/polybar-onlinestatus.svg" alt="PyPI version" height="18"></a>
    <a href="https://www.python.org/dev/peps/pep-0008/"><img title="PEP8" src="https://img.shields.io/badge/code%20style-pep8-blue.svg"></a>
    <a href="https://pypi.org/project/polybar-onlinestatus"><img title="PyPI - Python Version" src="https://img.shields.io/pypi/pyversions/polybar-onlinestatus"></a>
</p>

polybar module that checks if you are online

To install use `pip install polybar-onlinestatus`

And use module below:

```
[module/onlinestatus]
type = custom/script
exec = polybar-onlinestatus
tail = true
label = %{T4} %output% %{T-}
format-underline = #07BDEE
```

```font-3 = Hack Nerd Font:style=Bold:size=12```

You can use any font you want, but make sure icon is big enough. I recommend Nerd Hack but it's up to you.

For more options use ```polybar-onlinestatus --help``` in your terminal and assign options in ```exec = polybar-onlinestatus``` line.

Icon used by default is ``, if you are unable to see it - install nerd font from nerdfonts.com, replace it with your own or use --boolean-mode.
