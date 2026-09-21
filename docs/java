let numeroSenha = 0;
let fila = [];

function retirarSenha() {
numeroSenha++;

let senha = "A" + String(numeroSenha).padStart(3, "0");

fila.push(senha);

atualizarFila();

alert("Sua senha é " + senha);


}

function chamarSenha() {
if (fila.length === 0) {
alert("Não há senhas aguardando atendimento.");
return;
}

let senha = fila.shift();

document.getElementById("senhaAtual").textContent = senha;

atualizarFila();


}

function atualizarFila() {
let lista = document.getElementById("fila");

lista.innerHTML = "";

fila.forEach(function(senha) {
    let item = document.createElement("li");

    item.textContent = senha;

    lista.appendChild(item);
});


}
