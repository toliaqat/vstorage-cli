# VStorage Viewer

This is a terminal-based application for traversing a tree-like structure of data from the Agoric VStorage API. The application displays the data in a series of columns and provides navigation using arrow keys. Additionally, it includes a data panel for displaying detailed JSON data.

<img width="1718" alt="Screenshot 2024-06-10 at 8 53 07 PM" src="https://github.com/toliaqat/vstorage-cli/assets/6778940/4a93fc96-886e-4c2f-85d7-6ed7b2159558">

## Features

- Traverse a tree-like structure of data from the Agoric VStorage API.
- Display children nodes in a series of columns.
- Navigate between columns using left and right arrow keys.
- Get decoded data from the selected node.

## Install dependencies
This project uses Go modules. Ensure you have Go installed and then run:

```shell
go mod tidy
```

## Usage

Run the application:

```shell
go run main.go
```
