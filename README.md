# dashboard_integracao_mysql_azure

### Criação de relatório integrado ao MySQL e Azure

#### Integração com MySQL via Azure, tratamento de dados e criação de relatório de acompanhamento

#### Tratamento dos dados
 - Carregamento das tabelas no Power BI para tratamento de dados via Power Query;
 - Remoção de colunas da tabela "Department", "project", "works_on" e "Dependent";
 - Remoção de colunas não utilizadas da tabela "dept_locations" e mescla das colunas "Dname" e "DLocation";
 - Tabela "employee":
    - Modificação do tipo da coluna "Salary" para o tipo decimal fixo;
    - Substituição dos valores nulos na coluna "Super_ssn" para 0;
    - Divisão da coluna complexa "Address" para separação do endereço em colunas de número e rua;
    - Colunas desnecessárias removidas;
- Geração da tabela "ColaboradoresXGerentes" a partir dos códigos da coluna "Super_ssn" e "Nome completo" da tabela "employee";
- Geração da tabela "Department_X_dept_locations".

#### Criação de relatório de acompanhamento
 - Gráfico de pizza da quantidade de colaboradores por sexo;
 - Gráfico de pizza das lojas por departamento;
 - Gráfico de barras da distribuição de colaboradores por gerente;
 - Gráfico de mapa com a localização dos colaboradores.