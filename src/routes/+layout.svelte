<script>
    import '../app.css'
    import '@fortawesome/fontawesome-free/css/all.min.css'
    import { base } from '$app/paths'
    import me from '$lib/assets/pb.gif'
    import noseguy from '$lib/assets/nose.png'
    import rain from '$lib/assets/rain.gif'
</script>

<div class="bg-[#0c0c0c] bg-[length:270px_920px] bg-no-repeat bg-[url('$lib/assets/rain.gif')]">
    <div class="grid grid-cols-1 md:grid-cols-8 grid-flow-row w-full h-screen h-full">
        <div class="flex justify-center items-center md:h-screen w-full">
            <!-- Space them evenly, take up whole width -->
            <div class="flex flex-col text-center items-center justify-evenly h-6/10 text-[#F2613F] gap-8">
                <a href={base + '/'} class=" rounded-lg"><img src={me} class="p-1 w-[6rem] h-[6rem] rounded-full hover:p-1.5 bg-[#3D0000]"></a>
                <a href={base + '/aboutme'} class="text-lg font-bold bg-[#3D0000] hover:bg-[#950101] py-4 px-8 rounded-lg">About Me!</a>
                <a href={base + '/resume'} class="text-lg font-bold bg-[#3D0000] hover:bg-[#950101] py-4 px-8 rounded-lg">Resume!</a>
            </div>
        </div>
        <!-- Rounded rectangle card -->
        <div class="w-full h-9/10 mb-8 col-span-7 my-8 overflow-y-auto">
            <div
                class="flex flex-col h-full mx-8 p-8 rounded-lg shadow-lg bg-[#3D0000]"
            >
            <slot />
            </div>
        </div>
     </div>
</div>

