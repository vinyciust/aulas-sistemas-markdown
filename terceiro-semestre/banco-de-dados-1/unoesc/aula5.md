## Modelo Relacional

Domínio para modelagem: é o que permeia a aplicação

Domínio dos dados:

### Atributo
Um item do dado, uma coluna.
            
                Nome: String
            
### Tupla
Um conjunto de pares chave-valor

                {(chave, valor)}

                Ex: {(nome, 'Highlander'), (idade, 34)}

  Tupla != Linha

  Uma consulta retorna linhas, não tuplas.

  Busca tuplas e retorna linha.

### Tabela

Cabeçalho:


### Chaves
 Identifica uma tupla

 BANCO RELACIONAL DEPENDE DE RELACIONAMENTO

 Chaves primarias: identificação única

 Chaves estrangeiras: equivalencia de valor com chave primária de outra tabela. 

            T2(fk(T1) → pk(T2))

            dominio(fk(T1)) = dominio(pk(T2))



## Modelo Lógico relacional

Regra: se tem relacionamento n pra n cria-se tabela intermediaria

