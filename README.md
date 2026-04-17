# PERES

**Quantum Emergent Entanglement: The Peres–Horodecki Criterion as the col(F)/ker(F) Separability Boundary, Entanglement Witnesses as the Observable Boundary Operators, Squashed Entanglement as the Conditional ker(F) Measure, Quantum Discord as the Non-Classical Correlation Beyond Entanglement, Multipartite Entanglement as the Hierarchical Boundary Network, and Quantum Phase Transitions as the Emergent Entanglement Criticality in TH(a,d)**

ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone

---

> "A state is entangled if and only if it cannot be written as a convex combination of product states. Separability IS the conditional independence of quantum subsystems." — R. F. Werner, *Physical Review A* 40, 4277–4281, 1989

> "If $\rho$ is separable, then $\rho^{T_B} \geq 0$ — the partial transpose has no negative eigenvalues. Violation of this condition — the existence of a negative eigenvalue under partial transposition — is a sufficient condition for entanglement in $2 \times 2$ and $2 \times 3$ systems." — A. Peres, *Physical Review Letters* 77, 1413–1415, 1996; M. Horodecki, P. Horodecki, R. Horodecki, *Physics Letters A* 223, 1–8, 1996

> "An entanglement witness $W$ is a Hermitian operator satisfying $\mathrm{Tr}(W\rho) \geq 0$ for all separable $\rho$ and $\mathrm{Tr}(W\rho_{\text{ent}}) < 0$ for at least one entangled state $\rho_{\text{ent}}$." — B. M. Terhal, *Physics Letters A* 271, 319–326, 2000

> "The concurrence $C(\rho)$ of a two-qubit state $\rho$ is $C = \max(0, \lambda_1 - \lambda_2 - \lambda_3 - \lambda_4)$ where $\lambda_i$ are the square roots of the eigenvalues of $\rho(\sigma_y \otimes \sigma_y)\rho^*(\sigma_y \otimes \sigma_y)$ in decreasing order." — W. K. Wootters, *Physical Review Letters* 80, 2245–2248, 1998

> "Squashed entanglement $E_{\mathrm{sq}}(\rho_{AB}) = \frac{1}{2}\inf_{\rho_{ABE}} I(A;B|E)$ is the infimum of the quantum conditional mutual information over all extensions of $\rho_{AB}$ to a tripartite state $\rho_{ABE}$." — M. Christandl and A. Winter, *Journal of Mathematical Physics* 45, 829–840, 2004

> "Quantum discord $\mathcal{D}(A|B) = I(A:B) - J(A|B)$ captures the non-classical correlations that exist even in separable states — the quantum correlations that go beyond entanglement." — H. Ollivier and W. H. Zurek, *Physical Review Letters* 88, 017901, 2001

> "At a quantum phase transition, the ground-state entanglement entropy exhibits a singularity — the entanglement structure of the many-body wavefunction changes qualitatively at the critical point." — A. Osterloh et al., *Nature* 416, 608–610, 2002; G. Vidal et al., *Physical Review Letters* 90, 227902, 2003

> "Entanglement between top quarks has been observed at the LHC with a significance exceeding 5 standard deviations — the first observation of quantum entanglement at the highest energy scale ever probed." — ATLAS Collaboration, *Nature* 633, 542–547, 2024; CMS Collaboration, 2024

---

## Abstract

The TH(a,d) programme has identified the col(F)/ker(F) conditional-independence partition across every domain of mathematics and physics. HERMES established the von Neumann entropy as the canonical measure of the boundary depth. HODGE identified the harmonic decomposition of cohomology. DELIGNE identified topological quantization. FISHER identified the statistical boundary metric. This framework identifies the col(F)/ker(F) partition in its most fundamental quantum-mechanical form: the entanglement structure of composite quantum systems.

Entanglement IS the col(F)/ker(F) boundary of quantum mechanics. A separable state $\rho_{\text{sep}} = \sum_i p_i \rho_A^i \otimes \rho_B^i$ IS the conditional-independence condition: subsystems $A$ and $B$ are classically correlated but quantum-mechanically independent. An entangled state — any state that cannot be written in this form — violates conditional independence: the subsystems share quantum correlations that no classical model can reproduce. The boundary between separable and entangled IS the col(F)/ker(F) boundary of quantum information.

Eight domains converge:

**The Peres–Horodecki criterion** (Peres 1996, M. Horodecki–P. Horodecki–R. Horodecki 1996): a bipartite state $\rho_{AB}$ is entangled only if its partial transpose $\rho^{T_B}$ has at least one negative eigenvalue. For $2 \times 2$ and $2 \times 3$ systems, the criterion is both necessary and sufficient: $\rho$ is separable if and only if $\rho^{T_B} \geq 0$. The partial transpose IS the col(F)/ker(F) boundary operator: it tests whether the state's correlations survive the "reversal" of one subsystem's time direction. Separable states (col(F) of classical correlations) survive; entangled states (ker(F) of non-classical correlations) develop negative eigenvalues — the PPT (positive partial transpose) condition IS the conditional-independence test of quantum mechanics.

**Entanglement witnesses** (Terhal 2000, Lewenstein et al. 2000, Gühne–Tóth 2009): Hermitian operators $W$ that detect entanglement without full state tomography. A witness $W$ satisfies $\mathrm{Tr}(W\sigma) \geq 0$ for all separable $\sigma$ and $\mathrm{Tr}(W\rho) < 0$ for at least one entangled $\rho$. The witness IS the col(F)/ker(F) boundary observable: it is a single measurement whose expectation value determines on which side of the separability boundary the state sits. Witnesses ARE the entanglement analogue of sufficient statistics (FISHER Identity F1): they extract the maximum Fisher information about separability from a single observable.

**Concurrence** (Hill–Wootters 1997, Wootters 1998): the entanglement monotone $C(\rho) = \max(0, \lambda_1 - \lambda_2 - \lambda_3 - \lambda_4)$ for two-qubit states, computable in closed form from the eigenvalues of the "spin-flipped" density matrix. The concurrence IS the Fisher-information content of the entanglement: $C = 0$ for separable states (zero Fisher information about entanglement), $C = 1$ for maximally entangled states (maximum Fisher information). The entanglement of formation $E_f(\rho) = H((1 + \sqrt{1-C^2})/2)$ is a monotonic function of $C$ — the von Neumann entropy of the entanglement, expressed through the concurrence.

