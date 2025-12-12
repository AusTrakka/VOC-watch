# VOC Watch 

Repo for automated tracking of Variant of Concern lists from various agencies. 

<img width="2042" height="986" alt="pango-watch-system" src="https://github.com/user-attachments/assets/63d81f9a-f57f-499d-99dc-82c6624b3e50" />

The collapse files can then be used with [pango-collapse](https://github.com/MDU-PHL/pango-collapse) to extract VOC/VOI/VOMs from SARS-CoV-2 lineage datasets. 

```bash
pango-collapse \
  --url https://raw.githubusercontent.com/AusTrakka/VOC-watch/master/collapse_files/ukhsa.txt \
  -o ukhsa.tsv \
  -l Nextclade_pango \
  nextclade.tsv
```
