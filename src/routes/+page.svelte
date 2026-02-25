<script>
    import heroMedia from "$lib/assets/heroMedia.jpg";
</script>

<!-- Hero -->
<section class="min-h-screen flex flex-col md:flex-row">
    <!-- Hero Text -->
    <div class="md:w-1/2 w-full flex items-center justify-center bg-[var(--color-surface)]">
        <div class="w-full max-w-xl px-6">
            <h1 class="text-6xl mb-8">Precision Custom Tooling</h1>
            <h3 class="text-lg mb-8">Exactly what you need (Within tolerance).</h3>
            <a href="#quote" class="inline-block btn-primary px-8 py-3 rounded-[var(--radius-md)] font-semibold transition-all duration-200 ease-out hover:bg-[var(--color-primary-hover)] hover:-translate-y-0.5 hover:shadow-md active:translate-y-0 active:shadow-sm">
                Request a Quote
            </a>
        </div>
    </div>
    <!-- Hero Media -->
    <div class="md:w-1/2 w-full bg-[var(--color-surface)] h-screen overflow-hidden">
        <img src={heroMedia} alt="Precision tooling in operation" class="w-full h-full object-cover"/>
    </div>
</section>

<!-- Trust -->
<section class="w-full min-h-[50vh] p-16 flex flex-col items-center bg-[var(--color-bg)]">
    <h2 class="text-3xl mb-10">Hear From Our Other Customers</h2>

    <div class="w-full max-w-6xl mx-auto px-6 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">

        <!-- Card 1 -->
        <div class="hover:border-[var(--color-accent)] hover:-translate-y-0.5 transition bg-[var(--color-surface)] border border-[var(--color-border)] rounded-[var(--radius-md)] p-6 shadow-sm">
            <p class="text-sm text-[var(--color-text-muted)] mb-4">
                “Their tooling held ±0.0002” across a 12-hour run. We reduced scrap by 18% in the first week.”
            </p>
            <p class="font-semibold text-[var(--color-primary)]">- Michael Scott</p>
            <p class="text-xs text-[var(--color-text-muted)]">Production Manager, MI Components</p>
        </div>

        <!-- Card 2 -->
        <div class="hover:border-[var(--color-accent)] hover:-translate-y-0.5 transition bg-[var(--color-surface)] border border-[var(--color-border)] rounded-[var(--radius-md)] p-6 shadow-sm">
            <p class="text-sm text-[var(--color-text-muted)] mb-4">
                “Lead times were cut in half and every insert was dead-on spec. Setup time dropped from 45 to 20 minutes.”
            </p>
            <p class="font-semibold text-[var(--color-primary)]">- Leonard Hofstadter</p>
            <p class="text-xs text-[var(--color-text-muted)]">Tooling Engineer, North River Machining</p>
        </div>

        <!-- Card 3 -->
        <div class="hover:border-[var(--color-accent)] hover:-translate-y-0.5 transition bg-[var(--color-surface)] border border-[var(--color-border)] rounded-[var(--radius-md)] p-6 shadow-sm">
            <p class="text-sm text-[var(--color-text-muted)] mb-4">
                “We pushed their cutters through hardened 4140 all shift with zero chatter. Tool life doubled.”
            </p>
            <p class="font-semibold text-[var(--color-primary)]">- David Wallace</p>
            <p class="text-xs text-[var(--color-text-muted)]">CNC Supervisor, Valley Fabrication</p>
        </div>

        <!-- Card 4 -->
        <div class="hover:border-[var(--color-accent)] hover:-translate-y-0.5 transition bg-[var(--color-surface)] border border-[var(--color-border)] rounded-[var(--radius-md)] p-6 shadow-sm">
            <p class="text-sm text-[var(--color-text-muted)] mb-4">
                “Custom fixturing arrived ready to run. First-article inspection passed without a single adjustment.”
            </p>
            <p class="font-semibold text-[var(--color-primary)]">- Chandler Bing</p>
            <p class="text-xs text-[var(--color-text-muted)]">Quality Lead, Summit Precision</p>
        </div>

    </div>
</section>

<!-- Services -->
<section class="w-full min-h-screen p-16 flex flex-col items-center bg-[var(--color-surface)]">
    <h2 class="text-3xl mb-24">Our Services</h2>

    <div class="w-full max-w-6xl mx-auto px-6 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-24">
        <!-- Service 1 -->
        <div class="cursor-pointer hover:border-[var(--color-accent)] hover:-translate-y-0.5 transition border border-[var(--color-border)] rounded-[var(--radius-md)] p-12 bg-white shadow-sm">
            <h3 class="text-xl mb-2">Custom Tool Design</h3>
            <p class="text-sm text-[var(--color-text-muted)]">
                Application-specific tooling engineered.
            </p>
        </div>

        <!-- Service 2 -->
        <div class="cursor-pointer hover:border-[var(--color-accent)] hover:-translate-y-0.5 transition border border-[var(--color-border)] rounded-[var(--radius-md)] p-12 bg-white shadow-sm">
            <h3 class="text-xl mb-2">CNC Tool Manufacturing</h3>
            <p class="text-sm text-[var(--color-text-muted)]">
                High-precision milling, turning, and grinding for carbide.
            </p>
        </div>

        <!-- Service 3 -->
        <div class="cursor-pointer hover:border-[var(--color-accent)] hover:-translate-y-0.5 transition border border-[var(--color-border)] rounded-[var(--radius-md)] p-12 bg-white shadow-sm">
            <h3 class="text-xl mb-2">Regrinding & Refurbishing</h3>
            <p class="text-sm text-[var(--color-text-muted)]">
                Restore worn tools to extend tool life.
            </p>
        </div>

        <!-- Service 4 -->
        <div class="cursor-pointer hover:border-[var(--color-accent)] hover:-translate-y-0.5 transition border border-[var(--color-border)] rounded-[var(--radius-md)] p-12 bg-white shadow-sm">
            <h3 class="text-xl mb-2">Tool Coating Services</h3>
            <p class="text-sm text-[var(--color-text-muted)]">
                Performance coatings that improve wear resistance and heat management.
            </p>
        </div>

        <!-- Service 5 -->
        <div class="cursor-pointer hover:border-[var(--color-accent)] hover:-translate-y-0.5 transition border border-[var(--color-border)] rounded-[var(--radius-md)] p-12 bg-white shadow-sm">
            <h3 class="text-xl mb-2">On-Site Technical Support</h3>
            <p class="text-sm text-[var(--color-text-muted)]">
                Hands-on troubleshooting or tool trials.
            </p>
        </div>
    </div>
