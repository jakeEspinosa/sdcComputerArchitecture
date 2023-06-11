<h1>Computer Architecture</h1>

<h2>Description</h2>
<p>
This repository houses the arithmetic logic unit (ALU) that I developed in Logisim as part of the <a href="https://study.com/academy/course/computer-science-306-computer-architecture.html">Study.com Computer Architecture class</a>. I learned so much about Boolean logic, digital circuits, and how processors work. My abstractions over the hardware are far less brittle now as I grasp the fundamentals of how computer hardware operates.
</p>

<h2>Operations</h2>
<p>
It can perform the following operations:
</p>

<ul>
  <li>Arithmetic addition</li>
  <li>Increment</li>
  <li>Decrement</li>
  <li>Comparision (greater than, less than, equal to)</li>
  <li>Logical bitwise NOT</li>
  <li>Logical bitwise AND</li>
  <li>Logical bitwise OR</li>
  <li>Register shift right</li>
  <li>Register shift left</li>
</ul>

<p>
  The ALU also has a control unit, but only 3 instructions are mapped to it at this time. In the future, I will fully map out the instruction set and develop an assembler for the instruction set.
</p>

<h2>Opcode Table</h2>
<table>
  <tr>
    <th>Name</th>
    <th>Symbolic Code</th>
    <th>Binary Code</th>
  </tr>
  <tr>
    <td>Addition</td>
    <td>ADD</td>
    <td>0001</td>
  </tr>
    <tr>
    <td>Increment</td>
    <td>INC</td>
    <td>0010</td>
  </tr>
    <tr>
    <td>Decrement</td>
    <td>DEC</td>
    <td>0011</td>
  </tr>
    <tr>
    <td>Comparison</td>
    <td>EVL</td>
    <td>0100</td>
  </tr>
    <tr>
    <td>Logical NOT</td>
    <td>NOT</td>
    <td>0101</td>
  </tr>
    <tr>
    <td>Logical AND</td>
    <td>AND</td>
    <td>0110</td>
  </tr>
  </tr>
    <tr>
    <td>Logical OR</td>
    <td>OR</td>
    <td>0111</td>
  </tr>
    <tr>
    <td>Register Shift Right</td>
    <td>RSH</td>
    <td>1000</td>
  </tr>
    <tr>
    <td>Register Shift Left</td>
    <td>LSH</td>
    <td>1001</td>
</table>
