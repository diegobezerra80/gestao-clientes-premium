# Projeto – Atualização de Clientes Premium

## 📌 Descrição
Este projeto tem como objetivo identificar clientes elegíveis para upgrade de categoria, atualizar seus limites de crédito e gerar mensagens personalizadas de agradecimento para clientes Premium utilizando inteligência artificial.

O processamento é realizado em Python, com auxílio da biblioteca Pandas para manipulação de dados e da API do Gemini para geração automática de mensagens.

---

## 🛠️ Tecnologias Utilizadas
- Python 3
- Google Colab
- Pandas
- Google Gemini API

---

## 📂 Estrutura do Projeto
- `notebook/`: Notebook principal do projeto
- `data/`: Arquivos CSV de entrada
- `output/`: Arquivo CSV com os dados atualizados

---

## 🚀 Funcionamento
1. Leitura dos dados dos clientes a partir de arquivos CSV.
2. Identificação dos clientes elegíveis para upgrade de categoria.
3. Atualização da classificação para **Premium** e ajuste do limite do cartão.
4. Geração de mensagens curtas e personalizadas de agradecimento utilizando IA.
5. Exportação dos dados atualizados para um novo arquivo CSV.

---

## 🔐 Segurança
A chave da API utilizada para acesso ao Gemini foi armazenada de forma segura por meio do recurso **Secrets do Google Colab**, evitando a exposição de dados sensíveis no código.

---

## ▶️ Como Executar
1. Abrir o notebook no Google Colab.
2. Configurar o Secret `GEMINI_API_KEY` no ambiente do Colab.
3. Executar todas as células do notebook em sequência.

---

## 📄 Resultado
O resultado final é um arquivo `clientes_update.csv` contendo os clientes atualizados e as mensagens de agradecimento para clientes Premium.
