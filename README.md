# Alfredo-Hern-ndez

I'm a microbiologist interested in microbiomes, genomics, ecology and evolution

#Este script cuenta el tamaño de las secuencias en formato *.fasta*
`awk '/^>/{if (l!="") print l; print; l=0; next}{l+=length($0)}END{print l}' file.fasta`

