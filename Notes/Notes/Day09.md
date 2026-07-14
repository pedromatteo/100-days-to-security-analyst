# Notes - Linux File System & Commands

## Useful Commands

pwd
Shows the current working directory.

ls
Lists files and directories.

cd
Changes the current directory.

mkdir
Creates directories.

touch
Creates empty files or updates their timestamp.

cp
Copies files.

mv
Moves or renames files.

rm
Removes files.

cat
Displays the entire contents of a file.

less
Opens a file page by page.

whoami
Shows the current logged-in user.

id
Displays user and group identifiers.

## Important Concepts

Absolute Path
Starts from the root directory (/).

Relative Path
Starts from the current directory.

cp vs mv

cp → creates a copy.

mv → moves or renames files.

## Investigation Notes

A typical HTTP connection follows this sequence:

```text
DNS
    ↓
TCP Three-Way Handshake
    ↓
HTTP GET
    ↓
HTTP 200 OK
    ↓
FIN / ACK
```

Key observations:

- TCP establishes the connection before HTTP.
- HTTP depends on TCP.
- The Ethernet Frame carries MAC addresses.
- The IP Packet carries IP addresses.
- ACK confirms received data.
- PSH delivers application data immediately.