Процессор (центральный процессор или CPU) является ключевым компонентом компьютера, отвечающим за выполнение инструкций программного обеспечения и управление операциями данных.

### Из чего состоит 
##### АЛУ (Арифметико-логическое устройство):
Основное исполнительное устройство процессора, которое выполняет арифметические (например, сложение, вычитание, умножение, деление) и логические операции (например, AND, OR, NOT) над данными.

##### Регистры:
Маленькие, быстрые области памяти внутри процессора, используемые для временного хранения данных и инструкций. Регистры включают регистры общего назначения (для хранения данных и адресов), регистры состояния (для хранения флагов состояния процессора) и другие специализированные регистры (например, счетчик инструкций, указатель стека).

##### Устройство управления (Control Unit):
Координирует и управляет выполнением инструкций процессора. Он извлекает инструкции из памяти, декодирует их и управляет выполнением соответствующих операций в других компонентах процессора.
##### Шины данных и управления:
Обеспечивают связь между различными компонентами процессора и другими устройствами в компьютере. Шина данных передает данные между процессором, памятью и другими устройствами, в то время как шина управления передает управляющие сигналы, такие как сигналы управления тактовым сигналом и сигналы чтения/записи.
##### Кэш-память:
Быстрая, но ограниченная по размеру память, используемая для временного хранения наиболее часто используемых данных и инструкций. Кэш-память помогает снизить задержки при доступе к данным и инструкциям, ускоряя выполнение программ.
##### Устройство периферийной обработки (Peripheral Processing Unit):
Некоторые современные процессоры включают специализированные устройства, такие как встроенные контроллеры для работы с периферийными устройствами (например, USB, Ethernet, SATA), устройства криптографического ускорения, устройства обработки графики и т. д.

### Взаимодействие АЛУ(**Арифметико-логическое устройство**) и [[CPU core | ядра процессора]]

Взаимодействие между ядром процессора и АЛУ заключается в том, что ядро процессора управляет работой АЛУ, передавая инструкции на выполнение, извлеченные из памяти, и контролируя последовательность операций. При получении инструкции на выполнение, ядро процессора передает соответствующие операнды и операторы в АЛУ для выполнения необходимой операции. Результаты операции передаются обратно ядру процессора для сохранения в памяти или регистрах.


### Turbo Boost
Турбо-режим процессора (иногда называемый также "Turbo Boost" или "Turbo Core") представляет собой функцию, которая автоматически увеличивает тактовую частоту процессора для повышения его производительности в случае необходимости. Он используется в современных процессорах для повышения скорости работы в тех случаях, когда приложения требуют дополнительной вычислительной мощности.
Основные черты турбо-режима:
- **Автоматическое управление:** Турбо-режим управляется встроенными алгоритмами управления процессором, которые мониторят нагрузку на процессор и условия работы системы. Турбо-режим может динамически адаптироваться к изменяющимся условиям нагрузки на процессор, что позволяет использовать доступные ресурсы максимально эффективно.
    
- **Увеличение тактовой частоты:** Когда процессор обнаруживает, что нагрузка на систему высока и имеется дополнительный тепловой запас (то есть температура процессора не превышает установленные пределы), турбо-режим может автоматически увеличить тактовую частоту процессора сверх его базовой частоты. Повышение тактовой частоты позволяет процессору обрабатывать больше инструкций за единицу времени, что в конечном итоге приводит к улучшению общей производительности системы.
    
- **Тепловой контроль:** Турбо-режим учитывает тепловые ограничения и предельные значения мощности процессора, чтобы избежать перегрева или превышения тепловых пределов.


[[memory pyramid]]
[[FDE cycle]]
[[]]
[[theory]]