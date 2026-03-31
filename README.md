# More Visualizations

These visual results clearly demonstrate the significant advantage of our method: it effectively leverages spatial guidance without strictly relying on hard mask conditions.

---

### Qualitative Analysis of Editing Robustness under Varying Segmentation Quality

![Figure 4](figure.jpg)

Figure R. Qualitative comparison demonstrating editing stability across different levels of UniPixel-3B segmentation accuracy. 
**(1) Accurate segmentation (IoU > 0.8):** In the first and second rows, when the predicted masks are highly accurate, our model achieves highly precise edits. 
**(2) Moderately noisy segmentation (0.4 < IoU < 0.8):** In the third and fourth rows, despite noticeable noise in the mask, our approach consistently identifies and edits the correct target subjects. 
**(3) Severe deviation with correct localization:** In the fifth row, the mask has a large deviation but still indicates the rough location of the target. Remarkably, our model automatically expands the receptive region to edit the complete intended object. **(4) Completely erroneous segmentation:** Even in the worst-case scenario (the last row), where the predicted mask is severely corrupted, our model maintains strong robustness and performs accurate regional editing. 