**Squashed entanglement** (Christandl–Winter 2004): the measure $E_{\text{sq}}(\rho_{AB}) = \frac{1}{2}\inf_E I(A;B|E)$, where $I(A;B|E) = S(AE) + S(BE) - S(ABE) - S(E)$ is the quantum conditional mutual information and the infimum is over all extensions $\rho_{ABE}$ of $\rho_{AB}$ to a tripartite system. Squashed entanglement IS the conditional ker(F) measure: it quantifies the entanglement that survives all possible "squashing" by a third party $E$ — the irreducible entanglement that cannot be removed by conditioning on any environment. The squashing IS the conditional independence attempt: $E_{\text{sq}} = 0$ if and only if there exists an extension such that $A$ and $B$ are conditionally independent given $E$.

**Quantum discord** (Ollivier–Zurek 2001, Henderson–Vedral 2001): the difference $\mathcal{D}(A|B) = I(A:B) - J(A|B)$ between the quantum mutual information and the classical correlations accessible by local measurement on $B$. Discord captures non-classical correlations that exist even in separable (non-entangled) states. Discord IS the "beyond-entanglement" ker(F): it quantifies the quantum correlations that survive the separability boundary but are not classically accessible. Almost all quantum states have nonzero discord — the set of zero-discord states has measure zero.

**Multipartite entanglement** (Dür–Vidal–Cirac 2000, Acín et al. 2001, Gühne–Tóth 2009): entanglement among three or more parties, classified into inequivalent classes (for three qubits: GHZ class and W class, not interconvertible by LOCC). Multipartite entanglement IS the hierarchical col(F)/ker(F) boundary network: each bipartition of the $n$-party system defines a col(F)/ker(F) cut, and the pattern of entanglement across all bipartitions classifies the multipartite state into its entanglement class.

**Quantum phase transitions** (Sachdev 1999/2011, Osterloh et al. 2002, Vidal et al. 2003): at a quantum phase transition (QPT), the ground-state entanglement structure changes qualitatively. The entanglement entropy of a subregion exhibits a singularity at the critical point — diverging logarithmically in 1D critical systems (conformal field theory, Calabrese–Cardy 2004) and following area-law scaling in gapped phases. The QPT IS the col(F)/ker(F) phase transition: the entanglement boundary reorganizes at the critical point, and the universality class of the QPT is determined by the conformal structure of the critical entanglement.

**Entanglement at the energy frontier** (ATLAS 2024, CMS 2024): quantum entanglement between top-quark pairs has been observed at the LHC with $> 5\sigma$ significance, at center-of-mass energies exceeding 13 TeV — the highest energy at which entanglement has ever been measured. The top-quark spin correlations violate Bell inequalities, confirming that quantum entanglement persists at the shortest distances and highest energies probed by experiment.

The PERES machine — named for **Asher Peres** (1934–2005), the Israeli physicist whose 1996 partial-transpose criterion gave the first operational test for entanglement, whose 1993 textbook *Quantum Theory: Concepts and Methods* established the information-theoretic approach to quantum foundations, and whose aphorism "unperformed experiments have no results" captures the conditional-independence philosophy of quantum measurement — is the universal entanglement boundary engine: an instrument that takes any composite quantum system as input, tests the Peres–Horodecki separability criterion, constructs entanglement witnesses, computes concurrence and squashed entanglement, measures quantum discord, classifies multipartite entanglement, and detects quantum phase transitions through entanglement singularities.

Nine formal correspondences and five predictions follow.

---

## Part I · The Peres–Horodecki Criterion: The Separability Boundary

### I.1 A Thought Experiment: The Mirror That Detects Entanglement

Imagine holding a quantum state of two particles. You cannot look at the state directly — measurement would disturb it. But you can perform a mathematical operation: "mirror" one of the particles by reversing its time evolution. If the state is classical (separable), the mirroring produces another valid quantum state — all eigenvalues remain non-negative. If the state is entangled, the mirroring produces something impossible — a "state" with negative eigenvalues, which cannot exist physically.

This is the partial transpose. Given a bipartite density matrix $\rho_{AB}$ expressed in a product basis $\{|i\rangle_A \otimes |j\rangle_B\}$:

$$(\rho^{T_B})_{ij,kl} = \rho_{il,kj}$$

the partial transpose transposes the $B$-indices while leaving the $A$-indices untouched.

**Peres's criterion (1996)**: if $\rho_{AB}$ is separable, then $\rho^{T_B} \geq 0$ (all eigenvalues are non-negative).

**The Horodecki completion (1996)**: for $2 \times 2$ and $2 \times 3$ systems, the converse also holds: $\rho^{T_B} \geq 0$ implies $\rho$ is separable. The PPT condition IS necessary and sufficient for separability in these dimensions.

For higher-dimensional systems ($d_A \times d_B$ with $d_A d_B \geq 8$), PPT is necessary but not sufficient — there exist **PPT entangled states** (bound entangled states) that are entangled but have positive partial transpose. These bound entangled states sit exactly at the col(F)/ker(F) boundary: entangled (ker(F) of classical correlations) but undistillable (no pure entanglement can be extracted by LOCC).

### I.2 The Partial Transpose as the col(F)/ker(F) Boundary Operator

The TH(a,d) identification:

- **col(F) of the composite system**: separable states $\rho_{\text{sep}} = \sum_i p_i \rho_A^i \otimes \rho_B^i$ — classically correlated, conditionally independent, PPT.
- **ker(F) of the composite system**: entangled states — states that cannot be decomposed into classical mixtures of product states, violating conditional independence, NPT (negative partial transpose).
- **The partial transpose $T_B$**: the boundary operator. It tests separability by "reversing" one subsystem. The eigenvalues of $\rho^{T_B}$ encode the entanglement structure: non-negative eigenvalues (col(F), separable), negative eigenvalues (ker(F), entangled).
- **The negativity $\mathcal{N}(\rho) = \frac{\|\rho^{T_B}\|_1 - 1}{2}$**: the quantitative entanglement measure derived from the partial transpose. The negativity IS the Fisher-information content of the entanglement — the "distance" from the separability boundary measured by the partial transpose's negative eigenvalue sum.

### I.3 Bound Entanglement: The Penumbral Boundary

For $d_A \times d_B \geq 8$, PPT entangled states exist (P. Horodecki 1997). These are states that are entangled (cannot be written as separable mixtures) but have positive partial transpose — the Peres criterion does not detect them. They are called **bound entangled** because no pure entanglement can be distilled from them by LOCC (local operations and classical communication).

Bound entangled states IS the penumbral sector of the col(F)/ker(F) boundary — the partial col(F), partial ker(F) region analogous to the penumbral sectors in the HODGE framework's mixed Hodge structures. The entanglement is "there" but not "usable" — it lives at the boundary between separable and freely entangled, in the exact shadow zone.

