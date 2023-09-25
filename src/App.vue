<template>
  <main>
    <div class="container">
      <header>
        <h1>Notes</h1>
        <button>+</button>
      </header>

      <div class="cards-conatiner">
      <div class="card">
      <p class="main-text">hello darkness my old friend</p>
      <p class="date">10/8/2023</p>
      </div>
      
      </div>
    </div>
  </main>
</template>


<style scoped>

main{
  height: 100vh;
  width: 100vw;
}

.container {
  max-width: 1000px;
  padding: 10px;
  margin: 0 auto;
}

header{
  display: flex;
  justify-content: space-between;
  align-items: center;
}
h1{
  font-weight: normal;
  margin-bottom: 25px;
  font-size: 75px;
}
button{
  border: none;
  padding: 10px;
  width: 75px;
  height: 75px;
  cursor: pointer;
  border-radius: 25px;
  background-color: rgb(21, 20, 20);
  color: whitesmoke;
  font-size: 30px;
}
.card{
  height: 225px;
  width: 225px;
  background-color: aqua;
  padding: 10px;
  border-radius: 15px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  margin-right: 20px;
  margin-bottom: 20px;
}
.main-text{
  font-size: 16px;
}
.date{
  font-size: 12px;
}
.cards-container{
  display: flex;
  flex-wrap: wrap ;
}



</style>