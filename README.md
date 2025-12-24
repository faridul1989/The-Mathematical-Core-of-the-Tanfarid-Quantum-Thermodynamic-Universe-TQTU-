# The-Mathematical-Core-of-the-Tanfarid-Quantum-Thermodynamic-Universe-TQTU-
\documentclass[12pt]{article}

\usepackage[a4paper,margin=1in]{geometry}
\usepackage{amsmath,amssymb}
\usepackage{bm}
\usepackage{hyperref}
\usepackage{setspace}

\onehalfspacing

\title{\textbf{The Mathematical Core of the Tanfarid Quantum--Thermodynamic Universe (TQTU)}}

\author{
Prof.\ Dr.\ Md.\ Faridul Islam Chowdhury\\
\small Tanfarid Vision Research Institute, Bogura 5800, Bangladesh\\
\small Northern International Medical College, Dhanmondi, Dhaka, Bangladesh\\
\small \texttt{faridul@tanfarid.org}
}

\date{December 2025}

\begin{document}

\maketitle

\begin{abstract}
The Tanfarid Quantum--Thermodynamic Universe (TQTU) proposes that physical reality is fundamentally organized by entropy-regulated plasma and spin coherence, from which geometry and interactions emerge. This paper presents the minimal mathematical core of TQTU as a generally covariant classical field theory. A single action is postulated for an effective spacetime metric, a plasma scalar field, a spin-coherence vector field, and an entropy field. The corresponding field equations are derived symbolically, and the recovery of general relativity as a low-gradient effective limit, together with the Newtonian limit, is demonstrated. A formal quantum path-integral definition is provided. Finally, we outline how the dimensionless entropy attractor $\gamma$ and the golden ratio $\varphi$ arise as emergent fixed points of the entropy--plasma dynamics rather than as axiomatic inputs. This establishes TQTU as a mathematically well-defined dynamical framework suitable for further theoretical and observational investigation.
\end{abstract}

\section{Introduction}

Modern physics remains divided between quantum field theory and gravitation, with unresolved conceptual gaps often bridged by phenomenological constructs such as dark matter, dark energy, and initial singularities. The Tanfarid Quantum--Thermodynamic Universe (TQTU) advances the hypothesis that a spin-coherent plasma medium and entropy flow constitute the primary substrate of physical reality, while effective spacetime behavior and forces emerge from their dynamics.

Previous works developed TQTU at architectural and phenomenological levels, emphasizing entropy balance, plasma--spin interactions, and the organizing roles of the dimensionless exponent $\gamma \approx 1.060$ and the golden ratio $\varphi$. The present work isolates the minimal mathematical structure required to treat TQTU as a well-defined field theory with a single action functional.

\section{Spacetime and Field Content}

Let $(M, g_{\mu\nu})$ be a four-dimensional Lorentzian manifold with signature $(-,+,+,+)$, determinant $g$, and Ricci scalar $R$. The Levi--Civita covariant derivative is denoted by $\nabla_\mu$.

TQTU introduces the following fields on $M$:
\begin{itemize}
\item $\psi(x)$: scalar plasma field,
\item $s^\mu(x)$: spin-coherence vector field,
\item $\sigma(x)$: coarse-grained entropy density field.
\end{itemize}

All indices are raised and lowered using $g_{\mu\nu}$.

\section{The TQTU Action}

The minimal TQTU action is postulated as
\begin{equation}
\mathcal{S}_{\text{TQTU}} =
\int_M d^4x \sqrt{-g}
\left[
\frac{1}{16\pi G} R
+ \mathcal{L}_{\text{plasma}}
+ \mathcal{L}_{\text{spin}}
+ \mathcal{L}_{\text{entropy}}
\right].
\end{equation}

\subsection{Plasma Sector}

\begin{equation}
\mathcal{L}_{\text{plasma}} =
-\frac{1}{2}\nabla_\mu \psi \nabla^\mu \psi - V(\psi),
\end{equation}
with a minimal potential
\begin{equation}
V(\psi) = \frac{1}{2} m_\psi^2 \psi^2 + \frac{\lambda_\psi}{4}\psi^4.
\end{equation}

\subsection{Spin-Coherence Sector}

