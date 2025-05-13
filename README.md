# cs-se4x03-assignment-4-solved
**TO GET THIS SOLUTION VISIT:** [CS-SE4X03 Assignment 4 Solved](https://www.ankitcodinghub.com/product/cs-se4x03-assignment-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92469&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS-SE4X03 Assignment 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Problem 1 Study the slides about deep learning and sections 1 to 4 and 6 of https://arxiv.org/abs/1801.05894.

Modify the netbp.m code so you can pass parameters as follows

<pre>function  cost = netbp2(neurons, data, labels, niter, lr, file)
%Trains a neural network with 4 layers.
%Layer 1 and layer 4 have 2 neurons, layer 2 has neurons(1) and
%layer 3 has neurons(2).
</pre>
<pre>%data is a matrix with two rows.  data(:,i) contains the (x,y)
%coordinates of point i.
%labels is a matrix with two rows.  labels(:,i) is [1;0]
%if data(:,i) is in category A and [0;1] if it is in category B.
%lr is learning rate
</pre>
<pre>%niter is maximum number of iterations
%file is a filename where the file is created by
%save(file,’W2’,’W3’,’W4’,’b2’,’b3’,’b4’)
%cost is a vector storing the value of
%the cost function after each iteration; cost(j) is the cost at
%iteration j
</pre>
[2 points] Implement the Matlab function

<pre>function category = classifypoints(file, points)
%Reads parameters from a file and classifies points into two
%categories, A or B. This file is created by netbp2.m.
%points is a matrix with two rows, where points(:,i) contains the
%(x,y) coordinates of point i.
%Returns vector category, where category(i) is 1 if
%points(1,i) &gt;= points(2,i) and 0 otherwise.
</pre>
[4 points] Run the function

function main_nn(neurons, learning_rate, niter)

with various parameters. Try to find parameters to this function such that in the plot classified.eps the grey region contains only A training points, and the white region con- tains only B training points. Note: your regions can be quite different from the regions in Figure 1.

[1 point] Summarize in 4 bullets what you have found useful/interesting in this problem.

Submit

• PDF: netbp2.m, classifypoints.m, the two plots produced by main_nn.m • Avenue: netbp2.m, classifypoints.m

2

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Do Not Share this document

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
Figure 1: Classified points

Problem 2 [7 points] Implement in Matlab the bisection method for finding a root of a scalar equation.

Consider the polynomial f(x) = (x − 2)9

= x9 − 18×8 + 144×7 − 672×6 + 2016×5 − 4032×4 + 5376×3 − 4608×2 + 2304x − 512. (a) [2 points] Write a Matlab script to evaluate this function at 161 equidistant points in

the interval [1.92, 2.08] using two methods: – evaluate (x − 2)9 directly

– evaluatex9−18×8+144×7−672×6+2016×5−4032×4+5376×3−4608×2+2304x−512 using Horner’s method

Plot the results in two different plots. Explain the differences between the two plots. (b) [2 points] Apply your bisection method to find a root starting with [1.92, 2.08], tolerance

10−6, and using the Horner’s evaluation.

Obviously, r = 2 is a root of multiplicity 9. Can you determine a value for r such that

|r − 2| &lt; 10−6?

(c) [2 points] If you cannot find a root with accuracy of 10−6 can you explain why? (d) [1 point] Apply Matlab’s fsolve to find a root of

x9 − 18×8 + 144×7 − 672×6 + 2016×5 − 4032×4 + 5376×3 − 4608×2 + 2304x − 512

using initial guess 1.9 and of (x − 2)9 with initial guess 1.9. Report your results.

3

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Do Not Share this document

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
Submit

• PDF: answers to (a-d)

Problem 3 [8 points] Implement Newton’s method for systems of equations.

Each of the following systems of nonlinear equations may present some difficulty in com- puting a solution. Use Matlab’s fsolve and your own implementation of Newton’s method

to solve each of the systems from the given starting point.

In some cases, the nonlinear solver may fail to converge or may converge to a point other

than a solution. When this happens, try to explain the reason for the observed behaviour. Report for fsolve and your implementation of Newton’s method and each of the systems

below, the number of iterations needed to achieve accuracy of 10−6 (if achieved). (a)

x1 +x2(x2(5−x2)−2)=13 x1 +x2(x2(1+x2)−14)=29

</div>
</div>
<div class="layoutArea">
<div class="column">
starting from x1 = 15, x2 = −2. (b)

</div>
</div>
<div class="layoutArea">
<div class="column">
(c)

</div>
</div>
<div class="layoutArea">
<div class="column">
startingfromx1 =(1+

</div>
<div class="column">
x 21 + x 2 2 + x 23 = 5 x1 + x2 = 1 x1 + x3 = 3

√√√ 3)/2,×2 =(1− 3)/2,×3 = 3.

√ x1 + 10×2 = 0 5(x3 − x4) = 0

√ (x2−x3)2=0 10(x1 − x4)2 = 0

</div>
</div>
<div class="layoutArea">
<div class="column">
startingfromx1 =1,x2 =2,x3 =1,x4 =1. (d)

</div>
</div>
<div class="layoutArea">
<div class="column">
starting from x1 = 0, x2 = 0.

</div>
<div class="column">
104x1x2 = 1

e−x1 + e−x2 = 1.0001

4

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Do Not Share this document

</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<div class="layoutArea">
<div class="column">
Submit

• PDF: answers to (a-d)

• Avenue: your Matlab code. Name your main file main_newton.m. When executed,

it should produce all required results.

Problem 4 [4 points] Consider two bodies of masses μ = 0.012277471 and μˆ = 1 − μ (Earth and Sun) in a planar motion, and a third body of negligible mass (moon) moving in the same plane. The motion is given by

</div>
</div>
<div class="layoutArea">
<div class="column">
u′′ = u + 2u′ − μˆ 1 1 2

u′′ = u − 2u′ − μˆ 2 2 1

</div>
<div class="column">
u1 + μ

((u1 + μ)2 + u2)3/2

u2

((u1 + μ)2 + u2)3/2

</div>
<div class="column">
− μ − μ

</div>
<div class="column">
(u1 − μˆ)

􏰆(u1 − μˆ)2 + u2􏰇3/2

u2 . 􏰆(u1 − μˆ)2 + u2􏰇3/2

</div>
<div class="column">
(1)

(2)

</div>
</div>
<div class="layoutArea">
<div class="column">
The initial values are

</div>
</div>
<div class="layoutArea">
<div class="column">
u1(0) = 0.994,

u′1(0) = 0,

u2(0) = 0,

u′2(0) = −2.001585106379082522420537862224.

</div>
</div>
<div class="layoutArea">
<div class="column">
Implement the classical Runge-Kutta method of order 4 and integrate this problem on [0,17.1] with uniform stepsize using 100, 1000, 10,000, and 20,000 steps. Plot the orbits, i.e. u2 versus u1 for each case. How many uniform steps are needed before the orbit appears to be qualitatively correct.

Submit

• PDF: the four plots.

• Avenue: all your Matlab code. Name your main file main_rk4.m. When executed, it

should produce the four plots.

Problem 5 [6 points] Integrate (1-2) with Matlab’s ODE solvers ode23, ode45, ode78, ode89, and ode113 from 0 to 1000 with absolute and relative error tolerances of 10−10. Report for each solver in a table

number of

solver CPU time steps failed steps function evaluations

ode23 ode45 .

Which is the most efficient solver on this problem? 5

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Do Not Share this document

</div>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<div class="layoutArea">
<div class="column">
Submit

• PDF: the table

• Avenue: all your Matlab code. Name your main file main_solvers.m; it should

produce this table on the screen.

Problem 6 Bonus, [10 points] Write a Matlab script main_bonus.m that

<ol>
<li>(a) &nbsp;[5 points] uses ode15s and produces the plots in Figure II.1.2 from https://archimede. dm.uniba.it/~testset/report/hires.pdf.</li>
<li>(b) &nbsp;[3 points] for relative and absolute tolerances of 10−6, produces the table
number of

solver CPU time steps failed steps function eval LU decompositions nonlinear solves

ode23s ode15s ode45

for the HIRES problem from this pdf (ode45 is an explicit method so it does not have nonlinear solves).
</li>
<li>(c) &nbsp;[2 points] What conclusions can you make from this experiment?</li>
</ol>
Submit

• PDF: the table, conclusions

• Avenue: all your Matlab code. main_bonus.m should produce this table on the

screen.

Problem 7 [10 points] For this problem use the file nbody.dat from Assignment 3. Write the body of the Matlab function

<pre>function T = findPeriod(t, x, y, z)
% FINDPERIOD finds the period of an object in a periodic
% motion.
% t is a vector with time instants.
% The position at time t(i) is x(i), y(i), z(i).
% If the data is not periodic, or if a period cannot be computed,
% then -1 is returned.
% The spacing between t(i) and t(i+1) is not necessarily
% uniform.
%
% The initial position is at time t(1) and it is given by
% x(1), y(1), z(1).
% This function finds (an approximation) for the period T such that
% at times t(1), t(1)+T, t(1)+2*T ...
</pre>
6

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Do Not Share this document

</div>
</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>% the object is at position x(1), y(1), z(1) again.
% Calculate T here
T = -1;
end
</pre>
(a) [5 points] Describe your algorithm in words and pseudo code.

(b) [5 points] Run the script script main_nbody.m. Validate your computations against the data at

http://www.windows2universe.org/our_solar_system/planets_table.html.

You will receive full marks if your results are accurate up to the first digit after the decimal

point. E.g. the period of Uranus is given as 84.01; full mark is if you obtain 84.0.

Submit

• PDF: the output of this script, findPeriod.m. • Avenue: all your Matlab code.

Problem 8 [4 points] The Kermack-McKendrick model for the course of an epidemic in a closed population is given by the system of ODEs

</div>
</div>
<div class="layoutArea">
<div class="column">
where t is time, and at time t,

</div>
</div>
<div class="layoutArea">
<div class="column">
dS = −βSI (3) dt

dI = βSI − γI (4) dt

dR = γI, (5) dt

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>S(t) is the number of people that are susceptible of being infected</li>
<li>I(t) is the number of infected people</li>
<li>R(t) is the number of people who are not infections (e.g. vaccinated or developed immunity)
The parameter β &gt; 0 is infection rate and the parameter γ &gt; 0 is recovery rate (see below). This is an SIR (Susceptible, Infected, Recovered) model, and one of the fundamental

models in epidemiology.

If we add the equations (3,4,5) we have

d (S + I + R) = 0. dt

7
</li>
</ul>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Do Not Share this document

</div>
</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="section">
<div class="layoutArea">
<div class="column">
That is, the total population does not change over time. Suppose we have initial values, at timet=0,S(0)=S0 &gt;0,I(0)=I0 &gt;0,andR(0)=0. Thenatanyt,

</div>
</div>
<div class="layoutArea">
<div class="column">
Let

</div>
<div class="column">
S(t)+I(t)+R(t)=S0 +I0.

R 0 = βγ .

</div>
</div>
<div class="layoutArea">
<div class="column">
From (4), I(t) will increase from its initial value when

I′(0) = βS(0)I(0) − γI(0) = γI0(R0S0 − 1) &gt; 0.

That is, when R0S0 &gt; 1, and will decrease when R0S0 &lt; 1.

The constant γ is the fraction of the population that will recover per day. For example,

if for COVID-19 there are d = 14 days to recover, γ = 1/d = 1/14 of the infected population will recover per day.

Using Matlab’s ode45, simulate (3,4,5) for t ∈ [0, 200] with a population of size n = 1000 and initial conditions I0 = 1, S0 = n − I0, R0 = 0. Use γ = 1/14. Experiment with various values for β. For each of R0S0 ∈ {0.9, 1, 3, 5}, plot S(t), I(t), R(t) versus t.

Submit

• PDF: the four plots

• Avenue: all your Matlab code. Name the main program main_sir.m

</div>
</div>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Do Not Share this document

</div>
</div>
</div>
</div>
