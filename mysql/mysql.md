# Show Processlist
Sometimes you'll notice performance issues with your database. One of the first things I do is check which queries are running.

```
show full processlist

```

This shows you which threads are running along with other useful information such as who is running the process, the hostname of the client running the query, the running query itself and how long the query has been in it's current state.

```
kill ${id}
```

Where id is the id of process listed from the `show full processlist` command.
