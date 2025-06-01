# CriandoBDAzure

Este repositório documenta a criação de um banco de dados SQL no Microsoft Azure, seguindo a trilha da DIO e a documentação oficial da Microsoft.


## Etapas Realizadas

**Grupo de Recursos:** `GrupoTeste`  
Organiza os recursos associados ao banco.

**Nome do Banco de Dados:** `dbtesting`

**Servidor:** `srvtestingiorg` (região: East US)  
Criado junto com o banco para hospedar a instância.

**Elastic Pool:** Não utilizado  
Um Elastic Pool permite compartilhar recursos (como CPU e memória) entre vários bancos de dados no Azure SQL.

**Ambiente de trabalho:** Desenvolvimento  
(otimizado para cargas de teste)

**Backup storage redundancy:**  
LRS (Local): Cópias no mesmo datacenter. Mais barato, menos seguro.
ZRS (Zona): Cópias em várias zonas da mesma região. Boa alta disponibilidade.
GRS (Geo): Cópias em outra região geográfica. Proteção contra falhas regionais.
GZRS (Geo + Zona): Combina ZRS e GRS. Máxima proteção e resiliência.
