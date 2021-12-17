# Transfred - Simple Alfred Workflow interface to translate-shell.

Translate from any language, to multiple languages - at the same time.

<img width="600" alt="1" src="https://user-images.githubusercontent.com/193781/146220277-c4dbd918-b0a4-4ec0-95a8-bf562cacd17c.png">

Translate-shell automatically detects input language, which is very convenient.

<img width="600" alt="2" src="https://user-images.githubusercontent.com/193781/146220284-1ee07476-188e-4e77-964b-b19819d90e3f.png">

## Setup & config

Dependends on GNU awk and translate-shell.
Install those on macOS with `brew install gawk translate-shell`

Adjust homebrew prefix in the workflow variables from `/opt/homebrew` to `/usr/local` if not on Apple silicon.

Configure target languages in the same place, in the format `no+en+de+es` as per output of `trans -T` to list language codes.

## Problems

If you have many languages and search too often, the translation server (Google by default) will rate limit you. Try again later. 
