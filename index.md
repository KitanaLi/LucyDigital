<!doctype html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Lucy — Digital Marketing & CRO Lead | AI Strategy, SEO & Automation</title>
  <meta name="description" content="Portfolio of Lucy: Digital Marketing & CRO Lead specializing in AI Strategy, SEO, Paid Social, and Automation. Case studies, dashboards, and resume." />
  <meta name="author" content="Lucy" />
  <meta property="og:title" content="Lucy — Digital Marketing & CRO Lead" />
  <meta property="og:description" content="Case studies, dashboards, and resume across CRO, SEO, AI strategy and automation." />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://<your-username>.github.io/" />
  <meta property="og:image" content="/assets/og-image.jpg" />
  <meta name="twitter:card" content="summary_large_image" />
  <link rel="icon" href="/assets/favicon.ico" />

  <!-- Tailwind CSS (via CDN is fine for GitHub Pages) -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            brand: {
              DEFAULT: '#0EA5E9', // sky-500 vibe for CTAs
              dark: '#0284C7',
              soft: '#E0F2FE'
            }
          },
          boxShadow: {
            soft: '0 10px 30px rgba(2,8,23,0.08)'
          }
        }
      }
    }
  </script>

  <!-- Schema.org Person -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Lucy",
    "jobTitle": "Digital Marketing & CRO Lead",
    "description": "AI Strategy, SEO, Paid Social, Automation",
    "url": "https://<your-username>.github.io/",
    "sameAs": [
      "https://linkedin.com/in/yourprofile"
    ]
  }
  </script>

  <style>
    /* Smooth gradient background and subtle texture */
    .bg-grid {
      background-image: radial-gradient(circle at 1px 1px, rgba(2,6,23,.06) 1px, transparent 0);
      background-size: 24px 24px;
    }
    .glass { backdrop-filter: saturate(160%) blur(10px); }
  </style>
