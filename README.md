# devops-netology
DevOps Netology homework

# DevOps Netology

## Игнорируемые файлы (Terraform)

Благодаря `terraform/.gitignore` из репозитория исключаются:
- каталоги `.terraform/` — локальные копии провайдеров;
- файлы состояния `*.tfstate` и `*.tfstate.*` — содержат чувствительные данные;
- журналы сбоев `crash.log`, `crash.*.log`;
- файлы переменных `*.tfvars`, `*.tfvars.json` — могут содержать секреты;
- файлы переопределений `override.tf`, `override.tf.json`, `*_override.tf`, `*_override.tf.json`;
- конфигурации CLI `.terraformrc`, `terraform.rc`.
