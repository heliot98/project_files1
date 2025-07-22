# 📂 Project Files 1

## 📌 Descrição (Português)
Este projeto em **Java** lê um arquivo CSV contendo uma lista de produtos com **nome**, **preço** e **quantidade**.  
Após a leitura, o programa calcula o **valor total** de cada produto (`preço x quantidade`) e gera um novo arquivo chamado `summary.csv`, que é salvo automaticamente dentro de uma pasta `out` criada no mesmo diretório do arquivo de origem.

✅ **Principais funcionalidades:**
- Leitura de arquivos CSV.
- Criação automática de uma pasta de saída.
- Escrita de um novo arquivo CSV com dados processados.
- Manipulação de dados usando classes e listas.

---

## 🚀 Como executar (Português)
### ✔ Pré-requisitos
- Java JDK 8 ou superior instalado.
- Um arquivo CSV de entrada com formato:  
  `Nome,Preço,Quantidade` (separados por vírgula).

Exemplo de arquivo de entrada (`produtos.csv`):
TV,1000.0,2
VideoGame,1500.0,1
Geladeira,2000.0,1

bash


### ▶ Passos para rodar
1. Clone o repositório:
   ```bash
   git clone https://github.com/heliot98/project_files1.git
Abra o projeto em sua IDE Java preferida (Eclipse, IntelliJ, VS Code com extensão Java).

Compile e execute a classe Program.java.

Quando solicitado, digite o caminho completo do seu arquivo CSV.

Após a execução, verifique a pasta out no mesmo diretório do arquivo original. Lá estará o arquivo summary.csv.

📄 Saída gerada
Para o exemplo acima, o arquivo summary.csv conterá:


TV,2000.00
VideoGame,1500.00
Geladeira,2000.00
📦 Estrutura do projeto
bash
Copiar
Editar
src/
 ├── application/
 │    └── Program.java       # Classe principal com a lógica de leitura e escrita
 ├── entities/
 │    └── Product.java       # Classe que representa o produto e calcula total
✨ Melhorias futuras
Tratar possíveis erros de formatação no CSV.

Permitir configuração do delimitador (vírgula, ponto e vírgula, etc.).

Criar testes unitários para validar a lógica.

🌎 English Version
📌 Description
This Java project reads a CSV file containing a list of products with name, price, and quantity.
After reading, it calculates the total value of each product (price x quantity) and generates a new file named summary.csv, automatically saved inside an out folder created in the same directory as the source file.

✅ Main features:

Read CSV files.

Automatically create an output folder.

Write a new CSV file with processed data.

Use of classes and lists to manage data.

🚀 How to run
✔ Requirements
Java JDK 8 or higher.

An input CSV file with the format:
Name,Price,Quantity

Example (products.csv):


TV,1000.0,2
VideoGame,1500.0,1
Geladeira,2000.0,1
▶ Steps
Clone the repository:

bash

git clone https://github.com/heliot98/project_files1.git
Open the project in your favorite Java IDE (Eclipse, IntelliJ, VS Code with Java).

Compile and run Program.java.

When prompted, enter the full path to your CSV file.

After execution, check the out folder in the same directory as the source file. The summary.csv will be there.

📄 Output example
For the example above, summary.csv will contain:


TV,2000.00
VideoGame,1500.00
Geladeira,2000.00
✨ Future improvements
Handle CSV formatting errors.

Allow custom delimiter configuration.

Add unit tests for validation.

✍ Author: Hélio Tarquínio
📌 Repository: project_files1
