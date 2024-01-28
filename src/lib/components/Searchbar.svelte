<script>
    import {SearchOutline} from 'flowbite-svelte-icons';
</script>

<form method="post" class="h-5 flex w-[390px] px-3 items-center">
    <input type="text" placeholder="search" class="border-2 h-8 placeholder-opacity-30 flex w-[80%] px-3 rounded-l-xl outline-none border-opacity-50 border-gray-300"/>
    <button class="border-2 border-l-0 border-gray-300 border-opacity-50 py-1 pr-1 rounded-r-xl">
        <SearchOutline class="px-1 opacity-50"/>
    </button>
</form>