Create a sample file first: `echo "hello world" > input.txt`

Execute command:
`docker run --rm   -v $(pwd):/data   alpine sh -c "cat /data/input.txt | tr a-z A-Z > /data/output.txt"`
