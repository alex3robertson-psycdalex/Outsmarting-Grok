Is 1/0 the same as 2/0

Thought for 29s

No, 10\frac{1}{0}\frac{1}{0}
 is not the same as 20\frac{2}{0}\frac{2}{0}
 in standard mathematics.In the real numbers (the usual number system we use for everyday math), division by zero is undefined. Neither expression has a value:There is no real number ( k ) such that 1=k×01 = k \times 01 = k \times 0
, because anything times 0 is 0.
There is no real number ( m ) such that 2=m×02 = m \times 02 = m \times 0
, for the exact same reason.

Since neither side of the equation has a defined value, you cannot say they are equal (or "the same"). They are simply invalid operations. Equality only applies to actual numbers.Why people sometimes think they’re “the same”You might hear someone claim “both equal infinity.” That’s a loose way of thinking about limits:As ( x ) approaches 0 from the positive side, 1x\frac{1}{x}\frac{1}{x}
 and 2x\frac{2}{x}\frac{2}{x}
 both grow without bound toward +∞+\infty+\infty
.

But even then, +∞+\infty+\infty
 is not a real number—it’s a symbol for “grows forever.” The two expressions still aren’t literally equal; they’re just both going to the same “place” in a loose sense. (And if you approach 0 from the negative side, both go to −∞-\infty-\infty
.)In more advanced systemsSome extended number systems treat them differently:In the Riemann sphere (complex numbers plus infinity), both 10\frac{1}{0}\frac{1}{0}
 and 20\frac{2}{0}\frac{2}{0}
 map to the single “point at infinity.” In that very specific context, they can be considered the same.
Computer algebra systems like SymPy actually output the same symbol (zoo = complex infinity) for both and say they are equal under that model.

But these are not the default real-number arithmetic most people mean when they ask this question. In school math, calculus, physics, etc., we simply say both are undefined and leave it at that.Bottom line: 10≠20\frac{1}{0} \neq \frac{2}{0}\frac{1}{0} \neq \frac{2}{0}
 because neither is a number at all. They’re both meaningless in ordinary math.

Explain Riemann sphere infinity

Limits of rational functions

Think about duals and such

Thought for 1m 19s

In dual numbers (and similar algebraic extensions like “duals and such”), 10\frac{1}{0}\frac{1}{0}
 and 20\frac{2}{0}\frac{2}{0}
 are still undefined — they don’t become equal or gain special status that distinguishes them.Dual numbers are expressions of the form a+bϵa + b\epsilona + b\epsilon
 where ( a, b ) are reals and ϵ2=0\epsilon^2 = 0\epsilon^2 = 0
 (but ϵ≠0\epsilon \neq 0\epsilon \neq 0
). They’re useful for automatic differentiation, but division works only when the real part of the denominator is nonzero:
a+bϵc+dϵ=ac−ad−bcc2ϵ(c≠0).\frac{a + b\epsilon}{c + d\epsilon} = \frac{a}{c} - \frac{ad - bc}{c^2}\epsilon \quad (c \neq 0).\frac{a + b\epsilon}{c + d\epsilon} = \frac{a}{c} - \frac{ad - bc}{c^2}\epsilon \quad (c \neq 0).

If the denominator is purely non-real (real part = 0), it’s a zero divisor and division is undefined. So 0=0+0ϵ0 = 0 + 0\epsilon0 = 0 + 0\epsilon
 still blocks division entirely — 10\frac{1}{0}\frac{1}{0}
 and 20\frac{2}{0}\frac{2}{0}
 remain invalid, just like in the reals. No equality, no infinity element here.However, if “duals and such” points toward structures that deliberately allow division by zero (wheels, projective extensions, etc.), then yes — 10\frac{1}{0}\frac{1}{0}
 and 20\frac{2}{0}\frac{2}{0}
 are the same.The most relevant is wheel theory (which extends any commutative ring so division is always defined, including by zero). The classic example is the wheel of real numbers R⊙\mathbb{R}^\odot\mathbb{R}^\odot
, built from pairs ( (a : b) ) (think “fractions” with special rules). Key points:10=1:0=∞\frac{1}{0} = 1:0 = \infty\frac{1}{0} = 1:0 = \infty
 (unsigned infinity).  
20=2:0=∞\frac{2}{0} = 2:0 = \infty\frac{2}{0} = 2:0 = \infty
 (the exact same element).  
