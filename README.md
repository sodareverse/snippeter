# snippeter
# Open-source program made in python and a self-made program for generating and parsing Lua API snippets.

<h3 align="center">Lua API snippet generator and parser</h3>
</p>

    * [Install](#installing)

    ### Prerequisites

First of all you need to install:

* python3

```sh
sudo apt-get install python3-pip
```

### Installing snippeter

1. Clone the repo

```sh
git clone https://github.com/sodareverse/snippeter.git --recursive
```

2. Open cloned repo

```sh
cd snippeter
```

3. Install python libraries

```sh
sudo pip3 install -r requirements.txt
```

4. Enter your repo owner and repo name of documentation to config.json

## Usage

1. Exit from project folder

```sh
cd ../
```

2. Run python project

```sh
python3 -m snippeter
```

3. Check out output.json

```sh
cd snippeter
cat output.json | tail
```
