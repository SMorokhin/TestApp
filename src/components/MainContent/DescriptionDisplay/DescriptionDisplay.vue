<template>
    <div class="d-flex mb-5 justify-content-start desc">
      <video
        class="rounded border border-warning"
        loop
        width="350"
        height="200"
        autoplay
        muted
        type='video/mp4; codecs="avc1.42E01E, mp4a.40.2"'
        :src="description.src"
      />
      <div class="text-description-right ">
        {{ description.description }}
      </div>
    </div>
</template>

<script src="./DescriptionDisplay.js"></script>
<link rel="stylesheet" src="./DescriptionDisplay.scss">
