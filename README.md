# Rosangela Furtado · QA

> A tela diz “pagamento falhou”. O banco mostra uma cobrança. E agora?

É esse tipo de desencontro que me interessa em qualidade de software. Quem está comprando precisa saber se pode tentar de novo. Para responder, eu olharia o que a tela informou, o que ficou registrado no pedido e quantas cobranças foram geradas.

Aqui compartilho meus projetos de QA e os cenários de teste por trás deles.

<details>
<summary><strong>Como eu testaria esse checkout?</strong></summary>

Imagine que o pagamento foi aprovado, mas a conexão caiu antes de a confirmação chegar à tela.

| Ação de quem compra | O que eu verificaria |
| --- | --- |
| Tocar em **Pagar** de novo | Se a nova tentativa mantém um único pedido e uma única cobrança. |
| Fechar a página e voltar pelo histórico | Se dá para encontrar o pedido e descobrir o estado do pagamento. |
| Aguardar a confirmação | Se a tela reflete o resultado e indica o próximo passo enquanto há dúvida. |

Para investigar uma divergência, eu reuniria o identificador do pedido, os horários das tentativas e os estados exibidos em cada etapa. Com essa sequência, outra pessoa consegue reconstruir o que aconteceu.

</details>

[Explorar meus repositórios →](https://github.com/rosangela-furtado?tab=repositories)
