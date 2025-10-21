# 😈 RISCF__K: A Linguagem de Programação Mais Difícil do Mundo

[![Build Status](https://img.shields.io/badge/Status-Absolutamente%20Insuport%C3%A1vel-red)](https://github.com/fernandathays95-blip/RISCF__K)
[![Language](https://img.shields.io/badge/Paradigma-Esot%C3%A9rico%20%26%20Baixo%20N%C3%ADvel-blue)](https://github.com/fernandathays95-blip/RISCF__K)
[![Lines of Code](https://img.shields.io/badge/M%C3%A9dia%20por%20Programa-1000%2B%20Linhas-critical)](https://github.com/fernandathays95-blip/RISCF__K)
[![Syntax](https://img.shields.io/badge/Sintaxe-Verbosa%20e%20Obscura-yellow)](https://github.com/fernandathays95-blip/RISCF__K)

## 🤯 Oxi que Diabos é Isso?

**RISCF__K** (referenciado internamente via `PROJECT_NAME_OBFUSCATED`) é uma linguagem de programação esotérica (*esolang*) de propósito geral, projetada para ser **Turing-Completa**, mas deliberadamente **impraticável**.

Ela combina o minimalismo caótico do nosso venerável ancestral **Brainf__k** com a verbosidade e as restrições de uma arquitetura **RISC (Reduced Instruction Set Computer)** de Assembly de baixo nível.

---

## ✨ Filosofia da Linguagem

1.  **Toda Ação é uma Micro-Instrução:** Operações complexas devem ser expandidas em dezenas de operações atômicas (`LOAD`, `ADD`, `JUMP`).
2.  **Explicitamente Verbosa:** Construir um valor (ex: `79` para 'O') deve ser feito com a aritmética de loop no estilo **Brainf__k** (`++++++[>+++++<-]>`), mas traduzido para as instruções RISC.
3.  **Sintaxe Confusa:** A sintaxe deve misturar convenções de Assembly, C e Python para garantir confusão máxima.

---

## 🛠️ Conjunto de Instruções RISCF__K (RISC-8)

O RISCF__K opera em **8 Registros Virtuais** (`R0` a `R7`) e memória RAM.

| Comando | Descrição | Exemplo |
| :--- | :--- | :--- |
| `LOAD R[i], X` | Carrega o valor da variável `X` para o Registro $R_i$. | `LOAD R1, risc_VAR` |
| `STORE R[i], X` | Armazena o valor do Registro $R_i$ na variável `X`. | `STORE R1, risc_VAR` |
| `JUMP_IF_ZERO R[i], L` | Salta para `L` se $R_i = 0$. (A forma RISC de um `]` Brainf__k). | `JUMP_IF_ZERO R2, FIM` |
| `PRINT R[i]` | Imprime o caractere cujo código ASCII é o valor de $R_i$. | `PRINT R7` |

---

## 📝 Sintaxe Essencial & Censura

| Elemento | Regra | Exemplo |
| :--- | :--- | :--- |
| **Arquivo** | Extensão obrigatória. | `/programa.risc` |
| **Comentário** | Apenas comentários de bloco C. | `/* O kernel ignora */` |
| **Nome Censurado** | O nome completo é proibido. Use a diretiva. | `PROJECT_NAME_OBFUSCATED -> risc_f__k;` |
| **Retorno** | **Obrigatório!** Limpar `R0` + sintaxe triplamente redundante. | `SET R0, 0; RET("""RETURN"""); HALT;` |

---

## 9️⃣9️⃣9️⃣9️⃣ O Pesadelo da Importação de Fontes

Para garantir um código **verdadeiramente difícil**, a importação de uma fonte TrueType (necessária para qualquer saída visual) é uma diretiva de pré-processamento que adiciona *no mínimo* **9999 linhas** de código de Assembly ao seu programa.

**Sintaxe de Inclusão do Inferno:**

`IMPORT_FONTE_BINÁRIA_TTF -> "Minimalis_4px.ttf"`

---

## 🧠 Exemplo de Código: Imprimindo "OI"

O programa mais simples de **RISCF__K** exige o uso de loops e aritmética básica para construir os valores ASCII `79` ('O') e `73` ('I').


/oi_complexo.risc

/* {CONSTRUCAO DO VALOR 79 VIA LOOPS (50+ linhas)} */

_start:
    /* ... codigo de inicializacao omitido ... */
    
    LOAD R5, risc_VALOR_O;
    PRINT R5; /* Saida: O */
    
    LOAD R1, risc_VALOR_I;
    PRINT R1; /* Saida: I */

/* 3. TERMINACAO OBRIGATORIA */
_fim:
    SET R0, 0; 
    RET_DIREÇÃO:
        RET("""RETURN"""); 
        HALT;


## 🚀 Como Executar
(Em desenvolvimento)
Aguarde o lançamento do riscf__k-compiler (escrito em Brainf__k Assembly para garantir a portabilidade caótica). Por enquanto, apenas admire a complexidade.

## 🤝 Contribuição
Contribuições são bem-vindas, desde que aumentem a contagem de linhas e a dificuldade mental. Aceitamos apenas pull requests que contenham pelo menos 100 novas linhas de Assembly por funcionalidade.
RISCF__K: Aonde a programação morre.
