![katoolin](https://cloud.githubusercontent.com/assets/8742190/9415562/83397aae-4840-11e5-8f72-28dfffcc70a9.png)
# katoolin v3.0
Automatically install all Kali linux tools

v3.0 is a Python 3 remake of the original [LionSec/katoolin](https://github.com/LionSec/katoolin), maintained by IamPhasm.

# Features
- Add Kali linux repositories
- Remove kali linux repositories
- Install Kali linux tools

# Requirements
- Python 3
- wget and gpg (used to fetch the Kali repository key)
- A Debian-based operating system with apt (tested on Ubuntu)

# Installation
- sudo su
- git clone https://github.com/IamPhasm/katoolin.git && cp katoolin/katoolin.py /usr/bin/katoolin
- chmod +x /usr/bin/katoolin
- sudo katoolin 

# What's new in v3.0
- Runs on Python 3 (Python 2 is no longer supported)
- Kali repository is added as its own file, `/etc/apt/sources.list.d/katoolin.list`, instead of editing `/etc/apt/sources.list`
- No more deprecated `apt-key`: the Kali archive key is stored in `/usr/share/keyrings/kali-archive-keyring.gpg` and the repo uses `signed-by`
- Removing the repositories also cleans up entries written by older versions
- Option 4 in the repository menu shows both `sources.list` and the Katoolin list
- Repository line now includes `non-free-firmware`

# Video
https://www.youtube.com/watch?v=8VxCWVoZEEE

# Usage
- Typing the number of a tool will install it
- Typing 0 will install all Kali Linux tools
- back : Go back
- gohome : Go to the main menu
- By installing armitage , you will install metasploit

# Warning
Before updating your system , please remove all Kali-linux repositories to avoid any kind of problem .

# I have some questions!

Please visit https://github.com/IamPhasm/katoolin/issues (v3.0) or the original project at https://github.com/LionSec/katoolin/issues

# Credits
- Original project: LionSec (https://github.com/LionSec/katoolin)
- v3.0 remake: IamPhasm

# Original author's contact
- Website : https://neodrix.com
- Youtube : https://youtube.com/inf98es
- Facebook : https://facebook.com/in98
- Twitter: @LionSec1
- Email : informatica98es@gmail.com
