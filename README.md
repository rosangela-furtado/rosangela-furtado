

# 👋 Oi, eu sou a Rosangela Furtado!

- 🔎 Trabalho com qualidade de software, de testes exploratórios à automação com Playwright e Selenium.
- 🧪 Gosto de testar o que acontece entre um clique e a confirmação que chega para quem usa o produto.
- 📍 Curitiba, PR · Aqui compartilho projetos de QA e os cenários por trás deles.

### Na minha bancada de testes

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/playwright/playwright-original.svg" height="38" alt="Playwright"> &nbsp; <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/selenium/selenium-original.svg" height="38" alt="Selenium"> &nbsp; <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg" height="38" alt="Java"> &nbsp; <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/groovy/groovy-original.svg" height="38" alt="Groovy"> &nbsp; <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" height="38" alt="Git"> &nbsp; <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/jenkins/jenkins-original.svg" height="38" alt="Jenkins">

Playwright · Selenium WebDriver · Java · Groovy · Git · Jenkins

[![Ver projetos de QA](https://img.shields.io/badge/Ver_projetos-542E91?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rosangela-furtado?tab=repositories) [![Abrir currículo interativo](https://img.shields.io/badge/Curr%C3%ADculo_interativo-08785B?style=for-the-badge)](https://curriculorosangelafurtado.netlify.app/)

<details>
<summary><strong>🧩 O pagamento falhou na tela, mas o banco cobrou. Como eu testaria?</strong></summary>

Imagine que o pagamento foi aprovado, mas a conexão caiu antes de a confirmação chegar à tela.

| Ação de quem compra | O que eu verificaria |
| --- | --- |
| Tocar em **Pagar** de novo | Se a nova tentativa mantém um único pedido e uma única cobrança. |
| Fechar a página e voltar pelo histórico | Se dá para encontrar o pedido e descobrir o estado do pagamento. |
| Aguardar a confirmação | Se a tela reflete o resultado e indica o próximo passo enquanto há dúvida. |

Para investigar uma divergência, eu reuniria o identificador do pedido, os horários das tentativas e os estados exibidos em cada etapa. Com essa sequência, outra pessoa consegue reconstruir o que aconteceu.

</details>
