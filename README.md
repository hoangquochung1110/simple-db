## How to run
Executable should be stored in `build` directory
To run it:
```shell
./build/main <path_to_db>
````

To select data:
```shell
db > select
```

To insert data:
```shell
db > insert 1 foo foo@bar.com
```

To run tests:
```shell
bundle exec rspec
```


### Part 6:
We provide **Cursor** abstraction layer which help `execute_select` and `execute_insert` can interact with the table entirely through the cursor without assuming anything about how the table is stored.
