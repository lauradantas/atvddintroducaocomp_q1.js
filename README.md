const nomes = ["Anny", "Levi", "Mary", "Analua", "Tiana"];
console.log("== NOMES ==");
nomes.forEach(function(nome, index) {
    console.log(`${index + 1}. ${nome}`);
});
console.log("\n== NOMES ==");
nomes.forEach((nome, index) => {
    console.log(`Posição ${index}: ${nome}`);
});
