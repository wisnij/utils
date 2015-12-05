These scripts intended to be managed by [vcsh](https://github.com/RichiH/vcsh). To set up on a new system:

```bash
# common settings
vcsh clone -b common https://github.com/wisnij/utils.git utils

# system-specific settings (optional)
vcsh clone -b cygwin https://github.com/wisnij/utils.git utils-cygwin
vcsh clone -b linux  https://github.com/wisnij/utils.git utils-linux
vcsh clone -b osx    https://github.com/wisnij/utils.git utils-osx
# ...
```
