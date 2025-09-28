InfnetFood
InfnetFood é um aplicativo mobile para pedidos e delivery de lanches e refeições, desenvolvido com React Native e Expo. O app oferece funcionalidades completas como login, navegação por categorias, carrinho de compras, perfil de usuário, acompanhamento de pedidos, mapa de restaurantes, checkout, tema personalizável e notificações simuladas.

📁 Estrutura do Projeto
text
InfnetFood/
│── App.js
│── package.json
│── babel.config.js
│── assets/
│   ├── logo.png
│   └── map.png
└── src/
    ├── api/               # Consumo da API de alimentos (TheMealDB)
    ├── components/        # Componentes reutilizáveis (cards, itens do carrinho, etc.)
    ├── navigation/        # Configuração da navegação (AuthStack, AppStack, RootNavigator)
    ├── screens/           # Telas do aplicativo (Login, Home, Produtos, Checkout, Mapa, Perfil)
    ├── store/             # Contextos para estado global (usuário, carrinho)
    └── theme/             # Configurações de cores e temas (claro/escuro)
⚡ Funcionalidades Principais
Login simples com dados simulados (mockados)

Tela inicial (Home) com categorias de refeições exibidas em FlatList

Listagem de produtos por categoria com cards estilizados

Carrinho de compras gerenciando itens adicionados e cálculo do total

Perfil do usuário com informações básicas

Visualização de pedidos com dados mockados

Mapa simulado mostrando localização dos restaurantes

Detalhes de restaurante incluindo endereço e itens do cardápio

Checkout com preenchimento de endereço e pagamento com validação básica

Fluxo de autenticação com rotas públicas (login) e privadas (home e demais)

Feedback visual ao adicionar produtos no carrinho

Suporte a temas claro e escuro com troca via configurações

Notificações simuladas para status de pedidos

Consumo da API pública TheMealDB para categorias e produtos

Estrutura preparada para testes unitários com Jest

Pronto para publicação via Expo

🛠️ Tecnologias Utilizadas
React Native

Expo (CLI e Go)

React Navigation para controle de rotas

Context API para gerenciamento global de estado (usuário e carrinho)

FlatList para renderização eficiente de listas

Lottie (opcional, para animações)

TheMealDB API para dados de refeições e categorias

🚀 Como Rodar o Projeto
Clone este repositório para sua máquina local:

bash
git clone <URL do repositório>
cd InfnetFood
Abra o projeto no VSCode ou sua IDE preferida.

Instale as dependências:

bash
npm install
Inicie o servidor Expo:

bash
npx expo start
Abra o app no emulador Android/iOS ou utilize o app Expo Go no seu celular para escanear o QR code exibido.

🎨 Notas de Design
Interfaces construídas com FlatList para desempenho otimizado em listas de categorias e produtos

Cartões visualmente estilizados para melhor usabilidade e estética

Tema claro e escuro configurável nas preferências do usuário

Feedback visual simples e direto ao adicionar itens ao carrinho

📌 Próximos Passos
Implementar notificações push reais via Expo Notifications

Integrar backend real para gerenciamento de usuários, pedidos e pagamentos

Melhorar responsividade e incluir animações para enriquecer a experiência do usuário

📸 Capturas de Tela
