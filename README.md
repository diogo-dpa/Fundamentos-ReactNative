# 📱 Fundamentos React Native
Código desenvolvido a partir de um template disponibilizado pela Rocketseat durante o Bootcamp GoStack, no qual foram praticados os fundamentos de React Native em uma aplicação, chamada GoMarketPlace, utilizando os conceitos vistos nas aulas.

## 🧿 Objetivo
Implementar as funcionalidades de:

- Realizar a autenticação e validação dos dados do usuário
- Utilização da lib Unform para validação de formulários
- Aplicar a usabilidade nas telas de login e cadastro
- Implementar rotas privadas no projeto

Os conceitos praticados foram:

- ✅ Uso do Typescript em uma aplicação com React Native
- ✅ Utilização do hook useContext para criação de contextos
- ✅ Uso do AsyncStorage para armazenar algumas informações do estado

## 🛴 Como rodar o código do projeto?
- Lembrando que, no caso, foi utilizado o emulador Android Studio para a aplicação funcionar.
1. Após clonar o código, entre na pasta e digite o comando no terminal
```
npm install
```
ou
```
// caso tenha o yarn instalado
yarn
```
2. Caso esteja utilizando emulador de Android, digite o comando abaixo no terminal
```
adb reverse tcp:3333 tcp:3333
```
3. Agora basta rodar
```
yarn android
```
