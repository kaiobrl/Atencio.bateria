# 🔋 Baterias Atencio - Sistema de Vendas Online

Sistema web responsivo para vendas de baterias automotivas com integração WhatsApp.

## 📋 Descrição

Plataforma de e-commerce simplificada para a loja **Baterias Atencio**, permitindo que clientes:
- Visualizem catálogo de baterias
- Adicionem produtos ao carrinho
- Preencham dados de entrega
- Finalizem pedidos via WhatsApp

## ✨ Características

- **Catálogo Dinâmico**: 6 modelos de baterias com diferentes amperagens
- **Carrinho de Compras**: Gerenciamento em tempo real de itens
- **Integração WhatsApp**: Pedidos enviados automaticamente via WhatsApp Business
- **Responsivo**: Layout adaptável para desktop e mobile
- **Sem Banco de Dados**: Funciona 100% no navegador (frontend)
- **Design Moderno**: Interface limpa e intuitiva com cores da marca

## 🛠️ Tecnologias

- HTML5
- CSS3 (Grid, Flexbox, Media Queries)
- JavaScript Vanilla (ES6+)
- WhatsApp API

## 📦 Produtos Disponíveis

| Modelo | Amperagem | Preço |
|--------|-----------|-------|
| Moura 60Ah | 60Ah | R$ 389,90 |
| Heliar 45Ah | 45Ah | R$ 299,90 |
| Zetta 70Ah | 70Ah | R$ 449,90 |
| Moura 90Ah | 90Ah | R$ 589,90 |
| Bosch 50Ah | 50Ah | R$ 349,90 |
| ACDelco 75Ah | 75Ah | R$ 479,90 |

## 🚀 Como Usar

1. Abra o arquivo `index.html` em um navegador web
2. Navegue pelo catálogo de baterias
3. Clique em "Adicionar" para adicionar produtos ao carrinho
4. Preencha os dados do cliente:
   - Nome completo
   - WhatsApp
   - Modelo do carro
   - Forma de pagamento
5. Clique em "Finalizar Pedido"
6. Será aberta uma janela do WhatsApp com o pedido pré-formatado
7. Confirme o envio da mensagem

## 💳 Formas de Pagamento

- **PIX**: Transferência instantânea
- **Cartão**: Até 6x sem juros
- **Dinheiro**: Pagamento à vista

## 📞 Contato

**WhatsApp da Loja**: [83] 98137-4944

> Edite o número no código (variável `numeroLoja`) se precisar atualizar.

## 📝 Estrutura do Código

```javascript
// Dados dos produtos
const produtos = [...]

// Renderização do catálogo
function renderProdutos() {...}

// Gerenciamento do carrinho
function addCarrinho(id) {...}
function removerItem(id) {...}
function renderCarrinho() {...}

// Finalização de pedidos
function finalizarVenda() {...}
```

## ✅ Funcionalidades Implementadas

- [x] Catálogo de produtos
- [x] Sistema de carrinho
- [x] Cálculo de total
- [x] Formulário de cliente
- [x] Integração WhatsApp
- [x] Validação de dados
- [x] Design responsivo
- [x] Desconto PIX removido

## 🔄 Próximas Melhorias (Sugestões)

- [ ] Persistência de dados (LocalStorage)
- [ ] Histórico de pedidos
- [ ] Cupons de desconto
- [ ] Calculadora de frete
- [ ] Busca e filtros de produtos
- [ ] Avaliações de clientes
- [ ] Dashboard administrativo

## 📱 Compatibilidade

- ✅ Chrome/Edge (desktop e mobile)
- ✅ Firefox (desktop e mobile)
- ✅ Safari (desktop e mobile)
- ✅ Navegadores mobile em geral

## 📄 Licença

Sistema desenvolvido para Baterias Atencio.

---

**Desenvolvido com ❤️ para otimizar as vendas**
