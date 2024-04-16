<template>
    <div>
    <Timeline :value="events">
    
    
    </Timeline>        
    </div>
</template>
<script lang="ts">

import Timeline from 'primevue/timeline';
import events from '../../../TimeyWimeys/events.json'
console.log(events);
export default{
    Timeline
}

</script>
<style lang="scss">
    
</style>