[![CI](https://github.com/nogibjj/SiMinL_Week5/actions/workflows/hello.yml/badge.svg)](https://github.com/nogibjj/SiMinL_Week5/actions/workflows/hello.yml)

# SiMinL_MiniProj5

# Requirements
Create a simple python application containerized with a dockerfile. The goal here is to both demonstrate running your application within a docker container (using docker run terminal commands) but to also build a docker image in your CI/CD pipeline which will be pushed to Docker Hub or other container management service.

# Preparation
1. Open codespaces
2. Wait for container to be built and virtual environment to be activated with requirements.txt installed
3.Extract: run make extract
4. Transform and load: run make transform_load
5. Query: run make query or alternatively write your own query using python main.py general_query <insert query>

# Sample CRUD Operations
Create: python main.py create_record 'Computer Science' 'STEM' 1500 1200
Read: python main.py read_data()
Update: python main.py update_record 1 'Electrical Engineering' 'STEM' 2000 1500
Delete: python main.py delete_record 1
