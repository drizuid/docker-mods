# kepubify - Docker mod for calibre-web

This mod adds kepubify to calibre-web, to be installed/updated during container start.

In calibre-web docker arguments, set an environment variable `DOCKER_MODS=linuxserver/mods:calibre-web-kepubify`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=linuxserver/mods:calibre-web-kepubify|linuxserver/mods:calibre-web-mod2`
