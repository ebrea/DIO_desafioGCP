# DIO_desafioGCP
1.	Criar um bucket no Cloud Storage
2.	Atualizar o arquivo contador.py com o nome do Bucket criado nas linhas que contém {SEU_BUCKET}.
3.	Fazer o upload dos arquivos contador.py e livro.txt para o bucket criado (clonados do https://github.com/marcelomarques05/dio-desafio-dataproc.git)
4.	Utilizar o código em um cluster Dataproc, executando um Job do tipo PySpark chamando gs://{SEU_BUCKET}/contador.py
5.  No Terminal Shell do GCP, executar o comando: git clone https://github.com/marcelomarques05/dio-desafio-dataproc.git  
5.	O Job irá gerar uma pasta no bucket chamada resultado. Dentro dessa pasta o arquivo part-00000 irá conter a lista de palavras e quantas vezes ela é repetida em todo o livro.
6.	O arquivo reultado.txt constam as 10 palavras mais usadas no livro.