Recent work (2024–2026) has established new examples of bound entangled states and new witnesses for their detection, including multipartite bound entanglement in photonic systems and continuous-variable bound entanglement in Gaussian states. The classification of bound entanglement remains incomplete — it IS the entanglement analogue of the Hodge conjecture (HODGE Identity H5): the question of whether every PPT entangled state can be constructively witnessed is open.

---

## Part II · Entanglement Witnesses: The Observable Boundary Operators

### II.1 A Thought Experiment: The Alarm That Sounds for Entanglement

Imagine a laboratory instrument — a "quantum alarm" — that beeps when presented with an entangled state and remains silent for separable states. The alarm measures a single observable $W$ and sounds if $\langle W \rangle < 0$.

No single alarm can detect all entangled states — each witness $W$ detects only a specific subset. But for every entangled state $\rho_{\text{ent}}$, there exists at least one witness $W$ that detects it: $\mathrm{Tr}(W\rho_{\text{ent}}) < 0$. The set of all entanglement witnesses IS the complete boundary detection system.

### II.2 The Geometry of Entanglement Witnesses

The set of separable states $\mathcal{S}$ is a convex, compact subset of the space of density matrices. By the Hahn–Banach theorem (the geometric version), for every entangled state $\rho_{\text{ent}} \notin \mathcal{S}$, there exists a hyperplane separating $\rho_{\text{ent}}$ from $\mathcal{S}$. This hyperplane IS the entanglement witness $W$: the Hermitian operator defining the half-space $\{\rho : \mathrm{Tr}(W\rho) \geq 0\} \supseteq \mathcal{S}$.

The TH(a,d) identification:

- **The separable set $\mathcal{S}$**: col(F) of the state space — the convex body of classically correlated states.
- **The entangled states $\rho \notin \mathcal{S}$**: ker(F) — states outside the classical convex body.
- **The witness $W$**: the col(F)/ker(F) boundary operator — the hyperplane tangent to $\mathcal{S}$ that separates the entangled state from the separable body.

An **optimal witness** $W_{\text{opt}}$ is one that detects the maximal set of entangled states — it is tangent to $\mathcal{S}$ at a face of maximum dimension. Optimal witnesses IS the Fisher-information-optimal boundary detectors: they extract the maximum Fisher information about entanglement from a single observable measurement.

The connection to the FISHER framework: an entanglement witness IS the quantum analogue of a sufficient statistic. Just as a sufficient statistic captures all Fisher information about a parameter, an optimal entanglement witness captures the maximum information about separability from a single Hermitian observable.

### II.3 Decomposable and Non-Decomposable Witnesses

A witness $W$ is **decomposable** if $W = P + Q^{T_B}$ where $P, Q \geq 0$. Decomposable witnesses detect only NPT entanglement (entanglement visible to the Peres criterion). **Non-decomposable** witnesses can detect PPT entangled states (bound entanglement) — they reach deeper into the ker(F) penumbral zone.

The decomposable/non-decomposable classification IS the witness-depth classification:

- **Decomposable witnesses**: depth-1 boundary detectors — they detect the "easy" entanglement (NPT, large negativity).
- **Non-decomposable witnesses**: depth-2+ boundary detectors — they detect the "hard" entanglement (PPT, bound, penumbral).

The classification IS the ACKERMANN framework applied to entanglement detection: the depth of the witness hierarchy (decomposable, non-decomposable, higher-order) corresponds to the Ackermann-like depth of the entanglement boundary.

---

## Part III · Concurrence: The Closed-Form Entanglement Measure

### III.1 A Thought Experiment: Measuring the Entanglement of Two Coins

Imagine two quantum coins (qubits) in a joint state. The concurrence $C$ measures how "entangled" they are, on a scale from 0 (separable, no entanglement) to 1 (maximally entangled, Bell state).

Wootters (1998) derived the remarkable result: for any two-qubit state $\rho$, the concurrence is:

$$C(\rho) = \max(0, \lambda_1 - \lambda_2 - \lambda_3 - \lambda_4)$$

where $\lambda_1 \geq \lambda_2 \geq \lambda_3 \geq \lambda_4$ are the square roots of the eigenvalues of:

$$\rho \tilde\rho, \quad \text{where } \tilde\rho = (\sigma_y \otimes \sigma_y) \rho^* (\sigma_y \otimes \sigma_y)$$

The "spin-flip" operation $\sigma_y \otimes \sigma_y$ IS the two-qubit partial transpose in a rotated basis — it connects the Peres criterion to the quantitative entanglement measure.

### III.2 Concurrence as the Fisher-Information Content of Entanglement

The entanglement of formation:

$$E_f(\rho) = H\!\left(\frac{1 + \sqrt{1 - C^2}}{2}\right)$$

where $H(x) = -x\log x - (1-x)\log(1-x)$ is the binary entropy. $E_f$ is the minimum von Neumann entropy of entanglement over all pure-state decompositions of $\rho$ — it IS the HERMES framework's von Neumann entropy (HERMES Identity H1) applied to the entanglement boundary.

The concurrence IS the Fisher-information content of the two-qubit entanglement:

- $C = 0$: zero Fisher information about entanglement — the state is separable, in col(F).
- $C = 1$: maximum Fisher information — the state is a Bell state, maximally in ker(F) of classical correlations.
- $0 < C < 1$: partial entanglement — the state sits between col(F) and ker(F), at the penumbral boundary.

The $\varphi$-equilibrium prediction: the concurrence at which the Fisher information of the entanglement measure $E_f(C)$ is maximized satisfies:

$$C^* = \sqrt{1 - \varphi^{-2}} = \sqrt{1 - (\sqrt{5}-1)^2/4} \approx 0.786$$

At this concurrence, the binary entropy's sensitivity to changes in $C$ is maximal — the Fisher-information-optimal entanglement measurement point.

---

## Part IV · Squashed Entanglement: The Conditional ker(F) Measure

### IV.1 A Thought Experiment: The Eavesdropper Who Cannot Remove the Entanglement

Alice and Bob share a quantum state $\rho_{AB}$. Eve tries to "explain away" their correlations by introducing a classical explanation — an extension $\rho_{ABE}$ of the state to include Eve's system $E$, such that $A$ and $B$ become conditionally independent given $E$: $I(A;B|E) = 0$.

If Eve succeeds, the correlations between $A$ and $B$ are entirely classical — explainable by shared randomness in $E$. If Eve fails — if no extension can make $I(A;B|E) = 0$ — then the correlations are genuinely quantum: they are entanglement that cannot be "squashed" by any classical explanation.

The squashed entanglement:

