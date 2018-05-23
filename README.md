# Useful Terminal Hacks


Some small tips and tricks to make the most out of the terminal and to get work done faster.

## General purpose

+	**Write output of a program to a file. `>` to redirect output to file and `>>` to append output to file.**

```

$	./a.out > file.txt

$	./a.out >> file.txt

```

+	**Share a folder on your local network.**

```

$	python -m SimpleHTTPServer 8000

```

Above command will host the HTTP server on port 8000 (you can change the port number if you want). To access the folder, go to `http://your_ip_address:8000`.


## Resources

+	[https://www.learnenough.com/command-line-tutorial](https://www.learnenough.com/command-line-tutorial)

