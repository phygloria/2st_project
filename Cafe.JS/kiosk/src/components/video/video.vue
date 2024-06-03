<script setup>
    import {ref} from 'vue';
    const Video = ref('Video');

</script>

<template>
    <div class="video-container">
        <Video id="app"controls autoplay muted loop>
            <source src="https://videos.pexels.com/video-files/2909914/2909914-hd_1366_720_24fps.mp4" controls="controls" >
        </Video>
    </div>
</template>

<style scoped>
video {
  width: 100%;
  height: auto;
  align-items: center;
  
}
</style>