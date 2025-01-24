
# Back-end do Project IA Documents

## Descrição
Este é o back-end do projeto que utiliza Flask para criar uma API que se comunica com o OpenAI para processar e analisar documentos.

## Instalação

1. Clone o repositório:
    ```bash
    git clone https://github.com/antonio-dev2710/project-ia-documents.git
    cd project-ia-documents/back-end-doc-ia
    ```

2. Crie um ambiente virtual e ative-o:
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows use `venv\Scripts\activate`
    ```

3. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

4. Crie um arquivo `.env` na raiz do diretório [back-end-doc-ia](http://_vscodecontentref_/0) e adicione sua chave da API OpenAI:
    ```env
    OPENAI_API_KEY=your_openai_api_key
    ```

## Uso

1. Inicie o servidor Flask:
    ```bash
    python main.py
    ```

2. Acesse a API em `http://127.0.0.1:5000`.

## Estrutura do Projeto

- `main.py`: Arquivo principal da aplicação Flask.
- `requirements.txt`: Lista de dependências do projeto.
- `vercel.json`: Configuração para deploy na Vercel.

## Deploy na Vercel

1. Certifique-se de que o arquivo `vercel.json` está configurado corretamente.
2. Faça o deploy usando a CLI da Vercel:
    ```bash
    vercel
    ```

## Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.
