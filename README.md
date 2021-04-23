# zsh_configuration

## Prerequisite
- Install zsh and zplug
	- zsh
		```
		apt install zsh
		```
	- zplug 
		```
		curl -sL --proto-redir -all,https https://raw.githubusercontent.com/zplug/installer/master/installer.zsh | zsh
		```

- grc

	```
	apt install grc
	```

- exa
	- Install by apt (Ubuntu 20.10 up)

		```
		apt install exa
		```

	- Install manually (https://the.exa.website/install/linux#manual) (Remember to `chown` and `chmod`)

- marlonrichert/zsh-autocomplete, In $HOME,

	```
	git clone https://github.com/marlonrichert/zsh-autocomplete.git
	```

- Nerd Fonts for Powerlevel 10k
	1. Download the `Hack.zip` from (https://github.com/ryanoasis/nerd-fonts/releases).
	2. Install the `Mono Windows` one. (at cilent)
	3. Set the font based on your terminal tutorial. (https://github.com/romkatv/powerlevel10k/blob/master/README.md#fonts)

- Config files

	- Put `.p10k.zsh`, `.zshrc`, and `.zprofile` in your home directory.
	- note that 

## Test everything is fine

```exec zsh```

If everything is alright, change your default shell.

```chsh -s $(which zsh)```

## Reload
Everytime you make a change to `.zshrc` or `.zprofile`, use `exec zsh` to reload and make it works.
