# ☀️ Simulador de Economia com Energia Solar — Ecovoxx

Este projeto é um **simulador interativo** que calcula o potencial de economia e o tempo de retorno do investimento (payback) ao adotar **energia solar fotovoltaica**.  
O objetivo é **demonstrar de forma prática e baseada em dados reais** os benefícios econômicos e ambientais da geração distribuída de energia limpa.

---

## 🚀 Funcionalidades

- 💡 **Cálculo automático** da economia mensal e anual com base no consumo do usuário.  
- 💰 **Estimativa de payback** — tempo necessário para o investimento se pagar.  
- 🌎 **Seleção de região**, ajustando o fator de geração média (kWh/kWp/mês).  
- 🏡 **Campo opcional de custo do sistema**, com valores personalizados.  
- 📊 **Exibição clara dos resultados**: custo atual, economia, e geração esperada.  
- ✅ **Design responsivo**, moderno e otimizado para dispositivos móveis.  
- ⚙️ **Simulação em tempo real**, sem necessidade de conexão com servidor.

---

## 🧮 Fórmulas Utilizadas

As estimativas seguem médias baseadas em dados reais do setor solar brasileiro:

- **Geração mensal (kWh)** = `Potência do sistema (kWp) × Fator regional`
- **Custo atual (R$)** = `Consumo mensal × Tarifa de energia`
- **Conta com energia solar (R$)** = `(Consumo - Geração) × Tarifa`
- **Economia mensal (R$)** = `Custo atual - Conta com energia solar`
- **Payback (anos)** = `Custo do sistema / (Economia mensal × 12)`

> 🔍 Fatores regionais baseados na média de irradiação solar (Atlas Solarimétrico do Brasil – EPE, 2023):
> - Nordeste: **155 kWh/kWp/mês**  
> - Sudeste: **130 kWh/kWp/mês**  
> - Sul: **120 kWh/kWp/mês**

---

## 🧠 Indicadores e Evidências Reais

Os cálculos se baseiam em dados públicos e estudos técnicos:

| Indicador | Fonte | Valor Médio |
|------------|--------|-------------|
| Custo médio do sistema residencial (2025) | ABSOLAR / Portal Solar | R$ 4.500 por kWp |
| Redução média da conta de energia | ANEEL | 80% a 95% |
| Vida útil dos painéis | Inmetro / EPE | 25 anos |
| Tempo médio de payback no Brasil | ABSOLAR | 3,5 a 6 anos |
| Valorização média do imóvel com energia solar | FIPE / Lopes Consultoria | +15% a +20% |

---

## 🧩 Tecnologias Utilizadas

- **HTML5** — estrutura do simulador  
- **CSS3 (vanilla)** — layout responsivo e tema sustentável  
- **JavaScript (puro)** — lógica de cálculo e manipulação do DOM   

---

## 👨‍💻 Equipe de Desenvolvimento

| Nome Completo | Função / Participação |
|----------------|-----------------------|
| **CÁSSIO CORDEIRO DO PRADO** | Desenvolvimento e análise técnica |
| **ELAINE REGINA GREGÓRIO SANTOS** | Pesquisa e sustentabilidade |
| **LUCAS EIJI DE MORAES YNADA** | Cálculos e modelagem de dados |
| **LUCAS SANTANA BRATEFICHE CORRÊA** | Front-end, design e integração |
| **PEDRO HENRIQUE ADÃO TORRES** | Planejamento e testes de usabilidade |

---

## 🌱 Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/bratefiche/Calculadora-de-economia-com-energia-solar.git

   ou

   acesso o repositorio e faça download do arquivo, ao abrir vai funcionar automaticamente.
