<!DOCTYPE html>
<html lang="en" class="scroll-smooth antialiased">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Finoma — Quietly Powerful Finance</title>
  <meta name="description" content="Finoma: Quick funds with transparent terms. Minimal, luxurious fintech for modern professionals." />

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>

  <style>
    /* Minimal custom styles */
    .focus-outline:focus-visible {
      outline: 2px solid rgba(0,0,0,0.6);
      outline-offset: 3px;
    }
    .focus-outline--inverted:focus-visible {
      outline: 2px solid rgba(255,255,255,0.8);
      outline-offset: 3px;
    }
  </style>
</head>

<body class="bg-white text-black font-sans">
  <!-- Navbar -->
  <header class="relative">
    <div class="absolute inset-0 bg-black"></div>
    <nav class="relative z-10">
      <div class="mx-auto max-w-7xl px-6">
        <div class="flex h-20 items-center justify-between">
          <!-- Brand -->
          <a href="#home" class="flex items-center gap-3 text-white focus-outline--inverted" aria-label="Finoma Home">
            <div class="h-9 w-9 rounded-full bg-white/10 ring-1 ring-white/20 flex items-center justify-center">
              <span class="font-serif text-xl leading-none tracking-tight">
                <img src="banner.jpg">
              </span>
            </div>
            <div class="leading-tight">
              <span class="block font-serif text-xl tracking-tight">Finoma</span>
              <span class="block text-xs text-white/70">Quick funds, Brighter tomorrow</span>
            </div>
          </a>

          <!-- Desktop Nav -->
          <div class="hidden items-center gap-8 md:flex">
            <a href="#home" class="text-sm text-white/80 hover:text-white transition-colors focus-outline--inverted">Home</a>
            <a href="#services" class="text-sm text-white/80 hover:text-white transition-colors focus-outline--inverted">Services</a>
            <a href="#features" class="text-sm text-white/80 hover:text-white transition-colors focus-outline--inverted">Features</a>
            <a href="#how" class="text-sm text-white/80 hover:text-white transition-colors focus-outline--inverted">How It Works</a>
            <a href="#contact" class="text-sm text-white/80 hover:text-white transition-colors focus-outline--inverted">Contact</a>
            <a href="#cta" class="inline-flex items-center rounded-full bg-white px-4 py-2 text-sm font-medium text-black shadow-sm transition hover:-translate-y-0.5 hover:opacity-90 focus-outline--inverted">Get Started</a>
          </div>

          <!-- Mobile Nav -->
          <details class="md:hidden text-white">
            <summary class="cursor-pointer rounded-full border border-white/20 px-3 py-1 text-sm hover:bg-white/10 focus-outline--inverted">Menu</summary>
            <div class="mt-3 rounded-lg border border-white/10 bg-black/90 p-3 backdrop-blur">
              <div class="flex flex-col">
                <a href="#home" class="px-2 py-2 text-sm text-white/90 hover:text-white focus-outline--inverted">Home</a>
                <a href="#services" class="px-2 py-2 text-sm text-white/90 hover:text-white focus-outline--inverted">Services</a>
                <a href="#features" class="px-2 py-2 text-sm text-white/90 hover:text-white focus-outline--inverted">Features</a>
                <a href="#how" class="px-2 py-2 text-sm text-white/90 hover:text-white focus-outline--inverted">How It Works</a>
                <a href="#contact" class="px-2 py-2 text-sm text-white/90 hover:text-white focus-outline--inverted">Contact</a>
                <a href="#cta" class="mt-2 inline-flex items-center justify-center rounded-md bg-white px-3 py-2 text-sm font-medium text-black transition hover:opacity-90 focus-outline--inverted">Get Started</a>
              </div>
            </div>
          </details>
        </div>
      </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="relative isolate bg-black text-white">
      <div class="mx-auto max-w-7xl px-6 pt-28 pb-24 md:pt-32 md:pb-28">
        <div class="grid items-center gap-12 md:grid-cols-2">
          <div class="reveal">
            <h1 class="font-serif text-4xl sm:text-5xl md:text-6xl leading-tight tracking-tight">
              Quietly confident finance for modern professionals.
            </h1>
            <p class="mt-6 max-w-xl text-base text-white/80 md:text-lg">
              Quick, transparent financial support—without the noise. Access short-term credit with clarity, repay with ease, and move forward with confidence.
            </p>
            <div class="mt-8 flex flex-wrap items-center gap-4">
              <a href="#cta" class="inline-flex items-center rounded-full bg-white px-5 py-2.5 text-sm font-medium text-black shadow-sm transition hover:-translate-y-0.5 hover:opacity-90 focus-outline--inverted">Get Started</a>
              <a href="#features" class="inline-flex items-center rounded-full border border-white/20 px-5 py-2.5 text-sm font-medium text-white/90 hover:text-white hover:bg-white/10 transition focus-outline--inverted">Explore Features</a>
            </div>
          </div>
          <div class="reveal">
            <div class="relative aspect-[4/3] w-full rounded-2xl border border-white/10 bg-gradient-to-b from-white/10 to-white/5 shadow-[inset_0_1px_0_0_rgba(255,255,255,0.06)]">
              <div class="absolute inset-0 flex items-center justify-center">
                <div class="text-center">
                  <!-- <div class="mx-auto mb-4 h-16 w-16 rounded-full bg-white/10 ring-1 ring-white/20"></div> -->
                  <!-- <p class="text-sm text-white/60">Professional grayscale illustration</p> -->
                 <img src="heroimage.jpg" class="relative aspect-[4/4] w-full rounded-2xl border border-white/10 bg-gradient-to-b from-white/10 to-white/5 shadow-[inset_0_1px_0_0_rgba(255,255,255,0.06)]">
                </div>
              </div>
            </div>
            <!-- <p class="mt-3 text-xs text-white/50">Optional imagery only—kept understated and monochrome.</p> -->
          </div>
        </div>
      </div>
    </section>
  </header>

  <!-- Main Content -->
  <main>
    <!-- Why Choose Finoma -->
    <section id="why" class="bg-white">
      <div class="mx-auto max-w-7xl px-6 py-20 md:py-24">
        <div class="reveal mx-auto max-w-3xl text-center">
          <h2 class="font-serif text-3xl md:text-4xl tracking-tight">Why Choose Finoma?</h2>
          <p class="mt-4 text-base text-gray-600 md:text-lg">Designed with restraint, built for speed, and delivered with transparency.</p>
        </div>
        <div class="mt-12 grid gap-6 sm:grid-cols-2 lg:grid-cols-4">
          <!-- Cards (Quick Processing, Transparent, Flexible, Trusted) -->
          <!-- Card 1 -->
          <div class="reveal rounded-xl border border-gray-200 bg-white p-6 shadow-sm transition hover:-translate-y-0.5 hover:shadow-md">
            <div class="mb-4 h-10 w-10 rounded-md bg-gray-100 flex items-center justify-center">
              <svg viewBox="0 0 24 24" class="h-5 w-5 text-gray-800" fill="none" stroke="currentColor" stroke-width="1.5">
                <path d="M13 3L4 14h7l-1 7 9-11h-7l1-7z" />
              </svg>
            </div>
            <h3 class="font-serif text-xl">Quick processing</h3>
            <p class="mt-2 text-sm text-gray-600">From request to approval in minutes—time is a luxury.</p>
          </div>
          <!-- Card 2 -->
          <div class="reveal rounded-xl border border-gray-200 bg-white p-6 shadow-sm transition hover:-translate-y-0.5 hover:shadow-md">
            <div class="mb-4 h-10 w-10 rounded-md bg-gray-100 flex items-center justify-center">
              <svg viewBox="0 0 24 24" class="h-5 w-5 text-gray-800" fill="none" stroke="currentColor" stroke-width="1.5">
                <path d="M2 12s4-7 10-7 10 7 10 7-4 7-10 7S2 12 2 12z" />
                <circle cx="12" cy="12" r="3" />
              </svg>
            </div>
            <h3 class="font-serif text-xl">Transparent terms</h3>
            <p class="mt-2 text-sm text-gray-600">Clarity at every step—no hidden surprises.</p>
          </div>
          <!-- Card 3 -->
          <div class="reveal rounded-xl border border-gray-200 bg-white p-6 shadow-sm transition hover:-translate-y-0.5 hover:shadow-md">
            <div class="mb-4 h-10 w-10 rounded-md bg-gray-100 flex items-center justify-center">
              <svg viewBox="0 0 24 24" class="h-5 w-5 text-gray-800" fill="none" stroke="currentColor" stroke-width="1.5">
                <path d="M7 7h10l-3-3M17 17H7l3 3" />
              </svg>
            </div>
            <h3 class="font-serif text-xl">Flexible repayment</h3>
            <p class="mt-2 text-sm text-gray-600">Match repayments with how you actually live and work.</p>
          </div>
          <!-- Card 4 -->
          <div class="reveal rounded-xl border border-gray-200 bg-white p-6 shadow-sm transition hover:-translate-y-0.5 hover:shadow-md">
            <div class="mb-4 h-10 w-10 rounded-md bg-gray-100 flex items-center justify-center">
              <svg viewBox="0 0 24 24" class="h-5 w-5 text-gray-800" fill="none" stroke="currentColor" stroke-width="1.5">
                <path d="M12 3l7 4v5c0 5-3.5 9-7 9s-7-4-7-9V7l7-4z" />
              </svg>
            </div>
            <h3 class="font-serif text-xl">Trusted brand</h3>
            <p class="mt-2 text-sm text-gray-600">Discretion, reliability, and service at the core.</p>
          </div>
        </div>
      </div>
    </section>
    <!-- Services Section -->
