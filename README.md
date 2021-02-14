# SBE-HelloWorld-elixir
Simple examples for SBOM by Example

## One liner

This is not an elixir tutorial,
but will cover some very basic elixir
for the purpose of understanding the SBOM.

The simplest "hello world" is to run a
command inside the elixir interpreter:

![command 1](./images/iex1.png)

Recall that the output for any elixir
program is the return value of
last statement.
So if you typing in a text string,
returns the text string.

In a program the statement to output
a string would be IO.put().
Note IO prints the output
and then the interpreter prints the
return value for the statement
(ie "ok" since the print was successful).

![command 2](./images/iex2.png)

hello.ex is a program

put code block here with link to file

that could be run from the command line
either by running the elixir command:

![command 3](./images/hello1.png)


or by including the run-time libraries
(see next section).

Release 1.0.0-SingleLine (add link) contains:
- a source bundle (hello.ex)
- .beam file (executable by an already running BEAM VM)
- SBOMs in various formats

## Stand alone executable - 1 hop

blah blah

Release 2.0.0-ExecOneHop (add link) contains:
- a source bundle (hello.ex)
- an executable file
   - for this demo, just one target machine - macos
   - TBD add in Nerves executable
- SBOMs in various formats for first hop of executable

## Stand alone executable - N hop

blah blah

Release 3.0-ExecFull (add link) contains:
- a source bundle (hello.ex)
- an executable file
   - for this demo, just one target machine - macos
   - TBD add in Nerves executable
- SBOMs in various formats containing SBOMs of dependencies as well
