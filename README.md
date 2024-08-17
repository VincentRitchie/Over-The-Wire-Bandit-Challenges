# OVERTHEWIRE (OTW) - BANDIT CHALLENGES 
#### Level 1 - 10

## Levels Contents

- [Level-1](#level-1)
- [Level-2](#level-2)
- [Level-3](#level-3)
- [Level-4](#level-4)
- [Level-5](#level-5)
- [Level-6](#level-6)
- [Level-7](#level-7)
- [Level-8](#level-8)
- [Level-9](#level-9)
- [Level-10](#level-10)

## Level 1
<a>
  <img src="https://github.com/VincentRitchie/VincentRitchie/blob/main/OTW-Bandit%20Level%201.jpeg" width="500" />
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

### Level 1 Screenshot
<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/Bandit%20Level%201.png" alt="Bandit Logo" width="650" />
</a>
<br>
<br>
<br>
## Level 2

<a>
  <img src="https://github.com/VincentRitchie/VincentRitchie/blob/main/OTW-Bandit%20Level%202.jpeg" alt="Bandit Logo" width="500" />
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

### Level 2 Screenshot

<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/Bandit%20Level%202.png" alt="Bandit Logo" width="650" />
</a>

<br>
<br>
<br>

## Level 3

<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/OTW%20-%20banditcover.png" alt="Bandit Logo" height="350" width="650" />
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

### Level 3 Screenshot

<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/OTW%20-%20Bandit%20Level%203.png" alt="Bandit Logo" width="650" />
</a>

<br>
<br>
<br>

## Level 4

<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/OTW%20-%20banditcover.png" alt="Bandit Logo" height="350" width="650" />
</a>

## Level 4 Table of Contents
- [Description](#description)
- [Pseudocode](#pseudocode)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshot](#screenshot)

### Description
In Level 4, you will find a hidden file in the `inhere` directory that contains the password for the next level.

### Pseudocode
```
1. Open the terminal.
2. Use SSH to connect to the Bandit server:
   ```
   ssh bandit4@bandit.labs.overthewire.org -p 2220
   ```
3. Enter the password: `<password_from_level_3>`.
4. Navigate to the `inhere` directory.
5. Use the `ls -a` command to list all files, including hidden ones.
6. Use the `cat` command to read the hidden file and retrieve the password.
7. Record the password for the next level.
```

### Features
- **Hidden Files:** Learn to locate and interact with hidden files in a Unix-like environment.
- **File Exploration:** Explore directories and identify key files.

### Installation
To begin the challenge, ensure you have a terminal with SSH capabilities:
```sh
ssh bandit4@bandit.labs.overthewire.org -p 2220
```

### Usage
Follow the steps in the pseudocode to connect to the Bandit server and retrieve the password for the next level.

### Level 4 Screenshot

<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/OTW%20-%20Bandit%20Level%204.png" alt="Bandit Logo" width="650" />
</a>

<br>
<br>
<br>

## Level 5
<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/OTW%20-%20banditcover.png" alt="Bandit Logo" height="350" width="650" />
</a>

## Level 5 Table of Contents
- [Description](#description)
- [Pseudocode](#pseudocode)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshot](#screenshot)

### Description
In Level 5, the password for the next level is stored in a file that is human-readable, 1033 bytes in size, and not executable.

### Pseudocode
```
1. Open the terminal.
2. Use SSH to connect to the Bandit server:
   ```
   ssh bandit5@bandit.labs.overthewire.org -p 2220
   ```
3. Enter the password: `<password_from_level_4>`.
4. Navigate to the `inhere` directory.
5. Use the `find` command to locate the file:
   ```
   find . -type f -size 1033c ! -executable
   ```
6. Use the `cat` command to read the file and retrieve the password.
7. Record the password for the next level.
```

### Features
- **File Search:** Learn to use the `find` command to search for files based on specific attributes.
- **Command Line Techniques:** Use various command-line options to locate and read files.

### Installation
To begin the challenge, ensure you have a terminal with SSH capabilities:
```sh
ssh bandit5@bandit.labs.overthewire.org -p 2220
```

### Usage
Follow the steps in the pseudocode to connect to the Bandit server and retrieve the password for the next level.

### Level 5 Screenshot
<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/OTW%20-%20Bandit%20Level%205.png" alt="Bandit Logo" width="650" />
</a>

<br>
<br>
<br>

## Level 6

<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/OTW%20-%20banditcover.png" alt="Bandit Logo" height="350" width="650" />
</a>

## Level 6 Table of Contents
- [Description](#description)
- [Pseudocode](#pseudocode)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshot](#screenshot)

### Description
In Level 6, the password for the next level is stored somewhere on the server and has all of the following properties: owned by user `bandit7`, owned by group `bandit6`, and 33 bytes in size.

### Pseudocode
```
1. Open the terminal.
2. Use SSH to connect to the Bandit server:
   ```
   ssh bandit6@bandit.labs.overthewire.org -p 2220
   ```
3. Enter the password: `<password_from_level_5>`.
4. Use the `find` command to locate the file:
   ```
   find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
   ```
5. Use the `cat` command to read the file and retrieve the password.
6. Record the password for the next level.
```

### Features
- **Advanced File Search:** Learn to use `find` with multiple parameters.
- **Command Line Techniques:** Improve your ability to search and manage files on a remote server.

### Installation
To begin the challenge, ensure you have a terminal with SSH capabilities:
```sh
ssh bandit6@bandit.labs.overthewire.org -p 2220
```

### Usage
Follow the steps in the pseudocode to connect to the Bandit server and retrieve the password for the next level.

### Level 6 Screenshot

<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/OTW%20-%20Bandit%20Level%206.png" alt="Bandit Logo" width="650" />
</a>

<br>
<br>
<br>
## Level 7

<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/OTW%20-%20banditcover.png" alt="Bandit Logo" height="350" width="650" />
</a>

## Level 7 Table of Contents
- [Description](#description)
- [Pseudocode](#pseudocode)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshot](#screenshot)

### Description
In Level 7, the password for the next level is located within a file that has been compressed multiple times. You will need to decompress it to retrieve the password.

### Pseudocode
```
1. Open the terminal.
2. Use SSH to connect to the Bandit server:
   ```
   ssh bandit7@bandit.labs.overthewire.org -p 2220
   ```
3. Enter the password: `<password_from_level_6>`.
4. Use the `ls` command to identify the compressed file.
5. Use the appropriate `gzip`, `bzip2`, and `tar` commands to decompress the file multiple times.
6. Use the `cat` command to read the final decompressed file and retrieve the password.
7. Record the password for the next level.
```

### Features
- **File Compression:** Learn to decompress files using multiple tools.
- **Command Line Techniques:** Enhance your skills in handling compressed files.

### Installation
To begin the challenge, ensure you have a terminal with SSH capabilities:
```sh
ssh bandit7@bandit.labs.overthewire.org -p 2220
```

### Usage
Follow the steps in the pseudocode to connect to the Bandit server and retrieve the password for the next level.

### Level 7 Screenshot

<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/OTW%20-%20Bandit%20Level%207.png" alt="Bandit Logo" width="650" />
</a>

<br>
<br>
<br>

## Level 8

<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/OTW%20-%20banditcover.png" alt="Bandit Logo" height="350" width="650" />
</a>

## Level 8 Table of Contents
- [Description](#description)
- [Pseudocode](#pseudocode)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshot](#screenshot)

### Description
In Level 8, the password for the next level is stored in a file, and it is the only line of text that occurs only once in the file.

### Pseudocode
```
1. Open the terminal.
2. Use SSH to connect to the Bandit server:
   ```
   ssh bandit8@bandit.labs.overthewire.org -p 2220
   ```
3. Enter the password: `<password_from_level_7>`.
4. Use the `ls` command to identify the file containing the password.
5. Use the `sort` and `uniq -u` commands to find the unique line of text.
   ```
   sort <filename> | uniq -u
   ```
6. Record the password displayed for the next level.
```

### Features
- **Text Processing:** Learn to use `sort` and `uniq` commands to process text files.
- **Command Line Techniques:** Practice identifying unique lines in large files.

### Installation
To begin the challenge, ensure you have a terminal with SSH capabilities:
```sh
ssh bandit8@bandit.labs.overthewire.org -p 2220
```

### Usage
Follow the steps in the pseudocode to connect to the Bandit server and retrieve the password for the next level.

### Level 8 Screenshot
<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/OTW-Bandit%20Level%208.png" alt="Bandit Logo" width="650" />
</a>

<br>
<br>
<br>

## Level 9

<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/OTW%20-%20banditcover.png" alt="Bandit Logo" height="350" width="650" />
</a>

## Level 9 Table of Contents
- [Description](#description)
- [Pseudocode](#pseudocode)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshot](#screenshot)

### Description
In Level 9, the password for the next level is stored in a file in a directory. The file is a binary file, and you need to use specific tools to find the password.

### Pseudocode
```
1. Open the terminal.
2. Use SSH to connect to the Bandit server:
   ```
   ssh bandit9@bandit.labs.overthewire.org -p 2220
   ```
3. Enter the password: `<password_from_level_8>`.
4. Use the `ls` command to locate the directory containing the file.
5. Use the `strings` command to extract human-readable text from the binary file.
   ```
   strings <filename>
   ```
6. Look for the password within the output and record it for the next level.
```

### Features
- **Binary File Analysis:** Learn to extract text from binary files using the `strings` command.
- **Command Line Techniques:** Develop skills in analyzing non-text files on Unix-like systems.

### Installation
To begin the challenge, ensure you have a terminal with SSH capabilities:
```sh
ssh bandit9@bandit.labs.overthewire.org -p 2220
```

### Usage
Follow the steps in the pseudocode to connect to the Bandit server and retrieve the password for the next level.

### Level 9 Screenshot

<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/OTW%20-%20Bandit%20Level%209.png" alt="Bandit Logo" width="650" />
</a>

<br>
<br>
<br>

## Level 10

<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/OTW%20-%20banditcover.png" alt="Bandit Logo" height="350" width="650" />
</a>

## Level 10 Table of Contents
- [Description](#description)
- [Pseudocode](#pseudocode)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshot](#screenshot)

### Description
In Level 10, the password for the next level is stored in a file that has been encoded using base64. You need to decode the file to retrieve the password.

### Pseudocode
```
1. Open the terminal.
2. Use SSH to connect to the Bandit server:
   ```
   ssh bandit10@bandit.labs.overthewire.org -p 2220
   ```
3. Enter the password: `<password_from_level_9>`.
4. Use the `ls` command to identify the encoded file.
5. Use the `base64` command to decode the file.
   ```
   base64 -d <filename>
   ```
6. Record the password displayed for the next level.
```

### Features
- **Encoding and Decoding:** Learn to decode files that have been encoded using base64.
- **Command Line Techniques:** Practice working with encoded data on a remote server.

### Installation
To begin the challenge, ensure you have a terminal with SSH capabilities:
```sh
ssh bandit10@bandit.labs.overthewire.org -p 2220
```

### Usage
Follow the steps in the pseudocode to connect to the Bandit server and retrieve the password for the next level.

### Level 10 Screenshot

<a>
  <img src="https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-1-10/blob/main/OTW%20-%20Bandit%20Level%2010.png" alt="Bandit Logo" width="650" />
</a>

<br>
<br>
<br>

![Level 11 - Level 20](https://github.com/VincentRitchie/Over-The-Wire-Bandit-Challenges-Level-11-20/blob/main/README.md)
##### Continued...
