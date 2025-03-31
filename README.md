🎰 Sorteadores de Números: Mega Sena e Quina com React Hooks Projeto desenvolvido para a disciplina de Front-End Avançado

Este projeto implementa dois simuladores de sorteio numérico usando React Hooks, reproduzindo os mecanismos dos jogos da Mega Sena e Quina brasileiros.

Tecnologias Utilizadas React (Componentes funcionais)

React Hooks (useState para gerenciamento de estado)

JavaScript

🎯 Componentes Principais

App.jsx - Componente Raiz Função: Orquestra a renderização dos dois componentes de sorteio.

HookMegasena.js - Sorteio da Mega Sena HookQuina.js - Sorteio da Quina


![aula2](https://github.com/user-attachments/assets/04968eab-b435-40ed-9cbc-50a35319de4a)

🔍 Funcionalidades Principais Componente Intervalo Numérico Quantidade Lógica de Sorteio Mega Sena 1-60 6 números Math.floor(Math.random() * 60) + 1 Quina 1-80 5 números Math.floor(Math.random() * 80) + 1

📌 Próximas Melhorias Adicionar botão para reiniciar sorteios

Implementar verificação de números repetidos

Adicionar animações durante o sorteio

Melhorar a interface com CSS

Adicionar responsividade para mobile
