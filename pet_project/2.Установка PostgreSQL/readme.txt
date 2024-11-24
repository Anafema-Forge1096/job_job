Playbook устанавливает Postgresql15 и Postgresql15-server на CentOS 8 и 9, предварительно необходимо загрузить репозитрии с официального сайта Postgres, с данными ОС есть трудности, репозиториев для них нет, в данном случае использовались унифицированные репозитории для CentOS

Ссылки на репозитории и порядок установки для CentOS8:
sudo dnf install -y https://download.postgresql.org/pub/repos/yum/reporpms/EL-8-x86_64/pgdg-redhat-repo-latest.noarch.rpm

Ссылки на репозитории и порядок установки для CentOS9:
sudo dnf install -y https://download.postgresql.org/pub/repos/yum/reporpms/EL-9-x86_64/pgdg-redhat-repo-latest.noarch.rpm

Предварительно посмотреть архитектуру процессора через uname -a, в случае если архтитектура не x86_64, то пройти на https://download.postgresql.org/pub/repos/yum/reporpms/ и выбрать актуальную с актуальным репозиторием