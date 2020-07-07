# ENGLISH

## Playbook made to create backups from Cisco IOS Devices
### Pre-req
- Create the destination directory, then configure it into the ```backup-confs-ios.yml``` on the **backup_root** variable.
- Include the device credentials on ```creds.yml```.
- Include the host addresses on ```hosts.ini```

### Running
To get this playbook executed, run like the following:

```ansible-playbook -i hosts.ini backup-confs-ios.yml```

If no error appears, the backup files will be on the configured directory.

---------

# PORTUGUÊS

## Playbook criado para realização de backups de equipamentos Cisco com IOS

### Pre-requisitos: 
- Necessário criar o diretório de destino dos backups e configurar o caminho na variável **backup_root** no arquivo ```backup-confs-ios.yml```.
- Necessário incluir as credenciais dos equipamentos no arquivo ```creds.yml```
- Necessário incluir os hosts no arquivo ```hosts.ini```

### Execução
Para executar, utilize o comando como no exemplo:

```ansible-playbook -i hosts.ini backup-confs-ios.yml```

Caso nenhum erro seja apresentado na execução do playbook, os arquivos com o backup das configurações estarão no diretório configurado.