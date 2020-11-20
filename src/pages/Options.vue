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
          <input type="checkbox" class="custom-control-input" id="customSwitch1" />
          <label class="custom-control-label" for="customSwitch1"><span>Show sign language videos</span></label>
        </div>
      </div>
      <div class="list-group-item">
        <div class="custom-control custom-switch">
          <input type="checkbox" class="custom-control-input" id="customSwitch2" />
          <label class="custom-control-label" for="customSwitch2"><span>Toggle this switch element</span></label>
        </div>
      </div>
      <div class="list-group-item">
        <div class="custom-control custom-switch">
          <input type="checkbox" class="custom-control-input" id="customSwitch3" />
          <label class="custom-control-label" for="customSwitch3"><span>Toggle this switch element</span></label>
        </div>
      </div>
      <div class="list-group-item">
        <div class="custom-control custom-switch">
          <input type="checkbox" class="custom-control-input" id="customSwitch4" />
          <label class="custom-control-label" for="customSwitch4"><span>Toggle this switch element</span></label>
        </div>
      </div>
      <div class="list-group-item">
        <div class="custom-control custom-switch">
          <input type="checkbox" class="custom-control-input" disabled id="customSwitch5" />
          <label class="custom-control-label" for="customSwitch5"><span>Toggle this switch element</span></label>
        </div>
      </div>
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

<style scoped>
  .list-group-item {
    margin-bottom: 0.5rem;
    padding: 0;
    border: none;
  }
  .custom-control {
    padding-left: 0;
  }
  .custom-control-label {
    width: 100%;
    line-height: 1.2rem;
    padding: 0.75rem 4rem 0.75rem  1.25rem;
    border: 1px solid #adb5bd;
    border-radius: 0.5rem;
    cursor: pointer;
  }
  .custom-control-input {
    left: unset;
    right: 0;
  }
  .custom-control-input:focus ~ .custom-control-label {
    box-shadow: 0 0 0 0.2rem rgba(241, 89, 42, 0.25);
  }
  .custom-control-input:checked ~ .custom-control-label {
    border-color: #f1592a;
  }
  .custom-control-input:not(:checked) ~ .custom-control-label {
    border-color:#adb5bd;
  }
  .custom-switch .custom-control-label::before {
    left: unset;
    right: 1.5rem;
    top: 1rem;
  }
  .custom-switch .custom-control-label::after {
    left: unset;
    right: calc(2.25rem + 2px);
    top: calc(1rem + 2px);
  }
</style>
