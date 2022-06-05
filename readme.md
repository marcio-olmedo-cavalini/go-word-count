# Word Count Application
Simple project that implements a CLI Application developed em Go, during my learning process

##Features
1) Word Count
2) Line Count
3) Byte Count

##How to execute
1) Clone the project
2) There are 3 options to execute (STOP Condition is Ctrl+C command):
    2.1) Word Count: Executed without arguments
    ```
    go run main.go
    ```
    2.2) Line Count: Executed with -l parameter
    ```
    go run main.go -l
    ```
    2.3) Byte Count: Executed with -b parameter
    ```
    go run main.go -b
    ```
3) It's possible to validate the functionalities executing the test class:
```
go test -v
```