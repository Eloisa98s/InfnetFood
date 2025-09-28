InfnetFood

InfnetFood é um aplicativo de pedidos e delivery de lanches e refeições desenvolvido em React Native com Expo, incluindo: login, listagem de categorias e produtos, carrinho de compras, perfil do usuário, pedidos, mapa de restaurantes, checkout, configurações de tema e notificações simuladas.

📁 Estrutura do Projeto
InfnetFood/
│── App.js
│── package.json
│── babel.config.js
│── assets/
│   ├── logo.png
│   └── map.png
└── src/
    ├── api/               # Consumo da API de alimentos
    ├── components/        # Componentes reutilizáveis (cards, itens do carrinho)
    ├── navigation/        # Navegação (AuthStack, AppStack, RootNavigator)
    ├── screens/           # Telas do app (Login, Home, Produtos, Checkout, Map, Perfil)
    ├── store/             # Contextos (user, cart)
    └── theme/             # Configurações de cores e tema

⚡ Funcionalidades

Login Simples com dados mockados

Home com categorias de refeições usando FlatList

Produtos de cada categoria

Carrinho de Compras gerenciando itens e total

Perfil do usuário com informações básicas

Pedidos com lista de pedidos mockados

Mapa Simulado mostrando restaurantes

Detalhes do Restaurante com endereço e item de cardápio

Checkout com endereço de entrega e pagamento (validação básica)

Fluxo de autenticação público (Login) e logado (Home)

Feedback Visual ao adicionar itens ao carrinho

Configurações para troca de tema claro/escuro

Notificações Simuladas de status do pedido

Consumo de API de alimentos (TheMealDB)

Testes Unitários (simulados ou integráveis com Jest)

Preparado para publicação com Expo

🛠️ Tecnologias Utilizadas

React Native

Expo

React Navigation

Context API (para usuário e carrinho)

FlatList para listas

Lottie (opcional para animações)

TheMealDB API (para produtos e categorias)

🚀 Como Rodar o Projeto

Clone ou baixe o projeto para sua máquina

Abra no VSCode

Instale as dependências:

npm install


Rode o projeto:

npx expo start


Abra no emulador Android/iOS ou pelo Expo Go no celular

🎨 Observações de Design

Telas com FlatList para categorias e produtos

Cartões (cards) estilizados para produtos e categorias

Tema claro/escuro configurável

Feedback visual básico ao adicionar itens ao carrinho

📌 Próximos Passos

Implementar notificações reais via Expo Notifications

Integração com backend real para pedidos e usuários

Melhorias no design responsivo e animações

📸 Prints do App
