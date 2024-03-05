Чтобы создать ssh ключ надо 
1)Вводим команду ssh-keygen -t "ed25519" -C "вашапочта@phystech.edu" 
2)Добавляем ключ для SSH подключения eval "$(ssh-agent -s)" 
3)Добавляем ключ в ssh-agent ssh-add ~/.ssh/id_ed25519

Для добавления ключа в аккаунт нужно 
1)Во вкладке SSH добавить новый ключ 
2)public key взять из созданного ключа

Для клонирования репозитория 
1)git clone git@github.com:username/repository.git
