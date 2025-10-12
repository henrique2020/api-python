# 🚀 API Back-End em Python com FastAPI + Uvicorn + MySQL

Este projeto é uma API RESTful desenvolvida em Python utilizando o framework FastAPI. A API se conecta a um banco de dados MySQL para realizar operações de leitura e escrita.

## 📦 Bibliotecas necessárias

Instale todas as dependências pelo comando `pip install -r requirements.txt` ou instale separadamente as bibliotecas abaixo

* bcrypt
* fastapi
* mysql.connector
* python-dotenv
* python-jose[cryptography]
* uvicorn

## 🧠 Estrutura do Projeto

```
.
├── python-api/
│   ├── dao/
│   │   ├── Database.py
│   │   ├── ExemploDAO.py
│   │   └── ...
│   ├── model/
│   │   ├── Exemplo.py
│   │   └── ...
│   ├── main.py
│   ├── middleware.py
│   ├── routes.py
│   ├── .env
│   └── requirements.txt
└── README.md
```

## ▶️ Execução

```cmd
cd ./api
uvicorn main:app
```

| Comando  | Descrição                                                                 |
| -------- | --------------------------------------------------------------------------- |
| --reload | Recarrega automaticamente o servidor em alterações (para desenvolvimento) |

_OBS.: A senha é a 1ª parte do e-mail_

## ⚠️ Disclaimer
Este projeto foi desenvolvido para trabalho o final da matéria de **Laboratório de Software (UCS)**, quaisquer informações presentes foram repassadas pelos professores.

Os `nomes/emails` dos docentes foram alterados para evitar qualquer tipo de exposição indesejada por parte da universidade.