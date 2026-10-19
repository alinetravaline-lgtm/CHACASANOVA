# Chá de Casa Nova · Aline & Hebert

Convite interativo do Chá de Casa Nova, 31 de outubro de 2026.

- Envelope com selo do monograma AH que abre ao clicar
- Programação (12h almoço com churrasco, 15h chá de casa nova) e o que levar
- Local: Chácara da Vó Inês, com link para o mapa
- Contagem regressiva e botão para salvar na agenda
- Lista de presentes com fotos e links do Mercado Livre
- Confirmação de presença pelo WhatsApp

## Como publicar

O site é um único arquivo, `index.html`, sem dependências nem build.
Na Vercel, importe este repositório como projeto com o preset **Other**.
No GitHub Pages, ative Pages na branch `main`, pasta raiz.

## Onde editar

No fim do `index.html`, no objeto `CONFIG`:

- `address1` e `address2`: endereço mostrado no convite
- `whatsapp`: número que recebe as confirmações (só números, com DDI 55)
- `start` / `end`: horário do evento

A lista de presentes está no array `GIFTS`, logo abaixo.
