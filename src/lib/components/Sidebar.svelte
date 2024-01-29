<script>
    import {HomeOutline,FireOutline , GithubSolid} from 'flowbite-svelte-icons';
    const nav = ["Home","Trends","github"]
</script>

<div class="bg-white hidden py-2 flex-col md:flex  fixed items-center pl-6 pr-8 top-[60px] h-screen border-r border-gray-500">
        <a href="#" class="flex justify-center items-center py-3"><HomeOutline class="mb-1"/> <p class="text-s ml-2 capitalize">{nav[0]}</p></a>
        <a href="#" class="flex justify-center items-center py-3"><FireOutline class="mb-1"/> <p class="text-s ml-2 capitalize">{nav[1]}</p></a> 
        <a href="#" class="flex justify-center items-center py-3"><GithubSolid class="mb-1"/> <p class="text-s ml-2 capitalize">{nav[2]}</p></a>
</div>
