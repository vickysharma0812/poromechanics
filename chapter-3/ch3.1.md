# Volume average of sum and product

<!-- markdownlint-disable MD041 MD013 MD033 MD012 -->

## Average of a sum

Let $e_{1}^{\alpha}$ and $e_{2}^{\alpha}$ be the two properties of the $\alpha$ phase, then

$$
\left\langle e_{1}^{\alpha}+e_{2}^{\alpha}\right\rangle^{\alpha} =\left\langle e_{1}^{\alpha}\right\rangle ^{\alpha}+\left\langle e_{2}^{\alpha}\right\rangle ^{\alpha}
$$

## Average of a product

Let $e_{1}^{\alpha}$ and $e_{2}^{\alpha}$ be the two properties of the $\alpha$ phase.

$$
e_{1}^{\alpha}=\left\langle e_{1}^{\alpha}\right\rangle ^{\alpha}+\mathring{e}_{1}^{\alpha}
$$

and

$$
e_{2}^{\alpha}=\left\langle e_{2}^{\alpha}\right\rangle ^{\alpha}+\mathring{e}_{2}^{\alpha}
$$

then,

$$
\left\langle e_{1}^{\alpha}e_{2}^{\alpha}\right\rangle ^{\alpha}=\left\langle e_{1}^{\alpha}\right\rangle ^{\alpha}\left\langle e_{2}^{\alpha}\right\rangle ^{\alpha}+\left\langle \mathring{e}_{1}^{\alpha}\mathring{e}_{2}^{\alpha}\right\rangle ^{\alpha}
$$


## Volume average of time derivative

