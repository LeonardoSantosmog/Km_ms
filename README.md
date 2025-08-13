# 🏎️ Conversor de Velocidade

Este é um simples programa em Python que converte valores de **quilômetros por hora (km/h)** para **metros por segundo (m/s)**.

## 📜 Como funciona
O programa:
1. Solicita ao usuário um valor de velocidade em km/h.
2. Converte para m/s usando a fórmula: `m/s = km/h ÷ 3.6`.
3. Exibe o resultado formatado.

## 📂 Código
```python
vel_km = float(input("Digite a distância em km/h: "))
vel_ms = vel_km / 3.6

print(f"A velocidade de {vel_km:.2f} km/h é equivalente a {vel_ms:.2f} m/s")
