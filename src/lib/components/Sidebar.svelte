<script>
    import {HomeOutline,FireOutline , GithubSolid} from 'flowbite-svelte-icons';
    const nav = ["Home","Trends","github"]
</script>

<div class="bg-white hidden flex-col md:flex pt-7 fixed items-center pl-12 pr-14 top-[63px] h-screen border-t border-r border-gray-400 border-opacity-50">
        <a href="/" class="flex justify-center items-center py-5"><HomeOutline /> <p class="text-s ml-2 capitalize">{nav[0]}</p></a>
        <a href="/about" class="flex justify-center items-center py-5"><FireOutline /> <p class="text-s ml-2 capitalize">{nav[1]}</p></a> 
        <a href="/" class="flex justify-center items-center py-5"><GithubSolid /> <p class="text-s ml-2 capitalize">{nav[2]}</p></a>
</div>
