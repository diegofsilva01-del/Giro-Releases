# GIRO 2.0 — Atualizações Android

Este repositório **público** é destinado **somente à distribuição de APKs assinados** do aplicativo pessoal GIRO 2.0.

O código-fonte, os testes, a configuração de compilação e o histórico de desenvolvimento permanecem no repositório **privado** `Giro-Android`.

## Como funciona

Após a primeira instalação da edição definitiva assinada, abra **GIRO 2.0 → Ajustes → Atualizações** e toque em **Verificar atualizações**. Quando uma versão estiver disponível aqui, o próprio aplicativo poderá baixá-la e iniciar o instalador Android mediante sua confirmação.

As versões instaláveis estarão em [Releases](https://github.com/diegofsilva01-del/Giro-Releases/releases), não nos arquivos da branch principal.

## Regras da publicação

- Publicar apenas APKs Android **release assinados com a chave permanente do proprietário**.
- Nome do APK: `GIRO-2-<versionCode>-<versionName>.apk`, por exemplo `GIRO-2-204-2.0.1.apk`.
- Tag de lançamento: `v<versionName>`, por exemplo `v2.0.1`.
- Disponibilizar checksum SHA-256 do APK para conferir integridade.
- **Nunca publicar** código-fonte privado, chave de assinatura, senhas, tokens, backups, fotos ou outros dados pessoais.
- **Nunca publicar** APK de depuração como atualização definitiva. Assinaturas diferentes impedem a instalação sobre a versão existente.

Ainda não há atualização oficial publicada até que a assinatura definitiva e o processo de migração sejam homologados.
