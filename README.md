# WTV — projeto Android para celular e TV Box

Aplicativo Android com interface em português, identidade visual escura em azul/roxo e suporte inicial a celulares e Android TV/TV Box. O app organiza links fornecidos pelo usuário; não hospeda canais nem garante que os sites de origem aceitem reprodução incorporada.

## Recursos implementados no código-fonte
- Categorias: canais abertos, documentários, entretenimento, notícias, esportes, filmes e desenhos.
- Pesquisa por nome.
- Favoritos guardados localmente.
- Painel de abertura do canal e opção de abrir o endereço no navegador.
- Navegação por setas e botão Voltar, pensada para controle remoto.
- Atalho de inicialização para Android TV/TV Box.

## Compilar o APK
1. Instale o Android Studio e o JDK 17.
2. Instale o Android SDK Platform 35 pelo SDK Manager.
3. Extraia este ZIP e abra a pasta `WTV` no Android Studio.
4. Aguarde a sincronização do Gradle.
5. Use **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
6. O APK de depuração deverá ser criado em `app/build/outputs/apk/debug/app-debug.apk`.

## Requisitos do projeto
- Android Gradle Plugin 8.6.1
- compileSdk 35, minSdk 23, targetSdk 28
- JDK 17

## Estado e limitações
Este arquivo contém o código-fonte, não um APK compilado. Neste ambiente não foi localizado Android SDK nem Gradle, portanto não foi possível produzir ou testar um instalador. A compatibilidade com modelos MXQ depende da versão Android e do WebView instalados no aparelho. Alguns sites podem bloquear iframes, exigir autenticação ou mudar de endereço. Use apenas transmissões e conteúdos que você esteja autorizado a acessar.
