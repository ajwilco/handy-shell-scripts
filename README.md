# handy-shell-scripts
Mostly just quick tools I wrote out of day-to-day frustrations with bash.

I primarily work in Debian or Ubuntu based systems, that may effect how useful the scripts are for you. For instance, `apts-get` is just a thing to simplify a string of `apt` commands I got sick of typing.

Deploy any one script with:
```
chmod +x [script] && sudo cp [script] /usr/local/bin/
```

## apts-get
"apt: update, upgrade, cleanup."
- Only useful on systems that use the `apt` package manager.

## cpf
"Copy, Follow." Maybe cpcd would be a better name?

Alternative to `cp file.txt /to/place/ && cd /to/place`

## mvf
"Move, Follow." Maybe mvcd would be a better name?

Alternative to `mv file.txt /to/place/ && cd /to/place`

## myip
"What is my current external IP?"
- Depends on `curl` being installed.

## nsl
"Name Server Lookup." Maybe I didn't know about `nslookup` when I made this.
- Depends on `whois` being installed.

`whois` is very.. verbose.  I made this to just get the info I tend to need.
