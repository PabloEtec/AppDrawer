# AppDrawer

Aplicativo Android em Kotlin que demonstra o uso de um menu lateral (`Navigation Drawer`) com navegação entre telas conceituais de um aplicativo de exemplo.

## Visão geral

O projeto foi desenvolvido para exemplificar:

- uso de `DrawerLayout`
- integração com `MaterialToolbar`
- menu lateral com opções de navegação
- atualização dinâmica do conteúdo principal ao selecionar itens do menu
- estrutura mínima de projeto Android com Kotlin

## Funcionalidades

- Menu lateral acessível pela toolbar
- Itens do menu:
  - Início
  - Perfil
  - Configurações
- Conteúdo principal alterado conforme item selecionado
- Layout responsivo para dispositivos Android com suporte a edge-to-edge

## Tecnologias utilizadas

- Kotlin
- Android SDK
- AndroidX
- Material Components
- DrawerLayout
- ViewBinding / recursos XML

## Estrutura do projeto

```text
AppDrawer/
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
│   │   │   │       └── strings.xml
│   │   │   └── AndroidManifest.xml
│   │   └── ...
│   └── build.gradle.kts
├── build.gradle.kts
├── settings.gradle.kts
├── gradlew
├── gradlew.bat
├── gradle.properties
├── gradle/
└── README.md
```

## Requisitos

Antes de executar o projeto, verifique se você possui:

- Android Studio
- JDK 11 ou superior
- SDK Android configurado no ambiente
- Emulador Android ou dispositivo físico conectado

## Como executar

1. Clone o repositório:

```bash
git clone https://github.com/PabloEtec/AppDrawer.git
```

2. Abra o projeto no Android Studio.

3. Sincronize o Gradle.

4. Escolha um emulador ou dispositivo conectado.

5. Execute a aplicação:

```bash
./gradlew assembleDebug
```

Ou, diretamente no Android Studio, clique em `Run`.

## Arquivo principal

A lógica principal do aplicativo está em:

- `app/src/main/java/com/example/appdrawer/MainActivity.kt`

Esse arquivo:

- inicializa a activity principal
- configura o `DrawerLayout`
- cria o toggle do menu
- atualiza o texto principal conforme o item selecionado

## Observações

Este projeto funciona como um exemplo didático de implementação de navigation drawer em Android com Kotlin e Material Design.

## Licença

Este projeto não especifica uma licença no repositório e foi desenvolvido como exemplo de estudo.
