# Projeto AI900 - Inteligência de Documentos e Mineração de Conhecimento

## Objetivo
Este projeto tem como objetivo criar e utilizar um índice no Azure AI Search para analisar dados de uma fonte, enriquecendo-os com habilidades de IA e revisando os resultados em uma Loja de Conhecimento.

### Passo a passo

1. **Crie um Recurso do Azure AI Search:**
    - Acesse o portal do Azure e clique em "+ Criar um recurso".
    - Procure por "Azure AI Search" e crie um recurso com as configurações necessárias, incluindo assinatura, grupo de recursos, nome do serviço, localização e nível de preços.
    - Após a implantação, acesse o recurso criado.

2. **Crie um Recurso de Serviços de IA do Azure:**
    - No portal do Azure, clique em "+ Criar um recurso" e procure por "Serviços de IA do Azure".
    - Crie um plano de serviços de IA do Azure com as mesmas configurações de localização do Azure AI Search.

3. **Crie uma Conta de Armazenamento:**
    - No portal do Azure, clique em "+ Criar um recurso" e procure por "Conta de Armazenamento".
    - Configure a conta de armazenamento com as configurações padrão, incluindo o acesso anônimo de Blob habilitado.

4. **Configure o Armazenamento de Dados:**
    - Crie um contêiner na conta de armazenamento para armazenar os dados de avaliação, como "Coffee-Reviews".
    - Faça o upload dos arquivos de avaliação para o contêiner criado.

5. **Indexe os Documentos:**
    - No recurso do Azure AI Search, selecione "Importar dados" e escolha "Azure Blob Storage" como fonte de dados.
    - Conecte-se à sua conta de armazenamento e selecione o contêiner de avaliações.
    - Configure as opções de enriquecimento de dados, como habilidades cognitivas e campos a serem indexados.
    - Crie um índice e um indexador para os dados importados.

6. **Consulte o Índice:**
    - Use o Search Explorer no portal do Azure para testar consultas no seu índice.
    - Escreva consultas JSON para pesquisar documentos e filtrar resultados por critérios como localização ou sentimento.

7. **Revise o Armazenamento de Conhecimento:**
    - Acesse o armazenamento de conhecimento associado ao Azure AI Search para visualizar os dados enriquecidos e as projeções.
    - Explore as tabelas e informações extraídas das avaliações usando o portal do Azure.

Este guia fornecerá uma base sólida para você criar e utilizar índices no Azure AI Search, enriquecendo seus dados com inteligência artificial e revisando os resultados na Loja de Conhecimento. Se precisar de mais alguma coisa, estou à disposição para ajudar!
