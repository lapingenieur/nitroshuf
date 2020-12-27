# nitroshuf

Command Line Interface (CLI) for Nitrogen

# What is nitroshuf ?

Nitroshuf is a CLI (Command Line Interface) bash script to manage nitrogen. It provides an interactive prompt as well as direct options to give it from the shell. It atcs directly on nitrogen's configuration file which makes it more powerfull.

# Usage

## With options from the Shell

### Nitroshuf's options

| option | description |
|-|-|
| `-g`, `--generate` | generate nitro**shuf**'s default config file (overwrites) |
| `-p, `--prompt`` | run the builtin prompt |
| `-v`, `--vers`, `--version` | print current nitro**shuf** version |
| `-h`, `--help` | print the "small" help page |

### Managing nitrogen

These are short options with a capital letter or long (and standard) options linked to the commands used in prompt mode.

| option | description |
|-|-|
| `-P`, `--print` | print nitrogen configuration file |
| `-F`, `--file`, `--files` | print name of current background images |
| `-S`, `--show` | open current background images in default viewer |
| `-A`, `--save` | save current nitrogen configuration to a copy |
| `-E`, `--edit` | edit current nitrogen configuration with `$EDITOR` |
| `-N`, `--nir` | restart (in fact *restore*) nitrogen |
| *(without)* | generate a random nitrogen configuration and ask to write it |

> Note : you can give several arguments (sometimes 2) to an option so these are given to the actually executed function. Reffer to Usage within the prompt for more informations.

## Within the prompt

The included prompt works like a shell : the first enterred word is the *command* (or *function*, as you will) and you might have to give it 

To enter the nitroshuf prompt, just execute `nitroshuf -p` from the shell.

| command | alias | arguments | description |
|-|-|-|
| `help` | `h` | (none) | print the builtin prompt's help (commands and their description) |
