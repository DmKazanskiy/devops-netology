# devops-netology

## 02-git-01-vsc

# Local .terraform directories
`**/.terraform/*` - Исключить из коммитов рекурсивно все директории `.terraform`

# .tfstate files

`*.tfstate` 
`*.tfstate.*` Исключить из коммитов все файлы с корневым расширением `tfstate`

# Crash log files
`crash.log` - Исключить из коммитов все файлы с именем `crash.log`

# Exclude all .tfvars files
`*.tfvars` - Исключить из коммитов все файлы с расширением `*.tfvars`

# Ignore override files as they are usually used...
```bash
override.tf
override.tf.json
*_override.tf
*_override.tf.json
```
Исключить из коммитов файлы override.tf, override.tf.json и все, заканчивающиеся на - `*_override.tf`, `*_override.tf.json`

# Include override files you do wish to add to version control using negated pattern

`!example_override.tf` - Включить в коммит все файлы с именем !example_override.tf


# Include tfplan files to ignore the plan output of command: terraform plan -out=tfplan
# example: *tfplan*

# Ignore CLI configuration files
`.terraformrc`, `terraform.rc` - Исключить из коммитов файлы с указанными наименованиями