<section id="services" class="bg-gray-50">
  <div class="mx-auto max-w-7xl px-6 py-20 md:py-24">
    <div class="reveal mx-auto max-w-3xl text-center">
      <h2 class="font-serif text-3xl md:text-4xl tracking-tight">Our Services</h2>
    </div>

    <div class="mt-12 grid gap-6 md:grid-cols-3">
      <!-- Service 1 -->
      <div class="reveal rounded-xl border border-gray-200 bg-white p-6 shadow-sm transition hover:-translate-y-0.5 hover:shadow-md">
        <div class="mb-4 h-10 w-10 rounded-md bg-gray-100 flex items-center justify-center">
          <svg viewBox="0 0 24 24" class="h-5 w-5 text-gray-800" fill="none" stroke="currentColor" stroke-width="1.5">
            <rect x="3" y="5" width="18" height="14" rx="2" />
            <path d="M3 10h18" />
          </svg>
        </div>
        <h3 class="font-serif text-xl">Digital Payment Card</h3>
        <p class="mt-2 text-sm text-gray-600">Activate instantly and begin using your digital card within minutes.</p>
      </div>

      <!-- Service 2 -->
      <div class="reveal rounded-xl border border-gray-200 bg-white p-6 shadow-sm transition hover:-translate-y-0.5 hover:shadow-md">
        <div class="mb-4 h-10 w-10 rounded-md bg-gray-100 flex items-center justify-center">
          <svg viewBox="0 0 24 24" class="h-5 w-5 text-gray-800" fill="none" stroke="currentColor" stroke-width="1.5">
            <rect x="4" y="6" width="16" height="12" rx="2" />
            <path d="M8 10h8M8 14h5" />
          </svg>
        </div>
        <h3 class="font-serif text-xl">Instant Credit</h3>
        <p class="mt-2 text-sm text-gray-600">Borrow short‑term amounts quickly, with elegant simplicity.</p>
      </div>

      <!-- Service 3 -->
      <div class="reveal rounded-xl border border-gray-200 bg-white p-6 shadow-sm transition hover:-translate-y-0.5 hover:shadow-md">
        <div class="mb-4 h-10 w-10 rounded-md bg-gray-100 flex items-center justify-center">
          <svg viewBox="0 0 24 24" class="h-5 w-5 text-gray-800" fill="none" stroke="currentColor" stroke-width="1.5">
            <path d="M3 17l6-6 4 4 8-8" />
          </svg>
        </div>
        <h3 class="font-serif text-xl">Behavioral Assessment</h3>
        <p class="mt-2 text-sm text-gray-600">Boost limits over time based on consistent, disciplined usage.</p>
      </div>
    </div>
  </div>
