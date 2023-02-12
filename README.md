# strong-password-generator

random-password-generator is a software that creates strong passwords that are only viewable to the user. The generated passwords can be seen in the generatedPasswords.log file. This is an output file that is created when the program is run. The salts.txt file is where the program randomly chooses words in the file to add to your hashed password.
## Installation

Open the terminal and run: 
```bash
git clone https://github.com/mohdtarek/random-password-generator.git
```
Once the file is cloned, run normally and follow the prompts in the ide compiler.

## Usage

```python
import logging as log
import random
from string import *
import hashlib
import binascii
import os
import colorama as cl
```

## Contributing

For any fixes or new additions feel free to make a pull request.

Please make sure to update tests as appropriate.

## License

MIT License
