<template>
  <!-- <div class="overlay">
  <div class="model">
  <textarea name="note" id="note" cols="30" rows="10"></textarea>
  <button>Add Note</button>
  <button class="close">Close</button>
  </div>
  
  </div> -->
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
header button{
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
.overlay{
  position:absolute;
  width: 100%;
  height: 100%;
  background-color: rgb(0, 0, 0,0.70);
  z-index: 10;
  display: flex;
  align-items: center;
  justify-content: center;
}
.model{
  width: 750px;
  background-color: white;
  border-radius: 15px;
  padding: 30px;
  position: relative;
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.model button{
  padding: 10px 20px;
  font-size: 20px;
  width: 100%;
  background-color:rgb(247, 79, 79) ;
  border: none;
  border-radius: .3em;
  color: white;
  cursor: pointer;
}

.model .close{
  background-color: rgb(21, 20, 20);
}



</style>