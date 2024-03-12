---
# Supplementary material

This is the interactive supplementary material to the submission of the paper  "UNDERSTANDING THE RELATIONSHIP BETWEEN VOICE AND ACCOMPANIMENTON SYMBOLIC MUSIC DATA", in *Proc. of the 22nd Int. Society for Music Information Retrieval Conf.*, San Francisco, 2024.

## Interactive Plots

First of all, you can show and hide both collections by clicking on the legend located on the right side of the plots. Alternatively, double-click on a specific collection to isolate it in the plot and hide the other one. You can also draw your mouse around the plot, hovering over the data points for each grade. A hover-over pop-up for each data point will appear, providing information about the score title, the values of the actual descriptor, and a summary for the rest of the descriptors for the score.
### Rhythm Onset Descriptor (RO)

In the following plot you can browse through the values of the Rhythmic Onset (RO) descriptor. Please refer to Section 3.2.1 of our paper for further detail and to see example.

{% include onset.html %}

### Rhythm Pattern Coincidence Descriptor (RPC)

In the following plot you can browse through the values of the Rhythmic Pattern Coincidence (RPC) descriptor. Please refer to Section 3.2.2 of our paper for further detail and to see example.

{% include rhythm_pattern_coincidence.html %}

### Melody Contour Descriptor (MC)

In the following plot you can browse through the values of the Melody Contour (MC) descriptor. Please refer to Section 3.2.3 of our paper for further detail and to see example.

{% include contour.html %}

### Melody Pattern Coincidence Descriptor (MPC)

 In the following plot you can browse through the values of the Melodic Pattern Coincidence (MPC) descriptor. Please refer to Section 3.2.4 of our paper for further detail and to see example.

{% include melody_pattern_coincidence.html %}

### Harmony (H)

In the following plot you can browse through the values of the Harmony (H) descriptor. Please refer to Section 3.2.5 of our paper for further detail and to see example.

{% include harmony.html %}

## Descriptors Correlation

In these dendograms, you can see the correlation between different descriptors and grades for both score collections.

Classical dendogram:

<img src="https://voice-and-co.github.io/assets/img/classical_cluster.png" width="70%" height="70%" class="center">

Rock & Pop dendogram:

<center>
	<img src="https://voice-and-co.github.io/assets/img/rock_and_pop_cluster.png" width="70%" height="70%">
</center>

# Kolmogorov-Smirnov

See below, the table with the p-values obtained by running non-parametric Kolmogorov–Smirnov test over the both collections. The symbol `*` denotes p<=0.05 and `**` denotes p<=0.01.

<center>
	<img src="https://voice-and-co.github.io/assets/img/kolmogorov.png" width="100%" height="100%">
</center>

