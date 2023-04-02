# Google Chrome Stable
	"https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb"
# Steam Client
	"https://store.steampowered.com/about/"
# Waydroid
	apt install curl ca-certificates -y
	curl https://repo.waydro.id | bash
# Spotify-Client
	curl -sS https://download.spotify.com/debian/pubkey_7A3A762FAFD4A51F.gpg | gpg --dearmor --yes -o /etc/apt/trusted.gpg.d/spotify.gpg
	echo "deb http://repository.spotify.com stable non-free" | tee /etc/apt/sources.list.d/spotify.list