</section>

<!-- Features Section -->
<section id="features" class="bg-white">
  <div class="mx-auto max-w-7xl px-6 py-20 md:py-24">
    <div class="reveal mx-auto max-w-3xl text-center">
      <h2 class="font-serif text-3xl md:text-4xl tracking-tight">Our Features</h2>
    </div>

    <div class="mt-12 grid gap-6 sm:grid-cols-2 lg:grid-cols-4">
      <!-- Feature 1 -->
      <div class="reveal rounded-xl border border-gray-200 bg-white p-6 shadow-sm transition hover:shadow-md">
        <div class="mb-3 h-8 w-8 rounded bg-gray-100 flex items-center justify-center">
          <svg viewBox="0 0 24 24" class="h-4 w-4 text-gray-800" fill="none" stroke="currentColor" stroke-width="1.5">
            <path d="M3 3h8v8H3zM13 3h8v5h-8zM13 10h8v11h-8zM3 13h8v8H3z"/>
          </svg>
        </div>
        <h3 class="font-serif text-lg">Smart Dashboard</h3>
        <p class="mt-1 text-sm text-gray-600">Clarity at a glance—balance, usage, repayment.</p>
      </div>

      <!-- Feature 2 -->
      <div class="reveal rounded-xl border border-gray-200 bg-white p-6 shadow-sm transition hover:shadow-md">
        <div class="mb-3 h-8 w-8 rounded bg-gray-100 flex items-center justify-center">
          <svg viewBox="0 0 24 24" class="h-4 w-4 text-gray-800" fill="none" stroke="currentColor" stroke-width="1.5">
            <path d="M20 7l-8 10-4-4" />
          </svg>
        </div>
        <h3 class="font-serif text-lg">Instant Verification</h3>
        <p class="mt-1 text-sm text-gray-600">Authenticate employment and identity in moments.</p>
      </div>

      <!-- Feature 3 -->
      <div class="reveal rounded-xl border border-gray-200 bg-white p-6 shadow-sm transition hover:shadow-md">
        <div class="mb-3 h-8 w-8 rounded bg-gray-100 flex items-center justify-center">
          <svg viewBox="0 0 24 24" class="h-4 w-4 text-gray-800" fill="none" stroke="currentColor" stroke-width="1.5">
            <circle cx="12" cy="12" r="9"/>
            <path d="M8 15a4 4 0 118 0M12 7v2"/>
          </svg>
        </div>
        <h3 class="font-serif text-lg">24/7 Support</h3>
        <p class="mt-1 text-sm text-gray-600">Responsive, discreet, and genuinely helpful.</p>
      </div>

      <!-- Feature 4 -->
      <div class="reveal rounded-xl border border-gray-200 bg-white p-6 shadow-sm transition hover:shadow-md">
        <div class="mb-3 h-8 w-8 rounded bg-gray-100 flex items-center justify-center">
          <svg viewBox="0 0 24 24" class="h-4 w-4 text-gray-800" fill="none" stroke="currentColor" stroke-width="1.5">
            <rect x="4" y="11" width="16" height="9" rx="2"/>
            <path d="M8 11V8a4 4 0 018 0v3"/>
          </svg>
        </div>
        <h3 class="font-serif text-lg">Data Privacy & Transparency</h3>
        <p class="mt-1 text-sm text-gray-600">Your data, handled with restraint and respect.</p>
      </div>
    </div>
  </div>
