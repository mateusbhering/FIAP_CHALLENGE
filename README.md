# FIAP Challenge - Loja Swift

Este projeto é uma aplicação web desenvolvida como parte do desafio da FIAP. Ele simula uma loja online com funcionalidades como seleção de produtos, cálculo de frete,e também a escolha de forma de pagamento e entrega.

## Link do Protótipo

[Protótipo no Figma](https://www.figma.com/design/0MF1DXyRlSwWSm3TCCPF09/Untitled?node-id=0-1&t=LO3687aUNmXaOdgG-1)

## Como rodar o projeto localmente

### Pré-requisitos

Antes de começar, certifique-se de ter os seguintes itens instalados em sua máquina:

- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) (extensão do VS Code)
- Um navegador web moderno (Google Chrome, Firefox, etc.)

### Passos

1. Abra o projeto no VS Code.
2. Clique com o botão direito no arquivo `login.html` localizado na pasta `paginas`.
3. Selecione a opção **"Open with Live Server"**.
4. O navegador será aberto automaticamente com o endereço local, geralmente algo como:

```
http://127.0.0.1:5500/paginas/login.html
```

5. Navegue pelas páginas e teste as funcionalidades.

## Funções presentes no app

### Funções de Carrinho

- **`addToCart(name, price, image)`**: Adiciona um produto ao carrinho.
- **`refreshProductsList()`**: Atualiza a lista de produtos selecionados no carrinho.
- **`updateCart()`**: Atualiza os itens e o total do carrinho.

### Funções de Pagamento

- **`selectPaymentMethod(method)`**: Seleciona a forma de pagamento (cartão, boleto ou PIX).
- **`updateSummary()`**: Atualiza o resumo do pedido com os dados de pagamento.

### Funções de Entrega

- **`selectDeliveryMethod(method)`**: Seleciona a modalidade de entrega.
- **`updateDeliverySummary()`**: Atualiza o resumo do pedido com os dados de entrega.

### Funções Gerais

- **`DOMContentLoaded` Event Listener**: Carrega os dados do carrinho do `localStorage` ao abrir a página.
- **`localStorage`**: Utilizado para armazenar os dados do carrinho e persistir entre sessões.

## Estrutura do Projeto

- **[`paginas/login.html`](paginas/login.html)**: Página inicial de login.
- **[`paginas/produtos.html`](paginas/produtos.html)**: Página principal onde os produtos são exibidos.
- **[`paginas/pagamento.html`](paginas/pagamento.html)**: Página de pagamento.
- **[`assets`](assets)**: Contém imagens e outros recursos estáticos.

## Observações

- Certifique-se de que o navegador tenha suporte para `localStorage`, pois ele é usado para armazenar os dados do carrinho.
- Caso encontre problemas, verifique se o Live Server está configurado corretamente.

## Contribuição

Sinta-se à vontade para abrir issues ou enviar pull requests para melhorias no projeto.

---

Se precisar de ajuda adicional, entre em contato!
