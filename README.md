# bridge_latent_knowledge_selection_gap_for_conversation
Codes for EMNLP2020 Paper "Bridging the Gap between Prior and Posterior Knowledge Selection for Knowledge-Grounded Dialogue Generation"
## Based on Sequential Knowledge Transformer (SKT)
The code and dataset can be found in \url{https://github.com/bckim92/sequential-knowledge-transformer}

# TODO:
The author is lazy.
Please concat chenxiuyi2017@ia.ac.cn 

## System Requirements
- see the env.sh

## Running Experiments
- for SKT, SKT+PIPM and the variants of PIPM in the paper
  - see train.sh
- for models with KDBTS
  - see train.teacher.sh for the first stage
  - see train.student.sh for the second stage

## pretrained checkpoints
- for results in table 2 in the paper
  - see inference.sh
