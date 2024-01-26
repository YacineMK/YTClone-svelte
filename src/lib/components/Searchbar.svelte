<script>
    import {SearchOutline} from 'flowbite-svelte-icons';
</script>

<form method="post" class="h-5 flex  items-center">
    <input type="text" placeholder="search" class="border-2 h-8 placeholder-opacity-30 placeholder- flex min-w-60 md:w-60 px-3 rounded-l-xl outline-none border-gray-400"/>
    <button class="border-2 border-l-0 border-gray-400 py-1 pr-1 rounded-r-xl">
        <SearchOutline class="px-1 "/>
    </button>
</form>