# Playbook criado para realização de backups de equipamentos cisco com IOS

## Pre-requisitos: 
- Necessário criar o diretório de destino dos backups e configurar o caminho na variável **backup_root** no arquivo ```backup-confs-ios.yml```.
- Necessário incluir as credenciais dos equipamentos no arquivo ```creds.yml```
- Necessário incluir os hosts no arquivo ```hosts.ini```

## Execução

```ansible-playbook -i hosts.ini backup-confs-ios.yml```

Caso nenhum erro seja apresentado na execução do playbook, os arquivos com o backup das configurações estarão no diretório configurado.