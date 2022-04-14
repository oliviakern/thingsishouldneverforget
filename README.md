# How to add a new line at the end of a bunch of files

For example, if I have a bunch of `.fasta` files, I have to do:

```bash
for f in *.fasta; do echo "" >> ${f}; done
```

# How to concatenate a bunch of files

For example, if I have a directory with a bunch of `.fasta` files, I have to do:

```bash
cat *.fasta >> all.fasta
```

where `all.fasta` will be the new file with everything concatenated.

