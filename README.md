Download Link: https://assignmentchef.com/product/solved-numerical-analysis-homework-5
<br>



<ul>

 <li>To get full credit, <em>you must write down sufficient intermediate steps</em>, only giving the final answer earns you no credit!</li>

 <li>Please make sure that your handwriting is recognizable, otherwise you only get partial credit for the recognizable part.</li>

</ul>

<ol>

 <li>Scaled integral of B-splines.</li>

</ol>

Deduce from the Theorem on derivatives of B-splines that the scaled integral of a B-spline <em>B<sub>i</sub><sup>n</sup></em>(<em>x</em>) over its support is independent of its index <em>i </em>even if the spacing of the knots is not uniform.

<ol>

 <li>Symmetric Polynomials.</li>

</ol>

We have a theorem on expressing complete symmetric polynomials as divided difference of monomials.

<ul>

 <li>Verify this theorem for <em>m </em>= 4 and <em>n </em>= 2 by working out the table of divided difference and comparing the result to the definition of complete symmetric polynomials.</li>

 <li>Prove this theorem by the lemma on the recursive relation on complete symmetric polynomials.</li>

</ul>

The above problems weigh 8 and 12 points, respectively.

<h1>2           C++ programming</h1>

<ul>

 <li>(20 points) Let <em>f </em>: R → R be a given function. Implement two modules to interpolate <em>f </em>by the quadratic and cubic cardinal B-splines, which corresponds to the two corollaries in the notes on unique interpolation by quadratic B-splines and complete cubic cardinal Bsplines, respectively.</li>

 <li>(10 points) Run your subroutines on the function</li>

</ul>

<em>,</em>

using 10 for quadratic B-splines and <em>t<sub>i </sub></em>= −6+<em>i</em>, <em>i </em>= 1<em>,…,</em>11 for complete cubic cardinal B-splines. Plot the polynomials against the exact function.

<ul>

 <li>(10 points) Define <em>E<sub>S</sub></em>(<em>x</em>) = |<em>S</em>(<em>x</em>) − <em>f</em>(<em>x</em>)| as the interpolation error. For the two cardinal B-spline interpolants, what are the values of <em>E<sub>S</sub></em>(<em>x</em>) at the sites <em>x </em>= −3<em>.</em>5<em>,</em>−3<em>,</em>−0<em>.</em>5<em>,</em>0<em>,</em>0<em>.</em>5<em>,</em>3<em>,</em>3<em>.</em>5? Program in C++ to output these values. Why are some of the errors close to machine precision? Which of the two B-splines is more accurate?</li>

 <li>(10 points) The roots of the following equation constitute a closed planar curve in the shape of a heart:</li>

</ul>

<em>.                      </em>(1)

Modify your C++ subroutines in the previous homework to plot the heart. As discussed in the lectures, the parameter of the curve should be the <em>cumulative chordal length </em>defined from <em>n </em>given points (<em>x</em><sub>1</sub><em>,y</em><sub>1</sub>), (<em>x</em><sub>2</sub><em>,y</em><sub>2</sub>), <em>…</em>. (<em>x<sub>n</sub>,y<sub>n</sub></em>) as

<em>.</em>

Choose <em>n </em>= 10<em>,</em>40<em>,</em>160 and produce three plots of the heart function. (<em>Hints</em>: Your knots should include the characteristic points and you should think about (i) how many pieces of splines to use? (ii) what boundary conditions are appropriate? ) You can choose the knots by C++ or by yourselves. No matter what method you use, make sure that the final result shown in your homework can be reproduced by running one simple command “produceHeartCurve” or something like that.

Thus the total point