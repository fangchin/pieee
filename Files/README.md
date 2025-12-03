# Proceedings of The IEEE (PIEEE) papers

This directory contains two subdirectories, gnuplot and data. The
former contains gnuplot command files. All of them are well commented,
with usage instructions.  The data subdirectory contains input data
files (csv or dat).

Following the modern workflow for LaTeX, only PDF files are used for
creating the final version.

To covert a SVG file to PDF, use the inkscape tool <https://inkscape.org/>

On a Linux computer, assuming the input file is named as input.svg, and the
output file is named as output.pdf, the following works:

$ inkscape input.svg --export-type=pdf --export-filename=output.pdf

where $ is the bash shell prompt.
