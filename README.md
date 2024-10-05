cone

abs(sqrt(x^2+y^2) +2*z) + sqrt(x^2+y^2) - 3



torus
(sqrt(x^2+y^2) - 2)^2 + z^2 -3


cylinder

abs(sqrt(x^2+y^2) - z) + abs(sqrt(x^2+y^2) + z) - 6


tetrahedron
abs(abs(abs(x)+2*y)+abs(x) + 2*z) + abs(abs(x)+2*y)+abs(x) - 3


tetra hendron prymid


abs(abs(abs(x)+2*y)+abs(x) + 2*z) + abs(abs(x)+2*y)+abs(x) - 3

Triangle prism

abs(abs(abs(x)+2*y)+abs(x) - z) + abs(abs(abs(x)+2*y)+abs(x) + z) = 2


square prymid

abs(abs(x-y)+abs(x+y) + 3*z) + abs(x-y)+abs(x+y) - 2


house tetra hedron

abs(abs(abs(x) - y) + abs(x) + abs(y) + 3*z) + abs(abs(abs(x) - y) + abs(x) + abs(y) - z) - 2


square

abs(abs(x-y)+abs(x+y) - 2*z) +abs(abs(x-y)+abs(x+y) + 2*z) - 5


Triangle prism

abs(abs(abs(x)+2*y)+abs(x) - z) + abs(abs(abs(x)+2*y)+abs(x) + z) - 2


cone

abs(sqrt(x^2+y^2) +2*z) + sqrt(x^2+y^2) - 3

abs(sqrt(x^2+y^2) +2*z) + sqrt(x^2+y^2) -6

torus
(sqrt(x^2+y^2) - 2)^2 + z^2 -3

cone

abs(sqrt(x^2+y^2) - z) + abs(sqrt(x^2+y^2) + z) - 6

tetrahedron
abs(abs(abs(x)+2*y)+abs(x) + 2*z) + abs(abs(x)+2*y)+abs(x) - 3

triangle prism
|||x|+2y|+|x| - z| + |||x|+2y|+|x| + z| = a

II> - SQUARE PYRAMID : abs(abs(x-y)+abs(x+y) + 3*z) + abs(x-y)+abs(x+y) - 6
||x-y|+|x+y| + 3z| + |x-y|+|x+y| = a

III - CUBE : abs(abs(x-y)+abs(x+y) - 2*z) +abs(abs(x-y)+abs(x+y) + 2*z) - 5

The Construction Operators for Shape M

mI : The Extend/Extrude across N+1 , makes a prism from shape M

m> : The Taper/Scale across N+1 , makes a pyramid or cone from shape M

mO : The Bisecting Rotate into N+1 , makes a sphere, cylinder, cone, or cyclotope from shape M

m(n) : The Fiber Bundle of M over surface of shape N , makes a hypertoric ring or framotope

m[n] : The Cartesian Product with shape M and N , makes (m,n)-duoprism, or other hyperprism not definable with linears

Commutative Relationships and Equalities

m[II] = mII : The Cartesian product with a square II is equal to a double extrude of m

m[IO] = mIO : The Cartesian product with a circle is equal to an extrude then rotate around hyperplane of m

mIIO = mIOI : The extrude then rotate of m-prism is equal to the rotate then extrude of m-prism

mI>O = mIO> : The taper then rotate of m-prism is equal to the rotate then taper of m-prism

Mathematical Definition of the Operators

• Extrude Shape M along Axis x_n

mI : |m - x_n| + |m + x_n| = a

• Taper Shape M along Axis x_n

m> : |m + 2x_n| + m = a

• Bisecting Rotate M-prism into K-space, mI : |m - x_n| + |m + x_n| = a

mIO : |m - √(x_n²+x_k²)| + |m + √(x_n²+x_k²)| = a

• Non-Intersecting Rotate M-prism into k-space, mI = |m - x_n| + |m + x_n| = a

mI(O) : |m - (√(x_n²+x_k²)-a)| + |m + (√(x_n²+x_k²)-a)| = b

• Cartesian Product with Shape M and N

m[n] : |m - n| + |m + n| = a

The First Dimension

I - LINE : |x| = a

The Second Dimension

IO / (II) - CIRCLE : √(x²+y²) = a

I> - TRIANGLE : ||x| + 2y| + |x| = a

II - SQUARE : |x-y| + |x+y| = a

The Third Dimension

IOO / (III) - SPHERE : √(x²+y²+z²) = a

IO(O) / ((II)I) - TORUS : (√(x²+y²) - a)² + z² = b²

IO> - CONE : |√(x²+y²) +2z| + √(x²+y²) = a

IOI - CYLINDER : |√(x²+y²) - z| + |√(x²+y²) + z| = a

I>> - TETRAHEDRON : |||x|+2y|+|x| + 2z| + ||x|+2y|+|x| = a

I>I - TRIANGLE PRISM : |||x|+2y|+|x| - z| + |||x|+2y|+|x| + z| = a

II> - SQUARE PYRAMID : ||x-y|+|x+y| + 3z| + |x-y|+|x+y| = a

III - CUBE : ||x-y|+|x+y| - 2z| +||x-y|+|x+y| + 2z| = a

abs(abs(x-y)+abs(x+y) + 3z)+ abs(x-y)+abs(x+y) -3

abs(abs((x/9.2)-y)+abs((x/9.2)+y) - 2*z) +abs(abs((x/9.2)-y)+abs((x/9.2)+y) + 2*z) - 5

CUBE : abs(abs(x-y)+abs(x+y) - 2*z) +abs(abs(x-y)+abs(x+y) + 2*z) - 5

elephant

abs(x*y)-z+abs(x*z)-y+abs(z*y)-x-z^2-x^2-y^2-(x*y*z)+1-(x*y)^2  


