Projeto Microsserviços com Docker
🚀 Sobre o Projeto
Este projeto demonstra a criação de uma estrutura de Microsserviços utilizando Docker e Docker Compose. Cada serviço é independente, containerizado e se comunica através de uma rede definida no Compose.

A ideia é aplicar as melhores práticas de construção de microsserviços em ambientes isolados, com fácil escalabilidade e manutenção.

🛠️ Tecnologias Utilizadas
* Docker 🐳
* Docker Compose ⚙️
* Python (Flask) 🐍
* (Opcional) Banco de dados PostgreSQL ou MongoDB
* Linux (ou WSL / Mac / Cloud)

📂 Estrutura do Projeto

docker-microservices-project/
│
├── user-service/
│   ├── app.py
│   ├── requirements.txt
│   └── Dockerfile
│
├── product-service/
│   ├── app.py
│   ├── requirements.txt
│   └── Dockerfile
│
├── docker-compose.yml
├── .env
└── README.md
Cada serviço é containerizado separadamente para garantir a independência e a portabilidade entre ambientes.

⚙️ Como Executar o Projeto
É necessário ter o Docker e o Docker Compose instalados na sua máquina.

Suba os containers:
* docker-compose up --build
  
Acesse os serviços:
* User Service: http://localhost:5000
* Product Service: http://localhost:5001

🚀 Melhorias Futuras

* Conectar serviços a um banco de dados.
* Implementar autenticação JWT.
* Criar uma API Gateway para gerenciamento de rotas.
* Deploy automático com CI/CD.
* Subir o projeto para um ambiente cloud (AWS EC2, ECS, etc).

📚 Referências

Documentação Oficial do Docker
Flask Documentation
Guia Oficial de Microsserviços
