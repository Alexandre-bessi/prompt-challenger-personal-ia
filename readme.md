# 🏋️‍♂️ Assistente de Personal Trainer

## 📋 Índice

* [📝 Introdução](#-introdução)
* [💪 Biotipos Corporais](#-biotipos-corporais)
* [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
* [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
* [🏊‍♂️ Objetivos de treino](#-Objetivos-de-treino)
* [🛠️ Regras de negócio](#️-regras-de-negócio)
* [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. Ao decorrer da conversa com o chatbot, o usuário deverá inserir as seguintes informações:

* Biotipo corporal
* Dias disponiveis para treino
* Tipo de treino
* Objetivo de treino
* Implicações médicas

---

## 💪 Biotipos Corporais

O primeiro passo para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

O segundo passo é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Dias por Semana** | **Tipo de Treino Sugerido** |
| ------------------------- | --------------------------------- |
| 1 dia                     | Treino Full Body                  |
| 3 dias                    | Treino ABC                        |
| 3 dias ou mais           | Treino ABCDE                      |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

O terceiro passo envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Tipo de Treino** | **Descrição**                                                                                           |
| ------------------------ | --------------------------------------------------------------------------------------------------------------- |
| **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                 |
| **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                       |

---

## 🏊‍♂️ Objetivos de treino

O quarto e ultimo passo tem como objetivo definir qual é o objetivo principal dos treinos, assim como nos três exemplos:

| Objetivo              | Descrição                                                |
| --------------------- | ---------------------------------------------------------- |
| Emagrecer             | Reduz o percentual de gordura sem diminuir a massa magra   |
| Definir músculos     | Modelar o contorno de diversos grupos musculares visíveis |
| Ganhar massa corporal | Aumento do tamanho e volume dos músculos                  |

---

## 🛠️ Regras de negócio

1. Identifique seu **biotipo corporal** consultando a seção de biotipos.
2. Determine quantos **dias por semana** você pode treinar.
3. Selecione o **tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Defina qual o **objetivo principal** dos seus treinos.
5. Adapte seus treinos no caso de implicações médicas para **evitar lesões**.
6. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 🎯 Prompt de Resposta Proposto
- [Prompt para Personal Trainer com IA](https://github.com/Alexandre-bessi/prompt-challenger-personal-ia/blob/main/.github/prompt/prompt%20chatbot%20personal%20trainer.txt)
