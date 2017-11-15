# fountain_nano

fountain_nano provides `nano` syntax highlighting for
[Fountain](https://fountain.io/), a lightweight screenplay markup language.

## Installation

### Local

To install for a single user:

    mkdir -p ~/.nano/syntax/ # (If it doesn't already exist.)
    cp fountain.nanorc ~/.nano/syntax/
    echo 'include ~/.nano/syntax/fountain.nanorc' >> ~/.nanorc

### Global

To install for all users:

    sudo cp fountain.nanorc /usr/share/nano/
    sudo echo 'include /usr/share/nano/fountain.nanorc' >> /etc/nanorc

Note: If nano was not installed through your package manager, you may need to
replace `/usr/share/nano/` with `/usr/local/share/nano`.

## License

MIT License

Copyright (c) 2017 IBPX

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
