# Conversor de presets Davinci Resolve para Winff

<p align="center">
<img width="800px" src="https://github.com/eddiecsilva/resolve-converter-winff-preset/blob/main/img/resolve-project-thumb.png" align="center" alt="white" /><br><br>

<!-- (site para ícones: https://shields.io/ ) -->

<img alt="Mantido" src="https://img.shields.io/badge/Mantido%3F-Sim-verde">
<img alt="Último commit do GitHub" src="https://img.shields.io/github/last-commit/eddiecsilva/resolve-converter-winff-preset">
<img alt="Tamanho do repositório do GitHub" src="https://img.shields.io/github/repo-size/eddiecsilva/resolve-converter-winff-preset">
<img alt="Atividade de commit do GitHub (branch)" src="https://img.shields.io/github/commit-activity/y/eddiecsilva/resolve-converter-winff-preset">

</p>

Um conjunto simples de predefinições para converter vídeos para o DaVinci Resolve Free e Studio no Linux.

# AVISO IMPORTANTE!
O **Davinci Resolve Free** tem suporte limitado para contêineres e codecs para edição e exportação de arquivos no Linux, exigindo o uso do contêiner .MOV / codec MPEG4 / formato de áudio AAC - o que geralmente produz arquivos enormes, tornando-os difíceis de manusear.

Já o **Davinci Resolve Studio** (a versão paga) não tem essas limitações, o que permite o uso de codecs mais modernos, como H264. Isso gera arquivos menores e mais otimizados, economizando processamento e espaço de armazenamento.

---

Para efeito de comparação, um arquivo hipotético exportado usando a predefinição "MPEG 4 - Manter formato" no Davinci Resolve Free acabou com 12.9Gb, enquanto o mesmo arquivo exportado com a predefinição "H264 - Manter formato" gerou um arquivo de 8.5Gb de qualidade visual semelhante.

---

## Como usar essas predefinições
* Baixe winff_resolve_diolinux.xml ou winff_resolve_diolinux.wff (eles têm o mesmo conteúdo) para o seu computador.
* Abra o Winff.
* Clique em Arquivos > Importar predefinições.
* Selecione o arquivo correto do seu computador e clique em "Abrir".

## Guia de predefinições
Todas as predefinições exportam vídeo com qualidade máxima e sem compressão forçada, o que pode resultar em arquivos muito grandes.

----
## Para Davinci Resolve Free
Predefinições para exportar vídeo e áudio com suporte multitrack habilitado
* MPEG 4 - 720p
* MPEG 4 - 1080p
* MPEG 4 - Mantem Formato

Predefinições para exportar vídeo sem áudio
* Remover áudio - MPEG 4 - 720p
* Remover áudio - MPEG 4 - 1080p
* Remover áudio - MPEG 4 - Mantem Formato

---
## Para Davinci Resolve Studio
Predefinições para exportar vídeo e áudio com suporte multitrack habilitado
* H264 - 720p
* H264 - 1080p
* H264 - Formato Mantem
* H264 - ProRes

Predefinições para exportar vídeo sem áudio
* Remover áudio - H264 - 720p
* Remover áudio - H264 - 1080p
* Remover áudio - H264 - Mantem Formato