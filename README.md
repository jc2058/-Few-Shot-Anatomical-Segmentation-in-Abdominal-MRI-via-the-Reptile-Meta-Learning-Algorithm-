[README-mri.md](https://github.com/user-attachments/files/34281592/README-mri.md)
# Few-shot MRI segmentation with Reptile meta-learning

MSc group project at Queen Mary University of London (2026). We tested whether Reptile meta-learning helps a compact U-Net adapt to new anatomical structures from 1–5 labelled examples.

## Results on unseen test tasks

| Labelled examples | Baseline Dice | Reptile Dice | Baseline IoU | Reptile IoU |
| --- | --- | --- | --- | --- |
| 1 | 0.1204 | 0.1459 | 0.1134 | 0.0814 |
| 3 | 0.1340 | 0.1527 | 0.1255 | 0.0822 |
| 5 | 0.1364 | 0.1256 | 0.1211 | 0.0728 |

Dice is calculated only on slices containing the target structure, and results are averaged across three random seeds. Scores stayed low and varied widely, so these are limited early results.

## Files

- `Group 2_Report_EMS741.pdf`: full report
