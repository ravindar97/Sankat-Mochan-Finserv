<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sankat Mochan Finserv</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
  <style>
    header {
      background:blueviolet url('https://upload.wikimedia.org/wikipedia/commons/3/30/Hanuman-ji.png');
      background-size: cover;
      background-position: center;
    }
    header::before {
      content: "";
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background: rgba(0, 0, 0, 0.6);
      z-index: 0;
    }
    header > * {
      position: relative;
      z-index: 1;
    }
  </style>
</head>
<body class="bg-white text-gray-800">
  <!-- Header -->
  <header class="relative text-white p-4 flex justify-between items-center">
    <div class="text-xl font-bold">Sankat Mochan Finserv</div>
    <nav class="space-x-4">
      <a href="#" class="hover:underline">Home</a>
      <a href="#services" class="hover:underline">Services</a>
      <a href="#apply" class="hover:underline">Apply</a>
      <a href="#contact" class="hover:underline">Contact</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="text-center py-20 bg-blue-50">
    <h1 class="text-4xl font-bold mb-4">Empowering Dreams with Trusted Loans</h1>
    <p class="text-lg mb-6">Affordable loans for businesses, homes, vehicles, and more—fast approvals, minimal paperwork.</p>
    <div class="space-x-4">
      <a href="#apply" class="bg-blue-900 text-white px-6 py-2 rounded">Apply Now</a>
      <a href="#calculator" class="bg-white border border-blue-900 text-blue-900 px-6 py-2 rounded">Loan Calculator</a>
    </div>
  </section>

  <!-- Loan Services Section -->
  <section id="services" class="py-16 px-6 bg-white">
    <h2 class="text-3xl font-bold text-center mb-12">Our Loan Services</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
      <div class="border p-6 rounded-lg shadow hover:shadow-lg">
        <h3 class="text-xl font-semibold mb-2"><i class="fas fa-briefcase mr-2 text-blue-900"></i>Small Business Loan</h3>
        <p>Support for your business needs with flexible repayment terms.</p>
      </div>
      <div class="border p-6 rounded-lg shadow hover:shadow-lg">
        <h3 class="text-xl font-semibold mb-2"><i class="fas fa-home mr-2 text-blue-900"></i>Home Loan</h3>
        <p>Make your dream home a reality with our affordable home loans.</p>
      </div>
      <div class="border p-6 rounded-lg shadow hover:shadow-lg">
        <h3 class="text-xl font-semibold mb-2"><i class="fas fa-car mr-2 text-blue-900"></i>Vehicle Loan</h3>
        <p>Get on the road quickly with easy vehicle financing options.</p>
      </div>
      <div class="border p-6 rounded-lg shadow hover:shadow-lg">
        <h3 class="text-xl font-semibold mb-2"><i class="fas fa-user-friends mr-2 text-blue-900"></i>Personal Loan</h3>
        <p>Quick funds for any personal need, no collateral required.</p>
      </div>
      <div class="border p-6 rounded-lg shadow hover:shadow-lg">
        <h3 class="text-xl font-semibold mb-2"><i class="fas fa-tractor mr-2 text-blue-900"></i>Agriculture Land Loan</h3>
        <p>Loans to support your agricultural land purchases and needs.</p>
      </div>
      <div class="border p-6 rounded-lg shadow hover:shadow-lg">
        <h3 class="text-xl font-semibold mb-2"><i class="fas fa-tree mr-2 text-blue-900"></i>Free Land Loan</h3>
        <p>Financial support for acquiring non-agricultural or open land.</p>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-16 bg-blue-50 px-6">
    <h2 class="text-3xl font-bold text-center mb-8">Contact Us</h2>
    <div class="max-w-2xl mx-auto space-y-4 text-center">
      <p><i class="fas fa-user mr-2"></i><strong>E Srinivas</strong></p>
      <p><i class="fas fa-envelope mr-2"></i> sankatmochanfinserv.com</p>
      <p><i class="fas fa-phone mr-2"></i> 94901 93678, 96404 76748</p>
    </div>
  </section>
</body>
</html>

