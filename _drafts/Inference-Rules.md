---
layout: blog
category: blog
use_math: true
title: Inference Rules
---

### Rules for $$\wedge$$

$$
\frac{X,Y}{X\wedge Y}, \frac{X\wedge Y}{X}, \frac{X\wedge Y}{Y}
$$

### Rules for $$\vee$$

$$
\frac{X}{X\vee Y}, \frac{X\vee Y,X\vdash Z,Y\vdash Z}{Z}
$$

### Rules for $$\Rightarrow$$

$$
\frac{X\vdash Y}{X\Rightarrow Y}, \frac{X,X\Rightarrow Y}{Y}
$$

### Rules for $$\Leftrightarrow$$

$$
\frac{X\Rightarrow Y,Y\Rightarrow X}{X\Leftrightarrow Y}, \frac{X\Leftrightarrow Y}{X\Rightarrow Y}, \frac{X\Leftrightarrow Y}{Y\Rightarrow X}
$$

Note that $$X \Leftrightarrow Y$$ and $$X = Y$$ are the same thing in
propositional logic.
