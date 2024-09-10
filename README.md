# Análise de Transcrições de Vendedores

## Visão Geral

Este projeto realiza uma análise aprofundada das transcrições de ligações de Vendedores (SDRs). O objetivo é extrair insights valiosos sobre o desempenho das vendas, identificar padrões de comunicação e fornecer recomendações para melhorias.

## Funcionalidades

O script Python neste projeto realiza as seguintes tarefas:

1. Carrega dados de transcrições de múltiplos SDRs a partir de arquivos JSON.
2. Consolida os dados em um único arquivo JSON para análise abrangente.
3. Utiliza a API GPT-4 da OpenAI para analisar as transcrições consolidadas.
4. Gera um relatório de análise em formato Markdown.

## Estrutura de Arquivos

- `consolidated_data.json`: Contém todas as transcrições de SDRs consolidadas.
- `analysis_result.md`: Relatório final da análise em formato Markdown.

## Análise

A análise abrange os seguintes aspectos:

1. **Nuvem de palavras-chave**: Identifica as palavras mais frequentes e relevantes relacionadas ao processo de venda.
2. **Principais objeções**: Destaca as objeções mais comuns levantadas pelos clientes.
3. **Padrões positivos**: Identifica práticas eficazes que contribuem para o sucesso das ligações.
4. **Padrões negativos**: Detecta áreas de melhoria no desempenho das ligações.
5. **Sugestões de treinamento**: Propõe áreas de desenvolvimento para melhorar o desempenho dos SDRs.

## Como Usar

1. Certifique-se de que os arquivos JSON originais das transcrições estão na pasta correta do Google Drive.
2. Execute o script Python para gerar o arquivo JSON consolidado e a análise.
3. Acesse `analysis_result.md` para ver os insights e recomendações detalhadas.

## Requisitos

- Python 3.x
- Bibliotecas: json, os, openai
- Acesso à API da OpenAI (chave de API necessária)
- Google Colab (para integração com Google Drive)

## Notas Importantes

- Este projeto utiliza a API GPT-4 da OpenAI. Certifique-se de ter créditos suficientes e de manter sua chave de API segura.
- Os dados das transcrições são sensíveis. Garanta que apenas pessoas autorizadas tenham acesso aos resultados.

## Próximos Passos

- Implementar visualizações dos dados para facilitar a compreensão dos insights.
- Automatizar a execução periódica da análise para acompanhamento contínuo.
- Integrar os insights com sistemas de treinamento e avaliação de desempenho dos SDRs.

Para quaisquer dúvidas ou sugestões, entre em contato com [seu nome/equipe responsável].
