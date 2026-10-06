# TM CAR - Gestão Completa | Android

Este projeto transforma o sistema web atual da TM CAR em um aplicativo Android usando Capacitor.

## Para gerar o APK usando somente o celular

O projeto já vem com um workflow do GitHub Actions que cria o APK automaticamente na nuvem.

### Passo a passo

1. Crie um repositório no GitHub (pode ser privado).
2. Envie todos os arquivos deste projeto para o repositório.
3. Entre na aba **Actions**.
4. Abra **Gerar APK TM CAR**.
5. Toque em **Run workflow**.
6. Aguarde a compilação terminar.
7. Abra a execução concluída e procure **Artifacts**.
8. Baixe **TM-CAR-APK**.
9. Dentro do arquivo baixado estará o `app-debug.apk` para instalar no Android.

Também existe execução automática quando houver um `push` na branch `main`.

## O que está preservado

- Sistema HTML/JavaScript atual da TM CAR.
- Clientes.
- Serviços.
- Orçamentos.
- Dashboard.
- Financeiro.
- Agendamentos.
- Contas.
- Análise de serviços.
- Backup/restauração local.
- Dados armazenados localmente no aparelho.

## Próxima etapa depois do primeiro APK

Depois de instalar e testar, podemos fazer uma segunda versão com recursos nativos, como:

- ícone e tela de abertura TM CAR;
- compartilhamento de orçamento pelo WhatsApp;
- geração de PDF;
- fotos dos veículos pela câmera;
- notificações de agendamento;
- backup mais seguro;
- sincronização em nuvem.

## Observação

O APK gerado pelo workflow é uma versão de teste (`debug`). Para publicar na Play Store ou distribuir uma versão assinada, será necessário configurar uma chave de assinatura própria.
