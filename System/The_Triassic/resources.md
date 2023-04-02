# Google Chrome Stable
	"https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb"
# Steam Client
	"https://store.steampowered.com/about/"
# Waydroid
	apt install curl ca-certificates -y
	curl https://repo.waydro.id | bash
# Spotify-Client
	wget -O- https://download.spotify.com/debian/pubkey.gpg | apt-key add -
	add-apt-repository "deb http://repository.spotify.com stable non-free"