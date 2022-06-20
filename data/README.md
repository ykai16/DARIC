This folder contains the normalized PIS tracks for a compendium of 19 cell types(lines) from the 4DN consortium.

1. All the data are aligned to hg38.
2. PIS tracks are normalized to the PIS track in H1ESC by the `normalize` command in `DARIC`.
3. `allSamples_PIS_std.bedGraph` and `allSamples_PIS_mean.bedGraph` is the track to show PIS variability (i.e standard deviation) and mean across the 19 cell types. 
4. `HMM_states.bed` is the genome annotation file showing the PIS variability. More details can be found in our manuscript.