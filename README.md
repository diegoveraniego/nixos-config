Device: HP Envy x360 ag000x

This is a config i tried when learning NixOS. The main problems that i encountered were:
- Emacs kept rebuliding when running `nixos-rebuild switch` this messed with Doom Emacs dependencies, so i had to run `doom sync` everytime.
- Bash config also kept deleting itself. I understand this is how Nix works, so i had to declare PATH in config
- Git config did that too. TODO Set user, mail, and key location inside `configuration.nix` while mantaining secrets (mail) when pushed to github.
- Game performance had stuttering. While games ran well, there was some screen tearing i did not know how to fix (yet). I come from using CachyOS and my pc is very low-end so i noticed the slight performance difference.

