Download Link: https://assignmentchef.com/product/solved-mpp-assignment-4-code-generation
<br>



Contents

<table>

 <tbody>

  <tr>

   <td width="31">1</td>

   <td width="323">Specification</td>

   <td width="249">2</td>

  </tr>

  <tr>

   <td width="31">2</td>

   <td width="323">Submissions</td>

   <td width="249">2</td>

  </tr>

  <tr>

   <td width="31">3</td>

   <td width="323">Plagiarism</td>

   <td width="249">3</td>

  </tr>

  <tr>

   <td width="31">4</td>

   <td width="323">Change Log</td>

   <td width="249">3</td>

  </tr>

 </tbody>

</table>




Assignment 4version 1.0

After completing this assignment, you will be able to

<ul>

 <li>explain the mechanism of some structures in a programming language.</li>

 <li>use Scala to implement a code generation phase for a stack-based machine like JVM.</li>

 <li>create a complete compiler for JVM.</li>

</ul>

1 Specification

In this assignment, you are required to write a code generation checker for a program written in MP. The code generation will generate Jasmin code from AST created from assignment 2. The Jasmin code then is transfered to Java bytecode which must be run correctly in a Java Virtual Machine (JVM). To complete this assignment, you need to:

<ul>

 <li>read carefully the specification of MP language</li>

 <li>Download assignment4.zip and unzip it.</li>

 <li>Modify main/mc/codegen/<a href="http://CodeGenerator.py">py</a> and main/mc/codegen/<a href="http://Emitter.py">Emitter.py</a> to implement this assignment.</li>

 <li>Modify test/<a href="http://CodeGenSuite.py">py</a> to create 100 testcases to test your code.</li>

</ul>

For regular and OISP students, there is a limitation on testcases: no array type, so theydon’t need to care how to generate code for array. For gifted students, there is no limitation.

2 Submissions

The operating system when cheking your submission is Linux.

<ul>

 <li>The deadline will be announced on the class website.</li>

 <li>You must submit three files: <a href="http://CodeGenerator.py">py</a>, <a href="http://Emitter.py">Emitter.py</a> and <a href="http://CodeGenSuite.py">CodeGenSuite.py</a>.</li>

</ul>




3 Plagiarism

<ul>

 <li>You must complete the assignment by yourself and do not let your work seen by someone else.</li>

 <li>You just submit your code in your allocated account. If you violate any requirement, you will be punished by the university rule for plagiarism.</li>

</ul>

4 Change Log