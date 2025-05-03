** About this project **

This project comes from the Command Line Tutorial for Rust and is named cli_grrs_rust_sample. The tool is used to parse through files and figure out if a certain pattern exists in that file, then prints out the lines where the pattern is located, if at all. The tool contains error handling for if a file doesn't exist or the buffer is overloaded and contains tests for empty strings, if the file doesn't exist, and testing if the file content is properly printed out. Future tests will include seeing what happens if a pattern doesn't exist in a file.

** How to Use **

The program takes in 2 arguments - the pattern and the file. You use it with cargo run with -- and the 2 arguments as follows:

```
cargo run -- <PATTERN> <PATH>
```

PATTERN represents the pattern you wish to look for in the file. PATH represents the path of the file you wish to look for the pattern within.

