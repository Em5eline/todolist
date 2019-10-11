<template>

<div id="app">
  <div class="container">
    <h1 class="titre">To-Do List du ...</h1>
    <form class="form-group" ...>
      <input class="txt form-control" type="text" v-model="name" />
      <button type="submit" class="btn btn-primary">Ajouter</button>
    </form>
    <ul class="list-group">
      <li ...>
        <label>
          <input type="checkbox" />
          <span>...</span>
        </label>
        <button class="delete-btn btn btn-primary" type="button" ... ><p class="delete"> x </p></button>
      </li>
    </ul>
  </div>
</div>
  
</template>

<script>

export default {

  data(){

  },

  computed: {

  },

  methods: {

  }

}

</script>


<style>

@import url('https://fonts.googleapis.com/css?family=Merienda+One&display=swap');


.txt {
  width: 300px;
}

.container {
  margin-left: 550px;
  margin-top: 50px;
  background-color: white;

}

span {
  margin: 15px;
  font-family: Merienda One, cursive;
}

.btn {
  margin-left:315px;
  margin-top:-57px;
  background-color: #405F30;
  border-color: #26391D;
  
}

.btn:hover {
  background-color: #507A3D;
}

.delete-btn {
  width: 20px;
  height: 20px;
  padding: 6px 0px;
  background-color: #7B1225;
  border: none;
  border-radius: 15px;
  font-size: 12px;
  margin-left: -2px;
  margin-top: -5px;
}

.delete {
  line-height: 0.65;
}

.delete-btn:hover {
  background: rgb(160, 23, 48);
}

.titre {
  font-family: Merienda One, cursive;
  font-size: 30px;
  margin-left: 10px;
}

ul {
  list-style: none;
  margin-left: 30px;
}

</style>