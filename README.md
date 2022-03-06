# much
_`much` is much more than less._

`much` = `grep` + `less` + `tail`

**Currently a very early prototype with limited functionality.**


## Usage
`much` needs to be provided a redirected stream,
```bash
some-command-that-produces-output | much
```


## Installation
Requires Python 3.10+ installed.

```
# Global installation
curl https://raw.githubusercontent.com/francium/much/master/much | sudo tee file.txt > /dev/null
```
