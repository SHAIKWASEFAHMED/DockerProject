### ENTRYPOINT
ENTRYPOINT is also used to run the container just like CMD. But there are few differences.
1. WE Cant override ENTRYPOINT , But we can override CMD.
2. We cant override ENTRYPOINT, if we try to do so it will go and append to the ENTRYPOINT Command.