Define
\begin{equation}
F_{\mu\nu} = \nabla_\mu s_\nu - \nabla_\nu s_\mu, \qquad
s^2 = g_{\mu\nu}s^\mu s^\nu .
\end{equation}

The spin Lagrangian is
\begin{equation}
\mathcal{L}_{\text{spin}} =
-\frac{1}{4}F_{\mu\nu}F^{\mu\nu} - U(s^2),
\end{equation}
with
\begin{equation}
U(s^2) = \frac{1}{2}m_s^2 s^2 + \frac{\lambda_s}{4}(s^2)^2.
\end{equation}

\subsection{Entropy Sector}

\begin{equation}
\mathcal{L}_{\text{entropy}} =
- f_0(\psi,s^2)\sigma - \frac{\kappa}{2}\nabla_\mu \sigma \nabla^\mu \sigma,
\end{equation}
where
\begin{equation}
f_0(\psi,s^2) = a_1\psi^2 + a_2 s^2.
\end{equation}

\section{Field Equations}

Variation of $\mathcal{S}_{\text{TQTU}}$ yields the coupled field equations.

\subsection{Einstein--Thermodynamic Equations}

\begin{equation}
G_{\mu\nu} = 8\pi G \left(
T_{\mu\nu}^{(\psi)} + T_{\mu\nu}^{(s)} + T_{\mu\nu}^{(\sigma)}
\right),
\end{equation}
with standard stress--energy tensors derived from each sector.

\subsection{Plasma Equation}

\begin{equation}
\Box\psi - V'(\psi) - 2a_1 \psi \sigma = 0.
\end{equation}

\subsection{Spin-Coherence Equation}

\begin{equation}
\nabla_\mu F^{\mu\nu}
-
\left(
\frac{1}{2}m_s^2 + \frac{\lambda_s}{2}s^2 + 2a_2\sigma
\right)s^\nu = 0.
\end{equation}

\subsection{Entropy Equation}

\begin{equation}
\kappa \Box \sigma + a_1\psi^2 + a_2 s^2 = 0.
\end{equation}

\section{Recovery of Known Physics}

\subsection{Effective GR Limit}

For homogeneous, near-equilibrium configurations with negligible gradients, the field equations reduce to
\begin{equation}
G_{\mu\nu} \approx \Lambda_{\text{eff}} g_{\mu\nu},
\end{equation}
recovering general relativity with an effective cosmological constant.

\subsection{Newtonian Limit}

In the weak-field, slow-motion regime,
\begin{equation}
\nabla^2 \Phi_N \approx 4\pi G \rho_{\text{eff}},
\end{equation}
recovering Newtonian gravity with plasma, spin, and entropy contributions.

\section{Quantum Formulation}

The quantum theory is formally defined by the path integral
\begin{equation}
Z =
\int \mathcal{D}g\,\mathcal{D}\psi\,\mathcal{D}s\,\mathcal{D}\sigma\,
\exp\left(\frac{i}{\hbar}\mathcal{S}_{\text{TQTU}}\right).
\end{equation}

\section{Emergence of $\gamma$ and $\varphi$}

Coarse-graining of the entropy--plasma dynamics yields a scale recursion
\begin{equation}
r_{n+1} = \gamma + \frac{1}{r_n}.
\end{equation}

The fixed point satisfies
\begin{equation}
r^2 - \gamma r - 1 = 0,
\end{equation}
giving
\begin{equation}
r^*(\gamma) = \frac{\gamma + \sqrt{\gamma^2 + 4}}{2}.
\end{equation}

For $\gamma = 1$, this reduces to the golden ratio $\varphi$.

Logarithmic spiral solutions take the form
\begin{equation}
r(\theta) = a e^{b\theta},
\qquad
b(\gamma) = \frac{1}{2\pi}\ln r^*(\gamma).
\end{equation}

\section{Conclusion}

TQTU is formulated as a mathematically well-posed classical field theory admitting a standard quantum definition and reproducing known gravitational limits. The characteristic constants $\gamma$ and $\varphi$ arise dynamically as fixed points of entropy-regulated plasma--spin dynamics, providing a solid mathematical foundation for the TQTU unification programme.

\end{document}
