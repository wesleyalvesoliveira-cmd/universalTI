# 🚀 Universal TI - Formulário de Inscrição para Estágio

Este é um projeto front-end de um formulário de cadastro dinâmico e altamente acessível, desenvolvido para o processo seletivo de Estágio em Engenharia de Software da **Universal TI**. 

O projeto foi construído utilizando tecnologias puras (Vanilla Web Stack) com foco em uma experiência de usuário (UX) fluida, validações robustas em tempo real e total aderência às práticas de acessibilidade (a11y).

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica e aplicação de atributos de acessibilidade ARIA.
* **CSS3:** Layout moderno estilo *split-screen* (tela dividida), totalmente responsivo e com paleta de cores institucional (tons de azul e branco).
* **JavaScript (Vanilla JS):** Lógica de validação em tempo real, manipulação de DOM e controle de estado do formulário.

---

## ✨ Funcionalidades Principais

* **Validação em Tempo Real:** O sistema analisa a entrada do usuário campo a campo à medida que ele digita, sem a necessidade de clicar em enviar para descobrir erros.
* **Feedback Visual Instantâneo:** Modificação dinâmica das bordas e fundos dos inputs (Verde para sucesso / Vermelho para erro) com mensagens claras logo abaixo do campo.
* **Acessibilidade Garantida (a11y):** Uso de atributos como `aria-live="polite"` e `aria-invalid` para garantir que leitores de tela notifiquem usuários com deficiência visual sobre os erros em tempo real.
* **Prevenção de Envio (Botão Inteligente):** O botão de submissão inicia desabilitado (`disabled`) e só é liberado quando todos os critérios de validação forem 100% satisfeitos. Há também uma trava de segurança no evento `submit`.

---

## 📦 Como Executar o Projeto

Para testar o projeto localmente, siga os passos abaixo no seu prompt de comando:

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/nome-do-seu-repositorio.git](https://github.com/seu-usuario/nome-do-seu-repositorio.git)