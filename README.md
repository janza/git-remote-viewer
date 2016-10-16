# Git remote viewer

Opens specified file in web interface of remote git service.

Supported services: bitbucket.org, github.com, gitlab.com

### Installation

```
sudo mv git-view /usr/local/bin/git-view
```

### Usage

```
git view file [linenumber]
```

Bonus vim mapping that opens currently selected line in the browser:

```
nmap gv :execute "!git-view % " . line(".")<CR>
```
