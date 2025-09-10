<img width="741" height="971" alt="desafio02 drawio" src="https://github.com/user-attachments/assets/049a2452-9ea9-4092-816c-34e483d8c84b" />
# Base Project: Gerenciando Instâncias EC2 na AWS
Fiz um diagrama para ilustrar uma arquitetura de sistema hospedado na AWS, projetada para suportar uma aplicação com acesso por funcionários:
1. Funcionários: Representam os usuários finais que acessam o sistema por meio de dispositivos como computadores.
2. Nuvem AWS: A infraestrutura principal é alocada na nuvem, acessada via uma conexão ou interface.
3. EC2: Uma instância EC2 atua como a camada de aplicação inicial, responsável por processar as requisições dos usuários.
4. EBS: O EBS é utilizado para armazenar logs e arquivos gerados pela aplicação, garantindo persistência de dados.
5. RDS: O RDS gerencia um banco de dados relacional, armazenando dados estruturados essenciais para a aplicação.
6. Backup de Fronteira e S3: Os dados da aplicação de fronteira são respaldados no Amazon S3, um serviço de armazenamento de objetos escalável e durável.
7. IAM Role: As políticas de controle de acesso (IAM Roles) definem as permissões e o nível de acesso para os serviços EC2, RDS e S3, assegurando a segurança e a segregação de responsabilidades.


