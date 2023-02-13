<template>
      <div className="App">
      <div class= "my-container">
         <h1 id="header1" class="headerclass">Nittany Lion</h1>
            <img src={nittLogo} alt="nitt" height={200} width={300} />
            <p id="paragraph">Penn State's mascot. Probably similar to a mountain lion.</p>
            <button class="details">DETAILS </button>
       </div> 
       <div class="buttons">
      <button class="changecolor">CHANGE COLOR </button>
      <button class="duplicate">DUPLICATE </button>
      <button class="newtitle">NEW TITLE </button>
      <button class="delete">DELETE </button>
      </div>
    </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
}
</script>

<style>
#app {
  .main
{
  font-style: italic;
  visibility: visible;
}
.App {
  text-align: center;
  visibility: visible;
  justify-content:center;
  display:flex;
}

.buttons {
  margin: 16px auto;
  display: flex;
  align-items: center;
  justify-content: space-evenly; 
}

.paragraph
{
  visibility: visible;
}

.changecolor
{
  background: skyblue;
  font-family: courier;
  padding-top: 5px;
  padding-right: 15px;
  padding-left: 15px;
  padding-bottom: 5px;  
  font-size: 22px;
}
.changecolor:hover
{
  background-color: pink;
}
.duplicate
{
  background: skyblue;
  font-family: courier;
  padding-top: 5px;
  padding-right: 15px;
  padding-left: 15px;
  padding-bottom: 5px;  
  font-size: 22px;
}
.duplicate:hover
{
  background-color: pink;

}
.details:hover
{
  background-color: skyblue;

}
.newtitle
{
  background: skyblue;
  font-family: courier;
  padding-top: 5px;
  padding-right: 15px;
  padding-left: 15px;
  padding-bottom: 5px;  
  font-size: 22px;
}
.newtitle:hover
{
  background-color: pink;
}

.delete
{
  background: skyblue;
  font-family: courier;
  padding-top: 5px;
  padding-right: 15px;
  padding-left: 15px;
  padding-bottom: 5px;  
  font-size: 22px;
}
.delete:hover
{
  background-color: pink;
}
.my-container{
    background: gray;
    width: 300px;
    text-align: center;
    font-family: cursive;
    border: 5px solid blue;
    padding-top: 1px;
    padding-right: 15px;
    padding-left: 15px;
    padding-bottom: 5px;
}
.details
{
  visibility: visible;
  border: 2px solid pink;
  background: pink;
  font-family: courier;
      padding-top: 5px;
    padding-right: 15px;
    padding-left: 15px;
    padding-bottom: 5px;  
  font-size: 22px;
  }
}
</style>
