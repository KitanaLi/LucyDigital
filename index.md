
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Lucy — Digital Marketing & CRO Lead | AI Strategy, SEO & Automation</title>
  <meta name="description" content="Portfolio of Lucy: Digital Marketing & CRO Lead specializing in AI Strategy, SEO, Paid Social, and Automation." />
  <meta name="author" content="Lucy" />
  <meta property="og:title" content="Lucy — Digital Marketing & CRO Lead" />
  <meta property="og:description" content="Case studies, dashboards, and resume across CRO, SEO, AI strategy and automation." />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://<your-username>.github.io/" />
  <meta property="og:image" content="/assets/og-image.jpg" />
  <meta name="twitter:card" content="summary_large_image" />
  <link rel="icon" href="/assets/favicon.ico" />

  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            brand: {
              DEFAULT: '#0EA5E9',
              dark: '#0369A1',
              soft: '#E0F2FE'
            },
            darkbg: '#0F172A',
            lightbg: '#F1F5F9'
          },
          boxShadow: {
            soft: '0 10px 30px rgba(0,0,0,0.1)'
          }
        }
      }
    }
  </script>
  <style>
    body {
      background: linear-gradient(180deg, #0F172A 0%, #1E293B 100%);
      color: #E2E8F0;
    }
    a { color: #38BDF8; }
    a:hover { color: #7DD3FC; }
    .card {
      background-color: #1E293B;
      border: 1px solid #334155;
    }
    .section {
      background-color: #0F172A;
    }
  </style>
</head>
<body class="antialiased">

<header class="sticky top-0 z-50 bg-darkbg/80 backdrop-blur border-b border-slate-700">
  <div class="max-w-6xl mx-auto px-4 py-4 flex justify-between items-center">
    <a href="#home" class="font-semibold text-white text-lg">Lucy<span class="text-brand">.</span></a>
    <nav class="hidden md:flex gap-6 text-slate-200">
      <a href="#work" class="hover:text-brand">Work</a>
      <a href="#services" class="hover:text-brand">Services</a>
      <a href="#about" class="hover:text-brand">About</a>
      <a href="#contact" class="hover:text-brand">Contact</a>
      <a href="resume.md" class="px-4 py-2 rounded bg-brand text-slate-900 font-medium hover:bg-brand-dark">Resume</a>
    </nav>
  </div>
</header>

<section id="home" class="section py-20">
  <div class="max-w-6xl mx-auto px-4 grid md:grid-cols-2 gap-10 items-center">
    <div>
      <h1 class="text-4xl md:text-5xl font-extrabold text-white">Hi, I’m Lucy — <span class="text-brand">Digital Marketing & CRO Lead</span></h1>
      <p class="mt-4 text-slate-300 text-lg">I design growth systems across SEO, paid social, and AI-driven experimentation. Explore my case studies, dashboards, and approach to performance marketing.</p>
      <div class="mt-6 flex flex-wrap gap-4">
        <a href="case-studies.md" class="px-5 py-3 rounded bg-brand text-slate-900 font-medium hover:bg-brand-dark">View Case Studies</a>
        <a href="dashboards.md" class="px-5 py-3 rounded border border-slate-600 hover:bg-slate-800 text-slate-100">Dashboards</a>
      </div>
    </div>
    <div>
      <img src="/assets/hero.jpg" alt="Lucy working setup" class="rounded-2xl shadow-soft border border-slate-700" />
    </div>
  </div>
</section>

<section id="work" class="py-20">
  <div class="max-w-6xl mx-auto px-4">
    <h2 class="text-3xl font-bold text-white">Selected Work</h2>
    <div class="mt-8 grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
      <div class="card rounded-2xl p-5">
        <img src="/assets/case-cro.jpg" alt="CRO testing" class="rounded-lg mb-4" />
        <h3 class="font-semibold text-white text-lg">CRO Program: +28% CVR in 60 Days</h3>
        <p class="text-slate-400 text-sm mt-1">A/B testing across landing pages; improved conversion rate and lead quality.</p>
      </div>
      <div class="card rounded-2xl p-5">
        <img src="/assets/case-ai.jpg" alt="AI SEO" class="rounded-lg mb-4" />
        <h3 class="font-semibold text-white text-lg">AI Overview SEO: Entity-Led Wins</h3>
        <p class="text-slate-400 text-sm mt-1">Structured data, topical authority, and AI visibility improvements.</p>
      </div>
      <div class="card rounded-2xl p-5">
        <img src="/assets/case-paid.jpg" alt="Paid social" class="rounded-lg mb-4" />
        <h3 class="font-semibold text-white text-lg">Paid Social: High-Intent Lead Gen</h3>
        <p class="text-slate-400 text-sm mt-1">LinkedIn + Meta tactics for targeted lead generation.</p>
      </div>
    </div>
  </div>
</section>

<section id="contact" class="section py-16">
  <div class="max-w-4xl mx-auto text-center">
    <h2 class="text-3xl font-bold text-white">Let’s Improve Conversions and Visibility</h2>
    <p class="mt-3 text-slate-300">Available for consulting, project work, and collaborations.</p>
    <a href="mailto:hello@example.com" class="mt-6 inline-block px-6 py-3 bg-brand text-slate-900 font-medium rounded-full hover:bg-brand-dark">Email Me</a>
  </div>
</section>

<footer class="py-6 border-t border-slate-700 text-center text-slate-500 text-sm">
  © <span id="year"></span> Lucy. All rights reserved.
</footer>

<script>
  document.getElementById('year').textContent = new Date().getFullYear();
</script>

</body>
</html>
