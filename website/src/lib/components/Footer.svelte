<script>
    import LibrePass from '$lib/images/LibrePass.svelte';
</script>

<footer class="footer p-10 bg-base-200 text-base-content">
    <aside class="items-center my-auto grid-flow-col">
        <LibrePass size="50" />
        <p>
            LibrePass
            <br />
            Take control of your password with LibrePass
        </p>
    </aside>
    <nav>
        <header class="footer-title">Download</header>
        <a class="link link-hover" href="https://f-droid.org/en/packages/dev.medzik.librepass.android/" target="_blank">
            Android F-Droid
        </a>

        <a
            class="link link-hover"
            href="https://github.com/LibrePass/LibrePass-Android/releases/latest"
            target="_blank"
        >
            Android .apk
        </a>
    </nav>

    <nav>
        <header class="footer-title">Team</header>
        <a class="link link-hover" href="mailto:librepass@medzik.dev">Contact</a>
    </nav>

    <nav>
        <header class="footer-title">Legal</header>
        <a class="link link-hover" href="/privacy">Privacy policy</a>
    </nav>
</footer>
