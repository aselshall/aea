To integrate the equation:

$$
\int \frac{dv}{g - \frac{cv}{m}} = \int dt
$$

we’ll proceed with the integration on the left side. This is a standard integration that can be solved using a **u-substitution**.

### Step-by-Step Solution for the Left Integral

#### Rewrite the Integrand
Let’s focus on the left side:

$$
\int \frac{dv}{g - \frac{cv}{m}}
$$

#### Step 1: Substitution
To make the integral simpler, let:

$$
u = g - \frac{cv}{m}
$$

Then, the derivative of \( u \) with respect to \( v \) is:

$$
\frac{du}{dv} = -\frac{c}{m} \Rightarrow dv = -\frac{m}{c} \, du
$$

#### Step 2: Substitute into the Integral
Now, substitute \( u = g - \frac{cv}{m} \) and \( dv = -\frac{m}{c} \, du \) into the integral:

$$
\int \frac{dv}{g - \frac{cv}{m}} = \int \frac{-\frac{m}{c} \, du}{u}
$$

This simplifies to:

$$
-\frac{m}{c} \int \frac{1}{u} \, du
$$

#### Step 3: Integrate
The integral \( \int \frac{1}{u} \, du \) is a standard form and evaluates to \( \ln |u| \). So we get:

$$
-\frac{m}{c} \ln |u| = \int dt
$$

#### Step 4: Substitute Back for \( u \)
Now, substitute back \( u = g - \frac{cv}{m} \):

$$
-\frac{m}{c} \ln \left| g - \frac{cv}{m} \right| = t + C
$$

where \( C \) is the constant of integration.

#### Step 5: Solve for \( v \)
Now we can rearrange to solve for \( v \) in terms of \( t \).

1. Divide both sides by \( -\frac{m}{c} \):
   $$
   \ln \left| g - \frac{cv}{m} \right| = -\frac{c}{m} t + \frac{c}{m} C
   $$

2. Exponentiate both sides to eliminate the logarithm:
   $$
   g - \frac{cv}{m} = e^{-\frac{c}{m} t + C}
   $$

We can rewrite \( e^{C} \) as a new constant \( C_1 \):

$$
g - \frac{cv}{m} = C_1 e^{-\frac{c}{m} t}
$$

3. Isolate \( v \) to get:

$$
\frac{cv}{m} = g - C_1 e^{-\frac{c}{m} t}
$$

4. Multiply by \( \frac{m}{c} \):

$$
v = \frac{gm}{c} - \frac{m C_1}{c} e^{-\frac{c}{m} t}
$$

#### Step 6: Apply Initial Condition (if needed)
To determine \( C_1 \), suppose at \( t = 0 \), the initial velocity \( v(0) = 0 \). Substitute \( t = 0 \) and \( v(0) = 0 \) into the equation:

$$
0 = \frac{gm}{c} - \frac{m C_1}{c}
$$

Solving for \( C_1 \):

$$
C_1 = \frac{gm}{c}
$$

#### Final Solution
Substitute \( C_1 = \frac{gm}{c} \) back into the equation for \( v(t) \):

$$
v(t) = \frac{gm}{c} \left( 1 - e^{-\frac{c}{m} t} \right)
$$

### Interpretation
This solution describes the velocity of a free-falling parachutist under gravity and air resistance, where:
- \( \frac{gm}{c} \) is the **terminal velocity**.
- The term \( e^{-\frac{c}{m} t} \) shows how the velocity approaches terminal velocity over time. As \( t \to \infty \), \( e^{-\frac{c}{m} t} \to 0 \), and \( v(t) \to \frac{gm}{c} \).
