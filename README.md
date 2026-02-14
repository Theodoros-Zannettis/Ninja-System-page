<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Beginner to Pro Ninja System – by Theodoros Zannettis</title>
  <meta name="description" content="Beginner to Pro: Learn the Ninja Skills You Can’t Find on YouTube. One-time payment. Instant lifetime access." />

  <!-- Social preview -->
  <meta property="og:title" content="Beginner to Pro: Learn the Ninja Skills You Can’t Find on YouTube" />
  <meta property="og:description" content="Move past the basics. Learn professional techniques for confidence, speed, and consistency. One-time payment. Lifetime access." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="og-image.jpg" />
  <meta name="twitter:card" content="summary_large_image" />

  <!-- Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800;900&display=swap" rel="stylesheet">

  <!-- Tailwind -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            brandBg: '#F9FAFB',
            brandPrimary: '#E63946',
            brandAccent: '#1F2937',
            brandText: '#111827',
            brandSuccess: '#10B981'
          },
          fontFamily: { sans: ['Inter', 'ui-sans-serif', 'system-ui', 'sans-serif'] },
          boxShadow: {
            soft: '0 12px 34px rgba(17,24,39,0.12)'
          }
        }
      }
    }
  </script>
  <style> html { scroll-behavior: smooth; } </style>
</head>

<body class="bg-brandBg text-brandText font-sans">

  <!-- Mobile sticky CTA -->
  <div class="fixed bottom-0 inset-x-0 z-50 md:hidden bg-white/90 backdrop-blur border-t border-gray-200 p-3">
    <a href="#buy" class="block text-center w-full py-3 rounded-xl font-extrabold uppercase tracking-wide bg-brandPrimary text-white shadow-soft">
      Unlock Pro Level Techniques
    </a>
    <p class="text-center text-xs mt-1 text-gray-600">One-time payment. Instant lifetime access.</p>
  </div>

  <!-- HERO -->
  <header class="relative overflow-hidden">
    <!-- Premium background glow -->
    <div class="absolute inset-0 -z-10">
      <div class="absolute -top-24 -left-24 h-72 w-72 rounded-full bg-brandPrimary/10 blur-3xl"></div>
      <div class="absolute -top-16 -right-24 h-72 w-72 rounded-full bg-brandAccent/10 blur-3xl"></div>
      <div class="absolute bottom-0 left-1/2 -translate-x-1/2 h-64 w-[900px] rounded-full bg-brandPrimary/5 blur-3xl"></div>
    </div>

    <div class="max-w-6xl mx-auto px-4 pt-14 pb-10 md:pt-20 md:pb-16">
      <div class="text-center">
        <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-white border border-gray-200 text-sm text-gray-700">
          <span class="inline-flex h-2 w-2 rounded-full bg-brandSuccess"></span>
          Pro technique • Safety • Consistency
        </div>

        <h1 class="mt-5 text-4xl md:text-6xl font-black tracking-tight text-brandAccent leading-[1.05]">
          Beginner to Pro: <span class="text-brandPrimary">Learn the Ninja Skills You Can’t Find on YouTube</span>
        </h1>

        <p class="mt-5 text-lg md:text-xl text-gray-700 max-w-3xl mx-auto">
          Move past the basics. Learn the professional techniques that build the confidence, speed, and consistency you need to finish every run.
        </p>

        <div class="mt-8">
          <a href="#buy" class="inline-block px-8 py-4 rounded-2xl bg-brandPrimary text-white font-extrabold uppercase tracking-wide shadow-soft">
            🔓 Unlock Pro Level Techniques
          </a>
        <div class="mt-3 flex items-center justify-center gap-3 text-sm text-gray-700">
  <span class="inline-flex items-center gap-2">
    <span class="h-2 w-2 rounded-full bg-brandSuccess"></span> Technique
  </span>
  <span class="text-gray-300">•</span>
  <span class="inline-flex items-center gap-2">
    <span class="h-2 w-2 rounded-full bg-brandSuccess"></span> Safety
  </span>
  <span class="text-gray-300">•</span>
  <span class="inline-flex items-center gap-2">
    <span class="h-2 w-2 rounded-full bg-brandSuccess"></span> Consistency
  </span>
