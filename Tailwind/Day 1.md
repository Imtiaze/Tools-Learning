Topic

Padding - (p, px, py)
Colors - (bg-*, text-*)
Width - (w-*)
Flexbox basics
Centering (justify-center, items-center)
Rounded Corners
Shadow



Spacing (padding + margin)
------------------------------

Exercise 1

Create

+----------------------+
|                      |
|   Hello Laravel      |
|                      |
+----------------------+

Requirements

gray background
padding 8
margin top 10
rounded corners

Try yourself before seeing the answer.

<div class="bg-gray-200 p-8 mt-10 rounded">
    Hello Laravel
</div>

Colors (Background + Text + borders)
-------------------------------------

Exercise

Create a red warning box.

Requirements

red background
white text
rounded
padding 6

<div class="bg-red-600 text-white p-6 rounded">
    This is a warning red box
</div>



Widhth & Height
-------------------

Widht - w-full, w-1/2, w-64 (16rem)

h-screen, h-20

Flexbox
--------
<div class="flex">
    <div>A</div>
    <div>B</div>
</div>

output : A B

Center Items
------------
flex justify-center items-center

<div class="flex justify-center items-center h-screen">
    Hello
</div>



Mini Project (30 minutes)
-----------------------------

Build this card:

+----------------------------------+
|                                  |
| Laravel Dashboard                |
| Welcome Back                     |
|                                  |
| [ Login ]                        |
|                                  |
+----------------------------------+

Requirements

white card
shadow
rounded
padding
blue button
centered on screen

Try to build it yourself before checking the solution.

<body class="bg-gray-200 flex justify-center items-center h-screen">

<div class="bg-white shadow-xl px-10 py-5 rounded-lg w-96">
  
  <h1 class="font-bold text-2xl mb-2">Laravel Dashboard</h1>
  <p class="text-gray-500 mb-6">Welcome Back</p>
  <button class="bg-blue-600 text-white px-5 py-2 rounded mt-2 hover:bg-blue-700 transition">Login</button>
</div>
</body>