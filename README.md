*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body{
  width: 100%;
  height: 450%;
  background-color: #141212;
  display: flex;
  align-items: center;
  justify-content: center;
}

.num-container{
    width: 150%;
    height: 80px;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 28px;
    font-size: 25px;
    font-weight: bold;
    background-color: rgba(255, 0, 255, 0);
}

.calculator {
    width: 370px;
    height: 600%;
    margin: 10px auto;
    text-align: center;
    font-family: sans-serif;
    border-radius: 12px;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  
  input[type="text"] {
    width: 100%;
    height: 70px;
    font-size: 25px;
    text-align: right;
    padding-right: 10px;
    box-sizing: border-box;
    border-radius: 12px;
    border: none;
    background-color: rgba(238, 238, 238, 0.295);

  }
  
  .buttons {
    display: flex;
    flex-wrap: wrap;
  }
  
  button {
    width: 100%;
    height: 70px;
    font-size: 20px;
    border: 1px solid rgb(29, 25, 25);
    background-color: rgba(29, 25, 25);
    color: #fff;
    outline: none;
    border-radius: 100px;
    cursor: pointer;
    font-size: 25px;
  }
  
  .function{
    background-color:rgba(221, 221, 221, 0.411);
    font-size: 25px;
    height: 60px;
  }
  .operator{
    background-color:rgba(29, 25,25);
    font-size: 30px;
    height: 70px;
  }
  
  #clear{
    width: 100%;
    height: 70px;
    font-size: 20px;
    background-color: rgba(29,25,25);
    outline: none;
    border-radius: 100px;
    cursor: pointer;
  }
  
  #equals {
    background-color: rgb(255, 51, 0);
    color: #fff;
    height: 70px;
    border-radius: 100px;
  }

