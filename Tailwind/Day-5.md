
<div class="bg-white rounded-xl shadow overflow-hidden m-4">
    <table class="w-full">
        <thead class="bg-gray-50">
            <tr>
                <th class="px-6 py-3 text-left text-sm font-semibold text-gray-600">Name</th>
                <th class="px-6 py-3 text-left text-sm font-semibold text-gray-600">Email</th>
                <th class="px-6 py-3 text-left text-sm font-semibold text-gray-600">Status</th>
            </tr>
        </thead>

        <tbody>
            <tr class="border-b hover:bg-gray-50">
                <td class="px-6 py-3">John</td>
                <td class="px-6 py-3">john@example.com</td>
                <td class="px-6 py-3">
                    <span class="bg-green-100 text-green-700 px-3 py-1 rounded-full text-sm font-medium">Active</span>
                </td>
            </tr>
            <tr class="border-b hover:bg-gray-50">
                <td class="px-6 py-3">John</td>
                <td class="px-6 py-3">john@example.com</td>
                <td class="px-6 py-3">
                    <span class="bg-gray-100 text-gray-600 px-3 py-1 rounded-full text-sm font-medium">Inactive</span>
                </td>
            </tr>
            <tr class="border-b hover:bg-gray-50">
                <td class="px-6 py-3">John</td>
                <td class="px-6 py-3">john@example.com</td>
                <td class="px-6 py-3">
                    <span class="bg-gray-100 text-gray-600 px-3 py-1 rounded-full text-sm font-medium">Inactive</span>
                </td>
            </tr>
        </tbody>
    </table>
</div>


<body class="bg-gray-100">
    <div class="flex justify-between m-8 bg-white px-6 py-3 rounded-xl">
        <div>
            <h2 class="text-xl font-bold">Products</h2>
            <p class="text-sm">Manage your inventory</p>
        </div>
        <button class="bg-blue-600 text-white px-5 py-2 rounded-lg hover:bg-blue-700 transition duration-300">
            + Add Product
        </button>

    </div>    

    <div class="flex gap-6 m-8 bg-white px-6 py-3 rounded-xl">
        <input type="text" class="border  w-full">
        <button class="bg-blue-600 text-white px-5 py-2 rounded-lg hover:bg-blue-700 transition duration-300">
            + Add Product
        </button>

    </div>    
    </div>   

    <!-- Search & Filter -->
        <div class="bg-white rounded-xl shadow p-4 mb-6">

            <div class="flex flex-col md:flex-row gap-4">

                <input
                    type="text"
                    placeholder="Search products..."
                    class="w-full border border-gray-300 rounded-lg px-4 py-2 focus:border-blue-500 focus:ring-2 focus:ring-blue-200">

                <select
                    class="border border-gray-300 rounded-lg px-4 py-2 focus:border-blue-500 focus:ring-2 focus:ring-blue-200">
                    <option>All Categories</option>
                    <option>T-Shirts</option>
                    <option>Jeans</option>
                    <option>Shoes</option>
                </select>

            </div>

        </div> 
</body>