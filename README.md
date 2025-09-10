<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>NomadNexus — Perks, Relocation, Community</title>
  <meta name="description" content="NomadNexus is a digital hub for global professionals, offering perks, relocation tools, and community for seamless remote living." />
  <link rel="icon" href="./assets/logo.svg" />
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    .glass { backdrop-filter: blur(10px); background: rgba(255,255,255,0.06); }
    .hero-gradient { background: radial-gradient(1200px 600px at 20% 0%, rgba(99,102,241,0.15), transparent),
                                 radial-gradient(1000px 500px at 80% 10%, rgba(16,185,129,0.12), transparent); }
  </style>
</head>
<body class="antialiased bg-slate-950 text-slate-100">
  <header class="sticky top-0 z-40 bg-slate-950/80 backdrop-blur border-b border-white/10">
    <div class="mx-auto max-w-7xl px-4 py-3 flex items-center justify-between">
      <a href="#" class="flex items-center gap-2">
        <span class="font-semibold tracking-tight">NomadNexus</span>
      </a>
      <nav class="hidden md:flex items-center gap-6 text-sm text-slate-300">
        <a href="#features" class="hover:text-white">Features</a>
        <a href="#cities" class="hover:text-white">Cities</a>
        <a href="#partners" class="hover:text-white">Partners</a>
        <a href="#pricing" class="hover:text-white">Pricing</a>
      </nav>
      <a href="#waitlist" class="inline-flex items-center rounded-xl bg-indigo-500 hover:bg-indigo-400 px-4 py-2 text-sm font-semibold">Join Waitlist</a>
    </div>
  </header>

  <section class="hero-gradient">
    <div class="mx-auto max-w-7xl px-4 py-20 md:py-28 grid md:grid-cols-2 gap-10 items-center">
      <div>
        <h1 class="text-4xl md:text-6xl font-bold leading-tight">
          Relocate smarter. <span class="text-indigo-400">Live globally.</span>
        </h1>
        <p class="mt-5 text-lg text-slate-300">Perks marketplace, relocation toolkit, and community directory—
          everything you need to build a sustainable remote life abroad.</p>
        <div class="mt-8 flex flex-col sm:flex-row gap-3">
          <a href="#waitlist" class="px-6 py-3 rounded-xl bg-indigo-500 hover:bg-indigo-400 font-semibold text-center">Join the Waitlist</a>
          <a href="#features" class="px-6 py-3 rounded-xl border border-white/20 hover:border-white/40 text-center">Explore Features</a>
        </div>
      </div>
      <div>
        <div class="relative">
          <div class="absolute -inset-4 rounded-3xl blur-2xl bg-indigo-500/20"></div>
          <div class="relative glass border border-white/10 rounded-3xl p-4">
            <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?q=80&w=1600&auto=format&fit=crop" alt="Nomad city collage" class="rounded-2xl"/>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="features" class="py-20">
    <div class="mx-auto max-w-7xl px-4">
      <h2 class="text-3xl md:text-4xl font-bold">Everything in one hub</h2>
      <p class="mt-2 text-slate-400">Perks that save money, steps that save time, and a community that opens doors.</p>
      <div class="mt-10 grid md:grid-cols-3 gap-6">
        <div class="glass rounded-2xl p-6 border border-white/10">
          <h3 class="font-semibold text-lg">Perks Marketplace</h3>
          <p class="mt-2 text-slate-300">Curated discounts on housing, coworking, SIM/eSIM, banking, and insurance.</p>
        </div>
        <div class="glass rounded-2xl p-6 border border-white/10">
          <h3 class="font-semibold text-lg">Relocation Toolkit</h3>
          <p class="mt-2 text-slate-300">Country-specific visa guidance, apostille/FBI flow, and document checklists.</p>
        </div>
        <div class="glass rounded-2xl p-6 border border-white/10">
          <h3 class="font-semibold text-lg">Community Nexus</h3>
          <p class="mt-2 text-slate-300">Member map and profiles to connect by city, skill, and interests.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="cities" class="py-16 border-t border-white/10">
    <div class="mx-auto max-w-7xl px-4">
      <h2 class="text-3xl font-bold">City snapshots</h2>
      <p class="mt-2 text-slate-400">Fast facts to help you choose your next base.</p>
      <div class="mt-8 grid md:grid-cols-3 gap-6">
        <article class="glass border border-white/10 rounded-2xl p-5">
          <h3 class="font-semibold">Valencia, Spain</h3>
          <ul class="mt-2 text-sm text-slate-300 list-disc list-inside space-y-1">
            <li>Rent: €850–€1,200 (1BR)</li>
            <li>Climate: Mild, sunny</li>
            <li>Transit: Metro + bike-friendly</li>
          </ul>
        </article>
        <article class="glass border border-white/10 rounded-2xl p-5">
          <h3 class="font-semibold">Porto, Portugal</h3>
          <ul class="mt-2 text-sm text-slate-300 list-disc list-inside space-y-1">
            <li>Rent: €750–€1,100 (1BR)</li>
            <li>Climate: Temperate coastal</li>
            <li>Transit: Metro + walkable</li>
          </ul>
        </article>
        <article class="glass border border-white/10 rounded-2xl p-5">
          <h3 class="font-semibold">Chiang Mai, Thailand</h3>
          <ul class="mt-2 text-sm text-slate-300 list-disc list-inside space-y-1">
            <li>Rent: ฿10k–฿18k (1BR)</li>
            <li>Climate: Tropical</li>
            <li>Transit: Songthaews, Grab</li>
          </ul>
        </article>
      </div>
    </div>
  </section>

  <section id="partners" class="py-20">
    <div class="mx-auto max-w-7xl px-4">
      <div class="grid md:grid-cols-2 gap-8 items-center">
        <div>
          <h2 class="text-3xl font-bold">Partner with NomadNexus</h2>
          <p class="mt-3 text-slate-300">Bring exclusive perks to a growing community of global professionals. Coworking spaces, chambers, housing providers, and relocation services welcome.</p>
          <ul class="mt-4 text-slate-300 list-disc list-inside">
            <li>Zero-cost onboarding</li>
            <li>Revenue share on redemptions</li>
            <li>Verified reviews & visibility</li>
          </ul>
        </div>
        <form class="glass border border-white/10 rounded-2xl p-6" action="https://formspree.io/f/your-form-id" method="POST">
          <h3 class="font-semibold text-lg">Partner interest</h3>
          <label class="block mt-4 text-sm">Your Organization
            <input class="mt-1 w-full rounded-lg bg-slate-900 border border-white/10 px-3 py-2" name="org" required />
          </label>
          <label class="block mt-4 text-sm">Contact Email
            <input type="email" class="mt-1 w-full rounded-lg bg-slate-900 border border-white/10 px-3 py-2" name="email" required />
          </label>
          <label class="block mt-4 text-sm">Notes
            <textarea class="mt-1 w-full rounded-lg bg-slate-900 border border-white/10 px-3 py-2" name="notes" rows="3"></textarea>
          </label>
          <button class="mt-5 w-full rounded-xl bg-emerald-500 hover:bg-emerald-400 py-2 font-semibold">Submit</button>
        </form>
      </div>
    </div>
  </section>

  <section id="pricing" class="py-20 border-t border-white/10">
    <div class="mx-auto max-w-7xl px-4">
      <h2 class="text-3xl md:text-4xl font-bold">Simple, transparent pricing</h2>
      <p class="mt-2 text-slate-400">Early members lock lifetime perks.</p>
      <div class="mt-8 grid md:grid-cols-3 gap-6">
        <div class="glass rounded-2xl p-6 border border-white/10">
          <h3 class="font-semibold">Starter</h3>
          <p class="mt-1 text-3xl font-bold">Free</p>
          <ul class="mt-4 text-sm text-slate-300 space-y-2">
            <li>Community access</li>
            <li>Basic city snapshots</li>
            <li>Newsletter</li>
          </ul>
          <a href="#waitlist" class="mt-6 inline-block w-full text-center rounded-xl bg-slate-800 hover:bg-slate-700 py-2">Get Started</a>
        </div>
        <div class="glass rounded-2xl p-6 border border-emerald-400/30">
          <h3 class="font-semibold">Pro</h3>
          <p class="mt-1 text-3xl font-bold">$9<span class="text-base font-medium">/mo</span></p>
          <ul class="mt-4 text-sm text-slate-300 space-y-2">
            <li>Full perks marketplace</li>
            <li>Relocation toolkit</li>
            <li>City data & alerts</li>
          </ul>
          <a href="#waitlist" class="mt-6 inline-block w-full text-center rounded-xl bg-emerald-500 hover:bg-emerald-400 py-2">Go Pro</a>
        </div>
        <div class="glass rounded-2xl p-6 border border-white/10">
          <h3 class="font-semibold">Teams</h3>
          <p class="mt-1 text-3xl font-bold">Custom</p>
          <ul class="mt-4 text-sm text-slate-300 space-y-2">
            <li>Employee relocation perks</li>
            <li>Admin dashboard</li>
            <li>Priority support</li>
          </ul>
          <a href="#waitlist" class="mt-6 inline-block w-full text-center rounded-xl bg-indigo-500 hover:bg-indigo-400 py-2">Contact Sales</a>
        </div>
      </div>
    </div>
  </section>

  <section id="waitlist" class="py-20">
    <div class="mx-auto max-w-2xl px-4 text-center">
      <h2 class="text-3xl md:text-4xl font-bold">Be first in line</h2>
      <p class="mt-2 text-slate-300">Join the waitlist for launch updates and early access perks.</p>
      <form class="mt-6 flex flex-col sm:flex-row gap-3 justify-center" action="https://formspree.io/f/your-form-id" method="POST">
        <input type="email" name="email" required placeholder="you@example.com" class="w-full sm:w-auto sm:min-w-[320px] rounded-xl bg-slate-900 border border-white/10 px-4 py-3" />
        <button class="rounded-xl bg-indigo-500 hover:bg-indigo-400 px-6 py-3 font-semibold">Join Waitlist</button>
      </form>
      <p class="mt-3 text-xs text-slate-500">We respect your privacy. Unsubscribe anytime.</p>
    </div>
  </section>

  <footer class="py-12 border-t border-white/10">
    <div class="mx-auto max-w-7xl px-4 grid md:grid-cols-4 gap-8 text-sm text-slate-300">
      <div>
        <span class="font-semibold">NomadNexus</span>
        <p class="mt-3 text-slate-400">Perks • Relocation • Community</p>
      </div>
      <div>
        <h4 class="font-semibold">Product</h4>
        <ul class="mt-2 space-y-1">
          <li><a class="hover:text-white" href="#features">Features</a></li>
          <li><a class="hover:text-white" href="#pricing">Pricing</a></li>
        </ul>
      </div>
      <div>
        <h4 class="font-semibold">Company</h4>
        <ul class="mt-2 space-y-1">
          <li><a class="hover:text-white" href="#partners">Partners</a></li>
          <li><a class="hover:text-white" href="#waitlist">Contact</a></li>
        </ul>
      </div>
      <div>
        <h4 class="font-semibold">Legal</h4>
        <ul class="mt-2 space-y-1">
          <li><a class="hover:text-white" href="#">Terms</a></li>
          <li><a class="hover:text-white" href="#">Privacy</a></li>
        </ul>
      </div>
    </div>
    <p class="mt-8 text-center text-xs text-slate-500">© <span id="y"></span> NomadNexus. All rights reserved.</p>
  </footer>

  <script>
    document.getElementById('y').textContent = new Date().getFullYear();
  </script>
</body>
</html>
