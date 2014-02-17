# bash-boilerplate

This is a ridiculously simple boilerplate for creating bash scripts with tests. An example is provided.

## Usage

   1. Clone it into your project directory.
   2. Put the name of your script in the `./tests/run` file.
   3. Add `.test` files into the `tests` directory.
      - Inside these files you can `source "$MAIN"`
   4. Use `assert` to test your scripts functions and variables.
   5. Make the `./tests/run` file executable.
   6. Use `./tests/run` to run your tests.
