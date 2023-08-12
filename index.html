<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Calculadora de Abastecimento</title>
<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        display: flex;
        justify-content: center;
        align-items: center;
        min-height: 100vh;
        background-color: #f0f0f0;
    }
    .container {
        background-color: #ffffff;
        padding: 20px;
        border-radius: 10px;
        box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        max-width: 400px;
        width: 100%;
    }
    h1 {
        text-align: center;
    }
    label, input {
        display: block;
        margin-bottom: 10px;
    }
    button {
        background-color: #007bff;
        color: #ffffff;
        border: none;
        padding: 10px 20px;
        border-radius: 5px;
        cursor: pointer;
        width: 100%;
    }
    button:hover {
        background-color: #0056b3;
    }
    table {
        margin-top: 20px;
        width: 100%;
        border-collapse: collapse;
    }
    th, td {
        border: 1px solid #ddd;
        padding: 8px;
        text-align: left;
    }
    th {
        background-color: #f2f2f2;
    }
</style>
<script>
function calcularAbastecimento() {
    var capacidadeMaxima = parseFloat(document.getElementById("capacidadeMaxima").value);
    var kmParaAcabar = parseFloat(document.getElementById("kmParaAcabar").value);
    var consumoKmPorLitro = parseFloat(document.getElementById("consumoKmPorLitro").value);
    var percentEtanolGasolina = parseFloat(document.getElementById("percentEtanolGasolina").value);
    var teorAguaEtanol = parseFloat(document.getElementById("teorAguaEtanol").value);
    
    if (isNaN(kmParaAcabar) || isNaN(consumoKmPorLitro)) {
        alert("Por favor, preencha os campos 'KM para Acabar o Tanque' e 'Consumo de Combustível (km/l)'");
        return;
    }
    
    var combustivelNoTanque = (kmParaAcabar / consumoKmPorLitro);
    var combustivelACompletar = capacidadeMaxima - combustivelNoTanque;
    
    var percentEtanol = percentEtanolGasolina;
    var percentGasolina = 100 - percentEtanolGasolina;
    
    var litrosEtanol = (combustivelACompletar * percentEtanol) / 100;
    var litrosGasolina = (combustivelACompletar * percentGasolina) / 100;
    
    // Considerando o teor de água no etanol
    var litrosAguaEtanol = litrosEtanol * (teorAguaEtanol / 100);
    litrosEtanol -= litrosAguaEtanol;

    var tabelaResultado = document.getElementById("tabelaResultado");
    tabelaResultado.innerHTML = `
        <tr>
            <th>Combustível restante no tanque:</th>
            <td>${combustivelNoTanque.toFixed(2)} litros</td>
        </tr>
        <tr>
            <th>Abasteça com Etanol:</th>
            <td>${litrosEtanol.toFixed(2)} litros</td>
        </tr>
        <tr>
            <th>Abasteça com Gasolina:</th>
            <td>${litrosGasolina.toFixed(2)} litros</td>
        </tr>
    `;
}
</script>
</head>
<body>
<div class="container">
    <h1>Calculadora de Abastecimento</h1>
    <label for="percentEtanolGasolina">% de mistura Etanol-Gasolina:</label>
    <input type="number" id="percentEtanolGasolina" value="85">
    <label for="teorAguaEtanol">Teor de água no etanol (%):</label>
    <input type="number" id="teorAguaEtanol" value="5">
    <label for="kmParaAcabar">KM para Acabar o Tanque:</label>
    <input type="number" id="kmParaAcabar">
    <label for="consumoKmPorLitro">Consumo de Combustível (km/l):</label>
    <input type="number" id="consumoKmPorLitro">
    <label for="capacidadeMaxima">Capacidade Máxima do Tanque (litros):</label>
    <input type="number" id="capacidadeMaxima" value="60">
    <button onclick="calcularAbastecimento()">Calcular</button>
    <table id="tabelaResultado"></table>
</div>
</body>
</html>
