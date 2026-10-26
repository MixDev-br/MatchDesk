# MatchDesk

Monitoramento de conexão, overlay e informações de partidas de eFootball para Windows e Android.

[Português](README.md) · [English](README.en-US.md) · [Español](README.es-ES.md)

[Site oficial](https://mixdev-br.github.io/MatchDesk/) · [Downloads](DOWNLOADS.md) · [Suporte](SUPPORT.md)

## Estamos preparando algo novo

O MatchDesk está em transição para sua nova identidade. As novas builds ainda estão em preparação. O site completo será publicado junto com os aplicativos atualizados; até lá, o endereço oficial exibe uma prévia.

**Ainda não há pacotes MatchDesk disponíveis neste repositório.** As publicações e os downloads das marcas anteriores foram retirados. Consulte [Downloads e disponibilidade](DOWNLOADS.md) para acompanhar a distribuição oficial.

## Aplicativos

| Aplicativo | Plataforma | Finalidade |
| --- | --- | --- |
| **MatchDesk Pro** | Windows 10/11, 64 bits | Monitor de conexão, overlay, central de servidores, regiões e histórico de partidas. |
| **MatchDesk Scout** | Windows 10/11, 64 bits | Informações disponíveis sobre o adversário e a partida, em aplicativo próprio ou integrado ao Pro. |
| **MatchDesk Mobile** | Android com roteador OpenWrt compatível | Monitoramento de um PC, PlayStation ou Xbox pela rede local, usando o celular como painel. |
| **MatchDesk Trial** | Windows 10/11, 64 bits | Edição de avaliação do aplicativo principal. Disponibilidade e condições serão informadas na publicação. |

O suporte no PC contempla eFootball para Steam e Xbox PC. Recursos, requisitos e compatibilidade devem ser conferidos nas notas de cada build. O Scout é exclusivo para Windows; o monitoramento de consoles usa o Mobile e um roteador compatível.

## Antes de instalar

- Para captura direta de rede no Windows, o Pro utiliza [Npcap](https://npcap.com/#download), instalado pela fonte oficial. O Scout não exige Npcap.
- O Mobile exige um roteador executando OpenWrt. O firmware original do fabricante não é suficiente. Consulte o [guia de configuração](OPENWRT_MOBILE_GUIDE.md).
- As edições comerciais exigem licença correspondente. Uma licença de um aplicativo não implica acesso aos demais.
- Use as instruções do pacote publicado e extraia o conteúdo completo dos arquivos ZIP.

O aplicativo apresenta os dados que a sessão e a plataforma disponibilizam. Medições de latência, localização e identificação de adversários têm limites; a escolha de região não garante o resultado do matchmaking.

## Downloads e atualizações

As futuras builds serão publicadas pelos canais oficiais indicados em [DOWNLOADS.md](DOWNLOADS.md), com versão, plataforma, notas e informações de integridade. Não use cópias de terceiros nem arquivos renomeados como se fossem uma nova versão.

Durante a transição, o manifesto das builds retiradas não é mais publicado. A ausência de um manifesto não representa uma nova versão disponível.

## Ajuda e segurança

- [Suporte e diagnóstico](SUPPORT.md)
- [Mobile e OpenWrt](OPENWRT_MOBILE_GUIDE.md)
- [Relatar um problema](https://github.com/MixDev-br/MatchDesk/issues/new/choose)
- [Relatar uma vulnerabilidade em particular](SECURITY.md)
- [Histórico público](CHANGELOG.md)

Não publique chaves de licença, senhas, tokens, códigos completos de dispositivo ou capturas com dados pessoais. Os canais de atendimento existentes continuam disponíveis durante a transição.

## Sobre este repositório

Este é o repositório público de documentação e distribuição do MatchDesk, mantido pela MixDev. O código-fonte dos aplicativos é proprietário e não é disponibilizado aqui. O uso dos aplicativos segue os termos fornecidos com cada produto; a disponibilidade pública deste repositório não concede uma licença de código aberto.

MatchDesk é um projeto independente, sem vínculo, patrocínio ou aprovação da KONAMI. eFootball e as demais marcas citadas pertencem aos seus respectivos titulares.
