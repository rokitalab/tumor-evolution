# release notes

## current release
### release-v2

- Release date: 2024-01-16
- Status:
- Overview of changes:
    - This release adds the following data:
        - Maf files from only tumor data
        - Reference data

- Files changed
    - files added
        - `oncoprint-goi-lists-OpenPedCan-gencode-v39.csv`
        - `RefCDS_human_GRCh38_GencodeV39_liftover.rda`
       

- Analysis update
    - Newly-added analysis modules
        - sample-distribution-analysis
        - tmb-vaf-longitudinal
   
```
v2
├── gene-counts-rsem-expected_count-collapsed.rds
├── gene-expression-rsem-tpm-collapsed.rds
├── histologies.tsv
├── md5sum.txt
├── oncoprint-goi-lists-OpenPedCan-gencode-v39.csv
├── RefCDS_human_GRCh38_GencodeV39_liftover.rda
├── release-notes.md
├── snv-consensus-plus-hotspots.maf.tsv.gz
└── snv-mutation-tmb-coding.tsv
```

## previous release
## release-v1
- Data release data: 2023-05-24
- status: available

New files:
- `histologies.tsv`: OpenPedCan v12 histologies file


```
v1
├── gene-counts-rsem-expected_count-collapsed.rds
├── gene-expression-rsem-tpm-collapsed.rds
├── histologies.tsv
├── md5sum.txt
├── release-notes.md
└── snv-consensus-plus-hotspots.maf.tsv.gz
```
