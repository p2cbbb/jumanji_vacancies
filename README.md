### Каталог c вакансиями для Junior-разработчиков
##### Стек: Python, Django, Bootstrap, Postgresql

Ccылка на сайт: https://dnjumanji.herokuapp.com/

##### Функционал сайта: 
- размещение вакансий от лица компании 
- публикация резюме от лица соискателя 
- отклик на вакансии своим резюме

### Копирование репозитория и установка зависимостей
```bash
git clone https://github.com/p2cbbb/jumanji
cd jumanji
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
```

### Устанавливаем переменные окружения
```bash
export SECRET_KEY=<secret_key>
export DATABASE_NAME=<database_name>
export DATABASE_USER=<database_user>
export DATABASE_PASSWORD=<database_password>
export DATABASE_PORT=<database_port>
# Cloudinary stuff
export CLOUD_NAME=<cloud_name>
export API_KEY=<api_key>
export API_SECRET=<api_secret>
```