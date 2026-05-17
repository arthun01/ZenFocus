# 🍅 ZenFocus

Um aplicativo de cronômetro Pomodoro limpo e eficiente, desenvolvido para ajudar no foco e na gestão de tempo. Construído com um ecossistema moderno utilizando React Native e Expo.

## ✨ Funcionalidades

O projeto foi estruturado para oferecer uma ótima experiência de usuário, integrando as seguintes ferramentas:

- **Acompanhamento Visual:** Progresso do tempo animado em formato circular utilizando `react-native-circular-progress`.
- **Feedback Tátil:** Respostas físicas (vibração) integradas com `expo-haptics` para alertar sobre o fim dos ciclos.
- **Armazenamento de Dados:** Persistência de configurações ou histórico de sessões localmente via `@react-native-async-storage/async-storage`.
- **Navegação Fluida:** Transições de tela gerenciadas pelo `React Navigation`.
- **Animações Nativas:** Interfaces suaves construídas com `react-native-reanimated`.

## 🚀 Tecnologias Utilizadas

- [React Native](https://reactnative.dev/) (Nova Arquitetura habilitada)
- [Expo](https://expo.dev/) (SDK 54)
- [TypeScript](https://www.typescriptlang.org/)
- [React Compiler](https://react.dev/learn/react-compiler) (Experimental)

## 🛠️ Como executar o projeto

### Pré-requisitos

Certifique-se de ter o [Node.js](https://nodejs.org/) instalado em sua máquina. O uso de um dispositivo físico com o aplicativo [Expo Go](https://expo.dev/go) ou um emulador (Android Studio / Xcode) é recomendado.

### Instalação

1. Clone este repositório.
2. Instale as dependências do projeto:

```bash
npm install
```

### Rodando o aplicativo

Inicie o servidor de desenvolvimento do Expo:

Bash

```
npm start
```

No terminal, você verá um QR Code e algumas opções. Você pode:

- Pressionar `a` para abrir no emulador **Android**.
    
- Pressionar `i` para abrir no simulador **iOS**.
    
- Escanear o QR Code com a câmera do seu celular (iOS) ou com o aplicativo Expo Go (Android) para rodar no dispositivo físico.

## 📂 Scripts Disponíveis

No diretório do projeto, você pode rodar os seguintes comandos:

- `npm start`: Inicia o empacotador Metro.
    
- `npm run android`: Inicia o projeto diretamente no emulador Android.
    
- `npm run ios`: Inicia o projeto diretamente no simulador iOS.
    
- `npm run web`: Inicia o projeto no navegador web.
    
- `npm run lint`: Executa a verificação de código com o ESLint.
    
- `npm run reset-project`: Reseta o projeto base para começar do zero (útil caso queira limpar a estrutura padrão do Expo).

---

_Desenvolvido com ☕ e foco._