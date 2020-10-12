<template>
  <figure class="avatar">
    <img :src="src" :alt="alt" :width="size" :height="size" />
  </figure>

</template>

<script>
export default {
  name: 'Avatar',
  props: {
    src: {
      type: String,
      default:
        'https://instagram.fadb2-1.fna.fbcdn.net/v/t51.2885-19/s150x150/83724326_636332233820176_6021096574745051136_n.jpg?_nc_ht=instagram.fadb2-1.fna.fbcdn.net&_nc_ohc=DUfWU0lPcFEAX9EEuCV&oh=6dbd092ae9f36313d233667fc4bb8f83&oe=5FAD80DD'
    },
    alt: {
      type: String
    },
    size: {
      type: Number
    }
  }
}
</script>

<style scoped>
.avatar {
  padding: 2px;
  border-radius: 999px;
  display: inline-flex;
  background: linear-gradient(
    219deg,
    rgba(184, 63, 140, 1) 0%,
    rgba(237, 158, 90, 1) 100%
  );
  img {
    border-radius: inherit;
    border: 2px solid white;
  }
}
</style>
