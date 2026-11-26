# Plataforma de Gestão de Eventos e Ingressos

## Integrantes do Grupo
- Matheus Arouca Cidale Pereira (RGM: 11262101166)
- Alison José dos Anjos (RGM: 11261105005)
- Lucas Eduardo Ramos (RGM: 11261104446)
- Felipe Natã Mendes Moreira (RGM: 11261103561)

## Ambiente Utilizado
-SGBD: MYSQL 8.0.36
-Ferramenta: MYSQL Workbench /DBeaver

## Ordem de Execução dos Scripts 
1. Executar 01_ddl_estrutura.sql para criar o schema e tabelas.
2. Executar 02_dml_carga.sql para popular os dados iniciais.
3. Executar 03_objetos_prog.sql para compilar Views, Functions, Procedures e Triggers.
4. Executar 04_dql_consultas.sql para visualizar os relatórios analíticos.
5. Executar 05_dtl_testes.sql para validar as regras de negócio e testes.

## Justificativa dos Índices Criados
- idx_evento_data_status: criado nas colunas (data_inicio, status) da tabela evento para acelerar buscas de eventos futuros ativos na tela inicial.
- idx_pedido_participante: criado na coluna id_participante da tabela pedido para otimizar o histórico de compras do usuário.


