<template>
  <v-container>
    <div class="profile-card">
      <div class="profile-image">
        <img src="assets/rontale.jpg" />
      </div>
      <div class="profile-info">
        <h2>Rontale, Dan Keneth M.</h2>
      </div>
    </div>

    <div class="profile-card">
      <div class="profile-image">
        <img src="assets/rhigen.jpg" />
      </div>
      <div class="profile-info">
        <h2>Rhigen Abaca</h2>
      </div>
    </div>

    <div class="profile-card">
      <div class="profile-image">
        <img src="assets/nicolle.jpg"/>
      </div>
      <div class="profile-info">
        <h2>Nicolle Gutierrez</h2>
      </div>
    </div>
  </v-container>
</template>

<script>
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'manage',
});
</script>

<style>
.profile-card {
  display: flex;
  border: 1px solid #ccc;
  border-radius: 8px;
  margin: 10px;
  padding: 10px;
}

.profile-image {
  width: 100px;
  height: 100px;
  margin-right: 10px;
  overflow: hidden;
  border-radius: 50%;
}

.profile-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.profile-info {
  flex: 1;
}

h2 {
  font-size: 18px;
  margin: 0;
  padding: 0;
}
</style>