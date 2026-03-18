<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Egyptian Linguistics Olympiad — ELO 2026</title>
<script src="https://cdn.tailwindcss.com"></script>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet"/>
<style>
body{font-family:'Inter',sans-serif;-webkit-font-smoothing:antialiased;}
.page{display:block;}.page.hidden{display:none;}
.fade-in{animation:fi .3s ease both;}
@keyframes fi{from{opacity:0;transform:translateY(12px)}to{opacity:1;transform:none}}
.nav-active{color:#2563eb!important;font-weight:700!important;}
select{background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='12' height='8'%3E%3Cpath d='M0 0l6 8 6-8z' fill='%239ca3af'/%3E%3C/svg%3E");background-repeat:no-repeat;background-position:right 1rem center;background-size:10px;}
</style>
</head>
<body class="bg-white text-gray-900 overflow-x-hidden selection:bg-blue-100">

<!-- NAV -->
<nav class="bg-white border-b border-gray-100 sticky top-0 z-50">
  <div class="max-w-6xl mx-auto px-6 py-4 flex items-center justify-between">
    <div class="flex items-center gap-3 cursor-pointer" onclick="go('home')">
      <div class="w-10 h-10 bg-blue-600 rounded-lg flex items-center justify-center shadow-sm shrink-0"><span class="text-white font-bold text-xl">E</span></div>
      <span class="text-lg font-bold text-gray-900">Egyptian Linguistics Olympiad</span>
    </div>
    <div class="hidden md:flex items-center gap-8">
      <button data-page="home"    onclick="go('home')"    class="nav-link text-sm font-semibold text-gray-500 hover:text-blue-600 transition-colors">Home</button>
      <button data-page="samples" onclick="go('samples')" class="nav-link text-sm font-semibold text-gray-500 hover:text-blue-600 transition-colors">Samples</button>
      <button data-page="about"   onclick="go('about')"   class="nav-link text-sm font-semibold text-gray-500 hover:text-blue-600 transition-colors">About</button>
      <button onclick="go('register')" class="px-5 py-2.5 bg-blue-600 text-white text-sm font-bold rounded-lg hover:bg-blue-700 transition-all shadow-md">Register Now</button>
    </div>
    <button class="md:hidden p-1 text-gray-600" onclick="toggleMob()">
      <svg id="ic-open"  width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><line x1="3" y1="12" x2="21" y2="12"/><line x1="3" y1="6" x2="21" y2="6"/><line x1="3" y1="18" x2="21" y2="18"/></svg>
      <svg id="ic-close" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" style="display:none"><line x1="18" y1="6" x2="6" y2="18"/><line x1="6" y1="6" x2="18" y2="18"/></svg>
    </button>
  </div>
  <div id="mob-menu" class="md:hidden hidden flex-col gap-1 border-t border-gray-50 px-6 py-4">
    <button onclick="go('home')"    class="text-left px-3 py-2.5 rounded-lg text-gray-700 font-semibold hover:bg-gray-50">Home</button>
    <button onclick="go('samples')" class="text-left px-3 py-2.5 rounded-lg text-gray-700 font-semibold hover:bg-gray-50">Samples</button>
    <button onclick="go('about')"   class="text-left px-3 py-2.5 rounded-lg text-gray-700 font-semibold hover:bg-gray-50">About</button>
    <div class="pt-2 border-t border-gray-50">
      <button onclick="go('register')" class="w-full px-4 py-3 bg-blue-600 text-white text-sm font-bold rounded-lg hover:bg-blue-700">Register Now</button>
    </div>
  </div>
</nav>

<!-- HOME -->
<div id="page-home" class="page">

  <!-- Hero -->
  <section class="bg-white py-16 md:py-24 px-6">
    <div class="max-w-6xl mx-auto flex flex-col md:flex-row items-center gap-12">
      <div class="flex-1 space-y-6">
        <div class="inline-flex items-center gap-2 px-3 py-1 bg-blue-50 text-blue-600 text-xs font-bold rounded-full uppercase tracking-wider">
          <span class="w-1.5 h-1.5 bg-blue-500 rounded-full"></span>Our First Season in Egypt
        </div>
        <h1 class="text-4xl md:text-6xl font-extrabold text-gray-900 leading-tight">Egyptian <br/><span class="text-blue-600">Linguistics</span> Olympiad</h1>
        <p class="text-gray-600 text-lg max-w-lg leading-relaxed">Unlocking the secrets of language through logic. Open to <strong>all high school students</strong> in Egypt — no matter your school type or background.</p>
        <div class="flex flex-col sm:flex-row gap-4 pt-2">
          <button onclick="go('samples')" class="px-8 py-4 bg-blue-600 text-white font-bold rounded-xl hover:bg-blue-700 transition-all shadow-lg shadow-blue-200/50 flex items-center justify-center gap-2">Explore Samples <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"/><polyline points="14 2 14 8 20 8"/><line x1="16" y1="13" x2="8" y2="13"/><line x1="16" y1="17" x2="8" y2="17"/></svg></button>
          <button onclick="go('register')" class="px-8 py-4 bg-white border border-gray-200 text-gray-700 font-bold rounded-xl hover:bg-gray-50 transition-all">Join ELO 2026</button>
        </div>
        <div class="flex gap-8 pt-6 border-t border-gray-100">
          <div><p class="text-2xl font-extrabold text-blue-600">40+</p><p class="text-xs font-semibold text-gray-400 uppercase tracking-wide mt-0.5">Languages</p></div>
          <div><p class="text-2xl font-extrabold text-blue-600">3</p><p class="text-xs font-semibold text-gray-400 uppercase tracking-wide mt-0.5">Rounds</p></div>
          <div><p class="text-2xl font-extrabold text-blue-600">Free</p><p class="text-xs font-semibold text-gray-400 uppercase tracking-wide mt-0.5">To Enter</p></div>
        </div>
      </div>
      <div class="flex-1 w-full">
        <div class="rounded-3xl overflow-hidden shadow-2xl shadow-gray-200/60 border border-gray-100">
          <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?w=1000&auto=format&fit=crop&q=80" alt="Students collaborating" class="w-full h-auto object-cover" onerror="this.src='https://picsum.photos/seed/elo1/1000/700'"/>
        </div>
      </div>
    </div>
  </section>

  <!-- Welcome -->
  <section class="py-24 px-6 bg-gray-50 border-y border-gray-100">
    <div class="max-w-4xl mx-auto text-center space-y-10">
      <div><h2 class="text-3xl md:text-5xl font-bold text-gray-900 mb-4">Welcome to the ELO</h2><div class="w-20 h-1.5 bg-blue-600 mx-auto rounded-full"></div></div>
      <div class="space-y-5 text-gray-600 text-lg leading-relaxed text-left md:text-center">
        <p>The Egyptian Linguistics Olympiad (ELO) is an annual national competition that brings together secondary school students and experts from various fields of linguistics. As the official national qualifying event, the ELO identifies the brightest minds to represent Egypt in the International Linguistics Olympiad (IOL).</p>
        <p>The competition challenges participants to analyze the grammar, structure, and history of diverse languages through puzzles and problem-solving. No prior knowledge of linguistics or specific foreign languages is required — success depends on logical ability, patient work, and a willingness to think outside the box.</p>
        <div class="pt-4 flex flex-col items-center">
          <p class="font-bold text-blue-600 mb-6 italic">"Why not give some of our past problems a try and see if you have what it takes?"</p>
          <button onclick="go('samples')" class="flex items-center gap-2 text-gray-900 font-bold hover:text-blue-600 transition-colors group">View Past Problems <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="group-hover:translate-x-1 transition-transform"><polyline points="9 18 15 12 9 6"/></svg></button>
        </div>
      </div>
    </div>
  </section>

  <!-- What is Linguistics -->
  <section class="py-24 px-6 bg-white">
    <div class="max-w-6xl mx-auto flex flex-col md:flex-row items-center gap-16">
      <div class="flex-1 order-2 md:order-1">
        <div class="rounded-3xl overflow-hidden shadow-xl border border-gray-100">
          <img src="https://images.unsplash.com/photo-1456513080510-7bf3a84b82f8?w=800&auto=format&fit=crop&q=80" alt="Books" class="w-full" onerror="this.src='https://picsum.photos/seed/elo2/800/600'"/>
        </div>
      </div>
      <div class="flex-1 space-y-8 order-1 md:order-2">
        <div><span class="text-blue-600 font-bold tracking-widest text-xs uppercase">Understanding the Field</span><h2 class="text-4xl font-bold text-gray-900 mt-2">What is Linguistics?</h2></div>
        <p class="text-gray-600 text-lg leading-relaxed">Linguistics is the scientific study of language. It's not about how many languages you can speak, but how you analyze the systems behind them.</p>
        <div class="grid gap-2">
          <div class="flex gap-4 items-start p-4 rounded-2xl hover:bg-gray-50 transition-colors">
            <div class="w-12 h-12 bg-blue-100 text-blue-600 rounded-xl flex items-center justify-center shrink-0"><svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="11" cy="11" r="8"/><line x1="21" y1="21" x2="16.65" y2="16.65"/></svg></div>
            <div><h4 class="font-bold text-gray-900">Pattern Analysis</h4><p class="text-sm text-gray-500 mt-1">Decoding complex systems and uncovering hidden rules in language structure.</p></div>
          </div>
          <div class="flex gap-4 items-start p-4 rounded-2xl hover:bg-gray-50 transition-colors">
            <div class="w-12 h-12 bg-blue-100 text-blue-600 rounded-xl flex items-center justify-center shrink-0"><svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M9.5 2A2.5 2.5 0 0 1 12 4.5v15a2.5 2.5 0 0 1-4.96.44 2.5 2.5 0 0 1-2.04-2.44V4.5A2.5 2.5 0 0 1 7.5 2z"/><path d="M14.5 2A2.5 2.5 0 0 0 12 4.5v15a2.5 2.5 0 0 0 4.96.44 2.5 2.5 0 0 0 2.04-2.44V4.5A2.5 2.5 0 0 0 16.5 2z"/></svg></div>
            <div><h4 class="font-bold text-gray-900">Mental Processing</h4><p class="text-sm text-gray-500 mt-1">Exploring how the human brain handles grammar, meaning, and structure.</p></div>
          </div>
          <div class="flex gap-4 items-start p-4 rounded-2xl hover:bg-gray-50 transition-colors">
            <div class="w-12 h-12 bg-blue-100 text-blue-600 rounded-xl flex items-center justify-center shrink-0"><svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="16 18 22 12 16 6"/><polyline points="8 6 2 12 8 18"/></svg></div>
            <div><h4 class="font-bold text-gray-900">Computational &amp; AI</h4><p class="text-sm text-gray-500 mt-1">The science powering NLP, large language models, and speech recognition.</p></div>
          </div>
          <div class="flex gap-4 items-start p-4 rounded-2xl hover:bg-gray-50 transition-colors">
            <div class="w-12 h-12 bg-blue-100 text-blue-600 rounded-xl flex items-center justify-center shrink-0"><svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="10"/><circle cx="12" cy="12" r="6"/><circle cx="12" cy="12" r="2"/></svg></div>
            <div><h4 class="font-bold text-gray-900">Logic &amp; Systems</h4><p class="text-sm text-gray-500 mt-1">Applying rigorous reasoning to solve linguistic puzzles from scratch.</p></div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Important Dates -->
  <section class="py-24 px-6 bg-gray-50 border-y border-gray-100">
    <div class="max-w-6xl mx-auto">
      <div class="bg-white rounded-[28px] border border-gray-100 overflow-hidden">
        <div class="px-8 py-5 border-b border-gray-100 flex items-center gap-3">
          <svg class="text-blue-600" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="4" width="18" height="18" rx="2"/><line x1="16" y1="2" x2="16" y2="6"/><line x1="8" y1="2" x2="8" y2="6"/><line x1="3" y1="10" x2="21" y2="10"/></svg>
          <h3 class="text-lg font-bold text-gray-900">Important Dates</h3>
        </div>
        <div id="dates-rows" class="divide-y divide-gray-50"></div>
      </div>
    </div>
  </section>

  <!-- CTA -->
  <section class="py-20 px-6 bg-white">
    <div class="max-w-4xl mx-auto bg-blue-50 rounded-[40px] p-8 md:p-16 text-center border border-blue-100 relative overflow-hidden">
      <div class="absolute -top-10 -right-10 w-48 h-48 bg-blue-100 rounded-full opacity-50 pointer-events-none"></div>
      <div class="absolute -bottom-14 -left-14 w-64 h-64 bg-blue-100 rounded-full opacity-30 pointer-events-none"></div>
      <div class="relative z-10 space-y-6">
        <h2 class="text-3xl md:text-4xl font-bold text-gray-900 italic">Ready to test your logic?</h2>
        <p class="text-gray-600 text-lg max-w-xl mx-auto">Join students from across Egypt in this inaugural season. No language background needed — only your sharp mind.</p>
        <button onclick="go('register')" class="px-10 py-5 bg-blue-600 text-white font-bold rounded-2xl hover:bg-blue-700 transition-all shadow-xl shadow-blue-200 text-lg">Start Registration</button>
      </div>
    </div>
  </section>
</div>

<!-- SAMPLES -->
<div id="page-samples" class="page hidden">
  <div class="min-h-screen bg-white py-16 px-6">
    <div class="max-w-4xl mx-auto">
      <button onclick="go('home')" class="flex items-center gap-2 text-blue-600 font-bold mb-10 hover:text-blue-800">
        <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><line x1="19" y1="12" x2="5" y2="12"/><polyline points="12 19 5 12 12 5"/></svg>Back to Home
      </button>
      <header class="mb-12"><h2 class="text-4xl font-extrabold text-gray-900 mb-3">Past Papers &amp; Samples</h2><p class="text-gray-500 text-lg">Sharpen your logic with archived national selection problems. All self-contained — no prior knowledge needed.</p></header>
      <div class="space-y-4" id="samples-list"></div>
      <div class="mt-16 p-8 md:p-10 bg-blue-600 rounded-[32px] text-white shadow-xl shadow-blue-200 relative overflow-hidden">
        <div class="relative z-10">
          <h3 class="text-2xl font-bold mb-3">Need more practice?</h3>
          <p class="text-blue-100 mb-5">Explore the International Linguistics Olympiad's archive of puzzles from around the globe.</p>
          <a href="https://ioling.org" target="_blank" class="inline-block px-6 py-3 bg-white text-blue-600 font-bold rounded-xl hover:bg-gray-50 shadow-lg">Visit IOL Archive ↗</a>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- ABOUT -->
<div id="page-about" class="page hidden">
  <div class="min-h-screen bg-white py-16 px-6">
    <div class="max-w-4xl mx-auto space-y-16">
      <header class="text-center space-y-4">
        <h2 class="text-4xl md:text-5xl font-extrabold text-gray-900">About ELO</h2>
        <p class="text-gray-500 text-lg max-w-2xl mx-auto">The official gateway for high school students in Egypt to enter the global world of linguistics.</p>
      </header>
      <div class="grid md:grid-cols-2 gap-12 items-center">
        <div class="space-y-6">
          <h3 class="text-2xl font-bold text-gray-900">Our Mission</h3>
          <p class="text-gray-600 leading-relaxed text-lg">We aim to discover and foster the linguistic and logical talents of <strong>all Egyptian high school students</strong>. Whether you are in a STEM school, a national school, or private education, ELO is for you.</p>
          <div id="about-bullets" class="space-y-4"></div>
        </div>
        <div class="rounded-3xl overflow-hidden shadow-xl border border-gray-100">
          <img src="https://images.unsplash.com/photo-1516321497487-e288fb19713f?w=800&auto=format&fit=crop&q=80" alt="Students studying" class="w-full" onerror="this.src='https://picsum.photos/seed/elo3/800/600'"/>
        </div>
      </div>
      <div class="space-y-4"><h3 class="text-2xl font-bold text-gray-900">Frequently Asked Questions</h3><div id="faq-list" class="space-y-3"></div></div>
      <div class="bg-gray-50 rounded-[32px] p-10 space-y-8 border border-gray-100">
        <h3 class="text-2xl font-bold text-gray-900 text-center">Get in Touch</h3>
        <div class="grid sm:grid-cols-3 gap-8 text-center">
          <div class="space-y-2"><div class="w-12 h-12 bg-white rounded-2xl flex items-center justify-center mx-auto shadow-sm text-blue-600"><svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><polyline points="22,6 12,13 2,6"/></svg></div><p class="font-bold text-gray-900">Email</p><p class="text-gray-500 text-sm">info@elo-egypt.org</p></div>
          <div class="space-y-2"><div class="w-12 h-12 bg-white rounded-2xl flex items-center justify-center mx-auto shadow-sm text-blue-600"><svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0 1 18 0z"/><circle cx="12" cy="10" r="3"/></svg></div><p class="font-bold text-gray-900">Location</p><p class="text-gray-500 text-sm">Cairo, Egypt</p></div>
          <div class="space-y-2"><div class="w-12 h-12 bg-white rounded-2xl flex items-center justify-center mx-auto shadow-sm text-blue-600"><svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 0 0-3-3.87"/><path d="M16 3.13a4 4 0 0 1 0 7.75"/></svg></div><p class="font-bold text-gray-900">Community</p><p class="text-gray-500 text-sm">@ELOEgypt</p></div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- REGISTER -->
<div id="page-register" class="page hidden">
  <div class="min-h-screen bg-gray-50 py-16 px-6">
    <div id="reg-container" class="max-w-2xl mx-auto bg-white rounded-[40px] shadow-2xl shadow-gray-200/50 border border-gray-100 overflow-hidden">
      <div class="bg-blue-600 p-10 text-white text-center"><h2 class="text-3xl font-bold">Registration Form</h2><p class="text-blue-100/80 mt-1">ELO 2026 · The Inaugural Season in Egypt</p></div>
      <form id="reg-form" class="p-8 md:p-12 space-y-6">
        <div class="grid md:grid-cols-2 gap-6">
          <div class="space-y-2"><label class="text-sm font-bold text-gray-700 ml-1">First Name</label><input required type="text" placeholder="e.g. Ahmed" class="w-full px-5 py-4 rounded-2xl border border-gray-100 bg-gray-50/50 focus:bg-white focus:border-blue-500 focus:ring-4 focus:ring-blue-50 outline-none transition-all text-gray-900 placeholder-gray-400"/></div>
          <div class="space-y-2"><label class="text-sm font-bold text-gray-700 ml-1">Last Name</label><input required type="text" placeholder="e.g. Hassan" class="w-full px-5 py-4 rounded-2xl border border-gray-100 bg-gray-50/50 focus:bg-white focus:border-blue-500 focus:ring-4 focus:ring-blue-50 outline-none transition-all text-gray-900 placeholder-gray-400"/></div>
        </div>
        <div class="space-y-2"><label class="text-sm font-bold text-gray-700 ml-1">Email Address</label><input required type="email" placeholder="student@school.edu" class="w-full px-5 py-4 rounded-2xl border border-gray-100 bg-gray-50/50 focus:bg-white focus:border-blue-500 focus:ring-4 focus:ring-blue-50 outline-none transition-all text-gray-900 placeholder-gray-400"/></div>
        <div class="space-y-2"><label class="text-sm font-bold text-gray-700 ml-1">School Name</label><input required type="text" placeholder="Egyptian STEM or National High School" class="w-full px-5 py-4 rounded-2xl border border-gray-100 bg-gray-50/50 focus:bg-white focus:border-blue-500 focus:ring-4 focus:ring-blue-50 outline-none transition-all text-gray-900 placeholder-gray-400"/></div>
        <div class="grid md:grid-cols-2 gap-6">
          <div class="space-y-2"><label class="text-sm font-bold text-gray-700 ml-1">Grade Level</label><select class="w-full px-5 py-4 rounded-2xl border border-gray-100 bg-gray-50/50 focus:bg-white focus:border-blue-500 focus:ring-4 focus:ring-blue-50 outline-none transition-all appearance-none cursor-pointer text-gray-700"><option value="" disabled selected>Select grade</option><option>Grade 9</option><option>Grade 10</option><option>Grade 11</option><option>Grade 12</option></select></div>
          <div class="space-y-2"><label class="text-sm font-bold text-gray-700 ml-1">Phone Number</label><input type="tel" placeholder="+20 ..." class="w-full px-5 py-4 rounded-2xl border border-gray-100 bg-gray-50/50 focus:bg-white focus:border-blue-500 focus:ring-4 focus:ring-blue-50 outline-none transition-all text-gray-900 placeholder-gray-400"/></div>
        </div>
        <div class="pt-2">
          <button type="submit" class="w-full py-5 bg-blue-600 text-white font-bold rounded-2xl hover:bg-blue-700 transition-all flex items-center justify-center gap-3 text-lg shadow-xl shadow-blue-100">Join ELO 2026 <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><line x1="22" y1="2" x2="11" y2="13"/><polygon points="22 2 15 22 11 13 2 9 22 2"/></svg></button>
          <p class="text-center text-xs text-gray-400 mt-3">Your data will never be shared with third parties.</p>
        </div>
      </form>
    </div>
    <div id="reg-success" class="hidden max-w-md mx-auto text-center space-y-6 p-10 bg-blue-50 rounded-[40px] border border-blue-100 shadow-xl">
      <div class="w-20 h-20 bg-blue-600 rounded-3xl flex items-center justify-center mx-auto text-white shadow-lg"><svg width="40" height="40" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"/><polyline points="22 4 12 14.01 9 11.01"/></svg></div>
      <h2 class="text-3xl font-extrabold text-gray-900">Success!</h2>
      <p class="text-gray-600 leading-relaxed">Your application for ELO 2026 has been received. Check your inbox for the confirmation email and preparation guide.</p>
      <button onclick="go('home')" class="px-8 py-3 bg-blue-600 text-white font-bold rounded-xl hover:bg-blue-700">Back to Home</button>
    </div>
  </div>
</div>

<!-- FOOTER -->
<footer class="bg-white border-t border-gray-100 py-16 px-6">
  <div class="max-w-6xl mx-auto text-center space-y-8">
    <div class="flex justify-center gap-10">
      <a href="#" class="text-gray-400 hover:text-blue-600 text-sm font-bold transition-colors">Facebook</a>
      <a href="#" class="text-gray-400 hover:text-blue-600 text-sm font-bold transition-colors">Instagram</a>
      <a href="#" class="text-gray-400 hover:text-blue-600 text-sm font-bold transition-colors">LinkedIn</a>
      <a href="#" class="text-gray-400 hover:text-blue-600 text-sm font-bold transition-colors">Twitter</a>
    </div>
    <div><p class="text-gray-500 font-bold">Egyptian Linguistics Olympiad</p><p class="text-gray-400 text-xs tracking-widest uppercase mt-1">&copy; 2026 Inaugural Season · All Rights Reserved.</p></div>
  </div>
</footer>

<script>
var DATES=[
  {date:"Apr 01, 2026",event:"Registration Opens",detail:"Free registration at this website"},
  {date:"Apr 30, 2026",event:"Registration Closes",detail:"Final deadline for all applicants"},
  {date:"May 01, 2026",event:"Online Qualifier Begins",detail:"Remote exam period opens for all registered students"},
  {date:"May 31, 2026",event:"Online Qualifier Ends",detail:"Last day to complete the online qualifier"},
  {date:"Jun 15, 2026",event:"Qualifier Results",detail:"Top participants notified via email"},
  {date:"Jul 01, 2026",event:"National Finals",detail:"Top finalists — venue TBA"}
];
var SAMPLES=[
  {year:"2025",title:"National Finals Paper",type:"PDF",size:"1.2 MB",tags:["Hard","National"]},
  {year:"2024",title:"Round 1 Selection Test",type:"PDF",size:"850 KB",tags:["Easy","Intro"]},
  {year:"2023",title:"Official Training Samples",type:"ZIP",size:"4.5 MB",tags:["Medium","Mixed"]},
  {year:"2022",title:"Linguistics Logic Basics",type:"PDF",size:"1.1 MB",tags:["Beginner"]}
];
var BULLETS=["Identifying national finalists for the IOL","Promoting linguistics as a scientific academic path","Ensuring inclusivity for all high school students in Egypt","Connecting students with careers in AI, NLP, and cognitive science"];
var FAQS=[
  {q:"Do I need to know multiple languages?",a:"No. All problems are self-contained and solvable through pure logic."},
  {q:"Is there a registration fee?",a:"The competition is completely free at every stage."},
  {q:"What grades are eligible?",a:"All students enrolled in Grades 9 through 12 are eligible."},
  {q:"When will I hear back after registering?",a:"You will receive a confirmation email within 24 hours of submitting the form."},
  {q:"Can students from any type of school apply?",a:"Absolutely. STEM, national, private, and international schools are all welcome."}
];
var TAGS={Hard:"bg-red-50 text-red-600",National:"bg-purple-50 text-purple-600",Easy:"bg-green-50 text-green-600",Intro:"bg-teal-50 text-teal-600",Medium:"bg-amber-50 text-amber-600",Mixed:"bg-sky-50 text-sky-600",Beginner:"bg-blue-50 text-blue-600"};

function buildDates(){
  var el=document.getElementById('dates-rows');
  if(!el)return;
  el.innerHTML=DATES.map(function(d){
    return '<div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 px-8 py-4 hover:bg-gray-50 transition-colors">'
      +'<div class="flex items-center gap-6"><span class="text-sm font-bold text-blue-600 min-w-[130px]">'+d.date+'</span><span class="font-semibold text-gray-900 text-sm">'+d.event+'</span></div>'
      +'<span class="text-sm text-gray-400">'+d.detail+'</span></div>';
  }).join('');
}
function buildSamples(){
  var el=document.getElementById('samples-list');
  if(!el)return;
  el.innerHTML=SAMPLES.map(function(s){
    var tags=s.tags.map(function(t){return'<span class="text-[10px] font-bold px-2 py-0.5 rounded '+(TAGS[t]||'bg-gray-100 text-gray-500')+'">'+t+'</span>';}).join('');
    return '<div class="group p-6 border border-gray-100 rounded-2xl hover:border-blue-200 hover:shadow-lg transition-all flex flex-col sm:flex-row sm:items-center justify-between gap-4">'
      +'<div class="flex items-center gap-6"><div class="text-4xl font-black text-gray-100 group-hover:text-blue-600 transition-colors">'+s.year+'</div>'
      +'<div><h4 class="text-base font-bold text-gray-800">'+s.title+'</h4>'
      +'<div class="flex items-center gap-2 mt-1.5 flex-wrap"><span class="text-[10px] font-bold px-2 py-0.5 bg-gray-100 text-gray-500 rounded uppercase">'+s.type+'</span><span class="text-xs text-gray-400">'+s.size+'</span>'+tags+'</div></div></div>'
      +'<button class="flex items-center gap-2 px-6 py-2.5 bg-gray-50 group-hover:bg-blue-600 group-hover:text-white text-gray-700 rounded-xl transition-all font-bold text-sm shrink-0">Download <svg width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg></button></div>';
  }).join('');
}
function buildBullets(){
  var el=document.getElementById('about-bullets');
  if(!el)return;
  el.innerHTML=BULLETS.map(function(b){
    return '<div class="flex items-center gap-3"><svg class="text-blue-600 shrink-0" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"/><polyline points="22 4 12 14.01 9 11.01"/></svg><span class="text-gray-700 font-medium">'+b+'</span></div>';
  }).join('');
}
function buildFaqs(){
  var el=document.getElementById('faq-list');
  if(!el)return;
  el.innerHTML=FAQS.map(function(f,i){
    return '<div class="border border-gray-100 rounded-2xl overflow-hidden">'
      +'<button onclick="toggleFaq('+i+')" class="w-full flex items-center justify-between px-6 py-4 hover:bg-gray-50 text-left gap-4">'
      +'<span class="font-semibold text-gray-900">'+f.q+'</span>'
      +'<svg id="fi'+i+'" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" class="shrink-0 text-gray-400 transition-transform"><polyline points="6 9 12 15 18 9"/></svg></button>'
      +'<div id="fb'+i+'" class="hidden px-6 pb-5"><p class="text-gray-500">'+f.a+'</p></div></div>';
  }).join('');
}

function go(id){
  document.querySelectorAll('.page').forEach(function(p){p.classList.add('hidden');});
  document.querySelectorAll('.nav-link').forEach(function(l){
    var active=l.getAttribute('data-page')===id;
    l.classList.toggle('nav-active',active);
    l.classList.toggle('text-gray-500',!active);
  });
  var pg=document.getElementById('page-'+id);
  if(!pg)return;
  pg.classList.remove('hidden');
  pg.classList.add('fade-in');
  setTimeout(function(){pg.classList.remove('fade-in');},400);
  closeMob();
  window.scrollTo(0,0);
}
function toggleMob(){
  var m=document.getElementById('mob-menu');
  var open=!m.classList.contains('hidden');
  if(open){closeMob();}
  else{m.classList.remove('hidden');m.classList.add('flex');document.getElementById('ic-open').style.display='none';document.getElementById('ic-close').style.display='block';}
}
function closeMob(){
  var m=document.getElementById('mob-menu');
  m.classList.add('hidden');m.classList.remove('flex');
  document.getElementById('ic-open').style.display='block';document.getElementById('ic-close').style.display='none';
}
function toggleFaq(i){
  var b=document.getElementById('fb'+i),ic=document.getElementById('fi'+i);
  var h=b.classList.contains('hidden');
  b.classList.toggle('hidden');
  ic.style.transform=h?'rotate(180deg)':'';
}
document.getElementById('reg-form').addEventListener('submit',function(e){
  e.preventDefault();
  document.getElementById('reg-container').classList.add('hidden');
  var s=document.getElementById('reg-success');
  s.classList.remove('hidden');s.classList.add('fade-in');
});

window.addEventListener('DOMContentLoaded',function(){
  buildDates();buildSamples();buildBullets();buildFaqs();go('home');
});
</script>
</body>
</html>
