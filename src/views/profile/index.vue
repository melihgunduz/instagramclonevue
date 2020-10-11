<template>
  <div class="home">
    <CustomText tag="h1">Profile</CustomText>
    <CustomText tag="p"
      >Lorem ipsum dolor sit amet, consectetur adipisicing elit. Adipisci
      aliquid asperiores blanditiis earum labore laudantium magnam natus neque
      officia officiis qui quibusdam saepe sapiente, sint veniam! Autem
      doloremque illo quibusdam?
    </CustomText>

    <div id="nav">
      <router-link to="/profile">Profile</router-link> |
      <router-link to="/profile/igtv">IGTV</router-link> |
      <router-link to="/profile/save">Save</router-link> |
      <router-link to="/profile/tag">Tag</router-link> |
    </div>

    <router-view />
  </div>
</template>

<script>
import CustomText from '@/components/CustomText'
export default {
  name: 'Profile',
  components: {
    CustomText
  }
}
</script>

<style scoped></style>
