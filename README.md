jurjurjur


const perro {
    nombre. "spike",
    numero de patas: 4,
    tiene Rabo: true,
    collar: {
        etiqueta: "Spike",
        chip:true
    },
    amigos: [
        "Pogo",
        "lala",
    ],
    calcularNumerodePatas: sumar
}

function sumar (valor1,valor2){
    return valor1+valor2
}

const a = ""
const b = false
const c = 0 
const d = a || b || c
const e = a && b && C 
console.log( d ) // saldría 0, que es el último valor. Si hubiera uno de lso valores que fuera truthy (verdadero), d adoptaría ese valor
console.log(a) // ?? 
