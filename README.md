## NikrexV2-это-это инструмент для SMS-спама 💣 (работает на termux,windows,linux)


## Установка:
* Windows:
  * Установите Python 3.8 (https://www.python.org/downloads/release/python-38).
  * Запустите установщик, нажмите «добавить python в путь».
  * Установите  NikrexV2.
  * Откройте cmd или powershell в каталоге NikrexV2.
  * Выполните эту команду: `pip install -r requirements.txt`.
  * А это: `python Nikrexv2.py `.

* Termux:
  * `pkg update`.
  * `pkg install python3 python3-pip git -y`.
  * `git clone https://github.com/nkolotovkinOfficial/NikrexV2/`.
  * `cd Nikrexv2/`.
  * `pip3 install -r requirements.txt`.
  * `python3 Nikrexv2.py --help`.

## Пример SMS и звонков:
```python Nikrexv2.py --method SMS --time 20 --threads 15 --target +79771234567```
