# Automacao-API-JavaScript-PetStore-Postman
A automação de API no Postman foi validado o Response Body através de JavaScript e JsonSchema, funções para gerar variáveis dinâmicas, WorkFlow e Loop para validar cenários sem a necessidade de duplicar Requests.

Foi utilizado no projeto o intepretador em Node JS, JavaScript e o Newman htmlextra.

Seguem os comandos para executar o Newman no Git Bash:

Instalação do Newman para obter o relatório no terminal/Git Bash e para obter o relatório via htmlextra:
npm install -g newman // 
npm install -g Newman-reporter-htmlextra

Verificar a versão instalada do Newman:
newman –v

Comandos para gerar o relatório no terminal/Git Bash ou o relatório em htmlextra:
newman run <name_file.postman_collection.json> -e <name_file.postman_environment.json> // 
newman run <name_file.postman_collection.json> -e <name_file.postman_environment.json –-reporters=cli,htmlextra>
