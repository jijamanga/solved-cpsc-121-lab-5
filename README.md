Download Link: https://assignmentchef.com/product/solved-cpsc-121-lab-5
<br>



Create a program that:

<ol>

 <li>Prompts the user to input values for an array of five integers

  <ol start="2">

   <li>HINT: It helps your programming flow a LOT if you call the same function used in part 2.g</li>

  </ol></li>

 <li>Displays a menu, where the user may choose

  <ol>

   <li>Sum – Calculates and displays the sum of numbers in the array

    <ol>

     <li>Use this definition (with reference variable as parameter):</li>

     <li>void Sum(int array[], int &amp; result)//stores sum in result</li>

    </ol></li>

   <li>Mean – Calculates and displays the average of numbers in the array. Should not round.

    <ol>

     <li>Should not be an integer! ii. Should use the “Sum” function defined above</li>

    </ol></li>

   <li>Display – Displays the current values held in the array

    <ol>

     <li>Alternatively, you can just display it at the start of the menu’s prompt</li>

    </ol></li>

   <li>Sequencing – Displays the difference between each adjacent set of values

    <ol>

     <li>Ie if we had {3, 5, 2, 9, 0}, we would get the output 2 -3 7 -9</li>

     <li>This just needs to be printed, not saved</li>

    </ol></li>

   <li>Search – Indicate whether the user’s chosen value is contained in the array, or not (boolean result should be returned, ie bool function).</li>

   <li>Sort – Arrange the values within the array so that they are in ascending order.

    <ol>

     <li>Bubble or Selection sort will be relevant</li>

     <li>Extra Credit for BOGO sort (google/wiki)</li>

    </ol></li>

   <li>Edit – The user is re-prompted for input into the array (all elements)</li>

   <li>Exit – terminate the program</li>

  </ol></li>

 <li>Loop back to step 2</li>

</ol>

There should be at least 4 functions used in this program, including the function definition provided to you. The argument should be the array itself in most of these functions.

You should probably use a global const int for array size. Do not use global variables unless they’re constants!


