<template>
  <v-container>
    Members:
    <div class="member">
      <div class="member-image member1"></div>
      Rontale, Dan Keneth M.
    </div>
    <div class="member">
      <div class="member-image member2"></div>
      Rhigen Abaca
    </div>
    <div class="member">
      <div class="member-image member3"></div>
      Nicolle Gutierrez
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
.member {
  display: flex;
  align-items: center;
  margin-bottom: 10px;
}

.member-image {
  width: 50px;
  height: 50px;
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  border-radius: 50%;
  margin-right: 10px;
}

.member1 {
  background-image: url('rontale.jpg');
}

.member2 {
  background-image: url('rhigen.jpg');
}

.member3 {
  background-image: url('nicolle.jpg');
}
</style>