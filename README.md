<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Responsive Dashboard</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="font-sans bg-gray-100">

  <!-- Sidebar -->
  <div class="flex">
    <div class="w-64 bg-blue-800 text-white min-h-screen p-6">
      <h1 class="text-2xl font-bold mb-8">Dashboard</h1>
      <ul class="space-y-6">
        <li><a href="#" class="text-lg hover:text-blue-300">Home</a></li>
        <li><a href="#" class="text-lg hover:text-blue-300">Analytics</a></li>
        <li><a href="#" class="text-lg hover:text-blue-300">Users</a></li>
        <li><a href="#" class="text-lg hover:text-blue-300">Settings</a></li>
        <li><a href="#" class="text-lg hover:text-blue-300">Logout</a></li>
      </ul>
    </div>

    <!-- Main Content -->
    <div class="flex-1 p-6">
      
      <!-- Top Bar -->
      <div class="flex justify-between items-center bg-white shadow-md rounded-lg p-4 mb-6">
        <div class="text-xl font-semibold">Welcome Back, RAJPUT DEVENDRA SINGH</div>
        <div class="space-x-4">
          <button class="bg-blue-600 text-white px-4 py-2 rounded-lg hover:bg-blue-700">Notifications</button>
          <button class="bg-blue-600 text-white px-4 py-2 rounded-lg hover:bg-blue-700">Profile</button>
        </div>
      </div>

      <!-- Dashboard Cards -->
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- Card 1 -->
        <div class="bg-white p-6 rounded-lg shadow-lg">
          <h3 class="text-lg font-semibold">Total Users</h3>
          <p class="text-4xl font-bold mt-4">1,024</p>
        </div>
        
        <!-- Card 2 -->
        <div class="bg-white p-6 rounded-lg shadow-lg">
          <h3 class="text-lg font-semibold">Revenue</h3>
          <p class="text-4xl font-bold mt-4">$15,320</p>
        </div>

        <!-- Card 3 -->
        <div class="bg-white p-6 rounded-lg shadow-lg">
          <h3 class="text-lg font-semibold">Active Users</h3>
          <p class="text-4xl font-bold mt-4">720</p>
        </div>
      </div>

      <!-- Chart Section -->
      <div class="mt-8">
        <div class="bg-white p-6 rounded-lg shadow-lg">
          <h3 class="text-lg font-semibold mb-4">Sales Over Time</h3>
          <div class="bg-gray-300 h-56 rounded-lg">
            <!-- Placeholder for a chart (could be a JavaScript chart like Chart.js or just a simple placeholder) -->
            <p class="text-center text-gray-500 pt-24">RITIK FINANCE</p>
          </div>
        </div>
      </div>
    </div>
  </div>

</body>
</html>
