# Z.ai para Android (projeto)

Este projeto cria um aplicativo Android simples que abre https://chat.z.ai/ em uma WebView.

## Gerar o APK
1. Instale/abra o Android Studio.
2. Escolha **Open** e selecione a pasta `ZAI_Android`.
3. Aguarde a sincronização do Gradle e a instalação do Android SDK 35.
4. Use **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. O APK de teste será gerado em `app/build/outputs/apk/debug/app-debug.apk`.

## Observações
- Este é um cliente não oficial, feito apenas para abrir o site oficial.
- Não coleta nem envia credenciais para outro servidor; o conteúdo é carregado diretamente de `chat.z.ai`.
- O login por Google pode ser bloqueado pelo próprio provedor dentro de navegadores incorporados. Se isso acontecer, use login por e-mail no site ou abra o site no navegador.
- O app precisa de internet.
