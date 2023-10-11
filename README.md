#:root {
	--dark: #680747;
	--darkest: #141010;
    --violet:#c3195d; 
}
body{
    margin: 0;
}
.page{
    background-color: var(--darkest);
    min-height:100vh;
    font-size:x-large;
    width: 100vw;
    display:flex;
    flex-direction: column;
}
.cont{
    display: flex;
    flex-direction: column;
    justify-content:space-evenly;
    align-items: center;
    background-color:var(--violet);
    backdrop-filter: blur(10px);
    border-radius: 5px;
    border: 2px solid var(--light);
    box-shadow: 0px 0px 10px  var(--violet);
    width: 30vw;
    height: 80vh;
    min-width:300px;
    margin: 10vh auto;
    color: white;
}
.screen{
    display: flex;
    background-color: var(--dark);
    overflow: hidden;
    width: 95%;
    height: 25%;
    border-radius: 5px;
    border: 2px solid var(--grey);
}
.display{
    display: block;
    height:65%;
    padding-left: 10px;
}
.screen h1{
    
    font-size: 2rem;
}
.keypad{
    display: grid;
    background-color: var(--violet);
    grid-template-columns: 1fr 1fr 1fr 1fr;
    border-radius: 5px;
    width: 95%;
    height: 65%;
    column-gap: .3%;
    row-gap: .3%;
    user-select: none;
}
.key{
    display:flex;
    justify-content:center;
    align-items: center;
    font-size: 100%;
    background-color:#cbf078;
    transition: .3s;
    color:white;
    cursor:pointer;
    border-radius:5px;
    opacity: 0.9;
}
.op{
    background-color: #ff9a3c;
}
.clear , .AC{
    background-color:  #d8d7d7;
}
.sol{
    background-color: #ffe700;
}
.key:hover{
    opacity: 1;
    
} calculator1
