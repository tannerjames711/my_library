# my_library
If you clone this repository, you can then add the clone to your own account and rename it. Make sure you also edit the `__init__.py` file with your new names. After that, you can add functions to the `my_library.py` file.

# To use your library

```
#flush the old directory
!rm -r  'my_library'

my_github_name = 'uo-puddles'  #change to your github account name

clone_url = f'https://github.com/{my_github_name}/my_library.git'  #change my_library to new name if you rename

#this adds the library to colab so you can now import it
!git clone $clone_url

import my_library as my
```

# Test the import

`my.hello()`
