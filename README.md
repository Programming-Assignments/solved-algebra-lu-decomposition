Download Link: https://assignmentchef.com/product/solved-algebra-lu-decomposition
<br>



Note: Instructions given here are subject to change if it is determined that additional structure or clarity is warranted.

The purpose of this project is to explore a means of solving a matrix equation <em>A</em><strong>x </strong>= <strong>b </strong>by decomposing the coefficient matrix <em>A</em>. Under appropriate circumstance, such an approach may provide a methodology that has advantages in terms of computational efficiency.

Suppose we have an application that gives rise to a sequence of <em>n </em>× <em>n </em>linear systems <em>A</em><strong>x </strong>= <strong>b</strong><em><sub>k </sub></em>for <em>k </em>= 1<em>,…K</em>. An example may be a flow network (e.g. a shipping channel) in which the inflow and outflow data that determines <strong>b</strong><em><sub>k </sub></em>changes each hour while the network structure in <em>A </em>remains fixed. If <em>A </em>is <em>n </em>× <em>n</em>, a reduction of <em>A </em>to an echelon form requires about  operations. Back substitution to determine <strong>x </strong>requires another roughly 2<em>n</em><sup>2 </sup>operations. If <em>n </em>= 10, solving the system 24 times in a day requires ∼ 24000 operations. If we can perform the reduction of <em>A </em>once, and use this to convert <strong>b</strong><em><sub>k </sub></em>to a solution <strong>x</strong><em><sub>k </sub></em>24 times, the operation count drops by about 76% to ∼ 5600 total operations.

Carry out the following activities.

<ul>

 <li>Write a brief introduction to the topic of <em>LU </em> Be sure to include definitions of any new or significant terms. (Here, I would advise considering how you would present this to your classmates who are not likely to be familiar with terms like <em>upper triangular matrix</em>.) Also include some explanation of the steps inherent in solving <em>A</em><strong>x </strong>= <strong>b </strong>in the new form <em>LU</em><strong>x </strong>= <strong>b </strong>.</li>

 <li>Assuming that a given matrix <em>A </em>can be reduced to an echelon form without requiring a row swap at any point in the reduction process, describe an algorithm to obtain an <em>LU </em> Illustrate by decomposing</li>

</ul>

<table width="149">

 <tbody>

  <tr>

   <td width="83">−3<em>A </em>=  69</td>

   <td width="66">1            2 <sup></sup>2            −5 <em>.</em> 5 −6</td>

  </tr>

 </tbody>

</table>

Demonstrate the system solution process on the sytem <em>A</em><strong>x </strong>= <strong>b </strong>for this matrix <em>A </em>and <strong>b </strong>= [0 3 8]<em><sup>T</sup></em>.

<table width="643">

 <tbody>

  <tr>

   <td width="145">2 (3) Show that −46</td>

   <td width="497">1            −1 <sup></sup>−2           5  does not have an <em>LU </em>decomposition. Discuss the condition that2            11</td>

  </tr>

 </tbody>

</table>

causes the problem here. (This would have obvious ramifications for a program with a naive command to “divide by the <em>pivot</em>” at the <em>k<sup>th </sup></em>step.)

<ul>

 <li>Using the language of your choice write a program to perform and return an <em>LU </em>decomposition on a square matrix of arbitrary size. Include an exit strategy that can detect when the process (without pivoting) will fail. You may wish to return some indicative message to the user in this case. Choose some examples to demonstrate what your program produces. If reasonable, write a routine that can solve an equation <em>A</em><strong>x </strong>= <strong>b </strong>by calling your <em>LU </em>decomposition routine and performing the back substitution processes with the returned matrices <em>L </em>and <em>U</em>. Choose an example to demonstrate what your program produces.</li>

 <li>Write a brief conclusion or reflection on the <em>LU </em>decomposition and your experience. Consider strengths and weaknesses of the <em>LU </em>decomposition as a practical tool. You may find information in the literature on issues with numerical error, alternative algorithms, <em>PLU </em>or <em>LDU </em>decompositions, and existence and uniqueness considerations. (It is not necessary that you touch on all of these things, they are just examples of topics that you may come across and would like to include.) Use the format described on the following page if you include citations.</li>

</ul>

What to turn in: Please provide a typed paper or report that integrates activities (1), (2), (3), and (5). If possible, use a type setting tool or word processor that can format mathematical symbolism. If necessary, mathematical symbols can be neatly written in by hand. Displayed output from the program from (4) can be integrated into the narrative or included as an appendix. The report is due TBD.

Citation Format: References should be listed in alphabetical order by principle author surname. To cite a reference, include the reference number in square brackets to the right of the end of the citation.

For example

<em>In vitro studies of LDL modification indicate that the process occurs over time periods of minutes [2, 16] whereas MRCT occurs over hours and days [23] (again in vitro).</em>

The notations <em>[2, 16] </em>and <em>[23] </em>appearing in this sentence indicate to the reader that the first result cited can be found in references 2 and 16, and that the second result cited can be found in reference 23. Below you will find the requested format for any references that you use. The format is given for articles, books, and for websites/web-based documents.

Format for referencing an article:

Author(s), (year) title. <em>journal </em>volume/issue pages.

For example:

<ul>

 <li>Stocker, R. and Keaney, J., (2004) Role of Oxidative Modifications in Atherosclerosis.</li>

</ul>

<em>Rev. </em>84 1381-1478.

Format for referencing a book:

Author(s), (year) <em>title</em>, publisher, location.

For example:

<ul>

 <li>Brandrup J. and Immergut E. H., (1989) <em>Polymer Handbook</em>, Wiley, New York.</li>

</ul>

Format for referencing a website:

Author(s)(if known), (date accessed) <em>Webpage title</em>, Organization/publisher(in any). URL

For example:

<ul>

 <li>Landsberger, J. (accessed Aug. 25, 2010) <em>Study Guides and Strategies</em>, University of XYZ. http://www.studygs.net/citation.htm .</li>

</ul>

If the website author is not known, just write Web Contributor