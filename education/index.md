---
layout: page
title: Education research
excerpt: ""
modified: 
image:
  feature: feature/wide_ensemble.png
  credit: 
  creditlink: 
---

## Hierarchical Two-Parameter Logistic Item Response Model 

<small>This case study documents a Stan model for the two-parameter logistic model (2PL) with hierarchical priors. A brief simulation indicates that the Stan model successfully recovers the generating parameters. An example using a grade 12 science assessment is provided.</small>

[View](case-studies/hierarchical_2pl.html) <span class="note">(HTML)</span>

Author
: Daniel C. Furr

Keywords
: education, item response theory, two-parameter logistic model, hierarchical priors

Source Repository
: [example-models/education/hierarchical_2pl](https://github.com/stan-dev/example-models/tree/master/education/hierarchical_2pl)
<span class="note">(GitHub)</span>

R Package Dependencies
: <tt style="font-size: 90%">rstan, ggplot2, mirt</tt>

License
:  BSD (3 clause), CC-BY


## Generalized Rating Scale Model with Latent Regression

<small>This case study documents a Stan model for the generalized rating scale model (GRSM) with latent regression. The latent regression portion of the model may be restricted to an intercept only, yielding a standard GRSM. A brief simulation indicates that the Stan model successfully recovers the generating parameters. An example using a survey of public perceptions of science and technology is provided.</small>

[View](case-studies/grsm_latent_reg.html) <span class="note">(HTML)</span>

Authors
: Daniel C. Furr

Keywords
: education, item response theory, generalized rating scale model

Source Repository
: [example-models/education/grsm_latent_reg](https://github.com/stan-dev/example-models/tree/master/education/grsm_latent_reg)
<span class="note">(GitHub)</span>

R Package Dependencies
: <tt style="font-size: 90%">rstan, ggplot2, ltm</tt>

License
:  BSD (3 clause), CC-BY


## Generalized Partial Credit Model with Latent Regression

<small>This case study documents a Stan model for the generalized partial credit model (GPCM) with latent regression. The latent regression portion of the model may be restricted to an intercept only, yielding a standard GPCM. A brief simulation indicates that the Stan model successfully recovers the generating parameters. An example using the TIMSS 2011 mathematics assessment is provided</small>

[View](case-studies/gpcm_latent_reg.html) <span class="note">(HTML)</span>

Authors
: Daniel C. Furr

Keywords
: education, item response theory, generalized partial credit model

Source Repository
: [example-models/education/gpcm_latent_reg](https://github.com/stan-dev/example-models/tree/master/education/gpcm_latent_reg)
<span class="note">(GitHub)</span>

R Package Dependencies
: <tt style="font-size: 90%">rstan, ggplot2, TAM</tt>

License
:  BSD (3 clause), CC-BY


## Rating Scale Model with Latent Regression

<small>This case study documents a Stan model for the rating scale model (RSM) with latent regression. The latent regression portion of the model may be restricted to an intercept only, yielding a standard RSM. A brief simulation indicates that the Stan model successfully recovers the generating parameters. An example using a survey of public perceptions of science and technology is provided.</small>

[View](case-studies/rsm_latent_reg.html) <span class="note">(HTML)</span>

Authors
: Daniel C. Furr

Keywords
: education, item response theory, rating scale model

Source Repository
: [example-models/education/rsm_latent_reg](https://github.com/stan-dev/example-models/tree/master/education/rsm_latent_reg)
<span class="note">(GitHub)</span>

R Package Dependencies
: <tt style="font-size: 90%">rstan, ggplot2, ltm</tt>

License
:  BSD (3 clause), CC-BY


## Partial Credit Model with Latent Regression

<small>This case study documents a Stan model for the partial credit model (PCM) with latent regression. The latent regression portion of the model may be restricted to an intercept only, yielding a standard PCM. A brief simulation indicates that the Stan model successfully recovers the generating parameters. An example using the TIMSS 2011 mathematics assessment is provided.</small>

[View](case-studies/pcm_latent_reg.html) <span class="note">(HTML)</span>

Authors
: Daniel C. Furr

Keywords
: education, item response theory, partial credit model

Source Repository
: [example-models/education/pcm_latent_reg](https://github.com/stan-dev/example-models/tree/master/education/pcm_latent_reg)
<span class="note">(GitHub)</span>

R Package Dependencies
: <tt style="font-size: 90%">rstan, ggplot2, TAM</tt>

License
:  BSD (3 clause), CC-BY


## Rasch Model with Latent Regression

<small>This case study documents a Stan model for the Rasch model with latent regression. The latent regression portion of the model may be restricted to an intercept only, yielding a standard Rasch model. A brief simulation indicates that the Stan model successfully recovers the generating parameters. An example using a grade 12 science assessment is provided.</small>

[View](case-studies/rasch_latent_reg.html) <span class="note">(HTML)</span>

Authors
: Daniel C. Furr

Keywords
: education, item response theory, rasch model

Source Repository
: [example-models/education/rasch_latent_reg](https://github.com/stan-dev/example-models/tree/master/education/rasch_latent_reg)
<span class="note">(GitHub)</span>

R Package Dependencies
: <tt style="font-size: 90%">rstan, ggplot2, TAM</tt>

License
:  BSD (3 clause), CC-BY



## Two-Parameter Logistic Item Response Model

<small>This tutorial introduces the R package edstan for estimating
two-parameter logistic item response models using Stan without knowing
the Stan language. Subsequently, the tutorial explains how the model
can be expressed in the Stan language and fit using the rstan
package. Specification of prior distributions and assessment of
convergence are discussed. Using the Stan language directly has the
advantage that it becomes quite easy to extend the model, and this is
demonstrated by adding a latent regression and differential item
functioning to the model. Posterior predictive model checking is also
demonstrated.</small>

[View](case-studies/tutorial_twopl.html) <span class="note">(HTML)</span>

Author
: Daniel C. Furr, Seung Yeon Lee, Joon-Ho Lee, and Sophia Rabe-Hesketh

Keywords
: education, item response theory, two-parameter logistic model

Source Repository
: [example-models/education/tutorial_twopl](https://github.com/stan-dev/example-models/tree/master/education/tutorial_twopl)
<span class="note">(GitHub)</span>

R Package Dependencies
: <tt style="font-size: 90%">rstan, reshape2, ggplot2,
gridExtra, devtools, edstan</tt>

License
:  BSD (3 clause), CC-BY


## Two-Parameter Logistic Model with Latent Regression

<small>This case study documents a Stan model for the two-parameter logistic model (2PL) with latent regression. The latent regression portion of the model may be restricted to an intercept only, yielding a standard 2PL. A brief simulation indicates that the Stan model successfully recovers the generating parameters. An example using a grade 12 science assessment is provided.</small>

[View](case-studies/2pl_latent_reg.html) <span class="note">(HTML)</span>

Authors
: Daniel C. Furr

Keywords
: education, item response theory, two-parameter logistic model

Source Repository
: [example-models/education/2pl_latent_reg](https://github.com/stan-dev/example-models/tree/master/education/2pl_latent_reg)
<span class="note">(GitHub)</span>

R Package Dependencies
: <tt style="font-size: 90%">rstan, ggplot2, TAM</tt>

License
:  BSD (3 clause), CC-BY