![REV](https://dm2302files.storage.live.com/y4mkVhPzA_6Ti4Kp8CPVe2g-MV-M2lnzhgiFWrnUO20l7PMZyncjWyzVinO84-Msn_JcDCXOwF9fnYn1MPl-BidGfT8Kl2y4roKtB48M80IjkAqwduk_xoppyI0LZSUlI752mzkYMXYulxSdimFKPMb3d140emV7uA7FVWIGI3wUxoxPmXFjmhCTLMprPMqeRAV?width=1000&height=1000&cropmode=none)

![REV](https://dm2302files.storage.live.com/y4m7NFlOcGR82tm9gagpBnvE1f3AK8WcCy79dYYjtPHRrKBTUQGdd6BhBHWunEl1DWjioWKkiJx2pocRjuC58cXjZl1ybDg-_Xot8jprYfPZyJEjzOTvFYplkrEaFFWB_v3JiQ_tq2GtMwZXfAReGP8nXsL-pHagORN1RN58yOxulgifb-a2upC7tFXy7xe6sN-?width=1000&height=1000&cropmode=none)

Figure: Representative elementary volume

Consider an REV shown above, in which $\Omega_{0}$ is the domain of the REV, $\Gamma_{0}$ is the boundary of REV. The domain of $\alpha$ phase is $\Omega_{0}^{\alpha}$, and its boundary $\Gamma_{0}^{\alpha}$. Let $E$ be some extensive quantity, $e^{\alpha}$ be the corresponding to intesive quantity. Then, the material time derivative of $e^{\alpha}$ is given by

$$
\frac{D_{E}}{Dt}\int_{\Omega_{0}^{\alpha}}e^{\alpha}d\Omega=\int_{\Omega_{0}^{\alpha}}\frac{\partial e^{\alpha}}{\partial t}d\Omega+\int_{\Gamma_{0}^{\alpha\alpha}}e^{\alpha}\mathbf{V^{\mathbf{\alpha}}}\cdot\mathbf{n}dS+\int_{\Gamma_{0}^{\alpha\beta}}e^{\alpha}\mathbf{u}\cdot\mathbf{n}dS
$$

$$
\frac{D_{E}}{Dt}\int_{\Omega_{0}}\gamma^{\alpha}e^{\alpha}d\Omega=\frac{\partial}{\partial t}\int_{\Omega_{0}}\gamma^{\alpha}e^{\alpha}+\int_{\Gamma_{0}^{\alpha\alpha}}\gamma^{\alpha}e^{\alpha}\mathbf{V^{\mathbf{\alpha}}}\cdot\mathbf{n}dS+\int_{\Gamma_{0}^{\beta\beta}}\gamma^{\alpha}e^{\alpha}\mathbf{V^{\mathbf{\alpha}}}\cdot\mathbf{n}dS
$$

noting, $\gamma^{\alpha}=0$ on $\Gamma_{0}^{\beta \beta}$ in above equation we can get:

$$
\frac{D_{E}}{Dt}\int_{\Omega_{0}^{\alpha}}e^{\alpha}d\Omega=\frac{\partial}{\partial t}\int_{\Omega_{0}^{\alpha}}e^{\alpha}+\int_{\Gamma_{0}^{\alpha\alpha}}e^{\alpha}\mathbf{V^{\mathbf{\alpha}}}\cdot\mathbf{n}dS
$$

By using Eq. \ref{eq:eq-1} and Eq. \ref{eq:eq-3}, we can obtain following expression:

$$
\int_{\Omega_{0}^{\alpha}}\frac{\partial e^{\alpha}}{\partial t}d\Omega=\frac{\partial}{\partial t}\int_{\Omega_{0}^{\alpha}}e^{\alpha}-\int_{\Gamma_{0}^{\alpha\beta}}e^{\alpha}\mathbf{u}\cdot\mathbf{n}dS
$$

Dividing above equation by $V_{0}$ we obtain:

$$
\left\langle \frac{\partial e^{\alpha}}{\partial t}\right\rangle =\frac{\partial}{\partial t}\left\langle e^{\alpha}\right\rangle -\frac{1}{V_{0}}\int_{\Gamma_{0}^{\alpha\beta}}e^{\alpha}\mathbf{u}\cdot\mathbf{n}dS
$$

or

$$
\theta^{\alpha}\left\langle \frac{\partial e^{\alpha}}{\partial t}\right\rangle ^{\alpha}=\frac{\partial}{\partial t}\theta^{\alpha}\left\langle e^{\alpha}\right\rangle ^{\alpha}-\frac{1}{V_{0}}\int_{\Gamma_{0}^{\alpha\beta}}e^{\alpha}\mathbf{u}\cdot\mathbf{n}dS
$$

Setting $e^{\alpha}=1$ in Eq. \ref{eq:eq-5}:

$$
\frac{\partial\theta^{\alpha}}{\partial t}=\frac{1}{V_{0}}\int_{\Gamma_{0}^{\alpha\beta}}\mathbf{u}\cdot\mathbf{n}dS
$$


## Volume average of spatial gradient

![REV](https://dm2302files.storage.live.com/y4mnOEm6tCDl-PBCzk5nXq1jfJE0bFIZDPYKKEnhL2Rz7ekyN9wJEm4h5KgEPLhRJshU5r19y6GeKL6otz1sYe5V3tyk6sVUvvkVXUalJhjUWPeqekZNtrGNrffIiPY9SKn2QWD4_IyCcUPrnWhLJBBGIKfRnbfWxAa64ygKHDxK9vSPZwUnpQkJrJHJTyfE9fK?width=1000&height=1000&cropmode=none)

![REV](https://dm2302files.storage.live.com/y4mL4w9b2ctjFa5N4qhK3BR-31Bp8j2r2tdMkZyyawyEeeWy-Jk997T7BSWxzcqIBRHUTE7VscABCgrQpeZ9N83THke9ii9iXwonxw0SpRUIz9QsO7AOheDPq2i6BNR4rZjjtsuRUx0MuGtJ83B6_ZeyGNH_LDxIzNfHS2hQ_Vqqz5U-VOjLtDSh4795YldF-S6?width=1000&height=1000&cropmode=none)

Figure: Representative elementary volume

Consider an REV shown above, in which $\Omega_{0}$ is the domain of the REV, $\Gamma_{0}$ is the boundary of REV. The domain of $\alpha$ phase is $\Omega_{0}^{\alpha}$, and its boundary $\Gamma_{0}^{\alpha}$. Let $E$ be some extensive quantity, $e^{\alpha}$ be the corresponding to intesive quantity.

$$
\label{eq:eq-1}
\int_{\Omega_{0}^{\alpha}}\mathbf{e}^{\alpha}\otimes\nabla d\Omega=\int_{\Gamma_{0}^{\alpha}}\mathbf{e}^{\alpha}\otimes\mathbf{n}ds=\int_{\Gamma_{0}^{\alpha\alpha}}\mathbf{e}^{\alpha}\otimes\mathbf{n}ds+\int_{\Gamma_{0}^{\alpha\beta}}\mathbf{e}^{\alpha}\otimes\mathbf{n}ds
$$

Now we will consider the gradient of average of $\mathbf{e}^{\alpha}$, note that this gradient operator is in terms of macroscopic coordinates. However, for the sake of simplicity, we will consider the directional derivative instead of spatial gradient. In this context, we move the REV in some arbitrary direction $\hat{\mathbf{s}}$ without changing the shape of the REV.

$$
\begin{split}
\label{eq:eq-2}
\mathbf{\hat{s}\cdot\nabla\int_{\Omega_{0}^{\alpha}}}\mathbf{e}^{\alpha}d\Omega &=\frac{d}{ds}\mathbf{\int_{\Omega_{0}^{\alpha}}}\mathbf{e}^{\alpha}d\Omega \\
& = \underset{\Delta s\rightarrow0}{\lim}\frac{1}{\Delta s}\left\{ \int_{\Omega_{0}^{\alpha}\left(s+\Delta s\right)}\mathbf{e}^{\alpha}d\Omega-\int_{\Omega_{0}^{\alpha}\left(s\right)}\mathbf{e}^{\alpha}d\Omega\right\} \\
& =\int_{\Gamma_{0}^{\alpha\alpha}}\mathbf{e}^{\alpha}\mathbf{n}\cdot\mathbf{\hat{s}}ds
\end{split}
$$
🧇
As a result,

$$
\label{eq:eq-3}
\mathbf{\nabla\otimes\int_{\Omega_{0}^{\alpha}}}\mathbf{e}^{\alpha}d\Omega=\int_{\Gamma_{0}^{\alpha\alpha}}\mathbf{n}\otimes\mathbf{e}^{\alpha}ds
$$

Using Eq. \ref{eq:eq-3} in Eq. \ref{eq:eq-1}, we can obtain following equation:

$$
\label{eq:eq-4}
\int_{\Omega_{0}^{\alpha}}\mathbf{e}^{\alpha}\otimes\nabla d\Omega=\left(\mathbf{\int_{\Omega_{0}^{\alpha}}}\mathbf{e}^{\alpha} d\Omega\right)\otimes\nabla+\int_{\Gamma_{0}^{\alpha\beta}}\mathbf{e}^{\alpha}\otimes\mathbf{n}ds
$$

Dividing both side by $V_{0}$, we obtain following relationship between gradient of average and average of gradient.

$$
\label{eq:eq-5}
\left\langle \mathbf{e}^{\alpha}\otimes\nabla\right\rangle =\left\langle \mathbf{e}^{\alpha}\right\rangle \otimes\nabla+\frac{1}{V_{0}}\int_{\Gamma_{0}^{\alpha\beta}}\mathbf{e}^{\alpha}\otimes\mathbf{n}ds
$$

Eq. \ref{eq:eq-2} can be described in the following form.

$$
\label{eq:eq-6}
\mathbf{\nabla\otimes\left\langle \mathbf{e}^{\alpha}\right\rangle }=\frac{1}{V_{0}}\int_{\Gamma_{0}^{\alpha\alpha}}\mathbf{n}\otimes\mathbf{e}^{\alpha}ds
$$

## Important results

Using $\mathbf{e}^{\alpha}=1$ in Eq. \ref{eq:eq-5}:

$$
\nabla\theta^{\alpha}=-\frac{1}{V_{0}}\int_{\Gamma_{0}^{\alpha\beta}}\mathbf{n}ds
$$

Using $\mathbf{e}^{\alpha}=1$ in Eq. \ref{eq:eq-6}:

$$
\mathbf{\nabla\theta^{\alpha}}=\frac{1}{V_{0}}\int_{\Gamma_{0}^{\alpha\alpha}}\mathbf{n}ds
$$

Hence,

$$
\frac{1}{V_{0}}\int_{\Gamma_{0}^{\alpha\alpha}}\mathbf{n}ds+\frac{1}{V_{0}}\int_{\Gamma_{0}^{\alpha\beta}}\mathbf{n}ds=0
$$
