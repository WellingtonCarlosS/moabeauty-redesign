# Moabeauty Redesign

Site institucional de Moany Rocha Beauty, profissional de design de sobrancelhas e micropigmentação. A página apresenta os serviços, o processo de atendimento e trabalhos realizados, com agendamento pelo WhatsApp.

## Recursos

- Layout responsivo para celular e desktop.
- Seções sobre a profissional, atendimento, serviços, portfólio e dúvidas frequentes.
- Galeria de trabalhos com navegação por controles, teclado e toque.
- Links para agendamento pelo WhatsApp e perfil no Instagram.
- Animações que respeitam a preferência do sistema por movimento reduzido.
- Fontes e imagens armazenadas localmente no projeto.

## Tecnologias

O site é estático e construído com HTML, CSS e JavaScript, sem dependências ou etapa de compilação.

## Executar localmente

Com o Python instalado, execute na raiz do repositório:

```powershell
py -m http.server 8000 --directory .\moabeauty-main
```

Depois, abra [http://localhost:8000](http://localhost:8000) no navegador. Para encerrar o servidor, pressione `Ctrl+C` no terminal.

## Estrutura

```text
.
├── moabeauty-main/
│   ├── index.html
│   ├── fonts/
│   └── img/
├── moabeauty-redesign/
│   ├── index.html
│   └── fontes WOFF2
├── vercel.json
└── README.md
```

`moabeauty-main` é a pasta configurada para publicação e contém a página e seus recursos de imagem e fontes. `moabeauty-redesign` mantém uma versão alternativa do HTML.

## Publicação

O projeto está configurado para publicação na Vercel. O arquivo `vercel.json` define `moabeauty-main` como diretório de saída; não é necessário executar build.

## Contato

- Instagram: [@moanyrocha_beauty](https://www.instagram.com/moanyrocha_beauty/)
- Agendamentos: [WhatsApp](https://wa.me/5527988076090)
