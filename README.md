# Modern Data Stack Project


## O objetivo desse projeto é criar um pipeline completo, utilizando ferramentas atuais de mercado como Snowflake e DBT.

### Requirements:

O pipeline foi desenvolvido utilizando plataformas cloud, sendo assim é necessario contas de acesso nos seguintes ambiente:

- Snowflake
- DBT

### WHAREHOUSE:

#### View's de origem:
   ##### STG_TPCH_SF1__CUSTOMER

![GET](images/customer.png)

   ##### STG_TPCH_SF1__NATION

![GET](images/nation.png)

   ##### STG_TPCH_SF1__REGION

![GET](images/region.png)

##### Tabela dimensão para load

   ##### DIM_CUSTOMER


![GET](images/dim01.png)


### Transformação:
 
     dim_customer.sql

![GET](images/flow.png)
    
    Logs:


![GET](images/execute.png)








