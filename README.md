# Structure
## Introduction
>Short introduction to the topic and field. You read and discussed your paper. You are the expert. Try to get across why this is interesting and important.

? Sequencing technology

### Explain terms
- "DNA"
- "DNA sequencing"
- "genealogical history" - a familytree
- "recombination"/"mutation" - insertion/deletion, copy number variant, single-nucleotide polymorphisms
- "allele"
- "phylogenetic tree" - way to show genealogical history
- "(ancestral) haplotypes"
- "succinct tree sequence"
- "ancestral recombination graph (ARG)"

?
- "focal site"
- "sequence of marginal trees"

## Aim (current situation)
Current methods are limited (throughput), there's a need for scalable efficient methods

## Data source
What data was used.

1000 Genomes Project
Simons Genome Diversity Project
UK Biobank

? Simulated dataset used

## Solution
Ways around incomplete sampling.

### Products
Open source tools (https://github.com/tskit-dev)
- tsinfer
- tskit

### Why open source in science is cool (Data & Code availability)
- replicability of results
- everyone could contribute (under code of conduct)
- tools can be adapted (depending on License) to fit own needs

For discussion, now or after the presentation: What do you think could be drawbacks of open source?
- How is it financed? Is it secure? Development could suddenly be stopped.
- User can be mean (reason for code of conduct) and take support/bug-fixes for granted
- embarassment of putting all your work out there
- potential that someone else copies your work (use appropriate License)
- sensitive information in data

## Drawbacks

?(## Other possible applications)

## Conclusion/Outlook


# get pdf of xaringan presentation
pagedown::chrome_print("index.Rmd")
