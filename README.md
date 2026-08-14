# Tight Logarithmic Bounds for Adversarial Online Phase Retrieval

## Abstract

We study realizable online phase retrieval: after an adversarial sensing vector $x_t$, a learner predicts the amplitude $|\left\langle w_*,x_t\right\rangle|$ and then observes it exactly. Recent work proves an $O(\log^4 d)$ information-theoretic bound for bounded two-ReLU regression and an $\Omega(\log d)$ lower bound using the absolute-linear subclass. We close this gap for that subclass with an efficiently implementable horizon-free bound. Our algorithm lifts amplitudes to binary measurements of a density matrix and projects onto each revealed measurement constraint in quantum relative entropy. A quantum Pythagorean inequality and data processing make the measured Kullback-Leibler divergences telescope. Consequently, cumulative KL and squared Hellinger loss for arbitrary adaptive positive-operator-valued measurements are at most $D(\rho_*\\|\rho_1)$. For a uniform prior this is $\log d-S(\rho_*)$. We prove that the KL value is exactly $\log(d/r)$ on maximally mixed rank-$r$ targets and give an effective-dimension Hellinger lower bound, making the entropy adaptation minimax sharp. The phase lift gives total squared amplitude loss at most $\log d$ for every horizon. A fixed target chosen before play and a nonanticipating dyadic sensing strategy force $\frac14\lfloor\log_2d\rfloor$ expected loss in $d-1$ rounds, with a matching lower-tail guarantee. Thus the worst-horizon minimax loss is $\Theta(\log d)$. We also prove a certified-interval upper bound of order $\log d+\sum_t\epsilon_t^2$ and a matching $\Omega(\log d+T\epsilon^2)$ lower bound for constant radius. Binary updates reduce to one-dimensional matrix-exponential root finding. The result requires exact probabilities or certified intervals, not sampled quantum outcomes.

## Keywords

tight, logarithmic, bounds, adversarial, online, phase, retrieval, study, realizable

## Files

- `main.pdf`, `supplement.pdf`
- `main.tex`, `supplement.tex`
- `references.bib`
- `aistats2027.sty`, `fancyhdr.sty`
- `main.pdf.ots`, `supplement.pdf.ots`, `README.md.ots` OpenTimestamps priority proofs
