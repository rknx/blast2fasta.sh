# blast2fasta.sh
Shell script to convert blast XML output (`-outfmt 5`) into FASTA or multiFASTA format.

## Usage
```sh
$ wget "https://raw.githubusercontent.com/rknx/blast2fasta.sh/master/blast2fasta.sh"
$ chmod +x blast2fasta.sh
$ cat <xmlfilename>.xml | blast2fasta.sh > <fastafilename>.fasta
```
