# ⚡ electronic-charge

Projeto de uma **carga eletrônica programável** utilizando Arduino, com controle de corrente e simulação de carga variável para fontes de alimentação. Ideal para testes laboratoriais com componentes eletrônicos e simulações em software.

---

## 📌 Descrição

Este projeto implementa uma carga eletrônica controlada por microcontrolador, capaz de simular o consumo de corrente de forma controlada.  
A aplicação foi desenvolvida com:

- **Arduino UNO**
- **Simulação em Proteus 8.5**
- **IDE Arduino para programação em C++**

A lógica embarcada permite regular dinamicamente a carga de acordo com os parâmetros definidos no código.

---

## 🔧 Componentes e Ferramentas

- Arduino IDE (versão mais recente)
- Proteus 8.5 Professional
- MOSFET canal N (IRFZ44 ou similar)
- Resistor de potência (para carga real)
- Sensor de corrente (opcional)
- Fonte de alimentação de teste

---

## 🗂️ Arquivos do Projeto

- `carga-eletronica-FINALIZADO_arduino.ino` → Código fonte em C++ (Arduino)
- `carga eletronica.pdsprj.zip` → Projeto do Proteus para simulação

---

## 🚀 Como usar

1. Abra o arquivo `.ino` na **IDE do Arduino**
2. Carregue o código em um Arduino Uno
3. Conecte os componentes conforme o circuito simulado
4. Use o monitor serial ou entrada digital para alterar a corrente de carga
5. Simule o circuito no Proteus, se quiser testar antes de montar fisicamente

---
---

## 💡 Possíveis melhorias

- Interface LCD para ajuste de corrente
- Controle por potenciômetro ou encoder
- Medição em tempo real de tensão e corrente
- Limite de temperatura com sensor (NTC)
- Integração com ESP32 para controle via Web

---

## 👨‍💻 Autor

**Samuel Cristian dos Santos**  
📍 Divinópolis – MG  
📧 [samuelc.01dev@gmail.com](mailto:samuelc.01dev@gmail.com)  
🔗 [linkedin.com/in/samuel-cristian](https://linkedin.com/in/samuel-cristian)  
💻 [github.com/samuelc-01](https://github.com/samuelc-01)

---

## 📝 Licença

Este projeto está licenciado sob os termos da licença MIT.  
Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
