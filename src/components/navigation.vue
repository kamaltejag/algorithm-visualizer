<template>
    <button  class="my-3 bg-rose-400 text-white p-3 rounded-md font-bold hover:scale-110 transition ease-in-out">Generate
        Bars</button>
    <div class="grid justify-items-center">
        <div class="lg:grid grid-cols-6 bg-gray-700 p-5 rounded-md gap-3">
            <button
                class="bg-blue-200 text-black px-3 py-2 rounded-md font-mono font-semibold hover:shadow-md hover:shadow-blue-100/40 hover:-translate-y-1 hover:bg-indigo-300 transition ease-in-out">Selection
                Sort</button>
            <button
                class="bg-blue-200 text-black px-3 py-2 rounded-md font-mono font-semibold hover:shadow-md hover:shadow-blue-100/40 hover:-translate-y-0.5 hover:bg-indigo-300 transition ease-in-out">Insertion
                Sort</button>
            <button
                class="bg-blue-200 text-black px-3 py-2 rounded-md font-mono font-semibold hover:shadow-md hover:shadow-blue-100/40 hover:-translate-y-0.5 hover:bg-indigo-300 transition ease-in-out">Merge
                Sort</button>
            <button
                class="bg-blue-200 text-black px-3 py-2 rounded-md font-mono font-semibold hover:shadow-md hover:shadow-blue-100/40 hover:-translate-y-0.5 hover:bg-indigo-300 transition ease-in-out">Quick
                Sort</button>
            <button
                class="bg-blue-200 text-black px-3 py-2 rounded-md font-mono font-semibold hover:shadow-md hover:shadow-blue-100/40 hover:-translate-y-0.5 hover:bg-indigo-300 transition ease-in-out">Heap
                Sort</button>
            <button
                class="bg-blue-200 text-black px-3 py-2 rounded-md font-mono font-semibold hover:shadow-md hover:shadow-blue-100/40 hover:-translate-y-0.5 hover:bg-indigo-300 transition ease-in-out">Radix
                Sort</button>
        </div>
    </div>
</template>

<script>
export default {
    name: "Navigation",
};
</script>
