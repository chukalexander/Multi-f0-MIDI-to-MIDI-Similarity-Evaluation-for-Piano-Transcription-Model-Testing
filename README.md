# Multi-f0-MIDI-to-MIDI-Similarity-Evaluation-for-Piano-Transcription-Model-Testing

0.1 Task
This final project is aimed at evaluating a piano transription model with a multi-f0, MIDI-to-MIDI comparison metric with mir_eval.multipitch.

42 audio test clips from the classical repertoire are performed by 2 players on a Yamaha Disklavier, which also outputs ground truth (reference) MIDI files that is perfectly aligned with the actual performance.

MIDI estimation is generated with Piano-Scribe, a web application implementation of the following paper:

Hawthorne, C., Elsen, E., Song, J., Roberts, A., Simon, I., Raffel, C., ... & Eck, D. (2017). Onsets and frames: Dual-objective piano transcription. arXiv preprint arXiv:1710.11153.
Piano-Scribe link: https://piano-scribe.glitch.me


0.2 Divided Workload

Alex Chuk:

Recording Session: setup and performance
Dataset: Data structuring and archiving
Coding: coded MIDI data import, storage as Python dictionaries, data analysis and visualization

Jiawen Mao:

Recording session: setup and performance
Dataset: audio post-production and MIDI export, data augmentation with pink noise
Coding: finalized coding pipeline; coded MIDI file parsing and multipitch evaluation functions


0.3 Dataset Overview
'Data documentation'

0.4 Backup in googledrive
https://drive.google.com/drive/folders/1StcsbwBaXjADoAc4oQe9pfIQsumWhfaM?usp=sharing



