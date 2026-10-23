# APPDrawer

<div align="center">

![APPDrawer Banner](https://img.shields.io/badge/Android-Kotlin-3DDC84?style=for-the-badge&logo=android)
![Material Design](https://img.shields.io/badge/Material%20Design-Drawer-FF6F61?style=for-the-badge)
![Gradle](https://img.shields.io/badge/Build-Gradle-02303A?style=for-the-badge&logo=gradle)
![Status](https://img.shields.io/badge/Status-Em%20desenvolvimento-yellow?style=for-the-badge)

<img src="https://via.placeholder.com/1200x400?text=APPDrawer+Preview" alt="Preview do APPDrawer" width="100%" />

</div>

Aplicativo Android em Kotlin desenvolvido para demonstrar navegação lateral por drawer menu, com interface moderna e uso de componentes do Material Design. O projeto oferece uma experiência simples e funcional para apresentar telas de início, configuração e perfil em um único fluxo visual.

---

## ✨ Visão Geral

O APPDrawer é uma aplicação mobile criada para praticar e demonstrar a estrutura básica de um app Android com navegação lateral. Ele contém uma `Toolbar` com botão de menu, um `DrawerLayout` com itens de navegação e uma área principal que atualiza o conteúdo conforme a opção selecionada.

A aplicação foi construída com foco em aprendizado de:
- UI em Android
- Uso de `MaterialToolbar`
- `DrawerLayout` e `NavigationView`
- Atualização dinâmica de conteúdo em Kotlin

---

## 🧩 Tecnologias Utilizadas

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android)
![Material3](https://img.shields.io/badge/Material%20Components-757575?style=flat-square)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle)
![Jetpack](https://img.shields.io/badge/AndroidX-3DDC84?style=flat-square)

### Stack principal
- Kotlin
- Android SDK
- AndroidX
- AppCompat
- Material Components
- DrawerLayout
- NavigationView
- Gradle Kotlin DSL

---

## 🚀 Funcionalidades

- Menu lateral (drawer navigation)
- Toolbar com ícone de menu para abrir o painel lateral
- Opções de navegação: Início, Configuração e Perfil
- Atualização dinâmica do texto principal da tela
- Interface responsiva e intuitiva em estilo Material Design

---

## 📁 Estrutura do Projeto

```text
APPDrawer/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/appdrawer/
│   │   │   │   └── MainActivity.kt
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   │   └── activity_main.xml
│   │   │   │   ├── menu/
│   │   │   │   │   └── navigation_drawer.xml
│   │   │   │   └── values/
│   │   │   └── AndroidManifest.xml
│   │   ├── androidTest/
│   │   └── test/
│   ├── build.gradle.kts
│   └── proguard-rules.pro
├── gradle/
│   ├── wrapper/
│   └── libs.versions.toml
├── build.gradle.kts
├── settings.gradle.kts
├── gradlew
├── gradlew.bat
├── gradle.properties
├── .gitignore
├── README.md
└── LICENSE
```

---

## 🛠️ Requisitos

Antes de executar o projeto, verifique se você possui:

- Android Studio instalado
- Android SDK configurado
- JDK 17 ou superior
- Emulador Android ou dispositivo físico com depuração habilitada

---

## ▶️ Como Executar

### 1. Clone o repositório

```bash
git clone https://github.com/biavsf/APPDrawer.git
cd APPDrawer
```

### 2. Abra o projeto no Android Studio

- Abra o Android Studio
- Selecione `Open an existing project`
- Escolha a pasta do repositório clonado

### 3. Sincronize o Gradle

O Android Studio irá baixar as dependências automaticamente. Caso necessário, clique em:

```bash
Sync Project with Gradle Files
```

### 4. Execute a aplicação

Você pode rodar pelo Android Studio:
- selecione um emulador ou um dispositivo conectado
- clique em `Run` ou `Run 'app'`

Ou via terminal:

```bash
./gradlew assembleDebug
```

Para instalar e rodar no dispositivo conectado/emulador:

```bash
./gradlew installDebug
```

---

## 📷 Demonstração

A aplicação apresenta uma interface com:
- barra superior
- botão de menu lateral
- painel com opções de navegação
- atualização do conteúdo da tela ao selecionar um item do menu

> Demo/Deploy: Não possui no momento.

---

## 📜 Licença

Este projeto está disponível sob a licença MIT. Caso queira reutilizar ou adaptar o código, você pode usar este projeto como base para estudos, protótipos ou desenvolvimento pessoal.

```md
MIT License

Copyright (c) 2026 APPDrawer

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🤝 Contribuição

Contribuições são bem-vindas. Se você quiser melhorar o projeto, siga os passos:

```bash
git checkout -b feature/minha-melhoria
git add .
git commit -m "Adiciona melhoria no APPDrawer"
git push origin feature/minha-melhoria
```

Depois, abra um Pull Request para revisão.

---

## 👤 Autor

- GitHub: [biavsf](https://github.com/biavsf)
- Projeto: APPDrawer

---

## 📌 Status

Status atual: em desenvolvimento / estudo de UI Android com drawer navigation.

---

Se quiser, eu também posso gerar uma versão:
- mais elegante e premium
- em inglês
- com badges mais sofisticados
- pronta para publicar no GitHub com aparência de projeto profissional
