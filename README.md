# GoDB — Lightweight JSON File Database in Go

GoDB is a lightweight, file-based database written in Go.
It allows you to store, read, update, and delete records using simple JSON files, without requiring any external database.

**This project is ideal for:**
* Small local applications
* Configuration storage
* Simple CLI tools
* Learning Go’s file I/O, mutexes, and JSON marshalling

## Features

- Store records as formatted .json files
- Read single records or entire collections
- Delete files or folders
- Thread-safe using sync.Mutex per collection
- Automatic directory creation
- Pluggable logger interface
- Zero external database required


## Getting Started

Clone the repository

```bash
  git clone https://github.com/sanidhyajaiswal/goDB.git
  cd goDB
```

Run the project

```bash
  go run main.go
```
## Future Improvements


- Add an Update method
- Add indexing support
- Add TTL (time-to-live) support
- Add CLI tool for browsing the DB
- Add backup & restore
- Add JSON schema validation