</section>

<!-- Offer -->
<section class="w-full min-h-[25vh] p-16 flex justify-center bg-[var(--color-bg)]">
    <div class="w-full max-w-4xl mx-auto border border-[var(--color-border)] rounded-[var(--radius-md)] bg-[var(--color-surface)] p-10 shadow-sm flex flex-col md:flex-row items-center justify-between gap-6">
        <!-- Text Content -->
        <div class="text-center md:text-left">
            <h2 class="text-3xl mb-2">15% Off Your First Order</h2>
            <p class="text-sm text-[var(--color-text-muted)]">
                Get precision tooling built to spec and save on your first production run. Guaranteed tolerances.
            </p>
        </div>

        <!-- CTA -->
        <div class="flex flex-col items-center md:items-end gap-3">
            <a href="#quote" class="btn-primary px-8 py-3 rounded-[var(--radius-md)] font-semibold transition-all duration-200 ease-out hover:bg-[var(--color-primary-hover)] hover:-translate-y-0.5 hover:shadow-md active:translate-y-0 active:shadow-sm">
                Request a Quote
            </a>
            <span class="text-xs text-[var(--color-text-muted)]">
                New customers only - Limited time
            </span>
        </div>
    </div>
</section>

<!-- Why Us -->
<section class="w-full min-h-[50vh] p-16 flex flex-col items-center bg-[var(--color-surface)]">
    <h2 class="text-3xl mb-10">Why Us?</h2>

    <div class="w-full max-w-6xl mx-auto px-6 flex flex-col gap-6">
        <!-- Reason 1 -->
        <div class="flex gap-6 p-6 border border-[var(--color-border)] rounded-[var(--radius-md)] bg-white shadow-sm">
            <div class="w-1.5 bg-[var(--color-primary)] rounded-full"></div>
            <div>
                <h3 class="text-lg mb-2">Tight Tolerance Guarantee</h3>
                <p class="text-sm text-[var(--color-text-muted)]">
                    Every tool is inspected to meet your exact specifications. Trust us with your long production runs and critical applications.
                </p>
            </div>
        </div>

        <!-- Reason 2 -->
        <div class="flex gap-6 p-6 border border-[var(--color-border)] rounded-[var(--radius-md)] bg-white shadow-sm">
            <div class="w-1.5 bg-[var(--color-primary)] rounded-full"></div>
            <div>
                <h3 class="text-lg mb-2">Fast, Reliable Lead Times</h3>
                <p class="text-sm text-[var(--color-text-muted)]">
                    Skilled Journeymen and in-house grinding capabilities let us deliver high-precision tooling when you need it.
                </p>
            </div>
        </div>

        <!-- Reason 3 -->
        <div class="flex gap-6 p-6 border border-[var(--color-border)] rounded-[var(--radius-md)] bg-white shadow-sm">
            <div class="w-1.5 bg-[var(--color-primary)] rounded-full"></div>
            <div>
                <h3 class="text-lg mb-2">Real Machining Expertise</h3>
                <p class="text-sm text-[var(--color-text-muted)]">
                    We work directly with your engineers and operators to ensure you get exactly what you need.
                </p>
            </div>
        </div>
    </div>
</section>

<!-- Final CTA -->
<section class="w-full min-h-[50vh] p-16 flex items-center justify-center bg-[var(--color-bg)]">
    <div class="w-full max-w-3xl mx-auto px-6">
        <div class="border border-[var(--color-border)] rounded-[var(--radius-md)] bg-[var(--color-surface)] p-10 shadow-sm text-center flex flex-col items-center gap-6">
            <!-- Heading -->
            <div>
                <h2 class="text-3xl mb-2">Request a Quote</h2>
                <p class="text-sm text-[var(--color-text-muted)]">
                    Tell us your specs and quantities. We deliver a fast, accurate quote with guaranteed tolerances.
                </p>
            </div>

            <!-- CTA Button -->
            <a href="#quote" class="btn-primary px-8 py-3 rounded-[var(--radius-md)] font-semibold transition-all duration-200 ease-out hover:bg-[var(--color-primary-hover)] hover:-translate-y-0.5 hover:shadow-md active:translate-y-0 active:shadow-sm">
                Get My Quote
            </a>

            <!-- Trust Note -->
            <p class="text-xs text-[var(--color-text-muted)]">
                Response within 1 business day - No obligation
            </p>
        </div>
    </div>
</section>