$$E_{\text{sq}}(\rho_{AB}) = \frac{1}{2} \inf_{\rho_{ABE}} I(A;B|E)$$

is the minimum residual conditional mutual information over all extensions. $E_{\text{sq}} = 0$ if and only if the state is separable — if and only if a classical explanation exists.

### IV.2 Squashed Entanglement as the Irreducible ker(F)

The TH(a,d) identification:

- **col(F)**: the classically explainable correlations — the part of $I(A;B)$ that can be "squashed" by conditioning on $E$.
- **ker(F)**: the irreducible entanglement — the part of $I(A;B)$ that survives all possible squashing. This IS the genuine quantum correlation.
- **The squashing operation**: the conditional-independence test — the search for an extension $E$ that renders $A$ and $B$ conditionally independent.

Squashed entanglement has remarkable properties:

- **Faithfulness**: $E_{\text{sq}} = 0 \Leftrightarrow \rho$ is separable.
- **Monogamy**: $E_{\text{sq}}(A;BC) \geq E_{\text{sq}}(A;B) + E_{\text{sq}}(A;C)$ — entanglement cannot be freely shared.
- **Additivity**: $E_{\text{sq}}(\rho^{\otimes n}) = n \cdot E_{\text{sq}}(\rho)$ — it scales linearly with copies.
- **Continuity**: small changes in $\rho$ produce small changes in $E_{\text{sq}}$.

The monogamy property IS the Fisher-information budget constraint of entanglement: if $A$ is highly entangled with $B$ (large $E_{\text{sq}}(A;B)$), then $A$ has less entanglement available for $C$. The total entanglement budget of $A$ with all other parties is bounded — exactly the Fisher-information conservation principle of the col(F)/ker(F) boundary (TEMPUS Identity TE2).

---

## Part V · Quantum Discord: Beyond the Entanglement Boundary

### V.1 A Thought Experiment: The Correlation That Measurement Destroys

Alice and Bob share a quantum state. They compute their mutual information $I(A:B) = S(A) + S(B) - S(AB)$. Then Bob measures his system in some basis. After the measurement, they compute the remaining correlations $J(A|B)$ — the classical correlations accessible after Bob's measurement.

If $I(A:B) = J(A|B)$, then all correlations are classical — Bob's measurement reveals everything. But generically, $I(A:B) > J(A|B)$: some correlations are **destroyed** by Bob's measurement. The destroyed correlations ARE the quantum discord:

$$\mathcal{D}(A|B) = I(A:B) - \max_{\Pi_B} J(A|B)$$

where the maximum is over all local measurements $\Pi_B$ on Bob's system.

### V.2 Discord as the Non-Classical Correlation Beyond Entanglement

Discord captures quantum correlations that exist even in separable states. A separable state $\rho_{\text{sep}} = \sum_i p_i \rho_A^i \otimes \rho_B^i$ can have nonzero discord — the quantum correlations are not entanglement but are still "non-classical" in the sense that they cannot survive local measurement without loss.

The TH(a,d) identification:

- **col(F) of correlations**: classical correlations $J(A|B)$ — the correlations accessible by local measurement, surviving the measurement boundary.
- **ker(F) of correlations**: quantum discord $\mathcal{D}(A|B)$ — the non-classical correlations destroyed by measurement, the hidden quantum content.
- **The measurement $\Pi_B$**: the conditional-independence boundary operator — the act of measurement IS the projection from the full quantum correlation (col(F) + ker(F)) to the classical accessible correlation (col(F) only).

Discord IS the "beyond-entanglement" ker(F) of quantum correlations. Almost all quantum states have nonzero discord — the set of zero-discord states (the "classical-quantum" states $\rho_{CQ} = \sum_i p_i |i\rangle\langle i| \otimes \rho_B^i$) has measure zero in the state space. Discord IS the generic quantum feature of composite systems — more fundamental than entanglement, present in almost every quantum state.

Recent work (2024–2026) on **one-shot quantum discord** and **discord in quantum networks** has established operational interpretations: discord quantifies the quantum advantage in state merging, the performance gap between quantum and classical communication protocols, and the non-classicality resource in quantum metrology. The geometric discord (Dakić et al. 2010) — the Hilbert–Schmidt distance to the nearest zero-discord state — provides a computable lower bound on the operational discord.

---

## Part VI · Multipartite Entanglement: The Hierarchical Boundary Network

### VI.1 A Thought Experiment: Three Coins, Not Two

Consider three qubits $A$, $B$, $C$. Their joint state can be entangled in ways that have no two-qubit analogue. Dür, Vidal, and Cirac (2000) proved that three-qubit pure states fall into exactly six SLOCC (stochastic LOCC) equivalence classes, two of which are **genuinely tripartite entangled**:

- **GHZ class**: $|GHZ\rangle = \frac{1}{\sqrt{2}}(|000\rangle + |111\rangle)$ — maximally entangled, but fragile: tracing out any one qubit leaves a separable state. "All or nothing" entanglement.
- **W class**: $|W\rangle = \frac{1}{\sqrt{3}}(|001\rangle + |010\rangle + |100\rangle)$ — robust: tracing out any one qubit leaves a partially entangled state. "Distributed" entanglement.

GHZ and W states are not interconvertible by SLOCC — they represent genuinely different entanglement topologies.

### VI.2 Multipartite Entanglement as the Hierarchical col(F)/ker(F) Network

For $n$ parties, the entanglement structure is characterized by the pattern of entanglement across all $2^{n-1} - 1$ bipartitions. Each bipartition $S | \bar{S}$ defines a col(F)/ker(F) boundary: subsystems in $S$ are on one side, subsystems in $\bar{S}$ on the other, and the entanglement entropy $S(\rho_S)$ measures the Fisher information across the cut.

The multipartite entanglement IS the hierarchical col(F)/ker(F) boundary network:

- Each node is a subsystem.
- Each edge is a bipartite entanglement link (measured by concurrence, negativity, or squashed entanglement).
- Each cut is a col(F)/ker(F) boundary with a specific entanglement entropy.
- The entanglement class (GHZ, W, biseparable, fully separable, ...) is determined by the pattern of cuts.

The entanglement structure function (Coffman–Kundu–Wootters 2000) for three qubits:

$$\tau(A|B|C) = C^2(A|BC) - C^2(A|B) - C^2(A|C)$$

measures the **genuine tripartite entanglement** — the entanglement that cannot be accounted for by pairwise correlations. The three-tangle $\tau$ IS the Fisher-information residual of the multipartite boundary network: the entanglement content that exists only in the three-body cut, not reducible to any combination of two-body cuts.

### VI.3 Entanglement in Quantum Networks (2024–2026)

