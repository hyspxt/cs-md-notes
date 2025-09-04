
> [!definition] Definition - Schema
> 
> A <b style="color:red">schema of a relationship</b> is a **name** of a relationship $R_{\prime}$ with a set of attributes $A_{1}, ..., A_{n}$, where the relationship is defined as: $$ R(A_1, ..., A_n) $$
>A <b style="color:red">schema of a database</b> is a set of schemes of relationships $R_1, ..., R_n$ and attributes: $$ R = \{R_1(A_1), ..., R_n(A_n)\} $$
>^def-schema

> [!definition] Definition - DBMS
> 
> A <b style="color:red">DBMS</b> (DataBase Management System) is a sw that handles data collections to grant privacy, integrity and efficient
>^def-DBMS

Definizione. Un DBMS (Database Management System) é un sistema sw di gestione per collezioni di dati che garantisce privacy, efficienza, affidabilitá (damage control sw/hw) ed efficacia. Un db é un qualsiasi set di dati gestito da un DBMS. Alcuni esempi sono PostgreSQL, MySQL. Questo tipo di gestione dei dati é peró soggetta a ridondanza nel caso gli stessi dati compaiano piú volte nel database e questo puó anche portare a inconsistenza e mismatch.