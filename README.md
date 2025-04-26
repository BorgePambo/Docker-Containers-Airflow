Esse docker-compose.yml sobe todo o ambiente do Airflow usando Docker:


Serviço	Função
postgres	Banco de dados Postgres para o Airflow guardar DAGs, usuários etc.
airflow-init	Inicializa o banco (migrações + cria usuário admin).
airflow-webserver	Interface Web para você ver e rodar os DAGs (porta 8080).
airflow-scheduler	Motor que dispara os DAGs na hora certa.