In fact, for any nonzero real ( x ), x0=∞\frac{x}{0} = \infty\frac{x}{0} = \infty
.  
There’s also a special “nullity” or bottom element ⊥=0:0=00\bot = 0:0 = \frac{0}{0}\bot = 0:0 = \frac{0}{0}
, which absorbs inconsistencies (e.g., ∞×0=⊥\infty \times 0 = \bot\infty \times 0 = \bot
, so you don’t get the collapse 1=21 = 21 = 2
 that naive attempts at 10\frac{1}{0}\frac{1}{0}
 produce).

This wheel is geometrically the real projective line (a circle) plus the extra hub point ⊥\bot\bot
. It’s inspired by projective geometry, where homogeneous coordinates identify scalar multiples: ( [1 : 0] ) and ( [2 : 0] ) are the same point at infinity.The projectively extended real line (without the extra ⊥\bot\bot
) does the same thing cleanly:
a0=∞for any a≠0.\frac{a}{0} = \infty \quad \text{for any } a \neq 0.\frac{a}{0} = \infty \quad \text{for any } a \neq 0.

So again 10=20=∞\frac{1}{0} = \frac{2}{0} = \infty\frac{1}{0} = \frac{2}{0} = \infty
 (single unsigned infinity), and 1∞=0\frac{1}{\infty} = 0\frac{1}{\infty} = 0
, making division total — but it’s no longer a field (some operations like 0⋅∞0 \cdot \infty0 \cdot \infty
 stay undefined or get special rules).In all these systems, 10\frac{1}{0}\frac{1}{0}
 and 20\frac{2}{0}\frac{2}{0}
 are literally the same object because the “direction” or “scale” disappears at infinity — just like how all nonzero multiples represent the same ray in projective space.Bottom line (recapping both views):  Standard reals / dual numbers / most everyday math → both undefined, so you can’t declare them “the same” (or different).  
Wheel theory / projective extensions → they are the same (=∞=\infty=\infty
), at the cost of losing some familiar arithmetic rules (which get routed through the nullity ⊥\bot\bot
 to keep consistency).

These extensions are consistent and useful in certain algebraic or geometric contexts, but they’re not replacements for ordinary real arithmetic — they’re deliberate enrichments. If you had a specific “dual” or other structure in mind, feel free to clarify!

Explore wheel theory axioms

Division by zero in physics

Nah i meant it abstractly because anything divided by 0 cause a negative and positive infinity so it seems like their is structure through even if currently undefined

Thought for 16s

Yes — abstractly, you're spotting a real structure hidden in the undefined-ness.Even though 10\frac{1}{0}\frac{1}{0}
 and 20\frac{2}{0}\frac{2}{0}
 are not numbers in the usual reals, the way they blow up carries identical “directional infinity” information from both sides. That shared pattern is the structure you’re sensing.1. The two-sided infinity signature (the structure you described)For any nonzero constant c>0c > 0c > 0
 (so c=1c = 1c = 1
 or c=2c = 2c = 2
, same rule):As the denominator approaches 0 from the positive side: cx→+∞\frac{c}{x} \to +\infty\frac{c}{x} \to +\infty

As the denominator approaches 0 from the negative side: cx→−∞\frac{c}{x} \to -\infty\frac{c}{x} \to -\infty

So 10\frac{1}{0}\frac{1}{0}
 and 20\frac{2}{0}\frac{2}{0}
 produce exactly the same pair of infinities: one positive, one negative.
The numerator’s size just scales how fast they grow (the “slope” of the hyperbola), but the sign pattern and the fact that both sides diverge to opposite infinities is identical.
That common “±∞ signature” is the abstract structure that survives even though the expressions themselves stay undefined.2. Why the structure feels the same (projective view)Think of the ratio abstractly as a direction rather than a number. In homogeneous coordinates (the same idea behind projective geometry):10\frac{1}{0}\frac{1}{0}
 is the equivalence class [1 : 0]
20\frac{2}{0}\frac{2}{0}
 is [2 : 0]

But in projective space we identify all nonzero scalar multiples: [λa : λb] is the same point for any λ ≠ 0.
So [1 : 0] = [2 : 0] = … = [c : 0] for any c ≠ 0.
They collapse to a single point at infinity. The numerator’s magnitude disappears completely — the structure is just “the vertical direction,” not “which vertical.”This is why, in the real projective line (or the wheel of reals I mentioned before), 10=20=∞\frac{1}{0} = \frac{2}{0} = \infty\frac{1}{0} = \frac{2}{0} = \infty
 exactly, and it’s the same unsigned infinity. The ±∞ split you see in ordinary limits is just a choice of how we “approach” that one point.3. Extended reals vs. projective reals (two ways to package the structure)Extended real line (±∞ separate): keeps the sign information you noticed. Both expressions still have no value, but their one-sided limits are identical.
