Download Link: https://assignmentchef.com/product/solved-ch-231-a-assignment-4
<br>
<h1>Problem 4.1 <em>Merge Sort                                                                                      </em></h1>

<ul>

 <li>(4 points) Implement a variant of Merge Sort that does not divide the problem all the waydown to subproblems of size 1. Instead, when reaching subsequences of length <em>k </em>it applies Insertion Sort on these <em>n/k </em></li>

 <li>(3 points) Apply it to the different sequences which satisfy best case, worst case and averagecase for different values of <em>k</em>. Plot the execution times for different values of <em>k</em>.</li>

 <li>(3 points) How do the different values of <em>k </em>change the best-, average-, and worst-case asymptotic time complexities for this variant? Explain/prove your answer.</li>

</ul>

<table width="564">

 <tbody>

  <tr>

   <td width="451">Algorithms and Data Structures</td>

   <td width="113">Course: CH-231-A</td>

  </tr>

  <tr>

   <td width="451">Jacobs University Bremen Dr. Kinga Lipskoch</td>

   <td width="113">February 23<sup>rd</sup>, 2021</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>(2 points) Based on the results from (b) and (c), how would you choose <em>k </em>in practice? Briefly explain.</li>

</ul>

<h2><strong>Problem 4.2 </strong>Recurrences</h2>

Use the substitution method, the recursion tree, or the master theorem method to derive upper and lower bounds for <em>T</em>(<em>n</em>) in each of the following recurrences. Make the bounds as tight as possible. Assume that <em>T</em>(<em>n</em>) is constant for <em>n</em>≤ 2.

<ul>

 <li>(2 points) <em>T</em>(<em>n</em>) = 36<em>T</em>(<em>n/</em>6) + 2<em>n</em>,</li>

 <li>(2 points) <em>T</em>(<em>n</em>) = 5<em>T</em>(<em>n/</em>3) + 17<em>n</em><sup>1<em>.</em>2</sup>,</li>

 <li>(2 points) <em>T</em>(<em>n</em>) = 12<em>T</em>(<em>n/</em>2) + <em>n</em><sup>2 </sup>lg<em>n</em>,</li>

 <li>(2 points) <em>T</em>(<em>n</em>) = 3<em>T</em>(<em>n/</em>5) + <em>T</em>(<em>n/</em>2) + 2<em><sup>n</sup></em>,</li>

 <li>(2 points) <em>T</em>(<em>n</em>) = <em>T</em>(2<em>n/</em>5) + <em>T</em>(3<em>n/</em>5) + Θ(<em>n</em>).</li>

</ul>