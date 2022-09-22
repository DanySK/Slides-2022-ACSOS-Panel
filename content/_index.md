 
+++

title = "Hot topics and current challenges in ACSOS"
description = "Introductory presentation before the panel discussion"
outputs = ["Reveal"]

+++


# Hot topics and current challenges in ACSOS

## A very partial view from [Danilo Pianini](mailto:danilo.pianini@unibo.it)

---

### Living in an infinite transient

**Classic world**

[![](https://mermaid.ink/svg/pako:eNodjbEKAyEQRH9FFsTm_AGLVGkCgYSktVl0Lyc5NXgrRxD_PV664fFmpoHLnsCAlC2kwEY0xQtFUkZ5LG_Vu5Q2zWve3YKFxfVhkxCX9KkstC6EXuuTuJfsaNsG2UtgOtCt8nBggkglYvDjox1VC_99C2ZETzPWlS3Y1IeKlfPzmxwYLpUmqB-PTOeAr4IRzIzrRv0Ht2g8Cg)](https://mermaid.live/edit#pako:eNodjbEKAyEQRH9FFsTm_AGLVGkCgYSktVl0Lyc5NXgrRxD_PV664fFmpoHLnsCAlC2kwEY0xQtFUkZ5LG_Vu5Q2zWve3YKFxfVhkxCX9KkstC6EXuuTuJfsaNsG2UtgOtCt8nBggkglYvDjox1VC_99C2ZETzPWlS3Y1IeKlfPzmxwYLpUmqB-PTOeAr4IRzIzrRv0Ht2g8Cg)
We care about efficiency (in time and space)

**Classic world**

[![](https://mermaid.ink/svg/pako:eNp1j8FqxDAMRH_FCEJaSPYDfNhTL4VCS3v1xdhy1jSWgyLvsoT8e-3sob30pGHmaZA2cNkjaOi6LVIUrbZeLpiw1723_N3ve9cZCnO-uYtlUW-fhpR6paWIGkdG68fxrD44O1zX6tw4CjbrvUhlGvxQNYu1pyC5Iz8qWvy7ayCSj4xOFIbQxhOeptOgkJCnu3KZ1pIWiZmeDfxTgtc8X_HPUTBAQk42-vrm1mADx4sGdJUegy2zGDC0V9QWyV93cqCFCw5QFm8FX6Kd2CbQwc4r7j_aYmh_)](https://mermaid.live/edit#pako:eNp1j8FqxDAMRH_FCEJaSPYDfNhTL4VCS3v1xdhy1jSWgyLvsoT8e-3sob30pGHmaZA2cNkjaOi6LVIUrbZeLpiw1723_N3ve9cZCnO-uYtlUW-fhpR6paWIGkdG68fxrD44O1zX6tw4CjbrvUhlGvxQNYu1pyC5Iz8qWvy7ayCSj4xOFIbQxhOeptOgkJCnu3KZ1pIWiZmeDfxTgtc8X_HPUTBAQk42-vrm1mADx4sGdJUegy2zGDC0V9QWyV93cqCFCw5QFm8FX6Kd2CbQwc4r7j_aYmh_)

It is a *neverending transient*, what do we care about?

---

### Understanding (eternal) transients

* How do we understand if our perennial transient "works"?
  * Some cases can be dealt with control techniques
  * Many assumptions $\rightarrow$ Full complexity remains hard to capture
  * Systems that perform better on paper may perform worse in simulation
    * Models are too simple
    * Models of self are too simple

* Learn how to contain non-linear effects
  * There's potential for catastrophic *security* flaws

**How do we compare different approaches?**

* We lack *metrics* and *benchmarks*
  * Can we build a **library of *standard* evaluation tools**?

---

### Critical engineering feats

* Many tools over the years
* Few of them are actually reusable
  * Fewer are documented to the point that non-authors can do something
  * Ask experts in other disciplines on how to document for humans?
* Critical: **modularity and reusability**
  * Many ad-hoc ideas, few *reusable libraries*

We might want to build a catalog of ACSOS tools

reuse $\gg$ reinvent
