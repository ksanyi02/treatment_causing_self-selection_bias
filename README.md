# Treatment-Induced Self-Selection Bias

#selection-bias #attrition-bias #behavioral-deterrence #endogeneity

## Overview

This project evaluates a UX experiment on an insurance claim form designed to observe how the timing of a legal notice impacts user compliance and fraud reduction. The experiment compares two front-end designs:

Version A: Post-fill disclaimer (signing at the end)

Version B: Upfront honesty priming (signing a disclosure first)


## The Challenge: Endogenous Attrition

Because the treatment emphasizes the legal consequences of fraudulent activity, the upfront priming variant is expected to cause a high drop-out (attrition) rate. This introduces endogenous self-selection bias, as the users who abandon the form differ systematically from those who complete it. Under these circumstances, standard evaluation metrics yield biased estimates of the true treatment effect.

This fictional experiment serves as a concrete case study demonstrating why traditional frequentist and Bayesian A/B testing paradigms fail in the presence of systemic attrition, and offers alternative statistical methods to recover unbiased causal effects.

## Inspiration

The concept for this project is inspired by the following - retracted - study: 

L.L. Shu, N. Mazar, F. Gino, D. Ariely, M.H. Bazerman. Signing at the beginning makes ethics salient and decreases dishonest self-reports in comparison to signing at the end. Proc. Natl. Acad. Sci. U.S.A. 109, 15197–15200 (2012). [LINK](https://www.researchgate.net/publication/230748958_Signing_at_the_beginning_makes_ethics_salient_and_decreases_dishonest_self-reports_in_comparison_to_signing_at_the_end)