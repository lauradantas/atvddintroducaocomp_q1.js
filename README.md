const nomes = ["Ana", "João", "Maria", "Pedro", "Carla"];

console.log("=== Lista de Nomes ===");
nomes.forEach((nome, index) => {
    console.log(`${index + 1}. ${nome}`);
});