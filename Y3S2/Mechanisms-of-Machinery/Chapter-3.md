# Chapter 3 : Velocity Analysis of Linkages

${toc}

Velocity and Acceleration of a system can be determined by the following methods of analysis :

1. Analysis by vector mathematics
2. Analysis by equations of relative motion
3. Analysis by complex number
4. Analysis by instant center methods

## 3.1 Velocity Analysis by Vector Mathematics

Let $P$ be a point in a position coordinate relative to the $xyz$-coordinate
system which itself moves relative to the $XYZ$-coordinate system

![[position-coordinate]](position-coordinate.png)

- $R$ = position vector of P relative to the $xyz$-system

- $R_P$ = position vector of P relative to the $XYZ$-system

- $R_o$ = position vector of $xyz$'s origin to relative $XYZ$'s system

From which $R_P=R_o+R$, where $R$ can be denoted in unit vectors as $R=xi+yj+zk$

Velocity can now be derived from $R_P$ by:

$$V_P=\dot R_P=\dot R_o+\dot R$$

where:

- $dot R_o = V_o$ is velocity vector of $xyz$'s origin to relative $XYZ$'s system

$$
\dot R= \frac{d}{dx}(xi+yi+zk) = ({\dot x}i+{\dot y}j+{\dot z}k)+(x\dot i+y\dot j+z\dot k)
$$

$$V={\dot x}i+{\dot y}j+{\dot z}k$$

we can rewrite unit vector derivatives in terms of the angular velocity vector $\omega$

$$\dot i = \omega \times i$$

$$\dot j = \omega \times j$$

$$\dot k = \omega \times k$$

$$
\dot R= V + x ( \omega \times i) + y( \omega \times j) + z( \omega \times k) \\
\dot R= V + \omega(xi+yj+zk)= V + \omega R
$$

Hence we can write the Velocity of P to the fixed system as the following:

$$
V_P=V_o + V + (\omega \times R )
$$

where:

- $V_o$ : velocity of the origin of the $xyz$ system relative to the $XYZ$ system

- $V$ : velocity of point $P$ relative to the $xyz$ system

- $\omega$ : angular velocity of the $xyz$ system relative to the $XYZ$

- $R$ : position vector of P with respect to the $xyz$ system

### Example 1

![[Example 3.1]](mechanisms-example3.1.png)

#### Solution

Given :
$O_2A = 200mm\ ,  AB = 1500mm\ , BO_4=400mm\ , 0_20_4=1350mm\ , \omega_2=4 rad/s\ , \theta=134.4 \degree \,  \beta=44.4{\degree}$

Required:
$V_B \quad and \quad \omega_3$

$$
V_B=V_A+(\omega_2 \times R) + V
$$

representing the velocities interms of the XYZ axis:

$$
V_B=V_Bcos(30+28.8)i+V_Bsin(30+28.8)j \\ \\
V_A=V_Acos(30+15.6)i+V_Bsin(30+15.6)j \\ \\
\omega_2 \times R=(\omega_2 \times R)j
$$

> the angles for $V_B$ and $V_A$ are $57\degree$ and $44.4\degree$ respectively on the textbook

since point $B$ is fixed into the $xyz$ system, $V=0$

from the given, we can calculate $V_A$ by using $V=\omega \times R$

$$
V_A=\omega \times R = \omega_2 \times 0_2A = 4\pi \cdot 200 = 800\pi mm/s
$$

from this we can substitue the computed $V_A$ value to the previous equations,

$$
V_B=V_A+(\omega \times R) \\ \\
V_Bcos(57 \degree)i+V_Bsin(57 \degree)j=V_Acos(44.4 \degree)i+V_Bsin(44.4 \degree)j + (\omega_2 \times R)j \\ \\
V_Bcos(57\degree)i+V_Bsin(57\degree)j=800\pi cos(44.4\degree)i+800\pi sin(44.4\degree)j + (\omega_2 \times R)j \\ \\
V_Bcos(57\degree)i+V_Bsin(57\degree)j=1795.66i+1758.44j + (\omega_2 \times R)j \\ \\
$$

collecting like terms (in terms of $i$ and $j$)

on the $i$-coordinate

$$
V_Bcos(57)=1795.66 \\ \\ \\
V_B=\frac{1795.66}{cos57 \degree} \\ \\ \\
V_B= 3296.97 mm/s
$$

on the $j$-coordinate

$$
V_Bsin(57 \degree)j + 1758.44 = \omega_3 \times R \\ \\
\omega_3 = \frac{3296.97sin(57 \degree)+1758.44}{R} =\frac{3296.97sin(57 \degree)-1758.44}{AB} =\frac{3296.97sin(57 \degree)+1758.44}{1500} \\ \\
\omega_3 = \frac{3296.97sin(57 \degree)+1758.44}{1500}=\frac{4523.51}{1500} \\ \\
$$

$$
\omega_3 = 3.01 rad/s
$$

## 3.2 Vector Analysis by equations of relative motion