</head>
<body class="text-slate-800 antialiased bg-white dark:bg-slate-950 dark:text-slate-100">

  <!-- Header / Nav -->
  <header class="sticky top-0 z-50 border-b border-slate-100/70 dark:border-slate-800/70 bg-white/80 dark:bg-slate-950/70 glass">
    <div class="max-w-6xl mx-auto px-4">
      <div class="flex items-center justify-between h-16">
        <a href="#home" class="font-semibold tracking-tight text-slate-900 dark:text-white">Lucy<span class="text-brand">.</span></a>
        <nav class="hidden md:flex items-center gap-6 text-sm">
          <a href="#work" class="hover:text-brand">Work</a>
          <a href="#services" class="hover:text-brand">Services</a>
          <a href="#about" class="hover:text-brand">About</a>
          <a href="#contact" class="hover:text-brand">Contact</a>
          <a href="resume.md" class="inline-flex items-center gap-2 rounded-full border px-4 py-2 hover:bg-slate-50 dark:hover:bg-slate-900">
            <span>Resume</span>
          </a>
        </nav>
        <button id="navBtn" class="md:hidden p-2 rounded border border-slate-200 dark:border-slate-800" aria-label="Open menu">☰</button>
      </div>
    </div>
    <div id="mobileNav" class="md:hidden hidden border-t border-slate-100 dark:border-slate-800 bg-white dark:bg-slate-950">
      <div class="max-w-6xl mx-auto px-4 py-4 grid gap-3 text-sm">
        <a href="#work" class="hover:text-brand">Work</a>
        <a href="#services" class="hover:text-brand">Services</a>
        <a href="#about" class="hover:text-brand">About</a>
        <a href="#contact" class="hover:text-brand">Contact</a>
        <a href="resume.md" class="inline-flex items-center gap-2 rounded-full border px-4 py-2 hover:bg-slate-50 dark:hover:bg-slate-900 w-max">Resume</a>
      </div>
    </div>
  </header>

  <!-- Hero -->
  <section id="home" class="relative overflow-hidden">
    <div class="absolute inset-0 bg-gradient-to-b from-brand/10 via-transparent to-transparent"></div>
    <div class="max-w-6xl mx-auto px-4 pt-16 md:pt-24 pb-10">
      <div class="grid md:grid-cols-2 gap-10 items-center">
        <div>
          <span class="inline-flex items-center gap-2 text-xs uppercase tracking-wider text-brand-dark font-semibold bg-brand-soft px-3 py-1 rounded-full">Digital Marketing · CRO · AI</span>
          <h1 class="mt-5 text-3xl md:text-5xl font-extrabold leading-tight">
            Hi, I’m Lucy — <span class="text-brand">Digital Marketing & CRO Lead</span>
          </h1>
          <p class="mt-4 text-base md:text-lg text-slate-600 dark:text-slate-300 max-w-prose">
            I design growth systems across SEO, paid social, and AI-driven experimentation. Here you’ll find selected work, dashboards, and how I think about performance.
          </p>
          <div class="mt-6 flex flex-wrap gap-3">
            <a href="case-studies.md" class="inline-flex items-center gap-2 bg-brand text-white rounded-full px-5 py-3 shadow-soft hover:bg-brand-dark">View Case Studies</a>
            <a href="dashboards.md" class="inline-flex items-center gap-2 rounded-full border px-5 py-3 hover:bg-slate-50 dark:hover:bg-slate-900">Dashboards</a>
            <a href="https://linkedin.com/in/yourprofile" class="inline-flex items-center gap-2 rounded-full border px-5 py-3 hover:bg-slate-50 dark:hover:bg-slate-900">LinkedIn</a>
          </div>
          <ul class="mt-6 flex flex-wrap gap-4 text-sm text-slate-500 dark:text-slate-400">
            <li>SEO & Content Systems</li>
            <li>Conversion Rate Optimization</li>
            <li>AI Strategy & Automation</li>
            <li>Paid Social (LinkedIn/Meta)</li>
          </ul>
        </div>
        <div class="relative">
          <!-- Hero image placeholder -->
          <div class="aspect-[4/3] rounded-2xl bg-grid border border-slate-200 dark:border-slate-800 shadow-soft overflow-hidden">
            <img src="/assets/hero.jpg" alt="Lucy working setup" class="w-full h-full object-cover" loading="lazy" />
          </div>
          <!-- Stat cards -->
          <div class="absolute -bottom-6 -left-3 md:-left-6 bg-white dark:bg-slate-900 border border-slate-200 dark:border-slate-800 rounded-2xl p-4 shadow-soft">
            <p class="text-2xl font-bold">8–10x</p>
            <p class="text-xs text-slate-500">ROAS improvement (best test)</p>
          </div>
          <div class="absolute -top-6 right-0 bg-white dark:bg-slate-900 border border-slate-200 dark:border-slate-800 rounded-2xl p-4 shadow-soft">
            <p class="text-2xl font-bold">1.2M+</p>
            <p class="text-xs text-slate-500">Monthly search impressions</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Selected Work / Case Studies Grid -->
  <section id="work" class="py-16 md:py-24 border-t border-slate-100 dark:border-slate-800">
    <div class="max-w-6xl mx-auto px-4">
      <div class="flex items-end justify-between gap-6">
        <div>
          <h2 class="text-2xl md:text-3xl font-bold">Selected Work</h2>
          <p class="mt-2 text-slate-600 dark:text-slate-300">A few highlights across CRO, SEO, AI, and paid social. More inside the case studies.</p>
        </div>
        <a href="case-studies.md" class="hidden md:inline-flex items-center gap-2 rounded-full border px-4 py-2 hover:bg-slate-50 dark:hover:bg-slate-900">All Case Studies →</a>
      </div>

      <div class="mt-8 grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Card 1 -->
        <article class="group rounded-2xl overflow-hidden border border-slate-200 dark:border-slate-800 bg-white dark:bg-slate-900 shadow-soft">
          <a href="case-studies.md#cro-program" class="block">
            <figure class="aspect-[16/9] overflow-hidden">
              <img src="/assets/case-cro.jpg" alt="CRO testing" class="w-full h-full object-cover group-hover:scale-105 transition" loading="lazy" />
            </figure>
            <div class="p-5">
              <h3 class="font-semibold">CRO Program: +28% CVR in 60 Days</h3>
              <p class="mt-1 text-sm text-slate-600 dark:text-slate-300">Hypothesis-led A/B testing across landing pages; improved TR submission and lead quality.</p>
              <span class="mt-3 inline-flex text-xs px-2 py-1 rounded-full bg-brand-soft text-brand-dark">CRO</span>
            </div>
          </a>
        </article>
        <!-- Card 2 -->
        <article class="group rounded-2xl overflow-hidden border border-slate-200 dark:border-slate-800 bg-white dark:bg-slate-900 shadow-soft">
          <a href="case-studies.md#ai-overview-seo" class="block">
            <figure class="aspect-[16/9] overflow-hidden">
              <img src="/assets/case-ai.jpg" alt="AI SEO" class="w-full h-full object-cover group-hover:scale-105 transition" loading="lazy" />
            </figure>
            <div class="p-5">
              <h3 class="font-semibold">AI Overview SEO: Entity-Led Wins</h3>
              <p class="mt-1 text-sm text-slate-600 dark:text-slate-300">Structured data, topical authority, and LLM-friendly content improved visibility in generative results.</p>
              <span class="mt-3 inline-flex text-xs px-2 py-1 rounded-full bg-brand-soft text-brand-dark">AI · SEO</span>
            </div>
          </a>
        </article>
        <!-- Card 3 -->
        <article class="group rounded-2xl overflow-hidden border border-slate-200 dark:border-slate-800 bg-white dark:bg-slate-900 shadow-soft">
          <a href="case-studies.md#paid-social" class="block">
            <figure class="aspect-[16/9] overflow-hidden">
              <img src="/assets/case-paid.jpg" alt="Paid social" class="w-full h-full object-cover group-hover:scale-105 transition" loading="lazy" />
            </figure>
            <div class="p-5">
              <h3 class="font-semibold">Paid Social: High-Intent Lead Gen</h3>
              <p class="mt-1 text-sm text-slate-600 dark:text-slate-300">LinkedIn + Meta tactics with native forms, document ads, and ABM audience logic.</p>
              <span class="mt-3 inline-flex text-xs px-2 py-1 rounded-full bg-brand-soft text-brand-dark">Paid Social</span>
            </div>
          </a>
        </article>
      </div>

      <div class="mt-8 md:hidden">
        <a href="case-studies.md" class="inline-flex items-center gap-2 rounded-full border px-4 py-2 hover:bg-slate-50 dark:hover:bg-slate-900">All Case Studies →</a>
      </div>
    </div>
  </section>

  <!-- Services -->
  <section id="services" class="py-16 md:py-24">
    <div class="max-w-6xl mx-auto px-4">
      <h2 class="text-2xl md:text-3xl font-bold">What I Do</h2>
      <p class="mt-2 text-slate-600 dark:text-slate-300 max-w-prose">I build performance stacks that compound: clear positioning, intent-led content, CRO foundations, and AI-assisted execution.</p>

      <div class="mt-8 grid md:grid-cols-3 gap-6">
        <div class="rounded-2xl border border-slate-200 dark:border-slate-800 p-6 bg-white dark:bg-slate-900">
          <h3 class="font-semibold">CRO & Experimentation</h3>
          <p class="mt-2 text-sm text-slate-600 dark:text-slate-300">Research → Hypotheses → A/B tests → Learnings repo. Metrics: CVR, TR rate, LTV, CPA.</p>
          <ul class="mt-3 text-sm list-disc list-inside text-slate-600 dark:text-slate-300">
            <li>Landing page systems</li>
            <li>Friction audits & UX</li>
            <li>Test design & analysis</li>
          </ul>
        </div>
        <div class="rounded-2xl border border-slate-200 dark:border-slate-800 p-6 bg-white dark:bg-slate-900">
          <h3 class="font-semibold">SEO & Content Systems</h3>
          <p class="mt-2 text-sm text-slate-600 dark:text-slate-300">Entity-led architecture, hub taxonomies, and technical hygiene.</p>
          <ul class="mt-3 text-sm list-disc list-inside text-slate-600 dark:text-slate-300">
            <li>Site & blog IA</li>
            <li>Structured data</li>
            <li>Editorial playbooks</li>
          </ul>
        </div>
        <div class="rounded-2xl border border-slate-200 dark:border-slate-800 p-6 bg-white dark:bg-slate-900">
          <h3 class="font-semibold">AI Strategy & Automation</h3>
          <p class="mt-2 text-sm text-slate-600 dark:text-slate-300">Workflow design, prompt ops, and QA frameworks to scale content and insights.</p>
          <ul class="mt-3 text-sm list-disc list-inside text-slate-600 dark:text-slate-300">
            <li>LLM research ops</li>
            <li>Content assistants</li>
            <li>Analytics automation</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- About -->
  <section id="about" class="py-16 md:py-24 border-t border-slate-100 dark:border-slate-800">
    <div class="max-w-6xl mx-auto px-4 grid md:grid-cols-2 gap-10 items-center">
      <div class="order-2 md:order-1">
        <h2 class="text-2xl md:text-3xl font-bold">About</h2>
        <p class="mt-3 text-slate-600 dark:text-slate-300">I’m a South African digital marketer with 9+ years in SEO, CRO, and paid social. I like clear strategy, clean execution, and dashboards that tell the truth.</p>
        <ul class="mt-4 text-sm text-slate-600 dark:text-slate-300 space-y-1">
          <li>• Tools: GA4, GSC, Looker/Whatagraph, Unbounce, Brandwatch</li>
          <li>• Channels: SEO, LinkedIn/Meta, PPC, Email</li>
          <li>• Sectors: B2B, Travel, SaaS, Finance, Education</li>
        </ul>
        <div class="mt-6 flex gap-3">
          <a href="resume.md" class="inline-flex items-center gap-2 bg-brand text-white rounded-full px-5 py-3 shadow-soft hover:bg-brand-dark">Download Resume</a>
          <a href="https://linkedin.com/in/yourprofile" class="inline-flex items-center gap-2 rounded-full border px-5 py-3 hover:bg-slate-50 dark:hover:bg-slate-900">Connect on LinkedIn</a>
        </div>
      </div>
      <div class="order-1 md:order-2">
        <div class="aspect-square rounded-2xl bg-grid border border-slate-200 dark:border-slate-800 shadow-soft overflow-hidden">
          <img src="/assets/profile.jpg" alt="Lucy portrait" class="w-full h-full object-cover" loading="lazy" />
        </div>
      </div>
    </div>
  </section>

  <!-- Dashboards / Logos -->
  <section class="py-16 md:py-24">
    <div class="max-w-6xl mx-auto px-4">
      <div class="rounded-2xl border border-slate-200 dark:border-slate-800 p-8 bg-white dark:bg-slate-900">
        <div class="flex flex-col md:flex-row md:items-center md:justify-between gap-6">
          <div>
            <h3 class="text-xl md:text-2xl font-semibold">Dashboards & Reports</h3>
            <p class="mt-2 text-slate-600 dark:text-slate-300">KPI snapshots you can actually use. Blended views across SEO, paid media, and CRO testing.</p>
          </div>
          <a href="dashboards.md" class="inline-flex items-center gap-2 bg-brand text-white rounded-full px-5 py-3 shadow-soft hover:bg-brand-dark">Open Dashboards</a>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact CTA -->
  <section id="contact" class="py-16 md:py-24 border-t border-slate-100 dark:border-slate-800">
    <div class="max-w-6xl mx-auto px-4">
      <div class="rounded-2xl p-8 md:p-12 bg-gradient-to-br from-brand-soft via-white to-white dark:from-slate-900 dark:via-slate-900 dark:to-slate-900 border border-slate-200 dark:border-slate-800 shadow-soft">
        <div class="grid md:grid-cols-3 gap-6 items-center">
          <div class="md:col-span-2">
            <h2 class="text-2xl md:text-3xl font-bold">Let’s improve conversions and visibility</h2>
            <p class="mt-2 text-slate-700 dark:text-slate-300">Open to consulting, fractional leadership, and project engagements.</p>
          </div>
          <div class="flex md:justify-end">
            <a href="mailto:hello@example.com" class="inline-flex items-center gap-2 bg-brand text-white rounded-full px-6 py-3 shadow-soft hover:bg-brand-dark">Email Me</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="py-10">
    <div class="max-w-6xl mx-auto px-4 text-sm text-slate-500 dark:text-slate-400">
      <div class="flex flex-col md:flex-row md:items-center md:justify-between gap-4">
        <p>© <span id="year"></span> Lucy. All rights reserved.</p>
        <ul class="flex gap-4">
          <li><a href="/privacy.md" class="hover:text-brand">Privacy</a></li>
          <li><a href="/colophon.md" class="hover:text-brand">Colophon</a></li>
          <li><a href="https://linkedin.com/in/yourprofile" class="hover:text-brand">LinkedIn</a></li>
          <li><a href="resume.md" class="hover:text-brand">Resume</a></li>
        </ul>
      </div>
    </div>
  </footer>

  <!-- Scripts -->
  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
    const btn = document.getElementById('navBtn');
    const mobile = document.getElementById('mobileNav');
    btn?.addEventListener('click', () => mobile.classList.toggle('hidden'));
  </script>

</body>
</html>
