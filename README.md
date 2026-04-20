# Licitacoes.ia

> Plataforma de inteligência em licitações públicas brasileiras.
> **Em breve.** Lista de espera: lbigor@icloud.com

## O que faz

**Coleta & matching**
- Scraping contínuo do PNCP (Portal Nacional de Contratações Públicas)
- Matching em 5 camadas: palavra-chave, CNAE, localização, faixa de valor, histórico
- Deduplicação inteligente de editais retificados
- Alertas em tempo real por canal preferido (e-mail, WhatsApp, webhook)

**Gestão de participação**
- State machine do edital: triado → estudando → propondo → participando → ganho/perdido
- Cadastro de empresa com documentos (certidões, balanços, atestados)
- Validação automática de habilitação técnica e fiscal
- Cronograma unificado (sessão, impugnação, recurso, homologação)

**Inteligência de preços**
- Histórico de preços homologados por item/órgão/região
- Sugestão de lance vencedor com margem mínima configurada
- Detecção de leilão irregular (preços inexequíveis)

**Pós-ganho (V2)**
- Gestão de contratos, aditivos e reajustes
- Controle de empenhos e notas de empenho
- Acompanhamento de pagamento e glosa
- Alerta de prazos contratuais

## Para quem

Empresas que vendem para o setor público e cansaram de:
- Perder editais por não monitorar em tempo real
- Precificar sem base histórica real
- Gerenciar participação em planilha
- Descobrir o pagamento só depois do atraso

## Stack

Java 21 · Spring Boot 3 · PostgreSQL · Flyway · arquitetura de 5 camadas para o motor de match.

## Fundador

Igor Lima — 15 anos desenvolvendo ERP para clientes que vendem ao setor público.
Vivi o problema dos dois lados: quem vende (clientes Sankhya) e quem monitora (o setor).

---

**Quer acesso antecipado?** Manda e-mail pra `lbigor@icloud.com` com assunto
"Licitacoes.ia — lista de espera" + CNPJ + setor principal.
