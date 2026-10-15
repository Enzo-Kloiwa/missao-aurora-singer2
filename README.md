# missao-aurora-singer2

# 🚀 Aurora Singer | MGPEB

**Módulo de Gerenciamento de Pouso e Estabilização de Base**
Fase 2 | Ciência da Computação, FIAP | Grupo 18

## 📌 Sobre o projeto
Simulação em Python de um controle de missão que organiza o pouso de
7 módulos em Marte. O sistema avalia regras de segurança e decide se cada
módulo deve **autorizar, restringir, adiar ou bloquear** o pouso.

> ⚠️ Projeto acadêmico. Os valores (vento, combustível, sensores) são
> hipóteses didáticas, não dados reais de missão.

## 🧠 O que o projeto demonstra
- **Estruturas de dados lineares, feitas à mão:** lista encadeada, fila de
  prioridade, fila (FIFO) e pilha (LIFO)
- **14 regras de segurança + 1 meta-regra** (R01 a R14 e M01)
- **Busca sequencial** e **ordenação por inserção**
- **Modelo matemático** da descida: h(t) = 1000 − 20t
- **Lógica booleana** com circuitos de portas AND, OR e NOT

## ▶️ Como executar
Não precisa instalar nada, só ter o Python 3.

```bash
python MGPEB.py
```
(No Windows, use `py MGPEB.py`.)

## 📊 Resultado esperado
1. Primeira rodada: 5 módulos pousam; a Logística é bloqueada por
   combustível e o Rover por massa
2. Após as correções simuladas: **os 7 módulos pousam**

## 🗂️ Estrutura dos arquivos
| Arquivo | Função |
|---|---|
| `MGPEB.py` | Código principal da simulação |
| `docs/Relatorio_MGPEB.pdf` | Relatório completo |

## 👥 Integrantes
| Nome | RM |
|---|---|
| Enzo Yugi Kloiwa | 574398 |
| Guilherme de Souza Santos | 574908 |
| Luke Malaquias Lage | 574356 |
| Rafaela Aparecida dos Santos Atanásio | 574868 |
| Yasmin Sampaio Barbieri | 576282 |

## 🛠️ Tecnologias
Python 3 (apenas biblioteca padrão: `dataclasses`, `datetime`, `enum`)
