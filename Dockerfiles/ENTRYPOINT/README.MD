### ENTRYPOINT
ENTRYPOINT is also used to run the container just like CMD. But there are few differences.
1. WE Cant override ENTRYPOINT , But we can override CMD.
2. We cant override ENTRYPOINT, if we try to do so it will go and append to the ENTRYPOINT Command..
3. If you use CMD and ENTRYPOINT and dont give any command from terminal, CMD acts as argument provider.
4. CMD will supply default arguments to the ENTRYPOINT. 
5. You can always override CMD ARGuments from RUNTIME.