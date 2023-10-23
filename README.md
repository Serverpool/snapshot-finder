# ServerPool local snapshot-finder

Форк оригинального solana-snapshot-finder, адаптированного для поиска Mainnet снепшотов сети Solana в локальной сети ДЦ [ServerPool.io](https://serverpool.io/).

#### Как работает скрипт?

- Скрипт работает аналогично оригинальному solana-snapshot-finder.
- Подробную инструкцию по запуску файндера, использованию флагов и дополнительную информацию смотрите здесь: [solana-snapshot-finder](https://github.com/c29r3/solana-snapshot-finder)


#### Установка без docker'а
``` 
sudo apt-get update \
&& sudo apt-get install python3-venv git -y \
&& git clone https://github.com/Serverpool/snapshot-finder.git \
&& cd snapshot-finder \
&& python3 -m venv venv \
&& source ./venv/bin/activate \
&& pip3 install -r requirements.txt
```

#### Запуск скрипта
`
python3 main.py --snapshot_path /путь_к_папке_со_снепами
`

#### Обновление скрипта
 `git pull https://github.com/Serverpool/snapshot-finder.git`
