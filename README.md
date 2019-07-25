# TAG
Bash script to tag repository with incremented version

Defines last repository tag version and creates new annotated tag with incremented version

## Usage

```bash
tag "Tag message here"
```

Output:

```bash
Tagging repo
Checked out master branch
Pulled origin
Last version is 0 3 30
Tagging version v0.3.31
Counting objects: 1, done.
Writing objects: 100% (1/1), 178 bytes | 0 bytes/s, done.
Total 1 (delta 0), reused 0 (delta 0)
To git@github.com:90poe/audit-reports-client-api.git
 * [new tag]         v0.3.31 -> v0.3.31
```

## Installation

```bash
wget https://github.com/Andreeey/tag/blob/master/tag
chmod +x tag
mv tag /usr/local/bin/
```
