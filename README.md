# trackhub-data-production
Trackhub data production

- From Kawaji-san lab, we get data and display them in Genome Browser+Trackhub:
  * cis-regulatory element regions
    - input: bed per sample (from Kawaji-san's pipeline) no strand(+/-) information
    - input: meta data (sample information?)
      - types of cre
      - no IDs
    - output: bigBed files + trackhub files
  * cis-regulatory activities
    - input: bigWig each sample and strand (ctss bed files maybe?)
    - input: meta data (sample information?)
    - output: trackhub files summarzing bigWig activity files
  * cis-regulatory variations
     - input: VCF.gz (variant call format) for human(hg38) and mouse(mm10)
     - human: https://jmorp.megabank.tohoku.ac.jp/downloads (jmorp)
     - mouse: https://molossinus.brc.riken.jp/mogplus/#JF1 (mog+)
     - output: vcfTabix
  * ChiP-Atlas data same cell lines
     - human(hg38) and mouse(mm10)
     - input: BED format?
     - output: converted to bigWig?

- data stored at: https://www.cloudflare.com
  - GitHub => cloudflare
