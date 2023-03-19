### ARG
1. ARG is used to supply few variables at the IMAGE Creation.
 docker build -t arg:v1 --build-arg VERSION=9 .
 2. ARG is the only instruction you can use before FROM. ARG declared before(ie.FROM) cant be accessed after FROM instruction.
