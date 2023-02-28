function numeros(valor){
    document.getElementById('display').value += valor;
    
}


function operacion(){
    var opera = document.getElementById('display').value;
    if(opera == 0){
        document.getElementById('display').value = "Sin operacion";
    } else{
        document.getElementById('display').value = eval(opera);
    }
}

function resetear(){
    document.getElementById('display').value = " ";
}

