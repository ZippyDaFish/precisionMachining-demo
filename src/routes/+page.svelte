<script>
    import heroMedia from "$lib/assets/heroMedia.jpg";
</script>

<!-- Hero -->
<section class="min-h-screen flex flex-col md:flex-row">
    <!-- Hero Text -->
    <div class="md:w-1/2 w-full flex items-center justify-center bg-[var(--color-surface)]">
        <div class="w-full max-w-xl px-6">
            <h1 class="text-6xl mb-8">Precision Custom Tooling</h1>
            <h3 class="text-lg">Exactly what you need (Within tolerance).</h3>
        </div>
    </div>
    <!-- Hero Media -->
    <div class="md:w-1/2 w-full flex items-center justify-center bg-[var(--color-surface)] h-screen overflow-hidden">
        <div class="w-full max-w-xl px-6 flex items-center justify-center h-full">
            <img src={heroMedia} alt="" class="max-h-[80%] w-auto object-contain" />
        </div>
    </div>
</section>

<!-- Trust -->
<section class="w-full min-h-[50vh] p-16 flex flex-col items-center bg-[var(--color-bg)]">
    <h2 class="text-3xl mb-10">Hear From Our Other Customers</h2>

    <div class="w-full max-w-6xl mx-auto px-6 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">

        <!-- Card 1 -->
        <div class="bg-[var(--color-surface)] border border-[var(--color-border)] rounded-[var(--radius-md)] p-6 shadow-sm">
            <p class="text-sm text-[var(--color-text-muted)] mb-4">
                “Their tooling held ±0.0002” across a 12-hour run. We reduced scrap by 18% in the first week.”
            </p>
            <p class="font-semibold text-[var(--color-primary)]">- Michael Scott</p>
            <p class="text-xs text-[var(--color-text-muted)]">Production Manager, MI Components</p>
        </div>

        <!-- Card 2 -->
        <div class="bg-[var(--color-surface)] border border-[var(--color-border)] rounded-[var(--radius-md)] p-6 shadow-sm">
            <p class="text-sm text-[var(--color-text-muted)] mb-4">
                “Lead times were cut in half and every insert was dead-on spec. Setup time dropped from 45 to 20 minutes.”
            </p>
            <p class="font-semibold text-[var(--color-primary)]">- Leonard Hofstadter</p>
            <p class="text-xs text-[var(--color-text-muted)]">Tooling Engineer, North River Machining</p>
        </div>

        <!-- Card 3 -->
        <div class="bg-[var(--color-surface)] border border-[var(--color-border)] rounded-[var(--radius-md)] p-6 shadow-sm">
            <p class="text-sm text-[var(--color-text-muted)] mb-4">
                “We pushed their cutters through hardened 4140 all shift with zero chatter. Tool life doubled.”
            </p>
            <p class="font-semibold text-[var(--color-primary)]">- David Wallace</p>
            <p class="text-xs text-[var(--color-text-muted)]">CNC Supervisor, Valley Fabrication</p>
        </div>

        <!-- Card 4 -->
        <div class="bg-[var(--color-surface)] border border-[var(--color-border)] rounded-[var(--radius-md)] p-6 shadow-sm">
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
        <div class="border border-[var(--color-border)] rounded-[var(--radius-md)] p-6 bg-white shadow-sm">
            <h3 class="text-lg mb-2">Custom Tool Design</h3>
            <p class="text-sm text-[var(--color-text-muted)]">
                Application-specific tooling engineered.
            </p>
        </div>

        <!-- Service 2 -->
        <div class="border border-[var(--color-border)] rounded-[var(--radius-md)] p-6 bg-white shadow-sm">
            <h3 class="text-lg mb-2">CNC Tool Manufacturing</h3>
            <p class="text-sm text-[var(--color-text-muted)]">
                High-precision milling, turning, and grinding for carbide.
            </p>
        </div>

        <!-- Service 3 -->
        <div class="border border-[var(--color-border)] rounded-[var(--radius-md)] p-6 bg-white shadow-sm">
            <h3 class="text-lg mb-2">Regrinding & Refurbishing</h3>
            <p class="text-sm text-[var(--color-text-muted)]">
                Restore worn tools to extend tool life.
            </p>
        </div>

        <!-- Service 4 -->
        <div class="border border-[var(--color-border)] rounded-[var(--radius-md)] p-6 bg-white shadow-sm">
            <h3 class="text-lg mb-2">Tool Coating Services</h3>
            <p class="text-sm text-[var(--color-text-muted)]">
                Performance coatings that improve wear resistance and heat management.
            </p>
        </div>

        <!-- Service 5 -->
        <div class="border border-[var(--color-border)] rounded-[var(--radius-md)] p-6 bg-white shadow-sm">
            <h3 class="text-lg mb-2">On-Site Technical Support</h3>
            <p class="text-sm text-[var(--color-text-muted)]">
                Hands-on troubleshooting or tool trials.
            </p>
        </div>

    </div>
</section>

<!-- Offer -->
<section class="w-full min-h-[25vh] p-16 flex flex-col justify-center bg-[var(--color-bg)]">
    <h2 class="text-3xl">15% Off Your First Order!</h2>
</section>

<!-- Why Us -->
<section class="w-full min-h-[50vh] p-16 flex flex-col items-center bg-[var(--color-surface)]">
    <h2 class="text-3xl">Hear From Our Other Customers</h2>
    <div class="w-full max-w-6xl mx-auto px-6">
        <p>Test stuff</p>
    </div>
</section>

<!-- Final CTA -->
<section class="w-full min-h-[50vh] p-16 flex flex-col items-center bg-[var(--color-bg)]">
    <h2 class="text-3xl">Request a Quote!</h2>
    <div class="w-full max-w-6xl mx-auto px-6">
        <p>Test stuff</p>
    </div>
</section>