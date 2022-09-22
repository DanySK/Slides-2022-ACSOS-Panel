 
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

[![](https://mermaid.ink/svg/pako:eNoVjDsKwzAQBa8itrYuoCJVmkAgIWnVLNIqFuhj1rsYY3z3yN1jmHkHhB4JHKTStzAji3l-fDPm0RYVYy0TRmtv5s090LoOsnEWutBLZTgwQSWumON4Oa7Ug8xUyYMbM1JCLeLBt3OoqNK_ewvghJUm0CWi0D3jj7GCS1hWOv9ihzIj)](https://mermaid.live/edit#pako:eNoVjDsKwzAQBa8itrYuoCJVmkAgIWnVLNIqFuhj1rsYY3z3yN1jmHkHhB4JHKTStzAji3l-fDPm0RYVYy0TRmtv5s090LoOsnEWutBLZTgwQSWumON4Oa7Ug8xUyYMbM1JCLeLBt3OoqNK_ewvghJUm0CWi0D3jj7GCS1hWOv9ihzIj)

We care about efficiency (in time and space)

**Classic world**

[![](https://mermaid.ink/svg/pako:eNp1j7FqAzEQRH9FbJXAnT_gilRpAoGEuFUjpNFZIK2OvZWNMf73SE6RNKl2mHk77N7I1wBaKOZ68Scnat6_LBvzxltTM88CF-b5xXxK9dj37lwkKYb10bQzA_5RPUsccwP7R_6oGPHvrqXEIQm8GsQ4xhMO62EyYMh6Nb7y3sqmqfKzpX9KcK75jD9H0UQFUlwK_ZHbgC3pCQWWli4DomtZLVm-d9Q1rccre1pUGiZqW3CK1-RWcYWW6PKO-zd0AV6Y)](https://mermaid.live/edit#pako:eNp1j7FqAzEQRH9FbJXAnT_gilRpAoGEuFUjpNFZIK2OvZWNMf73SE6RNKl2mHk77N7I1wBaKOZ68Scnat6_LBvzxltTM88CF-b5xXxK9dj37lwkKYb10bQzA_5RPUsccwP7R_6oGPHvrqXEIQm8GsQ4xhMO62EyYMh6Nb7y3sqmqfKzpX9KcK75jD9H0UQFUlwK_ZHbgC3pCQWWli4DomtZLVm-d9Q1rccre1pUGiZqW3CK1-RWcYWW6PKO-zd0AV6Y)

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
