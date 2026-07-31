# 🧑‍⚕️ Prova – Monitoramento de Saúde com Cálculo de IMC  

Este projeto é uma **atividade prática de Python** 🎯.  
A missão é simples: vamos criar um programa que **calcula o IMC (Índice de Massa Corporal)** e mostra uma mensagem sobre a condição de saúde da pessoa.  

Tudo isso direto no terminal, sem bibliotecas externas. 🚀  

---

## 📌 Objetivo
- Ler o **peso (kg)** e a **altura (m)** do usuário.  
- Calcular o **IMC** usando a fórmula:  

```python
IMC = peso / (altura ** 2)
```

- Mostrar o valor do IMC (com **duas casas decimais**).  
- Exibir uma **mensagem de orientação** sobre a condição de saúde.  

---

## 🛠️ Como funciona
👉 O programa pede **peso** e depois **altura** (nessa ordem).  
👉 Ele calcula o IMC e mostra:  
- O valor formatado.  
- A mensagem correspondente à faixa de saúde.  

---

## 🥉 Versão mínima
Regras bem simples:  

- Se o **IMC ≥ 30.0** → mostrar: **Cuidado com a Saúde** ⚠️  
- Caso contrário → mostrar: **Tudo ok** ✅  

📌 Exemplo:  
```
IMC: 31.22
Cuidado com a Saúde
```

```
IMC: 24.85
Tudo ok
```

---

## 🥇 Versão completa
Aqui entram as faixas detalhadas de classificação do IMC:  

| Faixa de IMC         | Mensagem exibida 📝                |
|-----------------------|------------------------------------|
| Menor que 18.5        | Abaixo do peso ⚖️                 |
| Menor que 24.9        | Peso normal 💪                     |
| Menor que 29.9        | Sobrepeso 🍔                      |
| Menor que 34.9        | Obesidade Grau I 🟠               |
| Menor que 39.9        | Obesidade Grau II 🔴              |
| Maior ou igual a 40.0 | Obesidade Grau III (mórbida) 🚨   |

📌 Exemplo:  
```
IMC: 22.37
Peso normal
```

---

## 🧪 Casos de teste (para treinar)
Tente rodar o programa com esses valores:

| Peso (kg) | Altura (m) | IMC calculado | Resultado esperado |
|-----------|------------|---------------|--------------------|
| 60        | 1.70       | 20.76         | Peso normal 💪     |
| 85        | 1.70       | 29.41         | Sobrepeso 🍔       |
| 95        | 1.60       | 37.11         | Obesidade Grau II 🔴 |
| 92        | 1.70       | 31.83         | Obesidade Grau I 🟠     |
| 110       | 1.70       | 38.06         | Obesidade Grau II 🔴 |
| 120       | 1.60       | 46.87         | Cuidado com a Saúde ⚠️ |

---

## 📂 Regras da prova
- O arquivo deve ter o nome **`prova_imc.py`**.  
- O programa deve rodar direto no terminal.  
- Nada de bibliotecas externas.  
- Use `print(f"IMC: {imc:.2f}")` para formatar direitinho.  

---

## ✨ Dica final
Use **`if` e `elif`** na ordem correta (do menor para o maior limite).  
Mantenha variáveis com **nomes claros** e **comentários curtos** para deixar o código organizado.  

Boa sorte e bora codar! 🚀🐍  