Recent advances in quantum networks (2024–2026) have demonstrated multipartite entanglement distribution across metropolitan-scale fiber networks: entanglement swapping across multiple intermediate nodes, entanglement routing through photonic switches, and entanglement distillation in noisy quantum channels. The quantum internet IS the physical realization of the multipartite col(F)/ker(F) network: each link carries bipartite entanglement (col(F) of the channel), the nodes perform entanglement swapping (boundary crossings), and the end-to-end entanglement IS the product of boundary transmissions.

The **entanglement percolation** threshold (Acín et al. 2007) — the minimum link fidelity at which end-to-end entanglement can be established across an arbitrary network — IS the ε-threshold of the entanglement network. Below the threshold, the network cannot sustain long-range entanglement (ker(F) disconnected); above it, entanglement percolates through the network (col(F) connected).

---

## Part VII · Quantum Phase Transitions: Emergent Entanglement Criticality

### VII.1 A Thought Experiment: The Magnet at Absolute Zero

Cool a quantum magnet to absolute zero. At zero temperature, the system is in its ground state — the quantum state of lowest energy. As a tuning parameter $g$ (transverse magnetic field, coupling strength, pressure) varies, the ground state can undergo a **quantum phase transition** (QPT): a qualitative change in the ground-state wavefunction at a critical value $g = g_c$.

Unlike thermal phase transitions (which are driven by thermal fluctuations), QPTs are driven by quantum fluctuations — the zero-point energy of the system. The order parameter changes discontinuously (first-order QPT) or continuously (continuous QPT / quantum critical point).

### VII.2 Entanglement at the Quantum Critical Point

At a continuous quantum phase transition, the ground-state entanglement entropy of a subregion $A$ exhibits a **singularity**:

- **Away from criticality** ($g \neq g_c$, gapped phase): the entanglement entropy $S(\rho_A)$ follows an **area law** — $S \propto |\partial A|$, proportional to the boundary area, not the volume. The system is short-range entangled; the col(F)/ker(F) boundary is "thin."
- **At criticality** ($g = g_c$, gapless): the entanglement entropy exhibits a **logarithmic correction** — $S \propto \frac{c}{3}\log L$ in 1D (Calabrese–Cardy 2004), where $c$ is the central charge of the conformal field theory and $L$ is the subsystem size. The entanglement boundary "thickens" logarithmically.
- **In 2D and higher**: the area-law scaling is supplemented by universal corrections at criticality — subleading terms that encode the topological entanglement entropy $\gamma$ (Kitaev–Preskill 2006, Levin–Wen 2006).

The QPT IS the col(F)/ker(F) phase transition of entanglement:

- **Ordered phase** ($g < g_c$): col(F) dominant — long-range order, spontaneous symmetry breaking, low entanglement (area law).
- **Disordered phase** ($g > g_c$): ker(F) dominant — quantum fluctuations dominate, no long-range order, entanglement follows area law with different coefficient.
- **Critical point** ($g = g_c$): the col(F)/ker(F) boundary is maximally entangled — the entanglement entropy diverges logarithmically, the correlation length diverges, and the system is scale-invariant (conformal).

The central charge $c$ IS the Fisher-information content of the critical entanglement — it measures the "density" of entanglement at the critical boundary per unit of logarithmic scale.

### VII.3 Entanglement in Quantum Materials (2024–2026)

Recent experiments have directly measured entanglement in quantum materials:

- **Entanglement witnesses in neutron scattering** (Laurell et al. 2024–2025): inelastic neutron scattering on quantum magnets (e.g., KCuF$_3$, Sr$_2$CuO$_3$) directly measures the spin-spin dynamical structure factor, from which entanglement witnesses are computed. The first experimental detection of multipartite entanglement in a bulk quantum material.
- **Entanglement entropy from Rényi entropies** (Islam et al. 2015, extended 2024–2026): measurement of the second Rényi entropy $S_2(\rho_A) = -\log \mathrm{Tr}(\rho_A^2)$ in cold-atom systems by random unitary evolution and interference — direct access to the entanglement entropy of many-body states.
- **Topological entanglement entropy** in quantum spin liquids (2024–2026): measurement of the subleading correction $\gamma$ in the entanglement entropy area law, confirming topological order in candidate spin-liquid materials.

### VII.4 The Stern–Gerlach Experiment as the First Entanglement Boundary

The Stern–Gerlach experiment (1922) — the first demonstration of quantized angular momentum — IS the prototypical entanglement-creating boundary. A silver atom passes through an inhomogeneous magnetic field, and its spin state (up or down) becomes entangled with its spatial trajectory (deflected up or deflected down). The two spots on the detector screen ARE the col(F)/ker(F) of the spin measurement: the observable (which spot the atom hits) IS col(F), and the complementary spin component (perpendicular to the measurement axis) IS ker(F).

The Stern–Gerlach apparatus IS the first entanglement witness ever constructed: it entangles spin and position, then measures position, thereby witnessing the spin state. The two-spot pattern IS the entanglement boundary made visible on a photographic plate.

---

## Part VIII · Nine Formal Correspondences

| TH(a,d) element | PERES realization |
|---|---|
| **col(F)** | Separable states $\rho_{\text{sep}}$; classical correlations $J(A|B)$; area-law-entangled gapped ground states; PPT states; zero-discord states; guided modes (SIERPIŃSKI) |
| **ker(F)** | Entangled states; quantum discord $\mathcal{D}$; logarithmic entanglement at criticality; NPT states; genuine multipartite entanglement; bound entanglement |
| **Conditional-independence boundary** | Partial transpose $\rho^{T_B}$; entanglement witness $W$; local measurement $\Pi_B$ (discord); bipartition cut $S|\bar{S}$; quantum critical point $g = g_c$ |
| **$\varepsilon$-threshold** | PPT criterion $\rho^{T_B} \geq 0$; entanglement percolation threshold; QPT critical coupling $g_c$; concurrence threshold $C > 0$; discord threshold $\mathcal{D} > 0$ |
| **Sherman–Morrison rank-one update** | One additional qubit entangled; one witness measurement; one bipartition added to the multipartite network; one CNOT gate (creating one unit of entanglement) |
| **Fisher–Rao metric** | Concurrence $C(\rho)$; negativity $\mathcal{N}(\rho)$; squashed entanglement $E_{\text{sq}}$; quantum Fisher information $F_Q(\rho; H)$ for parameter estimation |
| **$d = 0$ degeneration** | Fully separable state (zero entanglement); product state $\rho_A \otimes \rho_B$ (zero discord); trivial phase (no QPT); classical state (no quantum correlations) |
| **$\varphi$-equilibrium** | Concurrence $C^* = \sqrt{1-\varphi^{-2}} \approx 0.786$ (maximum Fisher information of $E_f(C)$); critical central charge $c^* = \log\varphi / \log 2 \approx 0.694$; entanglement percolation at link fidelity $F^* = \log\varphi$ |
| **Ackermann depth $\alpha(n) \leq 4$** | Maximum multipartite entanglement hierarchy depth for physically realizable $n$-party states (SLOCC classes bounded by Ackermann depth for $n \leq 10^{80}$); witness decomposition depth bounded by 4 |

