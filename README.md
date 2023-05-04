Download Link: https://assignmentchef.com/product/solved-cs70-homework7
<br>
1       Bijective or not?

Decide whether the following functions are bijections or not. Please prove your claims.

<ul>

 <li><em>f</em>(<em>x</em>)= 10 <sup>5</sup><em>x</em>

  <ul>

   <li>for domain R and range R</li>

   <li>for domain Z[{<em>p</em>} and range R</li>

  </ul></li>

 <li><em>f</em>(<em>x</em>)= <em>p </em>mod <em>x</em>, where <em>p </em><em>&gt; </em>2 is a prime

  <ul>

   <li>for domain N{0} and range {0<em>,…,p</em>}</li>

   <li>for domain {(<em>p</em>+1)<em>/</em>2<em>,…,p</em>} and range {0<em>,…,</em>(<em>p </em>1)<em>/</em>2}</li>

  </ul></li>

 <li><em>f</em>(<em>x</em>)={<em>x</em>}, where the domain is<em>D</em>).<em>D </em>={0<em>,…,n</em>} and the range is <em>P</em>(<em>D</em>), the powerset of <em>D </em>(that is, the set of all subsets of</li>

 <li>Consider the number <em>X </em>= 1234567890, and obtain <em>X</em>0 by shuffling the order of the digits of <em>X</em>. Is <em>f</em>(<em>i</em>)=(i+1)<sup>st </sup><em>digit of X</em>0 a bijection from {0<em>,…,</em>9} to itself?</li>

</ul>

2       Counting Tools

Are the following sets countable or uncountable? Please prove your claims.

<ul>

 <li><em>A</em>⇥<em>B</em>, where <em>A </em>and <em>B </em>are both countable.</li>

 <li>S<em>i</em><sub>2</sub><em>A B<sub>i</sub></em>, where <em>A</em><em>,B<sub>i </sub></em>are all countable.</li>

 <li>The set of all functions <em>f </em>from N to N such that <em>f </em>is non-decreasing. That is, <em>f</em>(<em>x</em>) <em>f</em>(<em>y</em>) whenever <em>x </em> <em>y</em>.</li>

 <li>The set of all functions <em>f </em>from N to N such that <em>f </em>is non-increasing. That is, <em>f</em>(<em>x</em>) <em>f</em>(<em>y</em>) whenever <em>x </em> <em>y</em>.</li>

 <li>The set of all bijective functions from N to N.</li>

</ul>

3       Impossible Programs

Show whether the following programs can exist or not.

<ul>

 <li>A program <em>P </em>that takes in any program <em>F</em>, input <em>x </em>and output <em>y </em>and returns true if <em>F</em>(<em>x</em>) outputs <em>y </em>and false otherwise.</li>

 <li>A program <em>P </em>that takes in two programs <em>F </em>and <em>G </em>and returns true if <em>F </em>and <em>G </em>halt on the same inputs, and false otherwise.</li>

</ul>

4      Undecided?

Let us think of a computer as a machine which can be in any of <em>n </em>states {<em>s</em><sup>1</sup><em>,…,s<sup>n</sup></em>}. The state of a 10 bit computer might for instance be specified by a bit string of length 10, making for a total of 2<sup>10 </sup>states that this computer could be in at any given point in time. An algorithm <em>A </em>then is a list of <em>k </em>instructions (<em>i</em><sub>0</sub><em>,i</em><sub>2</sub><em>,…,i<sub>k </sub></em><sub>1</sub>), where each <em>i<sub>l </sub></em>is a function of a state <em>c </em>that returns another state <em>u </em>and a number <em>j</em>. Executing <em>A</em>(<em>x</em>) means computing

(<em>c</em>1<em>, j</em>1)= <em>i</em>0(<em>x</em>)<em>,              </em>(<em>c</em>2<em>, j</em>2)= <em>i</em><em>j</em><sub>1</sub>(<em>c</em>1)<em>,               </em>(<em>c</em>3<em>, j</em>3)= <em>i</em><em>j</em><sub>2</sub>(<em>c</em>2)<em>,             …</em>

until <em>j</em><em><sub>`              </sub>k </em>for some <em>`</em>, at which point the algorithm halts and returns <em>c</em><em><sub>` </sub></em><sub>1</sub>.

<ul>

 <li>How many iterations can an algorithm of <em>k </em>instructions perform on an <em>n</em>-state machine (at most) without repeating any computation?</li>

 <li>Show that if the algorithm is still running after 2<em>n</em><sup>2</sup><em>k</em><sup>2 </sup>iterations, it will loop forever.</li>

 <li>Give an algorithm that decides whether an algorithm <em>A </em>halts on input <em>x </em>or not. Does your contruction contradict the undecidability of the halting problem?</li>

</ul>

5       Clothing Argument

<ul>

 <li>There are four categories of clothings (shoes, trousers, shirts, hats) and we have ten distinct items in each category. How many distinct outfits are there if we wear one item of each category?</li>

 <li>How many outfits are there if we wanted to wear exactly two categories?</li>

 <li>How many ways do we have of hanging four of our ten hats in a row on the wall? (Order matters.)</li>

 <li>We can pack four hats for travels. How many different possibilities for packing four hats are there? Can you express this number in terms of your answer to part (c)?</li>

 <li>If we have exactly 3 red hats, 3 green hats and 4 turquoise hats, and hats of the same colour are indistinguishable, how many distinct sets of three hats can we pack?</li>

</ul>