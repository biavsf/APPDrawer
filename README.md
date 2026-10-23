# APPDrawer

Aplicativo Android em Kotlin com navegação por drawer lateral (navigation drawer), desenvolvido para demonstrar a utilização de Material Design, `DrawerLayout`, `Toolbar` e navegação entre opções do menu.

## Visão geral

O projeto `APPDrawer` é uma aplicação mobile simples, criada como exemplo de interface com menu lateral e conteúdo dinâmico. Ao abrir o app, o usuário visualiza uma `Toolbar` com ícone de menu e, ao clicar, o drawer lateral é exibido com opções como:

- Início
- Configuração
- Perfil

Ao selecionar um item do menu, o texto principal da tela é atualizado para refletir a opção escolhida.

Este projeto utiliza o ecossistema Android nativo e é estruturado em módulos padrão de um app Android com Gradle.

## Tecnologias usadas

- Kotlin
- Android SDK
- AndroidX
- AppCompat
- Material Components
- DrawerLayout
- NavigationView
- Gradle Kotlin DSL
- Android Studio

### Dependências principais

- `com.google.android.material:material:1.12.0`
- `androidx.drawerlayout:drawerlayout:1.2.0`
- `androidx.appcompat:appcompat`
- `androidx.core:core-ktx`
- `androidx.activity:activity`
- `androidx.constraintlayout:constraintlayout`

## Estrutura do projeto

```text
APPDrawer/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/appdrawer/
│   │   │   │   └── MainActivity.kt
│   │   │   ├── res/
│   │   │   │   ├── layout/activity_main.xml
│   │   │   │   ├── menu/navigation_drawer.xml
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
└── README.md
```

## Requisitos

Antes de executar o projeto, certifique-se de que você possui:

- Android Studio instalado
- Android SDK configurado
- JDK 17+ (recomendado para compatibilidade com versões recentes do AGP/Android Studio)
- Emulador Android ou dispositivo físico com depuração habilitada

## Instalação

1. Clone o repositório:

```bash
git clone https://github.com/biavsf/APPDrawer.git
cd APPDrawer
```

2. Abra o projeto no Android Studio.

3. Aguarde o Gradle sincronizar as dependências do projeto.

4. Se necessário, baixe o SDK Android solicitado pelo projeto.

## Como executar

### Opção 1: via Android Studio

1. Abra o projeto no Android Studio.
2. Selecione um emulador ou conecte um dispositivo Android.
3. Clique em `Run` ou em `▶ Run 'app'`.
4. A aplicação será instalada e iniciada no dispositivo/emulador.

### Opção 2: via linha de comando

No diretório raiz do projeto, execute:

```bash
./gradlew assembleDebug
```

Ou, para instalar e executar no dispositivo conectado/emulador:

```bash
./gradlew installDebug
```

## Funcionalidades

- Menu lateral com navegação por drawer
- Toolbar com botão de abrir menu
- Suporte a itens do menu: início, configuração e perfil
- Atualização dinâmica do texto principal da tela conforme a opção selecionada
- Interface em Material Design

## Observações

Este projeto funciona como base para estudos de:

- Layouts Android
- Navegação em drawer
- Uso de `MaterialToolbar`
- Interação com `NavigationView`
- Lógica de atualização de UI em Kotlin

## Licença

Este projeto não informa uma licença específica no repositório. Caso precise usar ou redistribuir o código, verifique se há alguma política de uso conforme o contexto do projeto.

## Contribuição

Contribuições são bem-vindas. Para enviar alterações:

```bash
git checkout -b feature/minha-melhoria
git add .
git commit -m "Adiciona melhoria no APPDrawer"
git push origin feature/minha-melhoria
```

## Autor

- biavsf

## Status do projeto

Projeto em desenvolvimento/estudo, com foco em demonstração de navegação lateral em Android.
