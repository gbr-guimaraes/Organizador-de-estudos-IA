# Projeto-organizador-de-estudos
Este é um projeto desenvolvido utilizando a linguagem Python e o ambiente de progamacão Google colabs. O projeto se trata de uma ferramenta que utiliza a API Google Generative AI e PyPDF2 para auxiliar estudantes com foco em concursos públicos a organizar seus estudos em um cronograma a parttir do edital em formato PDF.

# Funcionalidades:
**Upload de arquivo PDF:** Utiliza as bibliotecas PyPDF2 e ipywidgets para receber um arquivo PDF do usuário e envia-lo para processamento pelo modelo Generative AI.

**Identifica cargos disponíveis:** Pede ao modelo Generative AI para listar os cargos disponíveis no edital a partir do texto extraído.

**Gera cronograma de estudos personalizado:** Com base no cargo escolhido, dias e horas disponíveis para estudo, o script solicita ao modelo Generative AI a criação de um cronograma de estudos personalizado.

**Interface amigável:** O script usa ipywidgets para fornecer uma interface simples para carregar o PDF, selecionar opções e gerar o cronograma.

# Requisitos:
- Python 3
- Biblioteca google-generativeai
- Biblioteca PyPDF2
- Biblioteca ipywidgets *(para uso interativo)*

# Instruções:
1 - **Configurar a chave de API:** Obtenha uma chave de API do Google Generative AI e armazene-a como uma variável de ambiente chamada API_KEY.
Alternativamente, você pode substituir diretamente API_KEY no script com sua chave real *(Não recomendado)*.

2 - **Executar o script:** Execute o script em um ambiente Python com as bibliotecas necessárias instaladas.

3 - **Siga as instruções exibidas na interface:**
    <li> Carregue o arquivo PDF do edital do concurso público.
    <li> Insira seu nome.
    <li> Selecione o cargo desejado na lista suspensa *(Preenchida após o upload do PDF. Pode demorar alguns segundos para atualizar)*.
    <li> Escolha os dias da semana que você tem disponível para estudar.
    <li> Especifique o número de horas que você pode dedicar por dia.
    <li> Clique no botão "Gerar" para obter seu cronograma de estudos personalizado *(Pode demorar alguns segundos para ser gerada)*.
  
# Observações:
- A qualidade do cronograma de estudos gerado depende das informações fornecidas no PDF e das capacidades do modelo Generative AI.
