# bashbase

bashbase (`db`) is a plaintext file database that runs in the bash shell. Each user will have their own database created automatically.

![maintainer](https://img.shields.io/badge/Maintainer-Akhil%20Pillai-lightgrey) ![release](https://img.shields.io/badge/release-v2.1.0-informational)

---

## Downloads

[![debianv2.1.0](https://img.shields.io/badge/Debian-v2.1.0-blue)](downloads/bashbase_2.1.0.deb)

[![shv2.1.0](https://img.shields.io/badge/Other-v2.1.0-blue)](downloads/bashbase_v2.1.0.zip)

---

## Setup

- Download the latest version. If using Debian or derivatives (i.e. Ubuntu) then download the `.deb` file. All other UNIX-based OS users (including MacOS): Download the `.zip` file.
- Debian users: Run `sudo dpkg -i <package-file> ; rm <package-file>`. All other UNIX-based OS users (including MacOS): Extract the zip archive's contents. There will be a file called `db`. Run `chmod 755 /path/to/db` in Terminal, then copy the file to `/usr/bin/` by executing `cp /path/to/db /usr/bin/db`.
- All you need to do is run `db` in your shell to set up the script.

---

## Usage

- `db` - Lists all the entries in the database.
- `db /help` - Displays the help menu.
- `db /find <search-term>` - Searches for `<search-term>` in the database.
- `db /new <key> <value>` - Creates a new set.
- `db /remove <line-number>` - Removes the entry on line number `<line-number>`.
- `db /clear` - Clears the database file. Asks for confirmation before clearing.
