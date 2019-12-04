# DeepEC Singularity recipe

Singularity recipe for [DeepEC](https://bitbucket.org/kaistsystemsbiology/deepec/src/master/).

First download the recipe, for example with a git clone of this repository.

Singularity container can be created with the command (this command needs admin right):

```
singularity build deepec.sif Singularity
```

The deepec.sif file size is around 1.3 GB.

Then DeepEC can be called with:

```
singularity exec deepec.sif python /programs/deepec/deepec.py -i fasta_file -o output_folder
```