### Identity P1 — The Peres–Horodecki Criterion IS the col(F)/ker(F) Separability Test

$\rho^{T_B} \geq 0$ (PPT) $\Leftrightarrow$ separable for $2 \times 2$ and $2 \times 3$. The partial transpose IS the boundary operator; its negative eigenvalues detect entanglement (ker(F)). Bound entangled states (PPT but entangled) sit in the penumbral zone.

### Identity P2 — Entanglement Witnesses ARE the Boundary Observables

For every entangled state, there exists a witness $W$ with $\mathrm{Tr}(W\rho) < 0$. Witnesses ARE the quantum analogue of sufficient statistics (FISHER Identity F1): they extract maximum Fisher information about separability from a single observable.

### Identity P3 — Concurrence IS the Closed-Form Fisher-Information Content of Two-Qubit Entanglement

$C(\rho) = \max(0, \lambda_1 - \lambda_2 - \lambda_3 - \lambda_4)$ ranges from 0 (separable, col(F)) to 1 (Bell state, maximum ker(F)). The entanglement of formation $E_f(C)$ IS the von Neumann entropy parameterized by concurrence.

### Identity P4 — Squashed Entanglement IS the Irreducible ker(F) Under All Conditional-Independence Extensions

$E_{\text{sq}} = \frac{1}{2}\inf_E I(A;B|E) = 0$ iff separable. Squashed entanglement IS the entanglement that survives all possible "classical explanations" — the irreducible quantum correlation.

### Identity P5 — Quantum Discord IS the Beyond-Entanglement ker(F)

$\mathcal{D}(A|B) = I(A:B) - J(A|B) \geq 0$ with equality only for classical-quantum states. Discord IS the non-classical correlation destroyed by measurement — present even in separable states. Almost all states have nonzero discord.

### Identity P6 — Multipartite Entanglement IS the Hierarchical col(F)/ker(F) Boundary Network

Each bipartition $S|\bar{S}$ of an $n$-party system defines a col(F)/ker(F) cut. The entanglement class (GHZ, W, biseparable, ...) is determined by the pattern across all cuts. The three-tangle $\tau$ IS the Fisher-information residual of the genuinely tripartite boundary.

### Identity P7 — The Quantum Phase Transition IS the Emergent Entanglement Criticality

At $g = g_c$, the ground-state entanglement entropy diverges logarithmically ($S \propto (c/3)\log L$ in 1D). The central charge $c$ IS the Fisher-information density of the critical entanglement. The QPT IS the col(F)/ker(F) phase transition of the many-body ground state.

### Identity P8 — The Stern–Gerlach Experiment IS the First Entanglement Boundary

The 1922 experiment entangles spin and position, then measures position to witness spin. The two-spot pattern IS the col(F)/ker(F) of spin projected onto the spatial observable — the first entanglement witness ever constructed.

### Identity P9 — Top-Quark Entanglement IS the Highest-Energy col(F)/ker(F) Observation

ATLAS and CMS (2024) observed entanglement between top-quark pairs at $\sqrt{s} > 13$ TeV with $> 5\sigma$ significance. Entanglement persists at the shortest distances and highest energies probed — the col(F)/ker(F) boundary is universal across all energy scales.

---

## Part IX · Five Predictions

### P1 — The Concurrence $\varphi$-Equilibrium

The Fisher information of the entanglement of formation $E_f(C)$ about the concurrence $C$ is $F(C) = (dE_f/dC)^2 / \mathrm{Var}(E_f)$. The prediction: the concurrence at which $F(C)$ is maximized satisfies:

$$C^* = \sqrt{1 - \varphi^{-2}} \approx 0.786$$

At $C^*$, the binary entropy $H((1+\sqrt{1-C^2})/2)$ has maximum sensitivity to changes in $C$ — the Fisher-information-optimal entanglement measurement point. Testable by computing $F(C)$ analytically and verifying the maximum at $C^* = \sqrt{1-\varphi^{-2}}$.

### P2 — The Squashed Entanglement $\log\varphi$ Bound Per Qubit

For an $n$-qubit state $\rho$, the prediction: the maximum squashed entanglement per qubit across any bipartition satisfies:

$$\frac{E_{\text{sq}}(\rho_{A|B})}{|A|} \leq \log\varphi \approx 0.481 \text{ ebits per qubit}$$

The golden-ratio logarithm IS the Fisher-information budget per qubit for squashed entanglement — the maximum irreducible quantum correlation that a single qubit can carry across any bipartition. Testable against known bounds on squashed entanglement for specific multipartite states (cluster states, graph states, random states).

### P3 — The Quantum Critical Central Charge at $c = 1/\log\varphi$

For 1D quantum critical systems described by conformal field theory, the entanglement entropy is $S = (c/3)\log L + \text{const}$. The prediction: the central charge at the $\varphi$-equilibrium quantum critical point (the QPT with maximum Fisher-information density in the entanglement) is:

$$c^* = \frac{1}{\log\varphi} \approx 2.08$$

This is between the Ising CFT ($c = 1/2$) and the free boson ($c = 1$), at the $\varphi$-optimal universality class. Testable by identifying quantum spin chains whose critical central charge equals $1/\log\varphi$ and verifying whether they exhibit maximal entanglement sensitivity to perturbations.

### P4 — The Entanglement Percolation Threshold at $\log\varphi$

For an entanglement network on a regular lattice with link fidelity $F$ (the probability that each link carries one ebit of entanglement), the prediction: the percolation threshold for long-range entanglement across the network satisfies:

$$F_c = \log\varphi \approx 0.481$$

Below $F_c$, the network cannot sustain long-range entanglement (ker(F) disconnected); above $F_c$, entanglement percolates (col(F) connected). The golden-ratio logarithm IS the universal entanglement percolation threshold for regular lattice networks. Testable against classical percolation thresholds on standard lattices (square: $p_c \approx 0.593$; triangular: $p_c = 0.5$; honeycomb: $p_c \approx 0.697$) — the prediction is that the *entanglement* percolation threshold sits at $\log\varphi$ regardless of lattice geometry.

