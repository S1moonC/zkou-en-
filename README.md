function odmocnina (a){
return  Math.sqrt(a);
}
console.log(`Odmocnina z 1312 je: ${odmocnina(1312)}`);



function jeliche(číslo) {
        return cislo % 2 === 1;
}
let cislo = 69;
if (jeliche(cislo)) {
  console.log(`${cislo} je liché.`);
} else {
  console.log(`${cislo} není liché.`);
}

function Prvekvpoli(prvek, pole) {
  return pole.includes(prvek);
}
const Pole = [1, 2, 3, 4, 5];
const hledanyPrvek = 420;

if (Prvekvpoli(hledanyPrvek, Pole)) {
  console.log(`Prvek ${hledanyPrvek} je v poli.`);
} else {
  console.log(`Prvek ${hledanyPrvek} není v poli.`);
}
