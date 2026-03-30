# 🐾 Capivaras de Wall Street

> **Domine o mercado. Multiplique sua herança. Vire lenda em 5 anos.**

Um jogo de RPG financeiro no estilo visual novel, com estética pixel art e capivaras investidoras. Tome decisões de investimento, enfrente eventos aleatórios do mercado e veja seu patrimônio crescer — ou desabar.

---

## 🎮 Como Jogar

O jogo roda diretamente no navegador. Basta abrir o arquivo `capyfinance_rpg.html` — sem instalação, sem dependências.

**Acesso online:** basta hospedar o arquivo em qualquer serviço de hospedagem estática (veja a seção [Deploy](#-deploy)).

---

## 🐱‍💼 Personagens

Escolha sua capivara antes de começar. Cada uma tem atributos que influenciam diretamente o mercado:

| Personagem | INT | Sorte | ESP | Bônus Especial |
|---|---|---|---|---|
| Filho de Economista | 20 | 10 | 10 | Previsões mais precisas |
| Ex-Trader | 10 | 10 | 20 | Reações rápidas ao mercado |
| Empreendedor | 15 | 10 | 15 | Atributos equilibrados |
| Sortudo | 5 | 25 | 10 | Mais eventos positivos |
| Herdeiro Conectado | 10 | 15 | 10 | Capital inicial maior (+R$5.000) |

- **Inteligência** aumenta a chance de as ações subirem
- **Sorte** aumenta a probabilidade de eventos positivos
- **Esperteza** melhora reações a movimentos do mercado

---

## 📈 Ações Disponíveis

| Ação | Setor | Preço Inicial | Volatilidade |
|---|---|---|---|
| AgroCapy | Agro | R$ 50,00 | Média (12%) |
| TechVara | Tech | R$ 150,00 | Alta (30%) |
| BankVara | Banco | R$ 100,00 | Baixa (8%) |
| EnergyCapy | Energia | R$ 80,00 | Baixa (10%) |
| RetailVara | Varejo | R$ 30,00 | Alta (20%) |

> Ações de alta volatilidade podem trazer ganhos expressivos — ou perdas igualmente expressivas.

---

## ⚙️ Mecânicas

### Investimento
- Compre e venda cotas em blocos de **R$ 100**
- Suas cotas ficam registradas em **quantidade fracionada** (ex: 0.667 cotas de TechVara)
- O valor da carteira é atualizado em tempo real conforme os preços mudam

### Passagem do Tempo
A cada rodada, escolha avançar:
- **+2 meses** — movimento pequeno, menos risco
- **+5 meses** — ritmo moderado
- **+9 meses** — avanço rápido, maior exposição a eventos

Cada mês simula uma variação de preço para todas as ações com base nos seus atributos.

### Eventos Aleatórios
A cada avanço de tempo, há **30% de chance** de um evento de mercado ocorrer:

**Eventos positivos:**
- Bônus Agrícola → AgroCapy sobe 30%
- Dividendos Tech → +R$ 1.200 no capital
- Mercado Otimista → Todas as ações sobem 10%
- Fusão Bancária → BankVara sobe 20%

**Eventos negativos:**
- Crise Energética → EnergyCapy cai 30%
- Multa Ambiental → -R$ 1.500 no capital
- Bolha Estourou → TechVara cai 40%
- Escândalo Varejo → RetailVara cai 35%

> O personagem **Sortudo** tem maior probabilidade de atrair eventos positivos.

### Relatório Final
Após 5 anos (60 meses), o jogo calcula:
- **Montante final** (capital + valor da carteira)
- **Lucro ou prejuízo** total
- **Taxa de juros simples equivalente** ao crescimento (% a.a.)
- **Taxa de juros compostos equivalente** ao crescimento (% a.a.)

---

## 🖥️ Interface

- **HUD superior:** capital em caixa, valor da carteira, total e período atual
- **Lista de ações:** preço atual, variação percentual, cotas possuídas, botões de compra/venda
- **Sidebar:** personagem ativo, botões de avanço de tempo, mini-gráfico do patrimônio
- **Gráfico completo:** evolução do patrimônio ao longo de toda a jornada
- **Modal de evento:** interrupção dramática com a capivara reagindo ao evento

**Atalhos de teclado:**
- `←` / `→` — navegar entre personagens na seleção
- `Enter` — confirmar seleção / avançar

---

## 🛠️ Tecnologias

- **HTML5 / CSS3 / JavaScript** puro — sem frameworks, sem dependências
- **Canvas API** para os gráficos de patrimônio
- **Google Fonts** (Press Start 2P) para a tipografia pixel art

---

## 🎨 Assets Visuais

Todos os sprites são pixel art originais:

- 5 capivaras personagens com expressões únicas
- 5 distintivos de antecedente
- Background de floresta noturna animado
- Arcade machine pixel art
- Coração pixel art para UI

---

## 📜 Licença

Projeto educacional de código aberto. Sinta-se livre para estudar, modificar e redistribuir.

---

*Feito por Evelyn Chiaperini, Ihago Nunes, Ihan Nunes e Maria Eduarda Ortega. 🐾*