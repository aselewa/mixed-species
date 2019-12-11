# mixed-species
Pipeline for processing mixed-species 10x data

## Usage

```
source activate mixedRunner

python mixedRunner.py --R1 path/to/R1.fastq.gz \
                      --R2 path/to/R2.fastq.gz \
                      --human_indices human_indices/ \
                      --chimp_indices chimp_indices/
                      --protocol 10x-v2 (or 10x-v3)
                      --cluster
```
