<!doctype html>
<html>
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
  </head>
  <body class="bg-gray-100 flex justify-center items-center min-h-screen">
    

    <div class="max-w-md w-full p-8 m-6 md:m-8 shadow bg-white rounded-xl">
        <h2 class="text-2xl font-bold mb-6">Create Student</h2>
        <div class="space-y-5">
            <div>
                <label class="block mb-2 font-semibold" >Name</label>
                <input type="text" class="border border-gray-300 p-2 rounded-xl focus:border-blue-300 focus:ring-2 focus:ring-blue-300 w-full" placeholder="Enter name"/>
            </div>
            <div>
                <label class="block mb-2 font-semibold" >Email</label>
                <input type="email" class="border border-gray-300 p-2 rounded-xl focus:border-blue-300 focus:ring-2 focus:ring-blue-300 w-full" placeholder="Enter email"/>
            </div>
            <div>
                <label class="block mb-2 font-semibold" >Password</label>
                <input type="password" class="border border-gray-300 p-2 rounded-xl focus:border-blue-300 focus:ring-2 focus:ring-blue-300 w-full" placeholder="Enter password"/>
            </div>
            <div class="flex gap-3">
                <button class="bg-blue-600 px-5 py-3 rounded-xl hover:bg-blue-700 transition duration-300 text-white cursor-pointer">Create User</button>
                <button class="bg-gray-200 px-5 py-3 rounded-xl hover:bg-gray-300 transition duration-300 cursor-pointer">Cancel</button>
            </div>
        </div>
    </div>

  </body>   
</html>

You now understand:
----------------
|✅ |Borders      |
---------------------
|✅ |Border colors|
-------------------

✅ Rounded corners
✅ rounded-full
✅ Buttons
✅ Button states
✅ hover:
✅ focus:
✅ Focus rings
✅ space-y
✅ Labels
✅ block
✅ Input styling
✅ w-full
✅ max-w-*
✅ Centering forms
✅ Transitions
✅ cursor-pointer
