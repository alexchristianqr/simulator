<template>
<div>
  <h1>Hola depositos</h1>
  <b-row>
    <b-col cols="6">
      <b-card title="Titulo 001">

        <b-form>
        <b-form-group label="Valor a invertir">
          <b-form-input></b-form-input>
        </b-form-group>

        <b-form-group label="Plazo en meses">
          <b-form-input></b-form-input>
        </b-form-group>


          <b-form-group label="Pago de intereses">
            <b-form-select v-model="selected" :options="options"></b-form-select>
          </b-form-group>
        </b-form>

      </b-card>

    </b-col>
    <b-col cols="6">
      <b-card title="Titulo 002"></b-card>

    </b-col>
  </b-row>
</div>
</template>

<script>
export default {
  name: "AppSimulator",
  data() {
    return {
      selected: null,
      options: [
        { value: null, text: 'Please select some item' },
        { value: 'a', text: 'This is First option' },
        { value: 'b', text: 'Default Selected Option' },
        { value: 'c', text: 'This is another option' },
        { value: 'd', text: 'This one is disabled', disabled: true }
      ]
    }
  }
}
</script>

<style scoped>

</style>