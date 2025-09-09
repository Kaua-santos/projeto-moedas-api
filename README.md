# 💱 Cotação de Moedas - Python + AwesomeAPI

Este é um projeto Python simples para consultar a **cotação de moedas em tempo real** utilizando a [AwesomeAPI](https://docs.awesomeapi.com.br/).

## 🚀 Funcionalidades

- ✅ Consulta de cotação de moedas como USD, EUR, BTC, entre outras
- ✅ Integração com a AwesomeAPI via requisições HTTP
- ✅ Retorno formatado com valores de compra, venda e variação
- ✅ Suporte a múltiplas moedas

## 📁 Estrutura do Projeto

├── src/ # Código-fonte
│ └── cotacao.py # Script principal de cotação
├── requirements.txt # Dependências do projeto
├── README.md # Documentação do projeto
└── main.py # Arquivo principal (execução)

less
Copiar código

## 🛠️ Tecnologias Utilizadas

- Python 3.x
- [Requests](https://pypi.org/project/requests/) – para fazer requisições HTTP
- AwesomeAPI – para dados de câmbio (https://docs.awesomeapi.com.br/)

## 📦 Instalação

Clone o repositório:

```bash
git clone https://github.com/seu-usuario/cotacao-moedas-python.git
cd cotacao-moedas-python
Crie um ambiente virtual (opcional):

bash
Copiar código
python -m venv venv
source venv/bin/activate      # Linux/Mac
venv\Scripts\activate         # Windows
Instale as dependências:

bash
Copiar código
pip install -r requirements.txt
▶️ Como Usar
Execute o script principal:

bash
Copiar código
python main.py
Você pode personalizar para buscar diferentes moedas. Exemplo de chamada usando o módulo cotacao.py:

python
Copiar código
from src.cotacao import buscar_cotacao

moeda = "USD-BRL"
cotacao = buscar_cotacao(moeda)
print(cotacao)
🧪 Exemplo de Retorno
json
Copiar código
{
  "USD": {
    "code": "USD",
    "codein": "BRL",
    "name": "Dólar Americano/Real Brasileiro",
    "bid": "5.1300",
    "ask": "5.1400",
    "high": "5.1600",
    "low": "5.1000",
    "varBid": "0.0200",
    "pctChange": "0.39",
    "timestamp": "1694265600"
  }
}
🤝 Contribuindo
Contribuições são bem-vindas!
Sinta-se à vontade para abrir uma issue ou enviar um pull request com sugestões, melhorias ou correções.

📄 Licença
Este projeto está licenciado sob a MIT License.

Desenvolvido com ❤️ por [Seu Nome ou @seu-usuario]

yaml
Copiar código
