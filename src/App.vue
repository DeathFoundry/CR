<script setup lang="ts">
import Auth1 from './components/Auth1.vue';
import DarkMode from './components/DarkMode.vue';
import TeamMembers from './components/TeamMembers.vue';
import {
  ResizableHandle,
  ResizablePanel,
  ResizablePanelGroup,
} from '@/components/ui/resizable'
</script>

<template>
    <DarkMode></DarkMode>

    <ResizablePanelGroup direction="horizontal">
    <ResizablePanel>

        <Auth1><</Auth1>

    </ResizablePanel>

    <ResizableHandle with-handle />

    <ResizablePanel>

        <TeamMembers></TeamMembers>

    </ResizablePanel>
  </ResizablePanelGroup>
</template>


