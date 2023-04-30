Download Link: https://assignmentchef.com/product/solved-cs2400-homework4-an-arm-program
<br>
Write an ARM program to

<ul>

 <li>in the data area, o declare and initialize two NULL-terminated strings labeled as StrOne, and StrTwo.

  <ul>

   <li>define a <strong><em>symbolic name</em></strong> called MAX_LEN and equivalent it with a number like 100 or greater. (Hint:</li>

  </ul></li>

</ul>

EQU must be used here.) o reserved a chunk of zeroed memory with a size of (MAX_LEN + 1), label this chunk of memory as MixStr.  (You may assume that the sum of the lengths of StrOne and StrTwo is no greater than

MAX_LEN)

<ul>

 <li>Store each one of the above three labels as a word with an address label, e.g., “adrStrOne DCD StrOne” for StrOne, and EXPORT each address label, e.g., “EXPORT adrStrOne”.</li>

</ul>

<ul>

 <li>in the main program, o Merge the first string labeled by StrOne and the second string labeled by StrTwo in a unit of one.

  <ul>

   <li>Store the ASCII string as a NULL-terminated string to memory labeled as MixStr o If one string is longer than the other one, just copy the rest of the longer one to MixStr</li>

   <li>g., <strong>“</strong><strong>Hello Metro State!</strong><strong>”</strong> and<strong> “</strong><strong>I like assembly programming.” </strong>should be mixed as <strong>“</strong><strong>H</strong><strong>I</strong><strong>e</strong> <strong>l</strong><strong>l</strong><strong>l</strong><strong>i</strong><strong>o</strong><strong>k</strong> <strong>e</strong><strong>M</strong> <strong>e</strong><strong>a</strong><strong>t</strong><strong>s</strong><strong>r</strong><strong>s</strong><strong>o</strong><strong>e m</strong><strong>S</strong><strong>b</strong><strong>t</strong><strong>l</strong><strong>a</strong><strong>y</strong><strong>t</strong> <strong>e</strong><strong>p</strong><strong>!</strong><strong>rogramming.</strong><strong>”</strong></li>

  </ul></li>

</ul>


