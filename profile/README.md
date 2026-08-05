<div align="center">
    
# DuplexGen:<br>Adaptive Synthesis of Human–AI Turn-Taking Dialogues

[![Project](https://img.shields.io/badge/Project%20Page-blue)](https://duplexgen.github.io)
[![Paper](https://img.shields.io/badge/Paper-arXiv-red)](https://arxiv.org/abs/2607.26178)

#### Takyoung Kim<sup>1,&ast;</sup>, Kang-wook Kim<sup>2,4,&ast;</sup>, Sang Hoon Woo<sup>2,5</sup>, Julia Hirschberg<sup>3</sup>, Gunhee Kim<sup>2</sup>, Dilek Hakkani-Tür<sup>1</sup> <br> <sub><sup>1</sup>University of Illinois Urbana-Champaign, <sup>2</sup>Seoul National University, <sup>3</sup> Columbia University <br> <sup>4</sup> University of California, Berkeley, <sup>5</sup> Georgia Institute of Technology <br> <sup>&ast;</sup>Equal Contribution

</div>

## Abstract

Turn-taking is a central component of full-duplex interaction. Which turn-taking behaviors are
appropriate varies with the scenario, yet current models apply a single norm regardless of
context. This limitation originates in their training data: human–human speech corpora capture
natural timing phenomena but provide little role grounding or scenario-specific norms, while
heuristic or prompted synthesis methods inject turn-taking behaviors without basing them on
human preferences. We introduce **DuplexGen**, a framework for generating dialogues with
scenario-adaptive turn-taking by calibrating LLM predictions against a small set of slot-level
human preference annotations. In six cooperative and competitive tasks, human turn-taking
preferences differ systematically, and DuplexGen aligns substantially more closely with those
preferences than uncalibrated prompting or training solely on generic human–human data; a
full-duplex model trained on DuplexGen-generated data exhibits distinctive, human-preferred
turn-taking behaviors. These results show that human calibration, not corpus scale or prompt
design alone, is what allows turn-taking synthesis to be scenario-specific.
