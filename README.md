# BNT  
## BNT(Base nacional de transito)
### Simulação de BNT utilizando _PostgreSQL_
#### -*Conteudo do repositorio*:

>
> * **Script do Banco** [:arrow_upper_right:](https://github.com/Brunbg/p3-BD2/blob/master/documentos/1-script-criacao.sql)  
>
> * **Inserts** [:arrow_upper_right:](https://github.com/Brunbg/p3-BD2/blob/master/documentos/2-inserts.sql)  
>
> * **Functions** [:arrow_upper_right:](https://github.com/Brunbg/p3-BD2/blob/master/documentos/3-views-funcoes-procedures.sql)  
>
> * **Procedures** [:arrow_upper_right:](https://github.com/Brunbg/p3-BD2/blob/master/documentos/3-views-funcoes-procedures.sql)  
>
> * **Views** [:arrow_upper_right:](https://github.com/Brunbg/p3-BD2/blob/master/documentos/3-views-funcoes-procedures.sql)  

#### *Tabelas do Banco*
> ###### :small_orange_diamond: **Primary Key**  
> ###### :small_blue_diamond: **Foreign Key**  
> ----
>|**ESTADO**|**CIDADE**|**ESPECIE**|**CATEGORIA_VEICULOS**|**TIPO**|
>|----------|----------|-----------|--------------------|---------|
>| UF :small_orange_diamond:|IDCIDADE :small_orange_diamond:|IDESPECIE :small_orange_diamond:|IDCATEGORIA :small_orange_diamond:|IDTIPO :small_orange_diamond:|
>| NOME |NOME|DESCRICAO|DESCRICAO|DESCRICAO|  
>|      |UF :small_blue_diamond:| |IDESPECIE :small_blue_diamond:| | 
>  
>|**MARCA**|**MODELO**|**CATEGORIA_CNH**|**INFRACAO**|
>|---------|----------|-----------------|------------|
>|IDMARCA :small_orange_diamond:|IDMODELO :small_orange_diamond:|IDCATEGORIACNH :small_orange_diamond:|IDINFRACAO :small_orange_diamond:|
>|NOME|DENOMINACAO|DESCRICAO|DESCRICAO|
>|ORIGEM|IDMARCA :small_blue_diamond:| |VALOR|
>| |IDTIPO :small_blue_diamond:| |PONTOS|  
>  
>|**CONDUTOR**|**VEICULO**|**MULTA**|
>|------------------|-----------|---------|
>|IDCADASTRO :small_orange_diamond:|RENAVAM :small_orange_diamond:|IDMULTA :small_orange_diamond:|
>|CPF|PLACA|RENAVAM :small_blue_diamond:|
>|NOME|ANO|IDINFRACAO :small_blue_diamond:|
>|DATANASC|IDCATEGORIA :small_blue_diamond:|IDCONDUTOR :small_blue_diamond:|
>|IDCATEGORIACNH :small_blue_diamond:|IDPROPRIETARIO :small_blue_diamond:|DATAINFRACAO|
>|ENDERECO|IDMODELO :small_blue_diamond:|DATAVENCIMENTO|
>|BAIRRO|IDCIDADE :small_blue_diamond:|DATAPAGAMENTO|
>|IDCIDADE :small_blue_diamond:|DATACOMPRA|VALOR|
>|SITUACAOCNH|DATAAQUISICAO|JUROS|
>| |VALOR|VALORFINAL|
>| |SITUACAO|PAGO| 
>  
>|**TRANSFERENCIA**|**LICENCIAMENTO**|
>|-----------------|-----------------|
>|IDHISTORICO :small_orange_diamond:|ANO :small_orange_diamond:|
>|RENAVAM :small_blue_diamond:|RENAVAM :small_orange_diamond: :small_blue_diamond:|
>|IDPROPRIETARIO :small_blue_diamond:|DATAVENC|
>|DATACOMPRA|PAGO|
>DATAVENDA| |



          
          https://blog.da2k.com.br/2015/02/08/aprenda-markdown/
          https://medium.com/@raullesteves/github-como-fazer-um-readme-md-bonit%C3%A3o-c85c8f154f8
     







