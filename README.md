# Análise de Chamadas / Ligações de Vendas com IA

Este projeto utiliza Inteligência Artificial para transcrever e analisar chamadas de vendas, fornecendo insights para melhorar o desempenho dos SDRs (Representantes de Desenvolvimento de Vendas).

## Estrutura do Projeto

1. `1_transcricao_ligacoes.py`: Transcreve arquivos de áudio usando o modelo Whisper da OpenAI.
2. `2_analise_consolidada.py`: Analisa as transcrições e gera insights usando o modelo GPT da OpenAI.

3. A estrutura do projeto e dos arquivos devem estar conforme abaixo:

![Claude](https://github.com/user-attachments/assets/426f6948-ae7d-4220-a55e-76ec87f50583)

## Funcionalidades

- Transcrição automatizada de arquivos de áudio MP3
- Análise de sentimento das transcrições de chamadas
- Identificação de objeções comuns e padrões de vendas
- Geração de nuvens de palavras e estatísticas-chave
- Análise individual e consolidada do desempenho dos SDRs

## Pré-requisitos

- Python 3.x
- Chave de API da OpenAI
- Google Colab (para executar os notebooks)
- Acesso ao Google Drive (para armazenar arquivos de áudio e resultados)

## Configuração

1. Clone este repositório para seu Google Drive.
2. Certifique-se de ter as chaves de API necessárias configuradas em seu ambiente Google Colab.
3. Instale as bibliotecas necessárias:
   ```
   !pip install openai nltk matplotlib wordcloud
   ```

## Uso

1. **Transcrição**:
   - Coloque os arquivos MP3 nas pastas apropriadas dos SDRs dentro do diretório `ai_gri` no Google Drive.
   - Execute `1_transcricao_ligacoes.py` para transcrever todos os arquivos de áudio.

2. **Análise**:
   - Execute `2_analise_consolidada.py` para realizar a análise individual e consolidada das transcrições.
   - O script irá gerar visualizações e salvar os resultados da análise em formato markdown.

## Saída

- Arquivos JSON contendo transcrições de chamadas para cada SDR
- Arquivo markdown com análise detalhada de padrões de vendas, objeções e sugestões de melhoria
- Visualizações incluindo distribuição de sentimentos, análise de duração de chamadas e nuvens de palavras

## Contribuições

Contribuições para melhorar os algoritmos de análise ou adicionar novas funcionalidades são bem-vindas. Por favor, envie um pull request com suas alterações propostas.

## Licença

[Licença MIT](LICENSE)

## Agradecimentos

- OpenAI por fornecer os modelos Whisper e GPT
- NLTK pelas ferramentas de processamento de linguagem natural
