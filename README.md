# DeliKami
# System Overview — Sistema de Gestão e Pedidos de Doceria

<div align="center">

  <img src="https://raw.githubusercontent.com/pkief/vscode-material-icon-theme/main/icons/store.svg" width="80" alt="Store Icon" />

  <br />

  ![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-orange?style=for-the-badge)
  ![License](https://img.shields.io/badge/Licen%C3%A7a-MIT-blue?style=for-the-badge)
  ![Version](https://img.shields.io/badge/Vers%C3%A3o-1.0.0-green?style=for-the-badge)

  <p align="center">
    Uma solução digital completa e simplificada para gestão de catálogo, pedidos online e pagamentos integrados para microempreendedores do ramo da confeitaria.
  </p>

</div>

---

## <img src="https://raw.githubusercontent.com/pkief/vscode-material-icon-theme/main/icons/document.svg" width="22" height="22" /> Sobre o Projeto

O **Sistema de Doceria** nasceu da necessidade de otimizar e profissionalizar o atendimento de vendas de doces artesanais. Desenvolvido sob a perspectiva de um microempreendedor, o sistema busca centralizar o fluxo de vendas desde o cadastro do cliente até a confirmação do pagamento, reduzindo o tempo de atendimento manual e minimizando erros em pedidos.

### <img src="https://raw.githubusercontent.com/pkief/vscode-material-icon-theme/main/icons/target.svg" width="22" height="22" /> Objetivos
* Proporcionar uma experiência de compra simples, rápida e intuitiva para os clientes.
* Exibir em tempo real o cardápio atualizado conforme a disponibilidade do estoque.
* Garantir praticidade com pagamento direto na plataforma.
* Oferecer um canal rápido de suporte direto via WhatsApp para eventuais dúvidas ou imprevistos.

---

## <img src="https://raw.githubusercontent.com/pkief/vscode-material-icon-theme/main/icons/settings.svg" width="22" height="22" /> Funcionalidades Principais

| Ícone | Funcionalidade | Descrição |
| :---: | :--- | :--- |
| <img src="https://raw.githubusercontent.com/pkief/vscode-material-icon-theme/main/icons/account.svg" width="20" /> | **Autenticação de Usuários** | Cadastro de novos clientes e sistema seguro de login/logout. |
| <img src="https://raw.githubusercontent.com/pkief/vscode-material-icon-theme/main/icons/list.svg" width="20" /> | **Cardápio Dinâmico** | Exibição de produtos divididos por categorias e filtrados por disponibilidade em estoque. |
| <img src="https://raw.githubusercontent.com/pkief/vscode-material-icon-theme/main/icons/shopping-cart.svg" width="20" /> | **Gestão de Carrinho & Pedidos** | Adição de itens, escolha de quantidades e finalização simplificada do checkout. |
| <img src="https://raw.githubusercontent.com/pkief/vscode-material-icon-theme/main/icons/credit-card.svg" width="20" /> | **Pagamento Integrado** | Efivação do pagamento diretamente no ambiente da aplicação. |
| <img src="https://raw.githubusercontent.com/pkief/vscode-material-icon-theme/main/icons/phone.svg" width="20" /> | **Suporte via WhatsApp** | Botão direto para contato instantâneo com a doceria em caso de suporte ou dúvidas. |

---

## <img src="https://raw.githubusercontent.com/pkief/vscode-material-icon-theme/main/icons/routing.svg" width="22" height="22" /> Fluxo da Aplicação

```text
[ Visitante ] ──> [ Cadastro / Login ] ──> [ Cardápio / Estoque ]
                                                     │
                                                     ▼
[ Atendimento via WhatsApp ] <── [ Pagamento ] <── [ Carrinho ]
