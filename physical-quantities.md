## [physical quantities](https://aselshall.github.io/aea/physical-quantities)

Fundamental and derived physical quantities that are commonly used in fluid mechanics


| **Quantity**          | **Equation**                       | **SI Unit**                        | **Dimension** | **In terms of SI system**                   | **Comment**                                       |
|-----------------------|------------------------------------|------------------------------------|---------------|---------------------------------------------|--------------------------------------------------|
| **Length**            | -                                  | Meter (m)                          | L             | m                                           | -                                                |
| **Time**              | -                                  | Second (s)                         | T             | s                                           | -                                                |
| **Mass**              | -                                  | Kilogram (kg)                      | M             | kg                                          | -                                                |
| **Density**           | $\rho = \frac{m}{V}$               | Kilogram per cubic meter (kg/m³)   | ML⁻³          | kg/m³                                       | -                                                |
| **Specific Weight**    | $\gamma = \rho g$                  | Newton per cubic meter (N/m³)      | ML⁻²T⁻²       | N/m³                                       | Weight per unit volume of a fluid                |
| **Specific Gravity**   | $SG = \frac{\rho}{\rho_{\text{ref}}}$ | Dimensionless                      | -             | Dimensionless                               | Ratio of the density of a substance to the reference density (usually water) |
| **Velocity**          | $v = \frac{d}{t}$                  | Meter per second (m/s)             | LT⁻¹          | m/s                                         | Describes rate of change of position              |
| **Acceleration**      | $a = \frac{v}{t}$                  | Meter per second squared (m/s²)    | LT⁻²          | m/s²                                        | Describes rate of change of velocity              |
| **Force**             | $F = ma$                           | Newton (N)                         | MLT⁻²         | kg·m/s²                                     | -                                                |
| **Pressure**          | $P = \frac{F}{A}$                  | Pascal (Pa)                        | ML⁻¹T⁻²       | kg/(m·s²) = N/m²                            | -                                                |
| **Shear Stress**      | $\tau = \frac{F}{A}$               | Pascal (Pa)                        | ML⁻¹T⁻²         | kg/(m·s²) = N/m²                            | -                                                |
| **Energy**            | $E = F \cdot d$                    | Joule (J)                          | ML²T⁻²         | kg·m²/s² = N·m                              | -                                                |
| **Power**             | $P = \frac{E}{t}$                  | Watt (W)                           | ML²T⁻³         | kg·m²/s³ = J/s                              | -                                                |
| **Viscosity (Dynamic)** | $\mu = \frac{\tau}{\frac{du}{dy}}$ | Pascal-second (Pa·s)               | ML⁻¹T⁻¹       | kg/(m·s) = N·s/m²                           | -                                                |
| **Kinematic Viscosity** | $\nu = \frac{\mu}{\rho}$          | Square meter per second (m²/s)     | L²T⁻¹         | m²/s                                        | -                                                |
| **Surface Tension**    | $\sigma = \frac{F}{l}$            | Newton per meter (N/m)             | MT⁻²          | kg/s²                                      | Affects fluid interfaces and bubbles             |
| **Flow Rate (Volumetric)** | $Q = A \cdot v$               | Cubic meter per second (m³/s)      | L³T⁻¹         | m³/s                                       | -                                                |
| **Flow Rate (Mass)**     | $\dot{m} = \rho Q$               | Kilogram per second (kg/s)         | MT⁻¹          | kg/s                                       | Important for mass balance in fluids             |
| **Reynolds Number**    | $Re = \frac{\rho v L}{\mu}$       | Dimensionless                      | -             | Dimensionless                               | Compares inertial forces to viscous forces       |
| **Froude Number**      | $Fr = \frac{v}{\sqrt{gL}}$        | Dimensionless                      | -             | Dimensionless                               | Used in open channel flow to compare inertial to gravitational forces |
| **Mach Number**        | $M = \frac{v}{c}$                 | Dimensionless                      | -             | Dimensionless                               | Compares flow velocity to the speed of sound     |
| **Weber Number**       | $We = \frac{\rho v^2 L}{\gamma}$   | Dimensionless                      | -             | Dimensionless                               | Compares inertial forces to surface tension      |
| **Bernoulli Equation** | $P + \frac{1}{2} \rho v^2 + \rho gh = \text{constant}$ | -         | -             | N/A                                          | Describes energy conservation in fluid flow      |
| **Ideal Gas Law**      | $PV = nRT$               | -                                  | -                   | -                                        | Relates pressure, volume, temperature, and number of moles of a gas |
| **Ideal Gas Constant** | $R \approx 8.314 \, \text{J/mol·K}$      | Joules per mole Kelvin (J/mol·K)   | $M L^2 T^{-2} \Theta^{-1}$ | kg·m²·s⁻²·K⁻¹·mol⁻¹                  | Universal constant used in the Ideal Gas Law   |
| **Gravitational Constant** | $g = 9.81 \, \text{m/s}^2$       | m/s²                               | $L T^{-2}$                      | m/s²                             | Acceleration due to gravity on Earth's surface |
| **Boltzmann Constant**    | $k_B \approx 1.38 \times 10^{-23} \, \text{J/K}$ | Joules per Kelvin (J/K)           | $M L^2 T^{-2} \Theta^{-1}$      | kg·m²/s²·K⁻¹                     | Relates temperature to molecular energy        |
| **Avogadro’s Number**  | $N_A \approx 6.022 \times 10^{23} \, \text{mol}^{-1}$  | Mole inverse $(\text{mol}^{-1}\)$ | Dimensionless | -                                         | Number of molecules or atoms in one mole of substance |

- Fundamental Quantities: Comments clarify their importance in fluid mechanics (e.g., length, time, mass).
- Derived Quantities: Explain how each quantity relates to fluid flow, pressure, shear, or energy conservation.
- Dimensionless Numbers: Provide insights into their role in classifying flow regimes (laminar, turbulent, etc.).
- Important Constants: Universal values in fluid mechanics, thermodynamics, and related fields

