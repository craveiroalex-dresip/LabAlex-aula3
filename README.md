# Documentacão do Modulo de Conexão

# Descrição
Este projeto implementa um padrão de conexão segura com o banco de dados, utilizando **Design Patterns** para evitar *hardcoding*.

## O que foi feito
- [x] Criação de repositório
- [x] Implementação do conflito de Merge
- [x] Resolução do conflito de merge
- [x] Separação deconfiguração

 ## Exemplo de Uso
 Abaixo, o código padrão utilizado pelo Arquiteto:

 ```python
 # Constante de configuração
 DB_HOST = "192.168.0.1"

 def conectar_banco():
     ***Conecta usando a constante definida***
     return f*Conectado ao {DB_HOST}*
