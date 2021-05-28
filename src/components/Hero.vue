<template>
  <div class="jumbotron">
      <div class="layover">
          <div class="text">
              <h2>HELLO WORLD!</h2>
              <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Reiciendis asperiores laboriosam ratione maiores doloremque delectus?</p>
              <hr>
              <button>GALLERIA</button>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: 'Hero'
}
</script>

<style>
.jumbotron {
    width: 100%;
    height: 600px;
    background-image: url("../assets/locandine.jpg");
    background-size: cover;
    background-repeat: no-repeat;
}
.layover {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.7);
}
.text {
    width: 80%;
    height: 60%;
    padding: 35px 50px;
    color: white;
}
h2 {
    font-size: 50px;
    font-weight: 300;
    margin-bottom: 20px;
}
p{
    font-size: 20px;
    margin-bottom: 20px;
}
button {
    margin-top: 30px;
    padding: 20px 20px;
    border-radius: 10px;
    border: none;
    font-size: 15px;
    font-weight: 600;
}
button:hover {
    background-color: lightblue;
    cursor: pointer;
}

</style>