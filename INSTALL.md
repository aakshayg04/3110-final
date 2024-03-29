To run the code, make sure opam is installed and you are able to run dune projects on your computer. Then download the code off and navigate to it in your terminal.
It might be something like:
``` sh
% cd 3110-final-main
```
Then install ocaml-canvas, the GUI library we are using to display our graphics:
``` sh
% opam install ocaml-canvas
```
Finally, build and run the program!
``` sh
% dune build
% dune exec bin/main.exe
```