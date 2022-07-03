# Automacao-API-JavaScript-PetStore-Postman
Automação de API no Postman utilizando validações através do JavaScript e JsonSchema

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
