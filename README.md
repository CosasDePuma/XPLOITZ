# XPLOITV

[![PyPI](https://img.shields.io/pypi/v/xploitv?color=blue&style=for-the-badge)](https://pypi.org/project/xploitv)
[![PyPI - Downloads](https://img.shields.io/pypi/dm/xploitv?color=green&style=for-the-badge)](https://pypi.org/project/xploitv)
[![License](https://img.shields.io/github/license/cosasdepuma/xploitv?color=orange&style=for-the-badge)](https://github.com/CosasDePuma/XPLOITV/blob/master/LICENSE)


## Disclaimer

This tool has been developed with a totally didactic purpose. `I am not responsible for the misuse of the same or for the damages caused to third parties.` Furthermore, this tool has no affinity or relationship with Xploitv or any of its developers.

## Installation

To install the tool, the easiest way is to use the pip command:

```py
python -m pip install xploitv
```

## Hack the world!

To see all the functionalities that the application offers, run the command:

<details>
  <summary>xploitv --help</summary>

  ```
  usage: xploitv [-h] [-v] [--version] [-t THREADS] [-x FORMAT] [-i ID | -w FILE]


  optional arguments:
  -h, --help            show this help message and exit

  information:
  -v                    Verbosity (Default: -vv)
  --version             Print the version

  performance:
  -t THREADS, --threads THREADS
                        Define the number of threads

  output:
  -x FORMAT, --extension FORMAT
                        Output extension (csv,txt)

  grabber (one required):
  -i ID, --id ID        Grab all the accounts linked to an identifier
  -w FILE, --wordlist FILE
                        Grab all the accounts linked to identifiers in a wordlist
  ```
</details>
<br>

To get all the accounts associated with an identifier, run the command:

```
xploitv -i <identifier>
```

```
____  ___      .__         .__  __
\   \/  /_____ |  |   ____ |__|/  |____  __
 \     /\____ \|  |  /  _ \|  \   __\  \/ /
 /     \|  |_> >  |_(  <_> )  ||  |  \   /
/___/\  \   __/|____/\____/|__||__|   \_/
      \_/__|

   [[ An automated Xploitv grabber ]]

[18:51:48] Let's hack this world!
[18:51:49] Grabbing accounts from 123456
            ...
```

### Wordlists

The true potential of this program comes from its ability to run using `wordlists`. Furthermore, this method of execution is carried out using concurrency techniques, that you can customize using the `-t` parameter:

```
xploitv -w <wordlist> -t 50
```

### Output and verbosity

Are you wondering how you can save your results? Easy.

Xploitv displays the results on the screen. You can customize the verbosity level using the `-v` parameter:

```
xploitv -i <identifier> -vvv
```
```
____  ___      .__         .__  __
\   \/  /_____ |  |   ____ |__|/  |____  __
 \     /\____ \|  |  /  _ \|  \   __\  \/ /
 /     \|  |_> >  |_(  <_> )  ||  |  \   /
/___/\  \   __/|____/\____/|__||__|   \_/
      \_/__|

   [[ An automated Xploitv grabber ]]

[19:03:30] Let's hack this world!
[19:03:31] Grabbing accounts from 123456
[19:03:31] Account from code 123456
Username: 'xxxx@gmail.com'
Password: 'xxxx'
[19:03:31] Account from code 123456
Username: 'xxxx@msn.com'
Password: 'xxxx'
```

To save the result, you can add the `-x` parameter that allows you to store the output in `txt` or `csv` format.

```
xploitv -i <identifier> -x csv
```
```
____  ___      .__         .__  __
\   \/  /_____ |  |   ____ |__|/  |____  __
 \     /\____ \|  |  /  _ \|  \   __\  \/ /
 /     \|  |_> >  |_(  <_> )  ||  |  \   /
/___/\  \   __/|____/\____/|__||__|   \_/
      \_/__|

   [[ An automated Xploitv grabber ]]

[19:07:17] Let's hack this world!
[19:07:17] Grabbing accounts from 123456
[19:07:17] Setting the output format to 'csv'
[19:07:17] Results stored in ./dump.csv
```


## Uninstall

Easy to install. Easy to uninstall. To do this, just run the command:

```
pip uninstall xploitv
```

## Support the developer!

Everything I do and publish can be used for free whenever I receive my corresponding merit.

Anyway, if you want to help me in a more direct way, you can leave me a tip by clicking on this badge:

<p align="center">
    </br>
    <a href="https://www.paypal.me/cosasdepuma/"><img src="https://img.shields.io/badge/Donate-PayPal-blue.svg?style=for-the-badge" alt="PayPal Donation"></a>
</p>
