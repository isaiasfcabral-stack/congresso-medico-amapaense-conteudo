# Conteúdo do app do IV Congresso Médico Amapaense

Este repositório alimenta o app do **IV Congresso Médico Amapaense** (27 a 29 de maio de 2027, Macapá-AP), organizado pela Academia Brasileira de Medicina — Regional Amapá. O app baixa estes arquivos quando abre. Uma mudança aqui chega aos celulares sem nova versão nas lojas.

## Não edite à mão

Os arquivos de conteúdo (os JSON, `fotos/` e `logos/`) são gerados a partir da planilha da grade científica, pelo comando `npm run enviar` do repositório do app. Uma edição feita direto neles some na próxima publicação. Este README não é gerado: ele pode ser editado aqui.

## Os arquivos

| Arquivo | O que contém |
|---|---|
| `evento.json` | Nome, datas, fuso, links e contato oficial do congresso |
| `atividades.json` | Mesas-redondas (com as palestras), minicursos, cafés com especialista e simpósios satélites |
| `pessoas.json` | Perfil público de palestrantes e convidados |
| `locais.json` | Auditórios e locais, com endereço e mapa |
| `apoio.json` | Entidades de realização, patrocínio e apoio |
| `fotos/` | Fotos de quem assinou o termo de uso de imagem |
| `logos/` | Logos das entidades |

Cada JSON segue o envelope `{schemaVersion, atualizadoEm, conteudo}`. O `atualizadoEm` de um arquivo só muda quando o conteúdo dele muda.

## Privacidade

Só entram dados públicos da programação. CRM, e-mail, telefone, cidade, logística de viagem, status do convite e observações dos palestrantes nunca saem da planilha; o `evento.json` traz apenas o contato oficial do congresso. Uma foto só é publicada com o termo de uso de imagem assinado.
