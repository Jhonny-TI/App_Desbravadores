# 📱 App Desbravadores - Controle de Requisitos

Aplicativo mobile desenvolvido em **React Native** para auxiliar desbravadores no acompanhamento dos requisitos de cada classe, com sistema de checklist, progresso automático e salvamento local.

---

## 🚀 Funcionalidades

✅ Navegação entre classes dos Desbravadores
✅ Checklist interativo para cada requisito
✅ Barra de progresso automática (%)
✅ Salvamento dos dados no dispositivo (AsyncStorage)
✅ Interface simples e intuitiva
✅ Organização por classes:

* Amigo
* Companheiro
* Pesquisador
* Pioneiro
* Excursionista
* Guia

---

## 🛠️ Tecnologias Utilizadas

* React Native
* React Navigation
* Async Storage
* JavaScript (ES6+)

---

## 📂 Estrutura do Projeto

```
App.js
 ├── HomeScreen (Tela inicial com classes)
 ├── ClassScreen (Tela de requisitos)
 ├── Navegação Stack
 └── Estilos (StyleSheet)
```

---

## 📊 Como Funciona

* O usuário escolhe uma classe.
* Cada requisito pode ser marcado como concluído ✅.
* O progresso é calculado automaticamente:

```
Progresso (%) = (Itens concluídos / Total de itens) * 100
```

* Os dados ficam salvos no celular usando **AsyncStorage**.

---

## 💾 Persistência de Dados

O app salva o progresso de cada classe separadamente usando:

```js
AsyncStorage.setItem(nomeDaClasse, dados)
```

E carrega automaticamente ao abrir:

```js
AsyncStorage.getItem(nomeDaClasse)
```

---

## 📸 Interface

* Tema escuro moderno 🌙
* Cards para cada requisito
* Barra de progresso animada
* Feedback visual com:

  * ⬜ Não concluído
  * ✅ Concluído

---

## ▶️ Como Rodar o Projeto

1. Instale as dependências:

```bash
npm install
```

2. Execute o projeto:

```bash
npx expo start
```

3. Abra no:

* Emulador Android/iOS
* Ou app Expo Go

---

## 🔥 Melhorias Futuras

* Login de usuário 👤
* Backup em nuvem ☁️
* Animações mais suaves 🎨
* Filtro por requisitos concluídos
* Sistema de metas

---

## 📌 Observação

Este projeto é voltado para uso educacional e apoio aos membros do Clube de Desbravadores, facilitando o acompanhamento dos requisitos de cada classe.

---

