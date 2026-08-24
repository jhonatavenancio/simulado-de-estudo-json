# 📚 Simulado VENA

Plataforma web para criar e realizar simulados personalizados a partir de arquivos JSON.

🔗 **Acesse:** https://simuladovena.netlify.app/

## ✨ Funcionalidades

* 📝 Questões exibidas uma por vez
* 🔄 Navegação entre questões
* ⏱️ Cronômetro de estudo com pausa
* 📊 Resultado geral e por matéria
* 🔍 Revisão das respostas e gabarito
* 🌙 Tema claro e escuro
* 📱 Interface responsiva para desktop, tablet e mobile
* 💾 Preferência de tema salva no navegador
* 🚫 Sem login e sem publicidade

  
<img width="1910" height="958" alt="image" src="https://github.com/user-attachments/assets/cedebb76-badd-4fcc-bd43-a640411a724c" />

<img width="1910" height="958" alt="image" src="https://github.com/user-attachments/assets/c2a368b8-3961-4f88-a316-42ab1bed43f2" />

<img width="1910" height="958" alt="image" src="https://github.com/user-attachments/assets/8191c11a-37ca-45ae-8b1b-3921628efa83" />

<img width="1910" height="958" alt="image" src="https://github.com/user-attachments/assets/ab3e4da5-5c49-48f8-b51a-93234624eaff" />





## 🚀 Como usar

### 1. Prepare as questões

Crie um arquivo `.json` seguindo este formato:

```json
[
  {
    "indice": 0,
    "materia": "Direito Constitucional",
    "pergunta": "Qual artigo da Constituição trata da liberdade de expressão?",
    "opcoes": {
      "A": "Artigo 1º",
      "B": "Artigo 5º",
      "C": "Artigo 10º",
      "D": "Artigo 20º"
    },
    "gabarito": "B"
  }
]
```

### 2. Carregue o JSON

Na tela inicial, você pode:

* Colar o JSON diretamente no campo de texto; ou
* Fazer upload de um arquivo `.json`.

### 3. Faça o simulado

Clique em **INICIAR SIMULADO** e responda às questões.

### 4. Confira o resultado

Ao finalizar, você verá:

* Percentual de acertos
* Acertos, erros e questões não respondidas
* Tempo total
* Desempenho por matéria

Também é possível revisar cada questão e comparar sua resposta com o gabarito.

## 📝 Formato do JSON

| Campo      | Tipo   | Descrição                       |
| ---------- | ------ | ------------------------------- |
| `indice`   | number | Índice da questão               |
| `materia`  | string | Disciplina da questão           |
| `pergunta` | string | Enunciado                       |
| `opcoes`   | object | Alternativas (`A`, `B`, `C`...) |
| `gabarito` | string | Letra da resposta correta       |

### Observações

* É possível usar qualquer quantidade de alternativas.
* Alternativas vazias não são exibidas.
* As matérias são identificadas automaticamente.

## 🛠️ Tecnologias

* HTML5
* CSS3
* JavaScript Vanilla
* LocalStorage

## 🎯 Uso

O Simulado VENA pode ser usado para:

* Preparação para concursos
* Estudos acadêmicos
* Revisão de conteúdo
* Autoavaliação
* Treino para provas
* Grupos de estudo

## 📌 Características

* Gratuito
* Sem cadastro
* Sem publicidade
* Os dados ficam no navegador
* Responsivo
* Pode funcionar offline após o carregamento

## 🌐 Acesse

**https://simuladovena.netlify.app/**

---

Feito para tornar a prática de questões mais simples e acessível. 📚
