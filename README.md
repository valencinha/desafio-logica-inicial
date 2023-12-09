//nome do herói, nível e exp 
let nomeDoHeroi = "Aquiles";
let xp = 8000;
let nivelDoHeroi; 

//## Objetivo

//Crie uma variável para armazenar o nome e a quantidade de experiência (XP) de um herói, depois utilize uma estrutura de decisão para apresentar alguma das mensagens abaixo:


switch(true){
    case xp <= 1000:
        nivelDoHeroi = "Ferro"; 
        console.log("O herói de nome " + nomeDoHeroi + " está no nível de " + nivelDoHeroi);
        break
   case xp >= 1001 && xp <= 2000:
        nivelDoHeroi = "Bronze"
        console.log("O herói de nome " + nomeDoHeroi + " está no nível de " + nivelDoHeroi);
        break
   case xp >= 2001 && xp <= 5000: 
        nivelDoHeroi = "Prata" 
        console.log("O herói de nome " + nomeDoHeroi + " está no nível de " + nivelDoHeroi);
        break
   case xp >= 6001 && xp <= 7000:
        nivelDoHeroi = "Ouro"
        console.log("O herói de nome " + nomeDoHeroi + " está no nível de " + nivelDoHeroi);
        break
   case xp >= 7001 && xp <= 8000:
        nivelDoHeroi = "Platina"
        console.log("O herói de nome " + nomeDoHeroi + " está no nível de " + nivelDoHeroi);
        break
   case xp >= 8001 && xp <= 9000:
        nivelDoHeroi = "Ascendente"
        console.log("O herói de nome " + nomeDoHeroi + " está no nível de " + nivelDoHeroi);
        break
   case xp >= 9001 && xp <= 10000: 
        nivelDoHeroi = "Imortal"
        console.log("O herói de nome " + nomeDoHeroi + " está no nível de " + nivelDoHeroi);
        break
   case xp >= 10001: 
        nivelDoHeroi = "Radiante"
        console.log("O herói de nome " + nomeDoHeroi + " está no nível de " + nivelDoHeroi);
        break                     


}
        //console.log("O herói de nome " + nomeDoHeroi + " está no nível de " + nivelDoHeroi); 

