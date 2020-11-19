<template>
  <Layout>
    <h1>Options</h1>
    <h2>Language</h2>
    <div class="list-group list-group-flush">
      <div class="list-group-item list-group-item-action">
        English
      </div>
    </div>
    <h2>Audio assistance</h2>
    <div class="list-group list-group-flush">
      <div class="list-group-item">
        <div class="custom-control custom-switch">
          <label class="custom-control-label" for="customSwitch1">Show sign language videos</label>
          <input type="checkbox" class="custom-control-input" id="customSwitch1" />
        </div>
      </div>
    </div>
    <div class="custom-control custom-switch">
      <input type="checkbox" class="custom-control-input" id="customSwitch1" />
      <label class="custom-control-label" for="customSwitch1">Toggle this switch element</label>
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Options',
  },
};
</script>
