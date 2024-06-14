<script>
   import { base } from '$app/paths'
</script>
<div class="hidden 2xl:flex w-full h-full">
   <embed src="{base + '/resume.pdf'}" width="100%" height="100%" class='rounded-lg'/>
</div>
<div>
   <p class="text-[#FF0000]">
      If you can't see the PDF on the viewer, <a href={base + '/resume.pdf'} class="underline hover:text-[#F2613F]" target="_blank" rel="noopener">click here!</a>
   </p>
</div>