</section>

<!-- How It Works Section -->
<section id="how" class="bg-gray-50">
  <div class="mx-auto max-w-7xl px-6 py-20 md:py-24">
    <div class="grid gap-10 md:grid-cols-2 md:items-center">
      <!-- Illustration -->
      <div class="reveal">
        <div class="relative aspect-[4/3] w-full rounded-2xl border border-gray-200 bg-gray-100 shadow-inner">
          <div class="absolute inset-0 grid place-items-center">
            <div class="text-center">
              <div class="mx-auto mb-3 h-14 w-14 rounded-full bg-gray-200"></div>
              <p class="text-sm text-gray-600">Grayscale interface mock</p>
            </div>
          </div>
        </div>
      </div>

      <!-- Steps -->
      <div class="reveal">
        <h2 class="font-serif text-3xl md:text-4xl tracking-tight">How It Works</h2>
        <ol class="mt-8 divide-y divide-gray-200 rounded-xl border border-gray-200 bg-white">
          <li class="p-5 md:p-6">
            <div class="flex items-start gap-4">
              <span class="flex h-8 w-8 items-center justify-center rounded-full bg-gray-100 text-sm font-medium text-gray-800">1</span>
              <div>
                <h3 class="font-serif text-lg">Sign Up</h3>
                <p class="mt-1 text-sm text-gray-600">Create your account in moments with essential details.</p>
              </div>
            </div>
          </li>
          <li class="p-5 md:p-6">
            <div class="flex items-start gap-4">
              <span class="flex h-8 w-8 items-center justify-center rounded-full bg-gray-100 text-sm font-medium text-gray-800">2</span>
              <div>
                <h3 class="font-serif text-lg">Verify Employment</h3>
                <p class="mt-1 text-sm text-gray-600">Instant checks keep the process swift and accurate.</p>
              </div>
            </div>
          </li>
          <li class="p-5 md:p-6">
            <div class="flex items-start gap-4">
              <span class="flex h-8 w-8 items-center justify-center rounded-full bg-gray-100 text-sm font-medium text-gray-800">3</span>
              <div>
                <h3 class="font-serif text-lg">Access Credit</h3>
                <p class="mt-1 text-sm text-gray-600">Use your approved line with clean, transparent terms.</p>
              </div>
            </div>
          </li>
        </ol>
      </div>
    </div>
  </div>
