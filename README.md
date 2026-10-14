# volatility3-

Команда для анализа оперативной памяти 

python3 vol.py -f dump.mem windows.plugin


1. Информация о системе и процесса
         
         windows.info: Общая информация.

         windows.pslist: Список активных процессов.   

         windows.pstree: Дерево процессов.

         windows.psscan: Сканирование памяти на наличие "мертвых" или скрытых процессов.

         windows.cmdline: Показывает командную строку процесса.

2. Сетевой анализ

         windows.netscan: Показывает все TCP/UDP соединения, порты, IP-адреса и PID владельца.

         windows.netstat: Более детальный разбор сетевых стеков.

3. Файловая система и объекты
   
         windows.filescan: Поиск всех файловых объектов в памяти (даже удаленных).

         windows.dumpfiles: Извлечение конкретных файлов из памяти по их пути или inode.

         windows.dlllist: Список загруженных DLL для каждого процесса.

4. Вредоносная активность (Malware Hunting)

         windows.malfind: Ищет признаки внедрения кода. Главный инструмент против руткитов и инжекторов.

         windows.hollowprocesses: Детект техники Process Hollowing (вирус убивает легитимный процесс и заселяет его своим кодом).

         windows.suspicious_threads: Поиск потоков, работающих в подозрительной памяти.

5. Реестр и конфигурация

         windows.registry.printkey: Чтение ключей реестра прямо из дампа.

         windows.amcache: Анализ артефактов совместимости приложений.


<img width="594" height="966" alt="image" src="https://github.com/user-attachments/assets/4ae33efc-cb32-4ee2-bb40-e81da62c12db" />

Интересное тут использовался | grep= "" чтобы найти процесс по номеру

<img width="2544" height="167" alt="image" src="https://github.com/user-attachments/assets/7018fad8-6884-4dd3-ab03-f4c56a8af4e1" />

