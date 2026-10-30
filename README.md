# PulseListen — protótipo demonstrativo

Protótipo navegável de interface para apresentação de um microserviço de Social Listening.

## Como executar
- Abra `index.html` em um navegador moderno; ou
- Sirva a pasta com qualquer servidor estático, por exemplo: `python -m http.server 8000` e acesse `http://localhost:8000`.

## O que está demonstrado
- Dashboard e indicadores ilustrativos;
- Central de menções com filtros;
- Cadastro local de afiliados;
- Contas profissionais em estado demonstrativo;
- Contrato de endpoints REST e exemplo de payload;
- Tela de sincronização simulada;
- Configurações visuais;
- Atalhos de contato com Heitor Serra Neto via WhatsApp: (19) 98248-0386.

## Limites importantes
Este é um protótipo frontend estático. Não contém backend Node.js/TypeScript, PostgreSQL, Docker, OAuth real, chamadas à API da Meta, webhooks ou persistência em servidor. Os dados e execuções são fictícios e existem apenas para demonstrar os fluxos e a proposta de integração.

A viabilidade da coleta de menções de terceiros — especialmente Stories e conteúdos de contas que não autorizam o app — precisa ser validada conforme os produtos, permissões e endpoints atualmente disponibilizados pela Meta. O projeto de produção deve respeitar estritamente a API oficial e não usar scraping.
