# dirscan

A tool to scan directories in a web server using a dictionary file.



## Contents
- [Supported OS](#supported-os)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Available options](#available-options)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)



## Supported OS
- GNU/Linux
- Windows
- macOS



## Prerequisites
- [Python3](https://www.python.org/downloads/)



## Installation
**1. Clone this repo:**
```
git clone https://github.com/the-weird-aquarian/dirscan.git
```

**2. Move into the project directory:**
```
cd dirscan
```

**3. Give executable permissions to the script (Not required for Windows):**
```
chmod +x dirscan
```



## Available options:
```
-h, --help              Show this help message and exit
-u, --url               URLs
-l, --list              Path to file with directories lists
```



## Usage
```
python3 dirscan -u <URLs>
```

A custom directories list can be set using:
```
python3 dirscan -u <URLs> -l <directories list>
```

**Examples:**
```
python3 dirscan -u google.com
```

```
python3 dirscan -u google.com github.com
```

```
python3 dirscan -u google.com 192.168.1.9 -l /home/user/Desktop/common_dir.txt
```



## Contributing
Pull requests can be submitted [here](https://github.com/the-weird-aquarian/dirscan/pulls). Any contribution to the project will be highly appreciated.



## License
This project is licensed under the terms of [GPLv3.0 license](https://github.com/the-weird-aquarian/dirscan/blob/main/LICENSE)