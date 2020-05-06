# my_library
If you clone this repository, you can then add the clone to your own account. In particular, you can add functions to the `my_library.py` file.

Here are the steps to follow.

![Clone my_library](https://www.dropbox.com/s/gi13x121zsj9kcz/Screenshot%202020-05-06%2013.30.06.png?raw=1)

You should now see these files in your new my_library repository.

![Contents of my_library](https://www.dropbox.com/s/hv1r07tn0itizr4/Screenshot%202020-05-06%2013.36.18.png?raw=1)


# To use your library from colab

```
#flush the old directory
!rm -r  'my_library'

my_github_name = 'uo-puddles'  #change to your github account name

clone_url = f'https://github.com/{my_github_name}/my_library.git'

#this adds the library to colab so you can now import it
!git clone $clone_url

import my_library as my
```

# Test the import

`my.hello()`
