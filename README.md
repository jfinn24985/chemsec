# chemsec

LaTeX style for automated creation of numeric chemical
labels for scientific documents.

For documentation run

    latex chemsec.dtx

To generate style file run

    latex chemsec.ins

The style file in this directory should always be identical
to the file generated by "latex chemsec.ins"

# Examples

To run an example change to test directory and run

    make clean example1

    make example1

to process the example1.tex file.

## Note

* The examples use the chemsec.sty file in the base
directory, this is not updated by the make program.

* The make program copies the example latex files and the
style file into the test directory. Dependency tracking
should keep these up to date.

* The clean target should remove everything but the
makefile from the test directory.