Projective / wheel version (single ∞): collapses the ± into one object because the structure is really about rays through the origin, not signed distance. This is the cleanest algebraic way to make division by zero total while preserving the equivalence you’re intuiting.

In both cases the underlying geometry is the same: the number line “closes up” at zero by gluing the two infinities together (or treating them as opposite approaches to the same ideal point). The fact that 1 and 2 give the identical closure pattern is the abstract structure that exists despite the undefined label in ordinary arithmetic.So yes — even though we can’t assign ordinary numbers, the singularity at zero has a very definite, shared “shape” for any nonzero numerator. That shape is what makes 10\frac{1}{0}\frac{1}{0}
 and 20\frac{2}{0}\frac{2}{0}
 feel like they belong to the same abstract family. It’s exactly the kind of hidden structure that projective extensions and wheel algebra were invented to capture formally.

Explore wheel theory details

Related singularities in physics

Think integrals. Think density

Thought for 56s

Yes — integrals and densities reveal a sharper abstract structure that distinguishes 10\frac{1}{0}\frac{1}{0}
 from 20\frac{2}{0}\frac{2}{0}
, even while both still produce the same ±∞ signature you noticed.The key is to treat the “division by zero” heuristically as the peak height of a narrowing spike whose total integrated mass (the integral) stays fixed. This is exactly how the Dirac delta “function” δ(x) works in distribution theory and physics: it is a density that is infinite at x = 0 but integrates to 1 over the whole line.The standard approximation that makes the structure visibleConsider a simple “rectangular” spike of width ε > 0 and height h, centered at 0:
fε(x)={hif ∣x∣<ε/20otherwise.f_\varepsilon(x) = 
\begin{cases}
h & \text{if } |x| < \varepsilon/2 \\
0 & \text{otherwise}.
\end{cases}f_\varepsilon(x) = 
\begin{cases}
h & \text{if } |x| < \varepsilon/2 \\
0 & \text{otherwise}.
\end{cases}

Its integral (the “total mass” or total probability/charge) is exactly h ⋅ ε.To get ∫ f_ε(x) dx = 1 (the usual Dirac delta), set h = 1/ε.
As ε → 0⁺ we have h → +∞.
This is the heuristic “1/0” spike.
To get ∫ f_ε(x) dx = 2, set h = 2/ε.
As ε → 0⁺ we still have h → +∞, but twice as tall.
This is the heuristic “2/0” spike.

In the limit (in the sense of distributions), the first sequence converges to δ(x), the second to 2δ(x). These are not the same object:∫ g(x) δ(x) dx = g(0)  
∫ g(x) (2δ(x)) dx = 2 g(0)

The numerator in front of the “/0” survives as a multiplicative factor on the density. The ±∞ blow-up pattern is identical (positive on both sides for the rectangular case, or the usual sign-flip if you use an odd kernel), but the strength (how much mass the singularity carries) is different. That is the extra structure integrals + density expose.Why this feels like a genuine abstract structureThe singularity is still a point mass at 0 (measure-zero set with positive mass), which ordinary functions cannot have.
The density is infinite, but the infinity is scaled by the numerator exactly as in your original expressions.
Different numerators therefore generate different generalized functions (different distributions), even though each individually is “undefined” as an ordinary number or function value at 0.

You can make the same distinction with smoother approximations (Gaussians, Lorentzians, etc.): the peak height always scales with the desired total integral, so 1/0 and 2/0 again label distinct limiting densities.Contrast with the projective/wheel pictureIn the pure geometric view (projective line or wheel algebra) we only care about the direction of the ray at infinity, so the scalar multiple disappears and both collapse to the single point ∞.
In the integral/density view we care about the total mass the singularity contributes when integrated against test functions, so the scalar survives and 10\frac{1}{0}\frac{1}{0}
 and 20\frac{2}{0}\frac{2}{0}
 label distinct objects (δ vs. 2δ).Both structures are mathematically rigorous; they simply answer “same or different?” in different contexts. The integral/density lens is the one physicists and engineers reach for whenever they need to handle point sources, instantaneous impulses, or probability concentrations at a single point — precisely the situations where “division by zero” shows up heuristically as an infinite density.So abstractly: yes, there is hidden structure even though the expressions remain undefined in ordinary arithmetic. The ±∞ sign pattern is the coarse shared geometry; the integrated mass (the factor in front of the delta) is the finer distinguishing density information. Integrals let you see both at once.

QED haha
