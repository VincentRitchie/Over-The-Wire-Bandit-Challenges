# OVERTHEWIRE (OTW) - BANDIT CHALLENGES 
#### Level 1 - 10

## Levels Contents

- [Level 1](#level1)
- [Level 2](#level2)
- [Level 3](#level3)
- [Level 4](#level4)
- [Level 5](#level5)
- [Level 6](#level6)
- [Level 7](#level7)
- [Level 8](#level8)
- [Level 9](#level9)
- [Level 10](#level10)

## Level 1
<a>
  <img src="https://overthewire.org/wargames/bandit/bandit.png" alt="Bandit Logo" width="650" />
</a>

## Level 1 Table of Contents
- [Description](#description)
- [Pseudocode](#pseudocode)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshot](#screenshot)

### Description
In Level 1 of the OverTheWire Bandit challenge, you need to connect to the Bandit server and access the `readme` file in the current directory to retrieve the password for the next level.

### Pseudocode
```
1. Open the terminal.
2. Use SSH to connect to the Bandit server:
   ```
   ssh bandit1@bandit.labs.overthewire.org -p 2220
   ```
3. Enter the password: `bandit0`.
4. Once connected, locate the file named `readme` in the home directory.
5. Use the `cat` command to display the contents of the `readme` file:
   ```
   cat readme
   ```
6. The contents of the file will display the password for the next level.
7. Record the password for use in the next level.
```

### Features
- **Basic SSH Connection:** Learn to establish an SSH connection to a remote server.
- **File Exploration:** Locate and read files within a Unix-like environment.

### Installation
To begin the challenge, ensure you have a terminal with SSH capabilities:
```sh
ssh bandit1@bandit.labs.overthewire.org -p 2220
```

### Usage
Follow the steps in the pseudocode to connect to the Bandit server and retrieve the password for the next level.

### Screenshot
<a>
  <img src="https://overthewire.org/wargames/bandit/bandit.png" alt="Bandit Logo" width="650" />
</a>

## Level 2

<a>
  <img src="https://overthewire.org/wargames/bandit/bandit.png" alt="Bandit Logo" width="650" />
</a>

## Level 2 Table of Contents
- [Description](#description)
- [Pseudocode](#pseudocode)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshot](#screenshot)

### Description
In Level 2, you will encounter a file with a name starting with a dash (`-`). You need to use appropriate methods to read this file.

### Pseudocode
```
1. Open the terminal.
2. Use SSH to connect to the Bandit server:
   ```
   ssh bandit2@bandit.labs.overthewire.org -p 2220
   ```
3. Enter the password: `<password_from_level_1>`.
4. Once connected, list files to locate the file starting with `-`:
   ```
   ls
   ```
5. Use the `cat` command to read the file:
   ```
   cat ./-
   ```
6. Record the password displayed for the next level.
```

### Features
- **Handling Special Filenames:** Learn to deal with filenames that start with a dash.
- **Command Line Techniques:** Use command-line options to handle tricky filenames.

### Installation
To begin the challenge, ensure you have a terminal with SSH capabilities:
```sh
ssh bandit2@bandit.labs.overthewire.org -p 2220
```

### Usage
Follow the steps in the pseudocode to connect to the Bandit server and retrieve the password for the next level.

### Screenshot
<a>
  <img src="https://overthewire.org/wargames/bandit/bandit.png" alt="Bandit Logo" width="650" />
</a>

## Level 3

<a>
  <img src="https://overthewire.org/wargames/bandit/bandit.png" alt="Bandit Logo" width="650" />
</a>

## Table of Contents
- [Description](#description)
- [Pseudocode](#pseudocode)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshot](#screenshot)

### Description
In Level 3, access a file with spaces in its name.

### Pseudocode
```
1. Open the terminal.
2. Use SSH to connect to the Bandit server:
   ```
   ssh bandit3@bandit.labs.overthewire.org -p 2220
   ```
3. Enter the password: `<password_from_level_2>`.
4. Once connected, list files to locate the file with spaces:
   ```
   ls
   ```
5. Use the `cat` command with escape characters to read the file:
   ```
   cat ./spaces\ in\ this\ filename
   ```
6. Record the password displayed for the next level.
```

### Features
- **Handling Spaces in Filenames:** Learn to handle filenames with spaces.
- **File Access:** Techniques to access and read files with special characters in their names.

### Installation
To begin the challenge, ensure you have a terminal with SSH capabilities:
```sh
ssh bandit3@bandit.labs.overthewire.org -p 2220
```

### Usage
Follow the steps in the pseudocode to connect to the Bandit server and retrieve the password for the next level.

### Screenshot
<a>
  <img src="https://overthewire.org/wargames/bandit/bandit.png" alt="Bandit Logo" width="650" />
</a>