</section>
<!-- Testimonials / Trust Section -->
<section id="testimonials" class="bg-white">
  <div class="mx-auto max-w-7xl px-6 py-20 md:py-24">
    <div class="reveal grid gap-10 md:grid-cols-2 md:items-center">
      
      <!-- Doctor Image -->
      <div class="flex items-center justify-center">
        <div class="relative h-64 w-64 rounded-2xl border border-gray-200 bg-gray-100 shadow-sm overflow-hidden">
          <!-- Prominent grayscale portrait placeholder -->
          <div class="absolute inset-0 grid place-items-center">
            <!-- <div class="h-32 w-32 rounded-full bg-gray-200 ring-1 ring-gray-300" role="img" aria-label="Doctor portrait placeholder"></div> -->
            <img src="experts.jpg" class="relative aspect-[4/4] w-full rounded-2xl border border-white/10 bg-gradient-to-b from-white/10 to-white/5 shadow-[inset_0_1px_0_0_rgba(255,255,255,0.06)]">
          </div>
        </div>
      </div>

      <!-- Quote -->
      <div class="flex flex-col justify-center">
        <h2 class="font-serif text-3xl md:text-4xl tracking-tight">What Experts Say</h2>
        <p class="mt-6 text-gray-600 text-base md:text-lg">
          “Finoma simplifies access to short-term credit with complete transparency. 
          Their process is quick, professional, and trustworthy—highly recommended for modern professionals seeking financial clarity.”
        </p>
        <p class="mt-4 text-gray-800 font-medium">— Dr. Priya R., Financial Consultant</p>
      </div>

    </div>
  </div>
</section>
<!-- Call to Action Section -->
<section id="cta" class="bg-black text-white">
  <div class="mx-auto max-w-7xl px-6 py-20 md:py-24 text-center">
    <h2 class="font-serif text-3xl md:text-5xl tracking-tight">Ready to Take Control of Your Finances?</h2>
    <p class="mt-6 text-gray-300 text-base md:text-lg max-w-2xl mx-auto">
      Sign up today and access quick, transparent credit tailored for modern professionals. Minimal paperwork, instant verification, and complete clarity.
    </p>
    <div class="mt-10 flex flex-col sm:flex-row justify-center gap-4">
      <a href="#home" class="inline-flex items-center justify-center rounded-full bg-white px-6 py-3 text-sm md:text-base font-medium text-black shadow-sm transition hover:-translate-y-0.5 hover:opacity-90 focus:outline-none focus-visible:ring-2 focus-visible:ring-white focus-visible:ring-offset-2">
        Get Started
      </a>
      <a href="#features" class="inline-flex items-center justify-center rounded-full border border-white/30 px-6 py-3 text-sm md:text-base font-medium text-white/90 hover:text-white hover:bg-white/10 transition focus:outline-none focus-visible:ring-2 focus-visible:ring-white focus-visible:ring-offset-2">
        Explore Features
      </a>
    </div>
  </div>
