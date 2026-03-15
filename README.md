Created a small version of grep in Rust.
Looks for a particular word in a poem.txt file and saves the output lines in a file called output.txt.
To access it, clone the repository, install cargo package and run cargo run -- {the word you are looking for} poem.txt.
Example usage: cargo run -- was poem.txt.
If you want to see it case independently, use the flag IGNORE_CASE=1 at start of the command.
example: IGNORE_CASE=1 cargo run -- was poem.txt
