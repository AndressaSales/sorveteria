<template>
    <div>
        <nav class=" flex items-center justify-between flex-wrap  bg-fuchsia-700 p-6">
            <div class="flex items-center flex-shrink-0 text-white mr-6">
                <NuxtLink to="/">
                    <span class="font-smilbold text-2xl text-white tracking-tight">Sorveteria</span>
                </NuxtLink>
            </div>
        </nav>
        <slot/>
    </div>
</template>