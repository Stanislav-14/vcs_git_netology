Second line

---

При добавлении в файл .gitignore будут игнорироваться следующие файлы  
.terraform/ локальные дирректории terraform которые скрыты  
*.tfstate  
*.tfstate.* это файлы состоянии инфраструктуру, созданной с помощью terraform  
crash.log  
crash.*.log файлы логов  
*.tfvars  
*.tfvars.json переменные terraform, которые не должны попадать в комит  
override.tf
override.tf.json
*_override.tf
*_override.tf.json  
.terraform.tfstate.lock.info
.terraformrc
terraform.rc это также все чувствительные файлы с перменными, конфигурацией, секретами, данные, которые не надо выставлять на публичное обозрение