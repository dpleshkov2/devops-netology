
Благодаря добавленному .gitignore в данной папке будущем будут проигнорированы:

- каталоги .terraform/ на всех уровнях вложенности
- файлы с именем в формате *.tfstate и *.tfstate.*
- лог-файлы crash.log и в формате crash.*.log

- файлы в формате *.tfvars и *.tfvars.json содержащие пароли и прочие секреты

- файлы override.tf и override.tf.json, а также файлы в формате *_override.tf и *_override.tf.json

- файлы .terraformrc и terraform.rc