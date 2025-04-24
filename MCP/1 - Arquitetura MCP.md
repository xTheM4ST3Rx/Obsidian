# 🛠️Tools
- São ferramentas que realizam ações. Elas são controladas pelo modelo , ou seja, **a própria LLM decide quando chamar**.
- **Autodiscovery**: LLM possui formas de entender quais tools estão disponíveis.


# 🗂️Resources
- Permite que servidores disponibilizem dados que podem ser lidos clients e usado como contexto pelo LLM.
- Resources são controlados pelo client (Application-controlled), ou seja, **o cliente decide quando usar e não o modelo**.
- **Diferente tipos de dados:** Arquivos, Banco de dados, respostas de API, Imagens, Arquivos de Log.
- Cada resource possui seu próprio URI
##### Exemplos:
- screen://host/image1
- file://caminho/file.pdf
- postgres?