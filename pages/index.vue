<template>
  <div>
    <div>
      <nuxt-link :to="switchLocalePath('ja')">日本語</nuxt-link>
      <nuxt-link :to="switchLocalePath('en')">English</nuxt-link>
    </div>
    <div>
      <h1>{{$t('message')}}</h1>
      <div>
        <img :src="$t('imgfile')">
      </div>
    </div>
  </div>
</template>

<script>
export default {
}
</script>
