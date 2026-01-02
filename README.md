# trimmomatic

#!/usr/bin/env bash

# ===== USER CONFIG =====
THREADS=40

# Input / Output
RAW_DIR=/HDD/HDD4/avipro/01_raw_file
TRIM_DIR=/HDD/HDD4/avipro/02_trim

# Trimmomatic
TRIMMOMATIC_BIN=$(which trimmomatic)

# Adapter (Trimmomatic 0.40)
ADAPTERS=/home/biolabs/miniforge3/pkgs/trimmomatic-0.40-hdfd78af_0/share/trimmomatic-0.40-0/adapters/TruSeq3-PE.fa
