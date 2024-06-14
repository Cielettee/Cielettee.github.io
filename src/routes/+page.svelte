<script>
    import Profile from '$lib/components/Profile.svelte'
    import { base } from '$app/paths'
</script>
<div class="flex flex-col justify-center items-center w-full h-full">
    <div class="flex w-full justify-center items-center">
        <Profile/>
    </div>
    <div class="flex flex-col w-full justify-centrer items-center mt-4 text-[#F2613F]">
        <h1 class="pl-6 text-3xl font-bold">Tessalyn Becker <i class="fa-solid fa-mug-hot" style="color: #F2613F"></i>
        </h1>
        <p class="text-lg">
            Security Analyst - Programmer - Artist
        </p>
    </div>
    <div class="flex flex-col items-center justify-center mt-2 text-[#F2613F]">
        <div>
            <a
                class="hover:text-[#FF0000]"
                href="https://github.com/Cielettee"
                target="_blank"
                rel="noopener"
            >
                <i class="fa-brands fa-github"></i>
            </a>
            <a
                class="hover:text-[#FF0000]"
                href="https://www.linkedin.com/in/tessalyn-becker/"
                target="_blank"
                rel="noopener"
            >
                <i class="fa-brands fa-linkedin"></i>
            </a>
        </div>
    </div>
</div>