</div>

        </div>

        <!-- Optional hero image later (keep it clean now) -->
        <div class="mt-10 max-w-4xl mx-auto rounded-3xl bg-white border border-gray-200 shadow-soft p-8 md:p-10">
          <div class="grid md:grid-cols-3 gap-4 text-left">
            <div class="rounded-2xl bg-brandBg border border-gray-200 p-5">
              <p class="text-sm text-gray-600">Build</p>
              <p class="mt-1 font-extrabold text-brandAccent">Confidence</p>
            </div>
            <div class="rounded-2xl bg-brandBg border border-gray-200 p-5">
              <p class="text-sm text-gray-600">Increase</p>
              <p class="mt-1 font-extrabold text-brandAccent">Speed</p>
            </div>
            <div class="rounded-2xl bg-brandBg border border-gray-200 p-5">
              <p class="text-sm text-gray-600">Achieve</p>
              <p class="mt-1 font-extrabold text-brandAccent">Consistency</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>

  <main class="max-w-6xl mx-auto px-4">

    <!-- ABOUT THE COACH -->
    <section aria-labelledby="coach" class="py-10 md:py-16">
      <div class="grid lg:grid-cols-2 gap-10 items-start">
        <div>
          <h2 id="coach" class="text-3xl md:text-4xl font-black text-brandAccent">
            Meet Your Coach: Theodoros Zannettis
          </h2>
          <p class="mt-2 text-gray-600">Sports Scientist | Cyprus’ First Certified Ninja Coach</p>

          <p class="mt-6 text-gray-700 text-lg">
            I’m not a YouTube trainer. I’ve studied human movement, Anatomy, physiology, biomechanics, sports psychology etc. — and spent the last 2.5 years teaching and evolving my knowledge.
          </p>

          <div class="mt-7 space-y-4">
            <div class="rounded-3xl bg-white border border-gray-200 shadow-soft p-6">
              <p class="font-extrabold text-brandAccent">🧠 The Scientist</p>
              <p class="mt-1 text-gray-700">I use my knowledge to help you move smarter — not just harder.</p>
            </div>
            <div class="rounded-3xl bg-white border border-gray-200 shadow-soft p-6">
              <p class="font-extrabold text-brandAccent">🚀 The Builder</p>
              <p class="mt-1 text-gray-700">I built the Ninja System from scratch. It works because it’s battle-tested on real people, not theory.</p>
            </div>
            <div class="rounded-3xl bg-white border border-gray-200 shadow-soft p-6">
              <p class="font-extrabold text-brandAccent">🎯 The Mission</p>
              <p class="mt-1 text-gray-700">To help you unlock clean, confident movement — the kind that finishes runs and smacks buzzers.</p>
            </div>
          </div>
        </div>

        <!-- Circle coach photo card -->
        <div class="rounded-3xl bg-white border border-gray-200 shadow-soft p-8">
          <div class="flex items-center gap-5">
            <!-- If coach.jpg exists, it will show. If not, you’ll see a nice placeholder circle. -->
            <div class="relative shrink-0">
              <img
                src="coach.jpg"
                alt="Coach Theodoros Zannettis"
                class="h-28 w-28 rounded-full object-cover border border-gray-200 shadow-soft"
                onerror="this.style.display='none'; document.getElementById('coachFallback').style.display='flex';"
              />
              <div id="coachFallback" style="display:none"
                   class="h-28 w-28 rounded-full bg-brandAccent text-white flex items-center justify-center font-black text-3xl shadow-soft border border-gray-200">
                TZ
              </div>
            </div>

