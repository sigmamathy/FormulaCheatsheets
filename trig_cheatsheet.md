# Definition of Trigonometry

Let $\Delta ABC$ be a triangle defined in $\mathbb{R}^2$ where $\angle B =\pi/2$,
with $x=BC$, $y=AB$, $r=AC$ and $\theta=\angle C$, we have:

- $$\sin\theta=\frac{y}{r}=\sum_{n=0}^{\infty}(-1)^{n}\frac{\theta^{2n+1}}{(2n+1)!}$$
- $$\cos\theta=\frac{x}{r}=\sum_{n=0}^{\infty}(-1)^{n}\frac{\theta^{2n}}{(2n)!}$$
- $$\tan\theta=\frac{y}{x}=\frac{\sin\theta}{\cos\theta}$$
- $$\csc\theta=\frac{r}{y}=\frac{1}{\sin\theta}$$
- $$\sec\theta=\frac{r}{x}=\frac{1}{\cos\theta}$$
- $$\csc\theta=\frac{x}{y}=\frac{1}{\tan\theta}$$

# Fundamental Trigonometric Identities

- Compound Angle Formula:
    - $$\sin(A\pm B)=\sin A\cos B\pm \cos A\sin B$$
    - $$\cos(A\pm B)=\cos A\cos B\mp \sin A\sin B$$
    - $$\tan(A\pm B)=\frac{\tan A \pm\tan B}{1\mp\tan A\tan B}$$
    - $$\csc(A\pm B)=\frac{\sec A\sec B\csc A\csc B}{\sec A\sec B\pm\csc A\csc B}$$
    - $$\sec(A\pm B)=\frac{\sec A\sec B\csc A\csc B}{\csc A\csc B\mp\sec A\sec B}$$
    - $$\cot(A\pm B)=\frac{\cot A\cot B\mp 1}{\cot B\pm\cot A}$$
    - $$\arcsin A\pm\arcsin B=\arcsin(A\sqrt{1-B^2}\pm B\sqrt{1-A^2})$$
    - $$\arccos A\pm\arccos B=\arccos(AB\mp\sqrt{(1-A^2)(1-B^2)})$$
    - $$\arctan A\pm\arctan B=\arctan(\frac{A\pm B}{1\mp AB})$$
    - $$\text{arccot }A\pm\text{arccot }B=\text{arccot}(\frac{AB\mp 1}{B\pm A})$$

- Double Angle Formula:
    - $$\sin(2A)=2\sin A\cos A$$
    - $$\cos(2A)=\cos^2 A-\sin^2 A=2\cos^2A-1=1-2\sin^2A$$
    - $$\tan(2A)=\frac{2\tan A}{1-\tan^2 A}$$

- Square Relationship:
    - $$\sin^2A+\cos^2A=1$$
    - $$\tan^2A+1=\sec^2A$$
    - $$\cot^2A+1=\csc^2A$$
    - $$\sec^2A+\csc^2A=\sec^2A\csc^2A$$

- Sum to Product and Product to Sum:
    - $$2\sin A\cos B=\sin(A+B)+\sin(A-B)$$
    - $$2\sin A\sin B=\cos(A-B)-\cos(A+B)$$
    - $$2\cos A\cos B=\cos(A+B)+\cos(A-B)$$
    - $$\sin A\pm\sin B=2\sin\frac{A\pm B}{2}\cos\frac{A\mp B}{2}$$
    - $$\cos A+\cos B=2\cos\frac{A+B}{2}\cos\frac{A-B}{2}$$
    - $$\cos A-\cos B=2\sin\frac{A+B}{2}\sin\frac{B-A}{2}$$

- Triple Angle Formula:
    - $$\sin 3A=3\sin A-4\sin^3A$$
    - $$\cos 3A=4\cos^3A-3\cos A$$
    - $$\tan 3A=\frac{3\tan A-4\tan^3 A}{1-3\tan^2 A}$$

- Half Angle Formula:
    - $$\tan\frac{A}{2}=\frac{\sin A}{1+\cos A}=\frac{1-\cos A}{\sin A}=\pm\sqrt{\frac{1-\cos A}{1+\cos A}}$$

- Power Reduction Formula:
    - $$\sin^2A=\frac{1-\cos 2A}{2}$$
    - $$\cos^2A=\frac{1+\cos 2A}{2}$$
    - $$\sin^3A=\frac{3\sin A-\sin 3A}{4}$$
    - $$\cos^3A=\frac{3\cos A+\cos 3A}{4}$$

# Trigonometry in Triangles

- Angle conversion:
    - $$\sin(A+B)=\sin C$$
    - $$\cos(A+B)=-\cos C$$
    - $$\tan(A+B)=-\tan C$$

- Sine Law and Cosine Law (Generalized Pythagorus Theorem)
    - $$\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C}=\text{diameter of the circumcircle}$$
    - $$c^2=a^2+b^2-2ab\cos C$$

- Angle sums:
    - $$\sin A+\sin B+\sin C=4\cos\frac{A}{2}\cos\frac{B}{2}\cos\frac{C}{2}$$
    - $$\cos A+\cos B+\cos C=4\sin\frac{A}{2}\sin\frac{B}{2}\sin\frac{C}{2}+1$$
    - $$\tan A+\tan B+\tan C=\tan A\tan B\tan C$$
    - $$\sin^2A+\sin^2B+\sin^2C=2+2\cos A\cos B\cos C$$
    - $$\cos^2A+\cos^2B+\cos^2C=1-2\cos A\cos B\cos C$$

# Trigonometric Substitution

- Weierstrass Substitution:

    Let $t=\tan\frac{x}{2}$
    - $$\sin x=\frac{2t}{1+t^2}$$
    - $$\cos x=\frac{1-t^2}{1+t^2}$$
    - $$\tan x=\frac{2}{1+t^2}$$