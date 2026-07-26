<script setup lang="ts">
import { Link } from '@inertiajs/vue3';
import { PlusCircleIcon } from '@lucide/vue';
</script>

<template>
    <Head title="Dashboard" />

    <Link
        href="Createfamily"
        class="cursor-hand h-2xs absolute right-4 w-2xs rounded-2xl border border-purple-400 text-center text-gray-500 hover:text-gray-700"
    >
        <PlusCircleIcon />Start A Family
    </Link>
    <Link
        href="Joinfamily"
        class="border-blue w-2xs rounded-2xl border bg-fuchsia-400 text-center"
    >
        Join family</Link
    >
    <Link href="Createfamily"> Upload Photo</Link>
    <div class="flex flex-1 flex-col gap-4 rounded-xl p-4">
        <h1>All photos</h1>
        <div class="grid auto-rows-min gap-4 md:grid-cols-3">
            <div
                class="relative aspect-video overflow-hidden rounded-xl border border-sidebar-border/70 dark:border-sidebar-border"
            >
                loejdjj
            </div>

            <div
                class="relative aspect-video overflow-hidden rounded-xl border border-sidebar-border/70 dark:border-sidebar-border"
            >
                yyesds
            </div>

            <div
                class="relative aspect-video overflow-hidden rounded-xl border border-sidebar-border/70 dark:border-sidebar-border"
            >
                huuuudd
            </div>
        </div>
        <div
            class="relative min-h-[100vh] flex-1 rounded-xl border md:min-h-min"
        >
            jahahaa
        </div>

        whhha
    </div>

    <div>
        <div class="bg-zinc -400 relative flex-1 rounded-2xl border">
            ff\xva
        </div>
        <div class="relative flex-1 rounded-2xl border bg-amber-400">
            nini na hwewe
        </div>
        <div class="relative flex-1 rounded-2xl border bg-pink-400">
            huhu uuh
        </div>
        <div class="relative flex-1 rounded-2xl border border-blue-400">
            brtee
        </div>
    </div>
</template>
