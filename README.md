# Exercicio 1
const Frutas = ['Açaí','Abacate','Banana']
const Legumes = ['Cenoura','Batata - doce','Beterraba']

const Compras = Frutas.concat(Legumes)
console.log(Compras) 

# Exercicio 2
const Numeros = ['1','2','3','4','5','6','7','8','9','10']

console.log(Numeros)

const parteNumeros = Numeros.slice(3,7)
console.log (parteNumeros)

# Exercicio 3
const frutas = ['Maçã', 'Banana', 'Laranja', 'Limão', 'Abacaxi']

const frutasRe = frutas.slice(2)
const frutasRe1 = frutas.slice(3)

frutas.splice(2,2,'Kiwi')
frutas.splice(2,3,'Pêssego')
console.log(frutas)

# Exercicio 4
const menuPrincipal = ['Pizza','Hamburguer','Macarronada','Lasanha','Prato feito']
const menuDeSobremesas = ['Torta Holandesa','Pudim','Brigadeiro', 'Bolo de Chocolate','Salada de Frutas']

const menuCompleto = menuPrincipal.concat(menuDeSobremesas)
console.log(menuCompleto) 
