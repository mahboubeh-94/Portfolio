# Portfolio
<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>پورتفولیو طراح محصول</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    body { font-family: 'Vazir', 'Roboto', sans-serif; }
    @font-face {
      font-family: 'Vazir';
      src: url('https://cdn.fontcdn.ir/Font/Persian/Vazir/Vazir.woff') format('woff');
    }
  </style>
</head>
<body class="bg-gray-100 text-gray-800">
  <!-- Header -->
  <header class="bg-white shadow sticky top-0 z-10">
    <div class="container mx-auto px-4 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold text-blue-600">نام شما | Your Name</h1>
      <nav>
        <ul class="flex space-x-4 space-x-reverse">
          <li><a href="#home" class="hover:text-blue-600">خانه</a></li>
          <li><a href="#projects" class="hover:text-blue-600">پروژه‌ها</a></li>
          <li><a href="#skills" class="hover:text-blue-600">مهارت‌ها</a></li>
          <li><a href="#about" class="hover:text-blue-600">درباره</a></li>
          <li><a href="#contact" class="hover:text-blue-600">تماس</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section id="home" class="bg-blue-600 text-white py-20">
    <div class="container mx-auto px-4 text-center">
      <h2 class="text-4xl font-bold mb-4">سلام، من طراح محصول هستم</h2>
      <p class="text-xl mb-6">Hi, I'm a Product Designer passionate about creating user-friendly and beautiful interfaces.</p>
      <a href="#projects" class="bg-white text-blue-600 px-6 py-3 rounded-lg hover:bg-gray-200">پروژه‌های من را ببینید</a>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="py-16">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold text-center mb-12">پروژه‌ها | Projects</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- Project 1 -->
        <div class="bg-white rounded-lg shadow-lg overflow-hidden">
          <img src="https://via.placeholder.com/400x200?text=Music+App" alt="اپلیکیشن موسیقی" class="w-full h-48 object-cover">
          <div class="p-6">
            <h3 class="text-xl font-bold mb-2">اپلیکیشن موسیقی</h3>
            <p class="text-gray-600 mb-4">طراحی رابط کاربری برای یک اپلیکیشن موسیقی با تمرکز بر تجربه کاربری ساده و جذاب.</p>
            <p class="text-gray-600 mb-4">Music App UI design focusing on a clean and engaging user experience.</p>
            <a href="#" class="text-blue-600 hover:underline">جزئیات بیشتر</a>
          </div>
        </div>
        <!-- Project 2 -->
        <div class="bg-white rounded-lg shadow-lg overflow-hidden">
          <img src="https://via.placeholder.com/400x200?text=E-Commerce+App" alt="اپلیکیشن تجارت الکترونیک" class="w-full h-48 object-cover">
          <div class="p-6">
            <h3 class="text-xl font-bold mb-2">اپلیکیشن تجارت الکترونیک</h3>
            <p class="text-gray-600 mb-4">طراحی یک اپلیکیشن خرید آنلاین با ناوبری بصری و فرآیند پرداخت ساده.</p>
            <p class="text-gray-600 mb-4">E-Commerce App with intuitive navigation and a streamlined checkout process.</p>
            <a href="#" class="text-blue-600 hover:underline">جزئیات بیشتر</a>
          </div>
        </div>
        <!-- Project 3 -->
        <div class="bg-white rounded-lg shadow-lg overflow-hidden">
          <img src="https://via.placeholder.com/400x200?text=To-Do+App" alt="اپلیکیشن وظایف" class="w-full h-48 object-cover">
          <div class="p-6">
            <h3 class="text-xl font-bold mb-2">اپلیکیشن وظایف</h3>
            <p class="text-gray-600 mb-4">طراحی اپلیکیشن مدیریت وظایف با تمرکز بر سادگی و قابلیت استفاده.</p>
            <p class="text-gray-600 mb-4">To-Do App designed for simplicity and usability.</p>
            <a href="#" class="text-blue-600 hover:underline">جزئیات بیشتر</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Skills Section -->
  <section id="skills" class="bg-gray-200 py-16">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold text-center mb-12">مهارت‌ها | Skills</h2>
      <div class="grid grid-cols-2 md:grid-cols-4 gap-4 text-center">
        <div class="bg-white p-4 rounded-lg shadow">طراحی UX</div>
        <div class="bg-white p-4 rounded-lg shadow">طراحی UI</div>
        <div class="bg-white p-4 rounded-lg shadow">فیگما | Figma</div>
        <div class="bg-white p-4 rounded-lg shadow">تحقیقات کاربری</div>
        <div class="bg-white p-4 rounded-lg shadow">پروتوتایپ‌سازی</div>
        <div class="bg-white p-4 rounded-lg shadow">طراحی پاسخگو</div>
        <div class="bg-white p-4 rounded-lg shadow">تفکر طراحی</div>
        <div class="bg-white p-4 rounded-lg shadow">دسترسی‌پذیری</div>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="py-16">
    <div class="container mx-auto px-4 text-center">
      <h2 class="text-3xl font-bold mb-12">درباره من | About Me</h2>
      <p class="text-lg mb-4">من یک طراح محصول مشتاق هستم که به خلق تجربیات کاربری جذاب و کاربردی علاقه‌مندم. هدفم طراحی محصولاتی است که زندگی کاربران را ساده‌تر و لذت‌بخش‌تر کند.</p>
      <p class="text-lg">I’m a passionate Product Designer focused on creating engaging and functional user experiences. My goal is to design products that make users’ lives easier and more enjoyable.</p>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="bg-blue-600 text-white py-16">
    <div class="container mx-auto px-4 text-center">
      <h2 class="text-3xl font-bold mb-12">تماس با من | Contact Me</h2>
      <p class="text-lg mb-6">برای همکاری یا سوالات، با من در ارتباط باشید!</p>
      <p class="text-lg mb-6">Reach out for collaborations or inquiries!</p>
      <div class="flex justify-center space-x-4 space-x-reverse">
        <a href="mailto:your.email@example.com" class="bg-white text-blue-600 px-4 py-2 rounded-lg hover:bg-gray-200">ایمیل</a>
        <a href="https://linkedin.com" class="bg-white text-blue-600 px-4 py-2 rounded-lg hover:bg-gray-200">لینکدین</a>
        <a href="https://x.com" class="bg-white text-blue-600 px-4 py-2 rounded-lg hover:bg-gray-200">ایکس</a>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-800 text-white py-4">
    <div class="container mx-auto px-4 text-center">
      <p>&copy; 2025 نام شما | Your Name. تمامی حقوق محفوظ است.</p>
    </div>
  </footer>
</body>
</html>
