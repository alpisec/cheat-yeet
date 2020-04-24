# Cheat-yeet

## tcpdump

Sniff data and cut it every 10 MB. Also output it to a testfile AND append a digit after that. The -i stands for the interface.
`tcpdump -i ens192 -C 10m -w TESTFILE`

Output should look like this:
> root@somemachine:/tmp# ls -lah
> -rw-r--r--  1 root root 9.6M Apr 24 06:54 TESTFILE
> -rw-r--r--  1 root root 9.6M Apr 24 06:54 TESTFILE1
> -rw-r--r--  1 root root 9.6M Apr 24 06:54 TESTFILE2
> -rw-r--r--  1 root root 9.3M Apr 24 06:54 TESTFILE3

you get the idea.

