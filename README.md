# boltdbweb

A simple web based boltdb GUI Admin panel.


##### Installation

MacOS (and ubuntu supported) installation via Brew:

```bash
brew tap isan-rivkin/toolbox
brew install boltdbweb
```

Alternative, Download binary from [releases](https://github.com/Isan-Rivkin/boltdbweb/releases).


##### Usage
```
boltdbweb --db-name=<DBfilename>[required] --port=<port>[optional]
```
- `--db-name:` The file name of the DB.
    - NOTE: If 'file.db' does not exist. it will be created as a BoltDB file.
- `--port:` Port for listening on... (Default: 8080)


##### Example
```
boltdbweb --db-name=test.db --port=8089
```
Goto: http://localhost:8089

##### Screenshots:

![](https://github.com/isan-rivkin/boltdbweb/blob/main/screenshots/1.png?raw=true)

![](https://github.com/isan-rivkin/boltdbweb/blob/main/screenshots/2.png?raw=true)

![](https://github.com/isan-rivkin/boltdbweb/blob/main/screenshots/3.png?raw=true)
