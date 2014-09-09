# Muro

**Muro is a configuration language which improves flexibility by data labeled method.**

This configuration language is supposed to use for automatic programming or system configuration.

### How to use?

Binding callback functions and begining to interpret configuration file written in Muro by using Muro-binding library. See examples for more usage.

### What does this name mean?

The configuration language **Muro** originates from *Higashi-Muroran station* in Hokkaido, Japan.

## Installation

Clone from GitHub repository.

```
git clone https://github.com/gfunction/muro.git
```

## Language Support

Muro supports **JavaScript** now because there is only JavaScript library. I'll soon make more libraries for another computer programming languages.

## Some Examples of Grammar

Here is 2 examples of Muro grammar.

e.g. The recoard name and data.

```
(RECOARD_NAME) (RECOARD_DATA)
```

e.g. The recoard name and labeled  data (starting with a colon `:`). Also this recoard has more than one data list.

```
(RECOARD_NAME) (RECOARD_LABEL_NAME) (RECOARD_DATA...)
    (ORG_DATA) (ORG_DATA_LABEL_NAME) (ADDITIONAL_DATA...)
        ...
```

See `examples` directory for more usage.

## License

The MIT License (MIT)

Copyright (c) 2014 TADOKORO Saneyuki, gfunction Computer Science Laboratory

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
