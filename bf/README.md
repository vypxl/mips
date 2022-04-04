# Brainfuck Interpreter in MIPS assembly

As the name says, this program can interpret Brainfuck programs.

To run a bf program:
  1. Put its source into `programs/<name>.bf`
  2. Remove all line breaks and quotes `"`
  3. Surround the whole source with quotes `"`.
  4. Change the `.include` directive at the top of `bf.mips` to include your file.
  5. Assemble and run the MIPS program in MARS.

Steps 2 and 3 are necessary so that MARS can include the file, it's not a limitation of the interpreter.

