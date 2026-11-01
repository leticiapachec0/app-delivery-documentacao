# App de Delivery

## O que é
Aplicativo para pedidos de lanches de uma lanchonete de bairro, com acompanhamento de entrega.

Atores: cliente, administrador e entregador.

Principais funções:
- Cliente faz pedidos e acompanha a entrega
- Administrador gerencia o cardápio e notifica o cliente quando o pedido sai para entrega
- Entregador marca o pedido como entregue

## Como rodar
1. Clone o repositório:
   ```bash
   git clone https://github.com/leticiapachec0/app-delivery-documentacao.git
   ```
2. Instale as dependências do projeto
3. Configure as variáveis de ambiente, como a chave do gateway de pagamento, a chave da API de mapas e os dados do banco
4. Execute o projeto
5. Para rodar os testes, use o comando de testes do projeto

## Estrutura
```
/src     código-fonte do app
/tests   testes unitários, de integração e de aceitação
/docs    documentação: requisitos, diagramas UML e decisões de arquitetura
```

## Como contribuir
1. Crie um branch para a sua tarefa, por exemplo feature/avaliar-entregador
2. Faça commits pequenos, com mensagens claras
3. Rode os testes antes de enviar
4. Atualize a documentação no mesmo commit se o código mudou
5. Abra um pull request para revisão dos colegas antes do merge
