<template>
  <q-page padding>
  <div class="row">
    <div class="col">
    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quia, cupiditate cumque! Expedita iusto molestias sequi in eveniet alias inventore temporibus pariatur! At ratione corrupti, deserunt alias aspernatur provident eius dignissimos!
      <div>
        <q-btn color="primary" label="Primary" @click="handleClick" />
      </div>
    </div>
    <div class="col">
    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quia, cupiditate cumque! Expedita iusto molestias sequi in eveniet alias inventore temporibus pariatur! At ratione corrupti, deserunt alias aspernatur provident eius dignissimos!
    </div>
  </div>
  </q-page>
</template>

<script>
export default {
  methods: {
    handleClick () {
      alert('hello world')
    }
  }
}
</script>