</section>
<!-- Footer Section -->
<footer class="bg-gray-900 text-white">
  <div class="mx-auto max-w-7xl px-6 py-16 md:py-20">
    <div class="grid grid-cols-1 md:grid-cols-3 gap-10">
      
      <!-- Brand Info -->
      <div>
        <!-- <a href="#home" class="flex items-center gap-3 text-white focus:outline-none focus-visible:ring-2 focus-visible:ring-white">
          <div class="h-10 w-10rounded-full bg-white/10 ring-1 ring-white/20 flex items-center justify-center">
            <span class="font-serif text-xl leading-none tracking-tight">F</span>
          </div>
          <div class="leading-tight">
            <span class="block font-serif text-lg tracking-tight">Finoma</span>
            <span class="block text-sm text-white/70">“Quick funds, Brighter tomorrow.”</span>
          </div>
        </a> -->
        
        <a href="#home" class="flex items-center gap-3 text-white focus-outline--inverted" aria-label="Finoma Home">
  <div class="h-9 w-9 rounded-md bg-white/10 ring-1 ring-white/20 flex items-center justify-center overflow-hidden">
    <img
      src="banner.jpg"
      alt="Finoma logo"
      class="h-full w-full object-cover"
    />
  </div>

  <div class="leading-tight">
    <span class="block font-serif text-xl tracking-tight">Finoma</span>
    <span class="block text-xs text-white/70">Quick funds, Brighter tomorrow</span>
  </div>