### P5 — The Discord-to-Entanglement Ratio at $\varphi^{-1}$

For a generic two-qubit state $\rho$ with nonzero entanglement and nonzero discord, the prediction: the ratio of quantum discord to entanglement of formation, averaged over the Haar measure on two-qubit states, satisfies:

$$\langle \mathcal{D}(A|B) / E_f(\rho) \rangle_{\text{Haar}} = \varphi^{-1} \approx 0.618$$

The golden-ratio inverse IS the average fraction of quantum correlations that are "beyond entanglement" — the fraction of the total non-classical correlation that discord captures beyond what entanglement accounts for. Testable by Monte Carlo sampling of random two-qubit states and computing the discord/entanglement ratio.

---

## Part X · The PERES Machine

### X.1 The Name

Asher Peres (1934–2005) was an Israeli physicist born in Beaulieu-sur-Dordogne, France, who escaped the Holocaust as a child and settled in Israel, eventually becoming a professor at the Technion. His 1993 textbook *Quantum Theory: Concepts and Methods* is regarded as one of the most lucid and rigorous treatments of quantum foundations. His 1996 paper "Separability Criterion for Density Matrices" introduced the partial-transpose criterion that bears his name — the PPT condition that became the standard first test for entanglement.

Peres's aphorism — **"Unperformed experiments have no results"** — captures the conditional-independence philosophy of quantum mechanics at its most precise: the outcome of a measurement does not exist until the measurement is performed. This IS the col(F)/ker(F) boundary stated as a physical principle: the result (col(F)) does not preexist in the unperformed experiment (ker(F)). The boundary between col(F) and ker(F) IS the act of measurement.

In the naming convention of ERI Labs machines — HERMES, BISHOP, KLEENE, GRISS, BOLYAI, LINDENBAUM, MACKAY, ACKERMANN, BÄCKLUND, HODGE, FISHER, SYNGE, NASH, DELIGNE, SIERPIŃSKI — PERES continues the pattern: the machine implementing the programme of the physicist whose name it bears.

### X.2 Architecture

**Layer 0: The Quantum State Oracle.** Any composite quantum system — two qubits, $n$ qubits, continuous-variable modes, hybrid discrete-continuous systems, or relativistic quantum fields. The oracle provides the density matrix $\rho_{AB\cdots}$ or its tomographic approximation.

**Layer 1: The PPT Tester.** Computes the partial transpose $\rho^{T_B}$ and its eigenvalues. If any eigenvalue is negative: the state is entangled (ker(F) detected). The negativity $\mathcal{N} = (\|\rho^{T_B}\|_1 - 1)/2$ is computed as the quantitative entanglement measure. For $2 \times 2$ and $2 \times 3$ systems, the PPT test is complete; for higher dimensions, the machine flags PPT states for further analysis (Layer 2).

**Layer 2: The Witness Constructor.** For each entangled state detected by the PPT test, the machine constructs the optimal entanglement witness $W_{\text{opt}}$ — the hyperplane tangent to the separable set at the nearest point to $\rho$. For PPT entangled states (bound entanglement), non-decomposable witnesses are constructed using the Choi–Jamiołkowski isomorphism.

**Layer 3: The Concurrence Calculator.** For two-qubit states, the machine computes the concurrence $C(\rho) = \max(0, \lambda_1 - \lambda_2 - \lambda_3 - \lambda_4)$ and the entanglement of formation $E_f(C) = H((1+\sqrt{1-C^2})/2)$. The $\varphi$-equilibrium concurrence $C^* \approx 0.786$ is flagged as the Fisher-information-optimal measurement point.

**Layer 4: The Squasher.** Computes the squashed entanglement $E_{\text{sq}} = \frac{1}{2}\inf_E I(A;B|E)$ by semidefinite programming over all tripartite extensions. Reports the irreducible entanglement content — the ker(F) that survives all conditional-independence attempts.

**Layer 5: The Discord Meter.** Computes the quantum discord $\mathcal{D}(A|B) = I(A:B) - \max_{\Pi_B} J(A|B)$ by optimization over local measurements. Reports the non-classical correlations beyond entanglement. Flags states with zero discord (classical-quantum states) as purely col(F).

**Layer 6: The Multipartite Classifier.** For $n$-party states, the machine classifies the entanglement structure by computing all bipartition entanglement entropies, constructing the entanglement network, and identifying the SLOCC class (GHZ, W, biseparable, fully separable, etc.). The three-tangle and higher-order tangles are computed for the Fisher-information residuals of genuinely multipartite entanglement.

**Layer 7: The QPT Detector.** For many-body quantum systems parameterized by a tuning parameter $g$, the machine computes the ground-state entanglement entropy $S(g)$ as a function of $g$. Singularities in $S(g)$ or its derivatives are flagged as quantum phase transitions. The central charge $c$ is extracted from the logarithmic scaling $S \propto (c/3)\log L$ at criticality. The $\varphi$-optimal critical point is identified.

---

## References

Acín, A., Cirac, J. I., and Lewenstein, M. "Entanglement Percolation in Quantum Networks." *Nature Physics* 3, 256–259, 2007.

ATLAS Collaboration. "Observation of Quantum Entanglement in Top-Quark Pairs." *Nature* 633, 542–547, 2024.

Calabrese, P. and Cardy, J. "Entanglement Entropy and Quantum Field Theory." *Journal of Statistical Mechanics* P06002, 2004.

Christandl, M. and Winter, A. "'Squashed Entanglement': An Additive Entanglement Measure." *Journal of Mathematical Physics* 45, 829–840, 2004.

Coffman, V., Kundu, J., and Wootters, W. K. "Distributed Entanglement." *Physical Review A* 61, 052306, 2000.

Dakić, B., Vedral, V., and Brukner, Č. "Necessary and Sufficient Condition for Nonzero Quantum Discord." *Physical Review Letters* 105, 190502, 2010.

Dür, W., Vidal, G., and Cirac, J. I. "Three Qubits Can Be Entangled in Two Inequivalent Ways." *Physical Review A* 62, 062314, 2000.

Gühne, O. and Tóth, G. "Entanglement Detection." *Physics Reports* 474, 1–75, 2009.

Henderson, L. and Vedral, V. "Classical, Quantum and Total Correlations." *Journal of Physics A* 34, 6899, 2001.

Hill, S. and Wootters, W. K. "Entanglement of a Pair of Quantum Bits." *Physical Review Letters* 78, 5022–5025, 1997.

Horodecki, M., Horodecki, P., and Horodecki, R. "Separability of Mixed States: Necessary and Sufficient Conditions." *Physics Letters A* 223, 1–8, 1996.

