---
layout: page
title: Research
description: Adriano Poci's research
---

### Current Research

Currently I am working on developing a self-consistent comprehensive galaxy formation model that combines triaxial orbit-superposition Schwarzschild dynamical models with full-spectral-fitting stellar-population analyses. The combination provides unprecidented archeological constraints on the formation and evolution of nearby galaxies. Not only does this method bridge the once-independent field of stellar populations and stellar kinematics, but there is a heavy emphasis on maintaining self-consistency (for instance, see earlier research below). A first application of this methodology was published in [Poci et al. (2019)](https://ui.adsabs.harvard.edu/abs/2019MNRAS.487.3776P/abstract). I am now working on extending and applying this model to data from the [Fornax3D survey](http://www.na.astro.it/Fornax3D/Fornax3D/Welcome.html).

<hr style="border:0.75pxpx solid black">

### Past Research

#### Jeans Dynamical Modeling

Earlier work was focused on investigating the impact of including the derived stellar mass-to-light ratio <MATH>(M<sub>&#9733;</sub>/L)</MATH> into dynamical models, in order to relax the assumption of a spatially-constant <MATH>M<sub>&#9733;</sub>/L</MATH> of most previous implementations. This work used the Jeans Anisotropic Model ([JAM](http://www-astro.physics.ox.ac.uk/~mxc/software/); [Cappellari, 2008](https://ui.adsabs.harvard.edu/abs/2008MNRAS.390...71C/abstract)).   
The results of that work were two-fold;

<style>
.resGrid {
  display: grid;
  grid-template-columns: auto auto;
  grid-column-gap: 10px;
  justify-content: space-between;
}

.resGrid > div {
  text-align: center;
}

.resPic {
  grid-row: 1 / 3;
  grid-column: 1
}
</style>
<h5><a name="massMGE"></a>&alpha;<sub>dyn.</sub> Mismatch</h5>
<a href="{{ BASE_PATH }}/assets/plMlMl.png"><img src="{{ BASE_PATH }}/assets/plMlMl.png" style="float: left; height: 80mm; margin-right: 0.5%; margin-bottom: 0.5em;" /></a>
<a href="{{ BASE_PATH }}/assets/MlMlModB.png"><img src="{{ BASE_PATH }}/assets/MlMlModB.png" style="float: left; height: 80mm; margin-right: 1%; margin-bottom: 0.5em;" /></a>
<p>Testing the impact of including a spatially-varying <MATH>M<sub>&#9733;</sub>/L</MATH> on the inferred dynamical mismatch parameter, <MATH>&alpha;<sub>dyn.</sub></MATH>. This parameter measures the offset between the dynamically-inferred and stellar-population-inferred galaxy mass, in effect constraining the accuracy of the assumed stellar Initial Mass Function (IMF). The case with the spatially-varying <MATH>M<sub>&#9733;</sub>/L</MATH> from my work is shown on the left, while the original result, for a spatially-constant <MATH>M<sub>&#9733;</sub>/L</MATH>, is shown on the right (<a href="https://ui.adsabs.harvard.edu/abs/2012Natur.484..485C/abstract">Cappellari et al., 2012</a>). This result shows that, while the dynamical models with a spatially-varying <MATH>M<sub>&#9733;</sub>/L</MATH> exhibit a systematic offset to lower <MATH>&alpha;<sub>dyn.</sub></MATH> values, importantly the non-linear trend with mass remains. This was the main goal of my <a href="http://hdl.handle.net/1959.14/1185049">Master's Thesis</a>.</p>
<h5><a name="bhc"></a>Total-Mass Density Profile Slopes</h5>
<p><a href="{{ BASE_PATH }}/assets/sDist-1.png"><img src="{{ BASE_PATH }}/assets/sDist-1.png" style="float: left; width: 30%; margin-right: 1%; margin-bottom: 0.5em;" /></a>In addition to IMF constraints, and owing to the specific dynamical model that was employed for the above result, we found interesting correlations with the total (dynamical) mass of galaxies. Rather than applying some baryonic+dark mass model, which requires assumptions about both the baryonic and dark-matter distributions, we constrained the total dynamical mass directly using the observed stellar kinematics. This allowed for robust measurements of the profile of the total-mass density as an explicit parameter of the dynamical models, and exploiting the large sample of galaxies, we built up statistically-significant distributions. Most notably, we find that the distribution of slopes of the profiles of the total-mass density is more concentrated than that of the stellar-mass density, and is centred on a nearly-isothermal value of <MATH>&gamma;<sub>tot.</sub> &sim; -2.1</MATH> (<a href="https://ui.adsabs.harvard.edu/abs/2017MNRAS.467.1397P/abstract">Poci et al., 2017</a>). This implies that the total mass is a critical parameter for galaxy formation, irrespective of the stellar or dark-matter distributions individually.</p><br clear="all" />
<p><a href="{{ BASE_PATH }}/assets/plSlopeSigma-bpl-MI.png"><img src="{{ BASE_PATH }}/assets/plSlopeSigma-bpl-MI.png" style="float: left; width: 60%; margin-right: 1%; margin-bottom: 0.5em;" /></a>These total-mass density slopes were also found to correlate with a number of other physical properties of galaxies. The strongest such correlation was found to be with the central velocity dispersion (within <MATH>1 R<sub>e</sub></MATH>), <MATH>&sigma;<sub>e</sub></MATH>, illustrated here. This correlation is interesting because it shows a clear transition at <MATH>log<sub>10</sub>&#x2061;<!--FUNCTION APPLICATION-->(&sigma;<sub>e</sub>) &sim; -2.1</MATH>. This is likely the regime above which massive galaxies experience many mergers which stabilise their outer mass distributions.</p>

<!-- Note: this is how to write a comment in HTML. Everything in here won't show up on your webpage.-->

<!--
To increase the size of the title, use fewer # in front of the paper title.
To decrease the size of the title, use more #.
To remove the italics, remove the * before and after the description
To remove the underline from the title, remove the <u> tags (<u> and </u>)
-->