</a>


        <p class="mt-4 text-sm text-white/70 max-w-xs">
          Finoma provides fast, transparent financial solutions for modern professionals.
        </p>
      </div>

      <!-- Quick Links -->
      <div>
        <h3 class="font-serif text-lg mb-4">Quick Links</h3>
        <ul class="space-y-2 text-sm text-white/70">
          <li><a href="#home" class="hover:text-white transition">Home</a></li>
          <li><a href="#services" class="hover:text-white transition">Services</a></li>
          <li><a href="#features" class="hover:text-white transition">Features</a></li>
          <li><a href="#how" class="hover:text-white transition">How It Works</a></li>
          <li><a href="#contact" class="hover:text-white transition">Contact</a></li>
        </ul>
      </div>

      <!-- Social & Contact -->
      <div>
        <h3 class="font-serif text-lg mb-4">Connect With Us</h3>
        <!-- <div class="flex items-center gap-4 mb-4">
          
          <a href="#" class="text-white/70 hover:text-white transition" aria-label="Twitter">
            <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24"><path d="M23 3a10.9 10.9 0 01-3.14 1.53A4.48 4.48 0 0022.4 1.6a9.14 9.14 0 01-2.88 1.1 4.51 4.51 0 00-7.69 4.1A12.8 12.8 0 013 2.4a4.48 4.48 0 001.4 6.02A4.52 4.52 0 012 7.5v.05a4.51 4.51 0 003.6 4.42 4.52 4.52 0 01-2.03.08 4.51 4.51 0 004.2 3.14A9.05 9.05 0 012 19.54a12.77 12.77 0 006.92 2.03c8.3 0 12.85-6.88 12.85-12.85 0-.2 0-.42-.02-.63A9.18 9.18 0 0023 3z"/></svg>
          </a>
          <a href="#" class="text-white/70 hover:text-white transition" aria-label="LinkedIn">
            <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24"><path d="M19 0h-14c-2.8 0-5 2.2-5 5v14c0 2.8 2.2 5 5 5h14c2.8 0 5-2.2 5-5v-14c0-2.8-2.2-5-5-5zm-11 19h-3v-10h3v10zm-1.5-11.2c-1 0-1.8-.8-1.8-1.8s.8-1.8 1.8-1.8 1.8.8 1.8 1.8-.8 1.8-1.8 1.8zm13.5 11.2h-3v-5.5c0-1.3-.5-2.1-1.7-2.1-1 0-1.5.7-1.7 1.4-.1.3-.1.7-.1 1.1v5.1h-3v-10h3v1.4c.4-.6 1.1-1.4 2.6-1.4 1.9 0 3.3 1.3 3.3 4v6z"/></svg>
          </a>
         
        </div> -->


        <div class="flex items-center gap-4 mb-4">
  <!-- Twitter -->
  <a href="#" class="text-white/70 hover:text-white transition" aria-label="Twitter">
    <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24">
      <path d="M23 3a10.9 10.9 0 01-3.14 1.53A4.48 4.48 0 0022.4 1.6a9.14 9.14 0 01-2.88 1.1 4.51 4.51 0 00-7.69 4.1A12.8 12.8 0 013 2.4a4.48 4.48 0 001.4 6.02A4.52 4.52 0 012 7.5v.05a4.51 4.51 0 003.6 4.42 4.52 4.52 0 01-2.03.08 4.51 4.51 0 004.2 3.14A9.05 9.05 0 012 19.54a12.77 12.77 0 006.92 2.03c8.3 0 12.85-6.88 12.85-12.85 0-.2 0-.42-.02-.63A9.18 9.18 0 0023 3z"/>
    </svg>
  </a>

  <!-- LinkedIn -->
  <a href="#" class="text-white/70 hover:text-white transition" aria-label="LinkedIn">
    <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24">
      <path d="M19 0h-14c-2.8 0-5 2.2-5 5v14c0 2.8 2.2 5 5 5h14c2.8 0 5-2.2 5-5v-14c0-2.8-2.2-5-5-5zm-11 19h-3v-10h3v10zm-1.5-11.2c-1 0-1.8-.8-1.8-1.8s.8-1.8 1.8-1.8 1.8.8 1.8 1.8-.8 1.8-1.8 1.8zm13.5 11.2h-3v-5.5c0-1.3-.5-2.1-1.7-2.1-1 0-1.5.7-1.7 1.4-.1.3-.1.7-.1 1.1v5.1h-3v-10h3v1.4c.4-.6 1.1-1.4 2.6-1.4 1.9 0 3.3 1.3 3.3 4v6z"/>
    </svg>
  </a>

  <!-- Instagram -->
  <a href="#" class="text-white/70 hover:text-white transition" aria-label="Instagram">
    <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24">
      <path d="M7 2C4.2 2 2 4.2 2 7v10c0 2.8 2.2 5 5 5h10c2.8 0 5-2.2 5-5V7c0-2.8-2.2-5-5-5H7zm10 2c1.7 0 3 1.3 3 3v10c0 1.7-1.3 3-3 3H7c-1.7 0-3-1.3-3-3V7c0-1.7 1.3-3 3-3h10zm-5 3a5 5 0 100 10 5 5 0 000-10zm0 2a3 3 0 110 6 3 3 0 010-6zm4.5-.5a1 1 0 110 2 1 1 0 010-2z"/>
    </svg>
  </a>

  <!-- YouTube -->
  <a href="#" class="text-white/70 hover:text-white transition" aria-label="YouTube">
    <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24">
      <path d="M23.5 6.2s-.2-1.6-.8-2.3c-.8-.9-1.7-.9-2.1-1C17.2 2.5 12 2.5 12 2.5h-.1s-5.2 0-8.6.4c-.5 0-1.4.1-2.1 1C.7 4.6.5 6.2.5 6.2S0 8.1 0 10v4c0 1.9.5 3.8.5 3.8s.2 1.6.8 2.3c.8.9 1.9.9 2.4 1 1.8.2 7.8.4 8.3.4h.1s5.2 0 8.6-.4c.5 0 1.4-.1 2.1-1 .6-.7.8-2.3.8-2.3s.5-1.9.5-3.8v-4c0-1.9-.5-3.8-.5-3.8zM9.6 15.5v-7l6.4 3.5-6.4 3.5z"/>
    </svg>
  </a>
</div>

        <p class="text-sm text-white/70">Email: <a href="mailto:support@finoma.com" class="hover:text-white">support@finoma.com</a></p>
        <p class="text-sm text-white/70 mt-1">&copy; 2025 Finoma. All rights reserved.</p>
      </div>

    </div>
  </div>
</footer>
  </main>
</body>
</html>
