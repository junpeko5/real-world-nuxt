<template>
  <div>
    <h1>Create vue</h1>
  </div>
</template>

<script>
export default {
  name: 'CreatePage',
  head() {
    return {
      title: 'Create an Event',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content:
            'You can create a new event in your neighborhood'
        }
      ]
    }
  },
}
</script>
