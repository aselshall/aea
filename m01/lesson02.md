To integrate the equation:

\[
\int \frac{dv}{g - \frac{cv}{m}} = \int dt
\]

we’ll proceed with the integration on the left side. This is a standard integration that can be solved using a **u-substitution**.

### Step-by-Step Solution for the Left Integral

#### Rewrite the Integrand

Let’s focus on the left side:

\[
\int \frac{dv}{g - \frac{cv}{m}}
\]

#### Step 1: Substitution

To make the integral simpler, let:
\[
u = g - \frac{cv}{m}
\]

Then, the derivative of \( u \) with respect to \( v \) is:
\[
\frac{du}{dv} = -\frac{c}{m}
\]

or equivalently,
\[
dv = -\frac{m}{c} \, du
\]

#### Step 2: Substitute into the Integral

Now, substitute \( u = g - \frac{cv}{m} \) and \( dv = -\frac{m}{c} \, du \) into the integral:

\[
\int \frac{dv}{g - \frac{cv}{m}} = \int \frac{-\frac{m}{c} \, du}{u}
\]

This simplifies to:

\[
-\frac{m}{c} \int \frac{1}{u} \, du
\]

#### Step 3: Integrate

The integral \( \int \frac{1}{u} \, du \) is a standard form and evaluates to \( \ln |u| \). So we get:

\[
-\frac{m}{c} \ln |u| = \int dt
\]

#### Step 4: Substitute Back for \( u \)

Now, substitute back \( u = g - \frac{cv}{m} \):

\[
-\frac{m}{c} \ln \left| g - \frac{cv}{m} \right| = t + C
\]

where \( C \) is the constant of integration.

### Step 5: Solve for \( v \)

Now we can rearrange to solve for \( v \) in terms of \( t \).

1. Divide both sides by \( -\frac{m}{c} \):
   \[
   \ln \left| g - \frac{cv}{m} \right| = -\frac{c}{m} t - \frac{c}{m} C
   \]

2. Exponentiate both sides to eliminate the logarithm:
   \[
   g - \frac{cv}{m} = e^{-\frac{c}{m} t + \text{constant}}
   \]

Certainly, let’s continue from where we left off to reach the desired form:

We had:

\[
\ln \left| g - \frac{cv}{m} \right| = -\frac{c}{m} t + C
\]

where \( C \) is the constant of integration. Let’s exponentiate both sides to remove the logarithm.

### Step 6: Exponentiate Both Sides

Exponentiating both sides gives:

\[
g - \frac{cv}{m} = e^{-\frac{c}{m} t + C}
\]

We can rewrite \( e^{-\frac{c}{m} t + C} \) as \( C_1 e^{-\frac{c}{m} t} \), where \( C_1 = e^C \) is a new constant.

So we have:

\[
g - \frac{cv}{m} = C_1 e^{-\frac{c}{m} t}
\]

### Step 7: Solve for \( v \)

Now, isolate \( v \) to find the solution in terms of \( t \):

1. Move \(\frac{cv}{m}\) to the other side:
   \[
   \frac{cv}{m} = g - C_1 e^{-\frac{c}{m} t}
   \]

2. Multiply both sides by \(\frac{m}{c}\) to solve for \( v \):
   \[
   v = \frac{gm}{c} - \frac{m C_1}{c} e^{-\frac{c}{m} t}
   \]

3. Let’s simplify by defining \( C_2 = \frac{m C_1}{c} \), another constant. Then the equation becomes:

   \[
   v(t) = \frac{gm}{c} - C_2 e^{-\frac{c}{m} t}
   \]

### Step 8: Apply Initial Condition (if needed)

To determine the constant \( C_2 \), we can use an initial condition. Suppose at \( t = 0 \), the velocity \( v(0) = 0 \).

1. Substitute \( t = 0 \) and \( v(0) = 0 \) into the equation:

   \[
   0 = \frac{gm}{c} - C_2
   \]

2. Solving for \( C_2 \):

   \[
   C_2 = \frac{gm}{c}
   \]

### Final Solution

Substitute \( C_2 = \frac{gm}{c} \) back into the equation for \( v(t) \):

\[
v(t) = \frac{gm}{c} \left(1 - e^{-\frac{c}{m} t}\right)
\]

This is the desired form:

\[
v(t) = \frac{gm}{c} \left(1 - e^{-\frac{c}{m} t}\right)
\]

### Interpretation

This solution describes the velocity of a free-falling parachutist under gravity and air resistance, where:
- \( \frac{gm}{c} \) is the **terminal velocity**.
- The term \( e^{-\frac{c}{m} t} \) shows how the velocity approaches terminal velocity over time. As \( t \to \infty \), \( e^{-\frac{c}{m} t} \to 0 \), and \( v(t) \to \frac{gm}{c} \).