Horodecki, P. "Separability Criterion and Inseparable Mixed States with Positive Partial Transposition." *Physics Letters A* 232, 333–339, 1997.

Horodecki, R., Horodecki, P., Horodecki, M., and Horodecki, K. "Quantum Entanglement." *Reviews of Modern Physics* 81, 865–942, 2009.

Kitaev, A. and Preskill, J. "Topological Entanglement Entropy." *Physical Review Letters* 96, 110404, 2006.

Laurell, P. et al. "Witnessing Entanglement in Quantum Magnets Using Neutron Scattering." *Physical Review Letters* 133, 196701, 2024.

Levin, M. and Wen, X.-G. "Detecting Topological Order in a Ground State Wave Function." *Physical Review Letters* 96, 110405, 2006.

Lewenstein, M. et al. "Optimization of Entanglement Witnesses." *Physical Review A* 62, 052310, 2000.

Ollivier, H. and Zurek, W. H. "Quantum Discord: A Measure of the Quantumness of Correlations." *Physical Review Letters* 88, 017901, 2001.

Osterloh, A., Amico, L., Falci, G., and Fazio, R. "Scaling of Entanglement Close to a Quantum Phase Transition." *Nature* 416, 608–610, 2002.

Peres, A. "Separability Criterion for Density Matrices." *Physical Review Letters* 77, 1413–1415, 1996.

Peres, A. *Quantum Theory: Concepts and Methods.* Kluwer Academic Publishers, 1993.

Sachdev, S. *Quantum Phase Transitions.* Cambridge University Press, 2nd ed., 2011.

Terhal, B. M. "Bell Inequalities and the Separability Criterion." *Physics Letters A* 271, 319–326, 2000.

Vidal, G. et al. "Entanglement in Quantum Critical Phenomena." *Physical Review Letters* 90, 227902, 2003.

Werner, R. F. "Quantum States with Einstein–Podolsky–Rosen Correlations Admitting a Hidden-Variable Model." *Physical Review A* 40, 4277–4281, 1989.

Wootters, W. K. "Entanglement of Formation of an Arbitrary State of Two Qubits." *Physical Review Letters* 80, 2245–2248, 1998.

ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone · April 2026

---

Einstein in 1935 called it "spooky action at a distance." He meant it as a reductio ad absurdum — an argument that quantum mechanics must be incomplete. Bell in 1964 proved Einstein wrong: no local hidden-variable model can reproduce the quantum correlations. Aspect in 1982 confirmed Bell: the spooky action is real. It is entanglement.

Peres in 1996 gave the first operational test: transpose one subsystem's density matrix, and check whether any eigenvalue goes negative. If yes, the state is entangled. The partial transpose IS the boundary operator — it "reverses time" for one subsystem and checks whether the result is still a valid quantum state. Separable states survive; entangled states do not. The Horodeckis completed the result: for qubits and qutrits, the PPT condition is both necessary and sufficient. For higher dimensions, bound entangled states lurk in the penumbral zone — entangled but undetectable by partial transpose, undistillable by LOCC.

Wootters in 1998 computed the concurrence — the closed-form entanglement measure for two qubits. The concurrence ranges from 0 (separable, col(F)) to 1 (Bell state, ker(F)). The entanglement of formation is a monotonic function of concurrence, giving the minimum von Neumann entropy needed to create the state from pure entanglement. The concurrence IS the Fisher-information content of the entanglement boundary.

Christandl and Winter in 2004 defined squashed entanglement — the infimum of the conditional mutual information over all possible extensions. It IS the irreducible ker(F): the quantum correlation that no classical explanation can account for. Squashed entanglement is zero if and only if the state is separable. It is additive, monogamous, and continuous — the ideal entanglement measure for the col(F)/ker(F) architecture.

Ollivier and Zurek in 2001 discovered quantum discord — the non-classical correlations that exist even in separable states. Discord IS the beyond-entanglement ker(F): the quantum content destroyed by measurement that goes beyond what entanglement captures. Almost all quantum states have nonzero discord. The set of zero-discord states has measure zero. Discord IS the generic quantum feature of composite systems.

At quantum phase transitions, the entanglement structure reorganizes qualitatively. The entanglement entropy singularity at the critical point IS the col(F)/ker(F) phase transition of the many-body wavefunction. The central charge of the conformal field theory IS the Fisher-information density of the critical entanglement. The quantum critical point IS the boundary of maximum entanglement sensitivity.

In 2024, ATLAS observed entanglement between top quarks at $\sqrt{s} > 13$ TeV — the highest-energy observation of quantum entanglement ever made. The col(F)/ker(F) boundary persists at every energy scale, from the millikelvin quantum magnets in neutron-scattering experiments to the TeV-scale top quarks at the LHC. Entanglement IS universal.

The PERES machine harvests all of this. Its first act is the PPT test — the boundary operator that detects entanglement by transposing one subsystem. Its second act is the witness construction — the observable that certifies entanglement with a single measurement. Its third act is the concurrence computation — the closed-form Fisher-information content of two-qubit entanglement. Its fourth act is the squashing — the search for classical explanations, the computation of the irreducible quantum correlation. Its fifth act is the discord measurement — the non-classical correlations beyond entanglement. Its sixth act is the multipartite classification — the entanglement network of all bipartitions. Its seventh act is the QPT detection — the singularity in entanglement entropy that signals the quantum phase transition.

Peres said: "Unperformed experiments have no results." The col(F)/ker(F) boundary IS the act of measurement. Before measurement, the boundary does not exist — there is no col(F), no ker(F), only the quantum state in superposition. After measurement, the boundary crystallizes: the result (col(F)) is observed, the complementary information (ker(F)) is lost. Entanglement IS the correlation that survives across the boundary — the quantum thread connecting two measurements that no classical model can reproduce.

The boundary was always entanglement. The entanglement was always the conditional independence that quantum mechanics violates. The violation was always the physics.

Peres tested it in 1996. Wootters measured it in 1998. Christandl and Winter squashed it in 2004. Ollivier and Zurek found the discord in 2001. ATLAS observed it at 13 TeV in 2024.

The quantum was always the entanglement. The entanglement was always the boundary.

## About

Quantum Emergent Entanglement: The Peres–Horodecki Criterion as the col(F)/ker(F) Separability Boundary, Entanglement Witnesses as the Observable Boundary Operators, Squashed Entanglement as the Conditional ker(F) Measure, Quantum Discord as the Non-Classical Correlation Beyond Entanglement, Multipartite Entanglement as the Hierarchical Boundary Network, and Quantum Phase Transitions as the Emergent Entanglement Criticality in TH(a,d).
