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

_This project is licensed under the zlib license._

Copyright (c) 2017 IBPX

This software is provided 'as-is', without any express or implied
warranty. In no event will the authors be held liable for any damages
arising from the use of this software.

Permission is granted to anyone to use this software for any purpose,
including commercial applications, and to alter it and redistribute it
freely, subject to the following restrictions:

1. The origin of this software must not be misrepresented; you must not
   claim that you wrote the original software. If you use this software
   in a product, an acknowledgment in the product documentation would be
   appreciated but is not required.
2. Altered source versions must be plainly marked as such, and must not be
   misrepresented as being the original software.
3. This notice may not be removed or altered from any source distribution.
