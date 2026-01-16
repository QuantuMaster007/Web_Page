<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sourabh Tarodekar | Technical Program Leader</title>
    
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        brand: '#ef5a43', 
                        slate: { 950: '#020617' }
                    }
                }
            }
        }
    </script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@300;700;900&family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    
    <style>
        body { font-family: 'Inter', sans-serif; }
        .display-font { font-family: 'Outfit', sans-serif; }
        .monogram { clip-path: polygon(25% 0%, 100% 0%, 75% 100%, 0% 100%); }
        .shield-card { 
            background: rgba(15, 23, 42, 0.03); 
            border: 1px solid rgba(15, 23, 42, 0.1);
            transition: all 0.3s ease;
        }
        .dark .shield-card {
            background: rgba(255,255,255,0.03); 
            border: 1px solid rgba(255,255,255,0.08);
        }
        .shield-card:hover { border-color: #ef5a43; transform: translateY(-5px); }
        input, textarea { background: transparent !important; }
    </style>
</head>

<body class="bg-white dark:bg-slate-950 text-slate-900 dark:text-slate-100 transition-colors duration-300">

    <nav class="fixed w-full z-50 bg-white/95 dark:bg-slate-950/90 backdrop-blur-md border-b border-slate-200 dark:border-slate-800 px-8 py-4">
        <div class="max-w-7xl mx-auto flex justify-between items-center">
            <div class="flex items-center gap-4">
                <div class="monogram bg-brand w-10 h-10 flex items-center justify-center text-white font-black text-xl">S</div>
                <div class="text-xs font-black tracking-[0.3em] uppercase">Sourabh Tarodekar</div>
            </div>
            <div class="hidden md:flex gap-8 text-[10px] font-bold tracking-widest uppercase opacity-60">
                <a href="#experience" class="hover:text-brand transition">Experience</a>
                <a href="#github" class="hover:text-brand transition">Technical Lab</a>
                <a href="#credentials" class="hover:text-brand transition">Credentials</a>
                <a href="#contact" class="hover:text-brand transition underline decoration-brand underline-offset-4">Contact</a>
            </div>
        </div>
    </nav>

    <section class="min-h-screen flex flex-col justify-center px-8 max-w-7xl mx-auto pt-20">
        <div data-aos="fade-up">
            <h1 class="display-font text-5xl md:text-8xl font-black mb-10 leading-[0.95] tracking-tighter">
                The <span class="text-brand italic">Bridge</span> Between Complex Systems.
            </h1>
            <div class="grid md:grid-cols-12 gap-12">
                <div class="md:col-span-8">
                    <p class="text-xl md:text-3xl font-light text-slate-500 dark:text-slate-400 leading-relaxed">
                        Orchestrating the synergy between <span class="text-slate-900 dark:text-white font-bold">Technical Program Management</span>, <span class="text-slate-900 dark:text-white font-bold">Supply Chain Operations</span>, <span class="text-slate-900 dark:text-white font-bold">NPI Hardware Engineering</span>, and <span class="text-slate-900 dark:text-white font-bold">CapEx Strategy</span>.
                    </p>
                </div>
                <div class="md:col-span-4 border-l-2 border-brand pl-8 space-y-6">
                    <div>
                        <p class="text-4xl font-black">$32M+</p>
                        <p class="text-[9px] font-bold uppercase tracking-widest opacity-50">CapEx Portfolio managed</p>
                    </div>
                    <div>
                        <p class="text-4xl font-black">7+ Yrs</p>
                        <p class="text-[9px] font-bold uppercase tracking-widest opacity-50">Global Program Excellence</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="experience" class="py-24 px-8 max-w-7xl mx-auto border-t border-slate-100 dark:border-slate-800">
        <h2 class="display-font text-xs font-black tracking-[0.6em] uppercase text-brand mb-20">Professional Tenure</h2>
        
        <div class="space-y-32">
            <div class="grid md:grid-cols-4 gap-12" data-aos="fade-up">
                <div class="md:col-span-1">
                    <p class="text-2xl font-black">Applied Materials</p>
                    <p class="text-sm font-bold opacity-40">2022 — PRESENT</p>
                    <p class="text-xs mt-2 text-brand font-bold uppercase tracking-tighter italic">Technical Program Manager III</p>
                </div>
                <div class="md:col-span-3">
                    <h3 class="display-font text-3xl font-bold mb-6">NPI Execution & CapEx Governance</h3>
                    <p class="text-lg text-slate-600 dark:text-slate-400 mb-8 leading-relaxed">
                        Directing the operating rhythm for <span class="text-slate-900 dark:text-white font-extrabold uppercase tracking-tight underline decoration-brand/30">CVD/PVD Wafer-Deposition Tools</span>. Bridging the gap between Silicon Valley engineering and global manufacturing sites.
                    </p>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                        <div class="bg-slate-50 dark:bg-slate-900/50 p-6 rounded-xl border border-slate-200 dark:border-white/5">
                            <span class="text-[10px] font-black text-brand uppercase block mb-2">Portfolio ROI</span>
                            <p class="text-sm font-medium italic">Managed $32M CapEx portfolio; reduced risk inventory by $11.2M via strategic reuse logic.</p>
                        </div>
                        <div class="bg-slate-50 dark:bg-slate-900/50 p-6 rounded-xl border border-slate-200 dark:border-white/5">
                            <span class="text-[10px] font-black text-brand uppercase block mb-2">Engineering Rhythms</span>
                            <p class="text-sm font-medium italic">Owned EVT/DVT/PVT phase-gates for high-complexity hardware builds.</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="grid md:grid-cols-4 gap-12 opacity-90" data-aos="fade-up">
                <div class="md:col-span-1">
                    <p class="text-2xl font-black">Ford Motor Co.</p>
                    <p class="text-sm font-bold opacity-40">2017 — 2020</p>
                    <p class="text-xs mt-2 text-brand font-bold uppercase tracking-tighter italic">Engineering Program Manager</p>
                </div>
                <div class="md:col-span-3">
                    <h3 class="display-font text-3xl font-bold mb-6">Global Supply & Product Development</h3>
                    <p class="text-lg text-slate-600 dark:text-slate-400 mb-8 leading-relaxed">
                        Led end-to-end supply readiness for chassis and suspension components for <span class="text-slate-900 dark:text-white font-extrabold">Global Mobility Platforms</span>. Managed 25+ Tier-1 suppliers across APQP/PPAP milestones.
                    </p>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                        <div class="bg-slate-50 dark:bg-slate-900/50 p-6 rounded-xl border border-slate-200 dark:border-white/5">
                            <span class="text-[10px] font-black text-brand uppercase block mb-2">Cost Optimization</span>
                            <p class="text-sm font-medium italic">Realized $1.4M in annual technical cost savings through design and material optimization.</p>
                        </div>
                        <div class="bg-slate-50 dark:bg-slate-900/50 p-6 rounded-xl border border-slate-200 dark:border-white/5">
                            <span class="text-[10px] font-black text-brand uppercase block mb-2">Supplier Governance</span>
                            <p class="text-sm font-medium italic">Established component qualification scorecards driving 100% compliance with launch readiness.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="github" class="py-24 px-8 bg-slate-50 dark:bg-slate-900/50 border-y border-slate-200 dark:border-slate-800">
        <div class="max-w-7xl mx-auto">
            <h2 class="display-font text-xs font-black tracking-[0.6em] uppercase text-brand mb-16">Technical Lab (GitHub)</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white dark:bg-slate-950 p-10 rounded-3xl border border-slate-200 dark:border-white/5 shadow-xl hover:border-brand transition-all">
                    <i class="fab fa-python text-3xl text-brand mb-6"></i>
                    <h4 class="text-xl font-black mb-4 uppercase italic leading-tight">CapEx Factory Readiness Logic</h4>
                    <p class="text-sm opacity-60 leading-relaxed mb-8">Python automation for tracking equipment qualification gates vs finance budgets.</p>
                    <a href="https://github.com/QuantuMaster007" target="_blank" class="text-[10px] font-black border-b-2 border-brand pb-1 uppercase tracking-widest">Source Repository</a>
                </div>
                <div class="bg-white dark:bg-slate-950 p-10 rounded-3xl border border-slate-200 dark:border-white/5 shadow-xl hover:border-brand transition-all">
                    <i class="fas fa-database text-3xl text-brand mb-6"></i>
                    <h4 class="text-xl font-black mb-4 uppercase italic leading-tight">Enterprise SQL Optimization</h4>
                    <p class="text-sm opacity-60 leading-relaxed mb-8">Performance tuning scripts for ERP databases to reduce leadership report latency.</p>
                    <a href="https://github.com/QuantuMaster007" target="_blank" class="text-[10px] font-black border-b-2 border-brand pb-1 uppercase tracking-widest">Source Repository</a>
                </div>
                <div class="bg-white dark:bg-slate-950 p-10 rounded-3xl border border-slate-200 dark:border-white/5 shadow-xl hover:border-brand transition-all">
                    <i class="fas fa-microchip text-3xl text-brand mb-6"></i>
                    <h4 class="text-xl font-black mb-4 uppercase italic leading-tight">MLOps Experiment Platform</h4>
                    <p class="text-sm opacity-60 leading-relaxed mb-8">Integrated pipeline (DVC/MLflow) for predicting hardware failure modes.</p>
                    <a href="https://github.com/QuantuMaster007" target="_blank" class="text-[10px] font-black border-b-2 border-brand pb-1 uppercase tracking-widest">Source Repository</a>
                </div>
            </div>
        </div>
    </section>

    <section id="credentials" class="py-24 px-8 max-w-7xl mx-auto">
        <div class="grid md:grid-cols-2 gap-24">
            <div>
                <h2 class="display-font text-xs font-black tracking-[0.6em] uppercase text-brand mb-12">Academic Honors</h2>
                <div class="space-y-10">
                    <div class="border-l-4 border-brand pl-8">
                        <p class="text-2xl font-black uppercase italic tracking-tighter">MBA, International Business</p>
                    </div>
                    <div class="border-l-4 border-brand pl-8">
                        <p class="text-2xl font-black uppercase italic tracking-tighter">MS, Business Analytics</p>
                    </div>
                    <div class="border-l-4 border-brand pl-8">
                        <p class="text-2xl font-black uppercase italic tracking-tighter">BS, Mechanical Engineering</p>
                    </div>
                </div>
            </div>
            <div>
                <h2 class="display-font text-xs font-black tracking-[0.6em] uppercase text-brand mb-12">Technical Validations</h2>
                <div class="grid grid-cols-2 gap-4">
                    <div class="shield-card p-6 rounded-2xl flex flex-col items-center text-center">
                        <i class="fas fa-certificate text-brand text-2xl mb-4"></i>
                        <p class="text-[10px] font-black uppercase tracking-[0.2em] leading-tight">PMP® Certified</p>
                    </div>
                    <div class="shield-card p-6 rounded-2xl flex flex-col items-center text-center">
                        <i class="fas fa-layer-group text-brand text-2xl mb-4"></i>
                        <p class="text-[10px] font-black uppercase tracking-[0.2em] leading-tight">Six Sigma Green Belt</p>
                    </div>
                    <div class="shield-card p-6 rounded-2xl flex flex-col items-center text-center">
                        <i class="fas fa-cubes text-brand text-2xl mb-4"></i>
                        <p class="text-[10px] font-black uppercase tracking-[0.2em] leading-tight">Product Manager (PMC)</p>
                    </div>
                    <div class="shield-card p-6 rounded-2xl flex flex-col items-center text-center">
                        <i class="fas fa-sync-alt text-brand text-2xl mb-4"></i>
                        <p class="text-[10px] font-black uppercase tracking-[0.2em] leading-tight">Agile Scrum Master</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-32 px-8 bg-slate-900 dark:bg-white text-white dark:text-slate-900 rounded-t-[5rem]">
        <div class="max-w-7xl mx-auto grid md:grid-cols-2 gap-20 items-center">
            <div>
                <h2 class="display-font text-5xl md:text-7xl font-black uppercase italic mb-6 leading-none">
                    Unlock <span class="text-brand">Potential.</span>
                </h2>
                <p class="text-xl md:text-2xl font-light opacity-80 mb-12 leading-relaxed">
                    Ready to scale global operations and technical programs to their full potential. <span class="font-bold underline decoration-brand italic">Hire me</span> to lead your next multi-million dollar mandate.
                </p>
                <div class="flex gap-10 text-4xl">
                    <a href="mailto:sourabh232@gmail.com" class="hover:text-brand transition"><i class="fas fa-envelope-open-text"></i></a>
                    <a href="https://linkedin.com/in/sourabh232" target="_blank" class="hover:text-brand transition"><i class="fab fa-linkedin-in"></i></a>
                    <a href="https://github.com/QuantuMaster007" target="_blank" class="hover:text-brand transition"><i class="fab fa-github"></i></a>
                </div>
            </div>

            <div class="bg-white/5 dark:bg-slate-100 p-10 rounded-[3rem] border border-white/10 dark:border-slate-200 shadow-2xl">
                <form action="https://formspree.io/f/xbddlbzj" method="POST" class="space-y-6">
                    <input type="text" name="name" placeholder="FULL NAME" required class="w-full border-b border-current/20 py-4 outline-none focus:border-brand transition text-sm font-bold tracking-widest">
                    <input type="email" name="email" placeholder="BUSINESS EMAIL" required class="w-full border-b border-current/20 py-4 outline-none focus:border-brand transition text-sm font-bold tracking-widest">
                    <textarea name="message" rows="2" placeholder="HOW CAN I HELP?" required class="w-full border-b border-current/20 py-4 outline-none focus:border-brand transition text-sm font-bold tracking-widest"></textarea>
                    <button type="submit" class="w-full py-5 bg-brand text-white font-black uppercase tracking-[0.4em] hover:bg-slate-800 transition-colors">Submit</button>
                </form>
            </div>
        </div>
    </section>

    <footer class="py-12 bg-slate-900 dark:bg-white text-center border-t border-white/5 dark:border-slate-200">
        <p class="text-[10px] font-black tracking-[0.5em] uppercase opacity-40">
            © 2026 Sourabh Tarodekar | MSBA | MBA | PMP | Precision Through Scale
        </p>
    </footer>

    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>AOS.init({ duration: 1000, once: true });</script>
</body>
</html>
