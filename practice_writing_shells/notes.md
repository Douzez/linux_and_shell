# Shell scripts

Do these three things to successfully write a shell script:

1. Write a script.
2. Give the shell permission to execute it.
3. Put it somewhere the shell can find it.

```shell
#!/bin/bash
# This is called a shebang, indicates what program is used to interpret the script.

echo "Hello, World!"

$ chmod 755 hello_world.sh
$./hello_world.sh
```

"755" gives you read, write, and execute permission. Everybody else will get only read and execute permission.
"700" script will be private for you (rwx).


