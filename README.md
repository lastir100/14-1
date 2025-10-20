# 14-1
Домашнее задание к занятию «Системы контроля версий» - Минин Александр

README.md modified 20.10.2025

добавлены .gitignore, ./terraform/.gitignore

```
в ./terraform/.gitignore добавлено содержание для игнорирования добавления в git:

папка .terraform/

файлы .tfsatate - файлы содержащие .tfsatate. в названии или расширение .tfsatate

файлы жуналов crash - crash.log или файлы с именем crash. вначале файла и одновременно с расширением .log 

файлы .tfvars с чуствительной информацией - с расширением .tfvars или .tfvars.json

файлы переопределения - override.tf, override.tf.json, *_override.tf, *_override.tf.json

файл блокировки, созданный terraform - .terraform.tfstate.lock.info

файлы конфигурации CLI - .terraformrc, terraform.rc
```
