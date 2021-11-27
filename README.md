# Tri

Tri is a CLI app from the workshop of Steve Francia
https://spf13.com/presentation/building-an-awesome-cli-app-in-go-oscon/.

It works as a TODO app designed to be simple and help you accomplish your goals. Currently supported features include adding todos, marking them as done, and finally listing your todos.

## Usage

> tri [command] [options]

### commands

`list` List your todos.

`add` Add a new todo.

`done` Mark a todo as done.

### options

`--all` Show all items.

`--done` Show only items marked as 'Done'.

`--priority` Set priority to the item you are adding. Priority:1,2,3. (default 2)

`--config` Set configurationn file.

`--datafile` Set data file to store items.
