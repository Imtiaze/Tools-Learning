🎯 Day 3 Exercise

First, look at the code above and run it so you can see the design.

Then recreate it yourself without copying.

Your requirements:

Navbar
Mobile:
Logo                 Admin

Desktop:
Logo                 Admin
Cards

Mobile:

┌──────────────┐
│ Products     │
└──────────────┘

┌──────────────┐
│ Orders       │
└──────────────┘

┌──────────────┐
│ Revenue      │
└──────────────┘

Desktop:

┌──────────┐ ┌──────────┐ ┌──────────┐
│ Products │ │ Orders   │ │ Revenue  │
└──────────┘ └──────────┘ └──────────┘

And when you hover over a card:

the shadow should become larger smoothly.


Responsive navbar
Responsive cards
Grid
Hover shadow
Smooth transition
Responsive font sizes


What to observe when you run it

Desktop:

┌──────────────────────────────────────────────────────────┐
│ My Store                                      Admin      │
└──────────────────────────────────────────────────────────┘

        Welcome back!
        Here's what's happening with your store today.

        ┌────────────┐ ┌────────────┐ ┌────────────┐
        │ Products   │ │ Orders     │ │ Revenue    │
        │            │ │            │ │            │
        │ 450        │ │ 125        │ │ $12,500    │
        └────────────┘ └────────────┘ └────────────┘


        Recent Orders

        ┌──────────────────────────────────────────────┐
        │ Order #1001                         $120     │
        │ 2 products                                   │
        │──────────────────────────────────────────────│
        │ Order #1002                         $250     │
        │ 4 products                                   │
        │──────────────────────────────────────────────│
        │ Order #1003                         $180     │
        │ 1 product                                    │
        └──────────────────────────────────────────────┘

Mobile:

┌──────────────────────────┐
│ My Store          Admin  │
└──────────────────────────┘

  Welcome back!

  Here's what's happening
  with your store today.

┌──────────────────────────┐
│ Products                 │
│                          │
│ 450                      │
└──────────────────────────┘

┌──────────────────────────┐
│ Orders                   │
│                          │
│ 125                      │
└──────────────────────────┘

┌──────────────────────────┐
│ Revenue                  │
│                          │
│ $12,500                  │
└──────────────────────────┘

┌──────────────────────────┐
│ Recent Orders            │
│                          │
│ Order #1001        $120  │
│ 2 products              │
│──────────────────────────│
│ Order #1002        $250  │
│ 4 products              │
│──────────────────────────│
│ Order #1003        $180  │
│ 1 product               │
└──────────────────────────┘

The three most important new things to look at are:

grid grid-cols-1 md:grid-cols-3
text-3xl md:text-4xl
transition duration-300 hover:shadow-lg


my answer:


<div class="min-h-screen bg-gray-100">

    <nav class="bg-gray-900 text-white px-6 py-4 md:px-10">
        <div class="flex justify-between items-center">
            <h2 class="font-bold text-xl md:text-2xl">My Store</h2>
            <p class="text-gray-300">Admin</p>
        </div>
    </nav>

    <main class="max-w-5xl mx-auto p-6 md:p-8">
        <div class="mb-8">
            <h2 class="text-3xl md:text-4xl font-bold">Welcome Back!</h2>
            <p class="text-gray-500 mt-2">Here's what's happening to your store today.</p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
            <div class="bg-white p-6 rounded-xl shadow hover:shadow-lg transition duration-300">
                <p class="text-gray-500">Products</p>
                <h2 class="text-3xl font-bold mt-2">450</h2>
            </div>

            <div class="bg-white p-6 rounded-xl shadow hover:shadow-lg transition duration-300">
                <p class="text-gray-500">Orders</p>
                <h2 class="text-3xl font-bold mt-2">125</h2>
            </div>

            <div class="bg-white p-6 rounded-xl shadow hover:shadow-lg transition duration-300">
                <p class="text-gray-500">Revenue</p>
                <h2 class="text-3xl font-bold mt-2">$12500</h2>
            </div>
            
        </div>

        <div class="bg-white p-6 mt-8 rounded-xl shadow">

            <h2 class="text-2xl font-bold mb-4">Recent Order</h2>
            
            <div class="flex justify-between items-center border-b py-4">
                <div>
                    <p class="font-medium">Order #1001</p>
                    <p class="text-sm text-gray-500">2 Products</p>
                </div>
                <p class="font-bold">$450</p>
            </div>

            <div class="flex justify-between items-center border-b py-4">
                <div>
                    <p class="font-medium">Order #1002</p>
                    <p class="text-sm text-gray-500">4 Products</p>
                </div>
                <p class="font-bold">$250</p>
            </div>
            <div class="flex justify-between items-center  py-4">
                <div>
                    <p class="font-medium">Order #1003</p>
                    <p class="text-sm text-gray-500">1 Products</p>
                </div>
                <p class="font-bold">$180</p>
            </div>
            

        </div>


    </main>

</div>


Day 3 score: 9.5/10 🏆

You've now learned:

✅ Responsive prefixes
✅ Mobile-first thinking
✅ md:
✅ Responsive padding
✅ Responsive typography
✅ Flex responsive layouts
✅ CSS Grid
✅ grid-cols-*
✅ Responsive Grid
✅ Hover
✅ Transition
✅ Duration
✅ Shadow effects


Next: Day 4

We'll move into real UI building:

Borders → Dividers → Buttons → Forms → Inputs → Focus states → Disabled states → Better cards

This is where you'll start being able to build actual Laravel CRUD interfaces rather than just dashboard examples.