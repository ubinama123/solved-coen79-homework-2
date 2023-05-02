Download Link: https://assignmentchef.com/product/solved-coen79-homework-2
<br>
<ol>

 <li>What is <em>encapsulation in OOP</em>? Give an example</li>

</ol>





































<ol start="2">

 <li>What is the time complexity of fun(). Please show your proof.</li>

</ol>




int fun(int n)

{

int count = 0;

for (int i = n; i &gt; 0; i /= 2)      for (int j = 0; j &lt; i; j++)         count += 1;   return count;

}




























<ol start="3">

 <li>Give a concise formula that gives <em>the <u>approximate</u> number of digits in a positive integer</em>. The integer is written in base 10.</li>

</ol>






















<ol start="4">

 <li>What are the differences between references and pointers?</li>

</ol>

















































<ol start="5">

 <li>What are the three ways we can use items defined in a namespace. Include examples in your answer.</li>

</ol>





























































<ol start="6">

 <li>Discuss about the output of the following code. How the result will change if we replace struct with class?</li>

</ol>







<table width="581">

 <tbody>

  <tr>

   <td width="581">1. struct Test {</td>

  </tr>

  <tr>

   <td width="581">2.     <strong>int</strong> x;</td>

  </tr>

  <tr>

   <td width="581">3. };   4.</td>

  </tr>

  <tr>

   <td width="581">5. <strong>int</strong> main() {</td>

  </tr>

  <tr>

   <td width="581">6.     Test t;</td>

  </tr>

  <tr>

   <td width="581">7.       t.x = 20;8.       cout&lt;t.x&lt;endl;9.       <strong>return</strong> 0;</td>

  </tr>

  <tr>

   <td width="581">10. }</td>

  </tr>

 </tbody>

</table>



















<ol start="7">

 <li>A The header of the point class is as follows:</li>

</ol>




<table width="653">

 <tbody>

  <tr>

   <td colspan="2" width="653">1.  <strong>class</strong> point2.  {</td>

  </tr>

  <tr>

   <td colspan="2" width="653">3.       <strong>public</strong>:4.       // CONSTRUCTOR</td>

  </tr>

  <tr>

   <td colspan="2" width="653">5.     point (<strong>double</strong> initial_x = 0.0, <strong>double</strong> initial_y = 0.0);           6.7.       // MODIFICATION MEMBER FUNCTIONS8.       void set_x (double&amp; value);9.       void set_y (double&amp; value);10.</td>

  </tr>

  <tr>

   <td colspan="2" width="653">11.      // CONST MEMBER FUNCTIONS12.      point operator+ (<strong>double</strong>&amp; <strong>in</strong>) <strong>const</strong>;13.</td>

  </tr>

  <tr>

   <td colspan="2" width="653">14.      <strong>private</strong>:15.      <strong>double</strong> x; // x coordinate of this point16.      <strong>double</strong> y; // y coordinate of this point</td>

  </tr>

  <tr>

   <td colspan="2" width="653">17.</td>

  </tr>

  <tr>

   <td colspan="2" width="653">18. };</td>

  </tr>

  <tr>

   <td width="25"> </td>

   <td width="628"> </td>

  </tr>

 </tbody>

</table>




<ul>

 <li>Which line of the following code results in an error? Explain why. § What’s the solution?</li>

</ul>








































<ol start="8">

 <li>What is the output of this code? Discuss your answer.</li>

</ol>








