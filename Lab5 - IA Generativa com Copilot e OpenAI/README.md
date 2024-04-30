# Projeto-05-AI900
## IA Generativa

### Objetivo
O objetivo deste projeto é criar um ambiente no Azure para utilizar o serviço Azure OpenAI, permitindo o acesso a modelos generativos de IA desenvolvidos pela OpenAI. Implementar um modelo específico (gpt-35-turbo) no Azure OpenAI Studio para gerar conteúdo em linguagem natural, demonstrando a capacidade de utilizar modelos de IA em cenários de interação textual. Além disso, entender e experimentar os filtros de conteúdo padrão do Azure OpenAI, bem como a possibilidade de criar filtros personalizados, visando garantir a aplicação de princípios de IA responsável e segura em interações geradas pela IA.

### Passo a Passo
O passo a passo está disponível na documentação oficial da Microsoft:

1. Explore o [Microsoft Copilot](https://www.microsoft.com/pt-br/microsoft-365/microsoft-office) no Microsoft Edge
2. Explore o [Azure OpenAI](https://azure.microsoft.com/pt-br/services/cognitive-services/openai/)
3. Explore [filtros de conteúdo](https://docs.microsoft.com/pt-br/azure/cognitive-services/openai-content-filters) no Azure OpenAI
4. Explore a IA generativa com o [Microsoft Copilot](https://copilot.github.com/)

### Preparação

#### Instalação e Acesso
1. Instale o [Microsoft Edge](https://www.microsoft.com/pt-br/edge)
2. Crie uma conta da [Microsoft](https://signup.live.com)
3. Faça login no Microsoft Edge usando sua conta da Microsoft

#### Acesso ao OneDrive e Documento
1. Acesse o [OneDrive](https://onedrive.live.com)
2. Baixe o documento Business Idea.docx [aqui](https://github.com/MicrosoftLearning/mslearn-ai-fundamentals/raw/main/data/generative-ai/Business%20Idea.docx) e salve-o na pasta Documentos do OneDrive

### Uso do Copilot
1. Ative o Copilot no Microsoft Edge
2. Interaja com o Copilot fazendo perguntas como "What is this document about?" e "What's the market opportunity for this business idea?"
3. Siga as respostas do Copilot para desenvolver um plano de negócios e criar uma apresentação

### Criação de um Plano de Negócios e Apresentação
1. Escreva o Plano de Negócios com base nas respostas do Copilot
2. Use o PowerPoint para criar uma apresentação com base nos insights gerados

### Redação de um E-mail
1. Inicie o Outlook
2. Componha um e-mail para investidores com a ajuda do Copilot para gerar o conteúdo

### Desafio Opcional
Tente explorar mais o Copilot em uma nova sessão para planejar um evento de promoção da alfabetização infantil em uma biblioteca local

### Provisão do Recurso Azure OpenAI
1. Acesse o [Portal do Azure](https://portal.azure.com)
2. Crie um recurso Azure OpenAI com as seguintes configurações:
   - Assinatura: Sua assinatura do Azure
   - Grupo de recursos: Escolha um existente ou crie um novo
   - Região: Leste dos EUA
   - Nome: Um nome exclusivo de sua escolha
   - Nível de preços: Padrão S0

### Exploração do Azure OpenAI Studio
1. Acesse o Azure OpenAI Studio
2. Explore as páginas disponíveis, como Modelos, Implantações, Playground do Chat e Playground DALL-E

### Implantação de um Modelo de Geração de Texto
1. Na página Modelos, escolha um modelo gpt-35-turbo com status "Implantável" como Sim e clique em "Implantar"
2. Configure a nova implantação com as opções necessárias

### Geração de Imagens com DALL-E
1. No Azure OpenAI Studio, vá para o playground DALL-E
2. Insira prompts para gerar imagens com base nas descrições fornecidas

### Explorar Filtros de Conteúdo
1. No Azure OpenAI Studio, vá para a página de Filtros de Conteúdo
2. Selecione "Criar filtro de conteúdo personalizado" para revisar as configurações padrão e personalizadas dos filtros de conteúdo

### Limpeza
Quando terminar, lembre-se de limpar os recursos no portal Azure para evitar custos adicionais. Você pode remover a implantação específica ou todo o recurso Azure OpenAI, conforme necessário.
