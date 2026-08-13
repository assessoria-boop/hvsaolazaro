# Hospital Veterinário São Lázaro · Landing Page 24h

Landing page estática (HTML único, sem dependências externas) para o Hospital Veterinário São Lázaro, Volta Redonda/RJ.

## Imagens que você precisa colocar nesta pasta

Todas em **.webp**, com exatamente estes nomes:

| Arquivo | O que é | Sugestão de tamanho |
|---|---|---|
| `logo.webp` | Logo do cliente (também usada como favicon) | 400x400 px, fundo branco/transparente |
| `1.webp` a `5.webp` | Prints reais das avaliações do Google (carrossel) | largura ~800 px, altura livre |
| `clinica1.webp` a `clinica4.webp` | Fotos da clínica (troca automática com fade) | proporção 4:3, ex. 1200x900 px |

Se alguma foto da clínica não for enviada, a página remove sozinha o espaço dela. O carrossel de depoimentos espera 5 prints; se enviar menos, apague os slides extras e os pontinhos correspondentes no `index.html`.

## Já configurado

- WhatsApp: `+55 24 99275-7156` (número não aparece na tela, só nos botões)
- Mensagem automática: "Olá encontrei vocês pelo Google, gostaria de atendimento."
- Google Tag Manager: `GTM-5BVRQSZN`
- Microsoft Clarity: `txwa43wbyz`
- Mapa: embed oficial do Google Maps do hospital
- Cores: roxo `#3B2270` e verde `#1F9D62` (botões de WhatsApp sempre no verde oficial `#25D366`)

## Como testar

Abra o `index.html` no navegador ou rode um servidor local:

```bash
python -m http.server 8000
```

## Publicação

Basta subir o `index.html` e as imagens `.webp` para a raiz do domínio.
