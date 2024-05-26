const vitorias = 0;
const derrotas = 0;

let saldo = vitorias - derrotas;

function decidirNivel(saldo) {
	let nivel;

    switch (true) {
    	case (saldo <= 10):
    		nivel = "Ferro";
            break;
        case (saldo >= 11 && saldo <= 20): 
        	nivel = "Bronze";
            break;
        case (saldo >= 21 && saldo <= 50): 
        	nivel = "Prata";
            break;
        case (saldo >= 51 && saldo <= 80): 
        	nivel = "Ouro";
            break;
        case (saldo >= 81 && saldo <= 90): 
        	nivel = "Diamante";
            break;
        case (saldo >= 91 && saldo <= 100):
        	nivel = "Lendário";
            break;
        default:
        	nivel = "Imortal";
    }    	
    return nivel;
}

const nivel = decidirNivel(saldo);
console.log("O Herói tem saldo de " + saldo + " e está no nível de " + nivel + ".");
