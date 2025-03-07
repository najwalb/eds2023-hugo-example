+++
title = "Diffusion models: mathematical definition"
author = ["Najwa Laabid"]
draft = false
+++

The building blocks of a discrete diffusion model are (<a href="#citeproc_bib_item_1">Sohl-Dickstein et al. 2015</a>):

-   Forward process  \\(q(x\_t|x\_{t-1})\\) defined in Equation [1](#orgb6a29f0).

\begin{equation}
q(x\_t|x\_{t-1}) = \text{Cat}(x\_t, p = x\_{t-1}Q\_{t-1})
\end{equation}


## References {#references}



<style>.csl-entry{text-indent: -1.5em; margin-left: 1.5em;}</style><div class="csl-bib-body">
  <div class="csl-entry"><a id="citeproc_bib_item_1"></a>Sohl-Dickstein, Jascha, Eric Weiss, Niru Maheswaranathan, and Surya Ganguli. 2015. “Deep Unsupervised Learning Using Nonequilibrium Thermodynamics.” In <i>Proceedings of the 32nd International Conference on Machine Learning</i>, 2256–65.</div>
</div>
