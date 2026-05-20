

структура 

my-data-pipeline/
├── dbt_project/
│   ├── models/
│   │   ├── staging/
│   │   ├── marts/
│   │   └── intermediate/
│   ├── macros/
│   ├── tests/
│   └── dbt_project.yml
│
├── airflow/
│   ├── dags/
│   │   ├── dbt_dags/
│   │   └── other_dags/
│   └── plugins/
│
├── scripts/
│
├── docker/
│   ├── docker-compose.yml
│   └── Dockerfile
│
├── .gitignore
├── requirements.txt
└── README.md


как создать проэкт


все начинаеться с одной папки проекта 
	далее создаем в гит репозиторий и связываем его с этой папкой 

    обязтельными файлами в любом проекте являются 
	    .gitignore  в этом файле перечисли все расширения файлов которым   запрешено попадание в   гит  
            так запрещаем файлы
                .env  конкретный файл
                *.log   все файлы с расширением .log
            так запрещаем папки 
                logs/ (добавь слеш в конце)
