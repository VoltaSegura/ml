# ml — entrega da disciplina Inteligência Artificial & Machine Learning (VoltaSegura)

> 🗂 **Ficha da CitizenTech** — resumo do produto **VoltaSegura** (ex-"CitizenTech"; renomeado em 10/11/2026):
> cidade São Paulo; cidadão = estudante universitário do período noturno;
> problema = falta de visão integrada das condições urbanas que influenciam a percepção de segurança no deslocamento;
> como funciona = comparação de alternativas de ida/volta com exposição estimada e confiança dos dados;
> ODS = 11 e 10. Ficha completa: monorepo **https://github.com/VoltaSegura/voltasegura**.
> ⚠️ O produto não garante segurança e não classifica bairros — comunicar apenas exposição estimada e confiança dos dados (=`docs`/04).

**Monorepo central (fonte da verdade)**: https://github.com/VoltaSegura/voltasegura

# VoltaSegura — IA & Machine Learning

Estudo de ML sobre o problema do VoltaSegura, com **dados reais e públicos** (não simulados — requisito da disciplina).

> ⚠️ Em construção. Ciclo completo: dados → modelo (XGBoost, Random Forest, MLP, LSTM ou KMeans+PCA) → treino/avaliação (≥10 combinações de hiperparâmetros, validação cruzada só no treino) → conclusão para o cidadão. Ver [`docs/02_entregas_disciplinas.md`](../../docs/02_entregas_disciplinas.md).

## Estrutura exigida

- `notebook` executado nesta pasta;
- `dados/README.md` com fonte, link e período de cada conjunto de dados;
- `requirements.txt`;
- `RELATORIO_ML.md` (2–4 páginas).

## Candidatos a pergunta de ML `[HIPÓTESE]`

- Padrões de ocorrências por distrito/horário (SSP-SP, Infosiga SP, SP156, IBGE) para classificar nascentes de dados insuficientes vs. consistentes — **sem rótulos absolutos de segurança**.
