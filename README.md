# Go Task 👍

Simple taks list manager CLI written in Go with cobra and BoltDB. All tasks are stored in a boltDB file in the users home directory called `tasks.db`.

## 👉 Getting Started

Clone the repository:

```sh
git clone "https://github.com/lukeomalley/go-task.git" && cd go-task
```

Install the binary

```sh
go install .
```

## 🤘 Usage

Go Task has a simple interface with three commands: `add`, `ls`, and `do`.

### Add a task:

```sh
> go-task add walk the dog

Added "walk the dog" to your task list.
```

### List all tasks:

```
> go-task ls

You have the following tasks:
  1. walk the dog 🦮
```

### Complete the first task in your list

```sh
> go-task do 1

Marked "1" as complete.
```

### Complete the first three tasks

```sh
> go-task do 1 2 3

Marked "1" as complete.
Marked "2" as complete.
Marked "3" as complete.
```
