# Docker local analytics build

### Includes

- Jupyter-notebook (pip libs: <a href="docker/jupyter-notebook/requirements.txt" target="_blank">requirements.txt</a>)
- PostgreSQL
- Clickhouse

### How to start
1. Make sure you have <a href="https://docker.com" target="_blank">Docker</a> installed
2. Navigate to the current repository path in your storage, using cli
3. Run in cli: `docker-compose up -d` 
<br/>or specified containers: `docker-compose up -d jupyter-notebook db-postgres db-clickhouse`
4. Use, e.g., Jupyter-notebook: <a href="http://localhost:8888" target="_blank">http://localhost:8888</a>

### Data
Jupyter-notebook workfolder: 
<br>`./data/notebook/work`

PostgreSQL data:
<br>`./data/postgresql`

Clickhouse data:
<br>`./data/clickhouse`

### Connection parameters
<a href=".env" target="_blank">look at .env file</a>
