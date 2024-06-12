<script>
    import Profile from '$lib/components/Profile.svelte'
</script>

<!-- Full height container -->
<div class="flex flex-col items-center w-full h-screen h-full">
    <!-- Top nav bar -->
    <div class="flex items-center justify-center w-full p-8">
        <!-- Space them evenly, take up whole width -->
        <div class="flex items-center justify-evenly w-full text-neutral-400">
            <a href="/aboutme" class="text-lg font-bold">AboutMe</a>
        </div>
    </div>
    <!-- Rounded rectangle card -->
    <div class="w-full h-full mb-8">
        <div
            class="flex flex-col items-center justify-center h-full mx-8 p-8 bg-white rounded-lg shadow-lg bg-zinc-950"
        >
            <div class="flex flex-col items-center justify-center">
                <Profile/>
            </div>
            <div class="flex flex-col items-center justify-center mt-4 text-neutral-400">
                <h1 class="text-3xl font-bold">Tessalyn Becker :3</h1>
                <p class="text-lg">
                    Security Analyst
                </p>
            </div>
            <div class="flex flex-col items-center justify-center mt-8 text-neutral-400">
                <div>
                    <p></p>
                </div>
                <div>
                    <a
                        href="https://github.com/Cielettee"
                        target="_blank"
                        rel="noopener"
                    >
                        <i class="fa-brands fa-github"></i>
                    </a>
                    <a
                        href=""
                        target="_blank"
                        rel="noopener"
                    >
                        <i class="fa-brands fa-twitter"></i>
                    </a>
                    <a
                        href="https://www.linkedin.com/in/tessalyn-becker/"
                        target="_blank"
                        rel="noopener"
                    >
                        <i class="fa-brands fa-linkedin"></i>
                    </a>
                </div>
            </div>
        </div>
    </div>
</div>
<style lang="postcss">

</style>
