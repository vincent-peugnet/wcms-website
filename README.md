# W official Website

This repo contain W's website hosted here: <https://w.club1.fr>

Repo of W is here: <https://github.com/vincent-peugnet/wcms>

It's just HTML.

## publishing

When browsing website folder in the terminal.

    rsync -e ssh -avz --exclude=".*"  . vincent@club1.fr:/home/vincent/web/wcms/

(this won't delete removed files)
