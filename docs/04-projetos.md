# Projetos em Andamento

## Interfone IP Wi-Fi

### Descrição

Interfone IP autônomo, conectado por Wi-Fi e totalmente compatível com Home Assistant.

### Proposta de Valor

Permitir comunicação e acionamento integrado à automação residencial sem depender de soluções fechadas ou incompatíveis com o ambiente local do usuário.

### Recursos Esperados

- Conexão Wi-Fi.
- Operação autônoma.
- Integração com Home Assistant.
- Acionamento de fechadura ou relé.
- API local ou integração por MQTT, conforme arquitetura final.
- Documentação de instalação e configuração.

### Próximos Passos

- Definir hardware base.
- Validar fluxo de áudio, acionamento e alimentação.
- Definir protocolo de integração.
- Criar documentação de instalação.

## Módulo RF Wi-Fi MQTT

### Descrição

Módulo para integração de sinais RF com rede Wi-Fi e MQTT, compatível com Home Assistant.

### Proposta de Valor

Levar dispositivos RF para automações modernas, mantendo compatibilidade com fluxos locais, MQTT e Home Assistant.

### Recursos Esperados

- Comunicação Wi-Fi.
- Publicação e assinatura MQTT.
- Integração com Home Assistant.
- Aprendizado, disparo ou ponte de sinais RF, conforme hardware.
- Interface de configuração simples.

### Próximos Passos

- Definir frequências e chipset RF.
- Definir tópicos MQTT.
- Criar discovery para Home Assistant.
- Testar alcance e estabilidade.

## MonitorNFE

### Descrição

Aplicativo para download de XML de notas fiscais referentes a CNPJ cadastrado e geração de DANFE.

### Proposta de Valor

Automatizar a obtenção, organização e visualização de documentos fiscais, reduzindo trabalho manual e risco de perda de XML.

### Recursos Esperados

- Cadastro de CNPJ.
- Download de XML.
- Organização por período, emitente ou chave.
- Geração de DANFE.
- Histórico de consultas.

### Próximos Passos

- Mapear requisitos legais e certificados necessários.
- Definir arquitetura de armazenamento.
- Criar fluxo de cadastro e consulta.
- Implementar geração de DANFE.

## DASN Simples Nacional

### Descrição

Aplicativo para acompanhar faturamento de optante do Simples Nacional e demonstrativo do documento DASN.

### Proposta de Valor

Oferecer visão simples e organizada do faturamento acumulado e das informações necessárias para acompanhamento e declaração DASN.

### Recursos Esperados

- Cadastro de empresa optante.
- Controle de faturamento mensal.
- Indicadores de acumulado anual.
- Demonstrativo do DASN.
- Exportação de relatórios.

### Próximos Passos

- Definir entradas de dados.
- Validar regras do Simples Nacional aplicáveis.
- Criar telas de acompanhamento.
- Gerar demonstrativos e relatórios.

## XW-Copy

### Descrição

Gerenciador de backup para organizar, executar e acompanhar rotinas de cópia e restauração de dados.

### Proposta de Valor

Oferecer uma ferramenta simples e confiável para proteger arquivos importantes, padronizar rotinas de backup e reduzir risco de perda de dados em ambientes pessoais, técnicos ou de pequenas empresas.

### Recursos Esperados

- Cadastro de perfis de backup.
- Seleção de origem e destino.
- Execução manual ou agendada.
- Histórico de execuções.
- Validação de cópias realizadas.
- Relatórios de sucesso, falha e arquivos ignorados.
- Suporte futuro a destinos locais, rede e armazenamento externo.

### Próximos Passos

- Definir escopo da primeira versão.
- Definir plataformas alvo.
- Escolher estratégia de cópia e verificação.
- Criar modelo de configuração dos perfis.
- Projetar interface inicial para acompanhamento das rotinas.
