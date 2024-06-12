<script>
    import '../app.css'
    import '@fortawesome/fontawesome-free/css/all.min.css'
    import { base } from '$app/paths'
    import noseguy from '$lib/assets/nose.png'
</script>

<div class="bg-[#1A120B]">
    <div class="grid grid-cols-1 md:grid-cols-8 grid-flow-row w-full h-screen h-full">
        <!-- Top nav bar -->
        <div class="flex justify-center items-center md:h-screen w-full">
            <!-- Space them evenly, take up whole width -->
            <div class="flex flex-col text-center items-center justify-evenly h-6/10 text-[#D5CEA3] gap-8">
                <a href={base + '/'} class="py-4 px-8 rounded-lg"><img src={noseguy} class="w-[6rem] h-[6rem] rounded-full"></a>
                <a href={base + '/aboutme'} class="text-lg font-bold hover:bg-[#3C2A21] py-4 px-8 rounded-lg">About Me!</a>
                <a href={base + '/newstuff'} class="text-lg font-bold hover:bg-[#3C2A21] py-4 px-8 rounded-lg">Current Stuff!</a>
                <a href={base + '/resume'} class="text-lg font-bold hover:bg-[#3C2A21] py-4 px-8 rounded-lg">Resume!</a>
            </div>
        </div>
        <!-- Rounded rectangle card -->
        <div class="w-full h-9/10 mb-8 col-span-7 my-8">
            <div
                class="flex flex-col items-center justify-center h-full mx-8 p-8 rounded-lg shadow-lg bg-[#3C2A21]"
            >
            <slot />
            </div>
        </div>
     </div>
</div>

