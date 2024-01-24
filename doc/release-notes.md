# release notes

## current release
### release-v2

- Release date: 2024-01-24
- Status:
- Overview of changes:
    - This release adds the following data:
        - Copy number data analysis
        - Maf files from only tumor data
        - Reference data

- Files changed
    - files added
        - `oncoprint-goi-lists-OpenPedCan-gencode-v39.csv`
        - `cnv-cnvkit-cns.tsv.gz`
        - `independent-specimens.methyl.primary.eachcohort.tsv`
        - `independent-specimens.methyl.primary-plus.eachcohort.tsv`
        - `independent-specimens.methyl.primary-plus.tsv`
        - `independent-specimens.methyl.primary.tsv`
        - `independent-specimens.methyl.relapse.eachcohort.tsv`
        - `independent-specimens.methyl.relapse.tsv`
        - `independent-specimens.rnaseqpanel.primary.eachcohort.tsv`
        - `independent-specimens.rnaseqpanel.primary-plus.eachcohort.tsv`
        - `independent-specimens.rnaseqpanel.primary-plus.tsv`
        - `independent-specimens.rnaseqpanel.primary.tsv`
        - `independent-specimens.rnaseqpanel.relapse.eachcohort.tsv`
        - `independent-specimens.rnaseqpanel.relapse.tsv`
        - `independent-specimens.rnaseq.primary-plus-pre-release.tsv`
        - `independent-specimens.rnaseq.primary-pre-release.tsv`
        - `independent-specimens.rnaseq.relapse-pre-release.tsv`
        - `independent-specimens.wgs.primary.eachcohort.tsv`
        - `independent-specimens.wgs.primary-plus.eachcohort.tsv`
        - `independent-specimens.wgs.primary-plus.tsv`
        - `independent-specimens.wgs.primary.tsv`
        - `independent-specimens.wgs.relapse.eachcohort.tsv`
        - `independent-specimens.wgs.relapse.tsv`
        - `independent-specimens.wgswxspanel.primary.eachcohort.prefer.wgs.tsv`
        - `independent-specimens.wgswxspanel.primary.eachcohort.prefer.wxs.tsv`
        - `independent-specimens.wgswxspanel.primary-plus.eachcohort.prefer.wgs.tsv`
        - `independent-specimens.wgswxspanel.primary-plus.eachcohort.prefer.wxs.tsv`
        - `independent-specimens.wgswxspanel.primary-plus.prefer.wgs.tsv`
        - `independent-specimens.wgswxspanel.primary-plus.prefer.wxs.tsv`
        - `independent-specimens.wgswxspanel.primary.prefer.wgs.tsv`
        - `independent-specimens.wgswxspanel.primary.prefer.wxs.tsv`
        - `independent-specimens.wgswxspanel.relapse.eachcohort.prefer.wgs.tsv`
        - `independent-specimens.wgswxspanel.relapse.eachcohort.prefer.wxs.tsv`
        - `independent-specimens.wgswxspanel.relapse.prefer.wgs.tsv`
        - `independent-specimens.wgswxspanel.relapse.prefer.wxs.tsv`
        - `snv-mutect2-tumor-only-plus-hotspots.maf.tsv.gz`
       

- Analysis update
    - Newly-added analysis modules
        - sample-distribution-analysis
        - tmb-vaf-longitudinal
        - update-histologies-temp
   
```
v2
├── cnv-cnvkit-cns.tsv.gz
├── gene-counts-rsem-expected_count-collapsed.rds
├── gene-expression-rsem-tpm-collapsed.rds
├── histologies.tsv
├── independent-specimens.methyl.primary.eachcohort.tsv
├── independent-specimens.methyl.primary-plus.eachcohort.tsv
├── independent-specimens.methyl.primary-plus.tsv
├── independent-specimens.methyl.primary.tsv
├── independent-specimens.methyl.relapse.eachcohort.tsv
├── independent-specimens.methyl.relapse.tsv
├── independent-specimens.rnaseqpanel.primary.eachcohort.tsv
├── independent-specimens.rnaseqpanel.primary-plus.eachcohort.tsv
├── independent-specimens.rnaseqpanel.primary-plus.tsv
├── independent-specimens.rnaseqpanel.primary.tsv
├── independent-specimens.rnaseqpanel.relapse.eachcohort.tsv
├── independent-specimens.rnaseqpanel.relapse.tsv
├── independent-specimens.rnaseq.primary-plus-pre-release.tsv
├── independent-specimens.rnaseq.primary-pre-release.tsv
├── independent-specimens.rnaseq.relapse-pre-release.tsv
├── independent-specimens.wgs.primary.eachcohort.tsv
├── independent-specimens.wgs.primary-plus.eachcohort.tsv
├── independent-specimens.wgs.primary-plus.tsv
├── independent-specimens.wgs.primary.tsv
├── independent-specimens.wgs.relapse.eachcohort.tsv
├── independent-specimens.wgs.relapse.tsv
├── independent-specimens.wgswxspanel.primary.eachcohort.prefer.wgs.tsv
├── independent-specimens.wgswxspanel.primary.eachcohort.prefer.wxs.tsv
├── independent-specimens.wgswxspanel.primary-plus.eachcohort.prefer.wgs.tsv
├── independent-specimens.wgswxspanel.primary-plus.eachcohort.prefer.wxs.tsv
├── independent-specimens.wgswxspanel.primary-plus.prefer.wgs.tsv
├── independent-specimens.wgswxspanel.primary-plus.prefer.wxs.tsv
├── independent-specimens.wgswxspanel.primary.prefer.wgs.tsv
├── independent-specimens.wgswxspanel.primary.prefer.wxs.tsv
├── independent-specimens.wgswxspanel.relapse.eachcohort.prefer.wgs.tsv
├── independent-specimens.wgswxspanel.relapse.eachcohort.prefer.wxs.tsv
├── independent-specimens.wgswxspanel.relapse.prefer.wgs.tsv
├── independent-specimens.wgswxspanel.relapse.prefer.wxs.tsv
├── release-notes.md
├── snv-consensus-plus-hotspots.maf.tsv.gz
├── snv-mutation-tmb-coding.tsv
└── snv-mutect2-tumor-only-plus-hotspots.maf.tsv.gz
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
