  
RAM (Random Access Memory) или оперативная память - это один из основных видов памяти в компьютере, используемый для временного хранения данных и инструкций, которые обрабатываются центральным процессором (CPU).  Она предоставляет CPU быстрый доступ к данным и инструкциям, что увеличивает скорость работы компьютера.
### **Виды оперативной памяти**:
    
- **DRAM (Dynamic Random Access Memory)**: Это самый распространенный тип оперативной памяти, который используется в современных компьютерах. Он требует периодического обновления данных (refresh), что делает его "динамическим".
- **SRAM (Static Random Access Memory)**: Этот тип памяти более быстрый и стабильный, чем DRAM, но он более дорог и обычно используется в качестве кэш-памяти на уровне процессора или встроенной памяти.
### **Типы форм-факторов**:
Оперативная память поставляется в различных форм-факторах, таких как [[dimm sodimm| DIMM и SODIMM ]], а также встроенные модули памяти для специализированных устройств.
### **Память с ошибками (ECC и Non-ECC)**:
Некоторые оперативные модули памяти поддерживают функцию исправления ошибок (ECC - Error-Correcting Code), которая позволяет обнаруживать и исправлять ошибки в данных. Другие модули не имеют такой функции и называются Non-ECC.
###  **Память двухканального режима**:
Двухканальный режим оперативной памяти (Dual-channel mode) - это режим работы, который позволяет компьютеру использовать два канала для передачи данных между оперативной памятью (RAM) и центральным процессором (CPU). Вот основные характеристики и преимущества двухканального режима
#### **Как это работает**
 - В двухканальном режиме оперативная память подключается к системной плате с помощью двух независимых каналов (обычно это два слота DIMM).
 - Каждый канал может передавать данные независимо от другого, что позволяет увеличить пропускную способность и скорость передачи данных между памятью и процессором.
#### **Преимущества**
    
- **Увеличенная пропускная способность**: Двухканальный режим позволяет увеличить пропускную способность системной шины памяти, что улучшает скорость доступа к данным.
- **Улучшенная производительность**: Благодаря повышенной пропускной способности двухканальной памяти, процессор может более эффективно получать данные из оперативной памяти, что может привести к улучшению производительности системы, особенно в задачах, требующих интенсивной работы с памятью.
- **Более стабильная работа**: Двухканальный режим также может обеспечить более стабильную работу системы, так как данные могут быть более равномерно распределены между двумя каналами.

### Стандарты ОЗУ
DDR (Double Data Rate) - это стандарт оперативной памяти, который позволяет удваивать скорость передачи данных по сравнению с обычной SDR (Single Data Rate) памятью. Он был разработан в ответ на потребность в более быстрой оперативной памяти для современных компьютерных систем.

Основные характеристики DDR:
1. **Удвоенная скорость передачи данных**: DDR использует технологию передачи данных на спадающем и нарастающем фронтах тактового сигнала, что позволяет удвоить скорость передачи данных по сравнению с SDR.
    
2. **Повышенная пропускная способность**: Благодаря удвоенной скорости передачи данных, DDR обеспечивает более высокую пропускную способность, что позволяет улучшить производительность компьютерных систем.
    
3. **Меньшее потребление энергии**: DDR использует меньшее напряжение питания по сравнению с некоторыми предыдущими стандартами оперативной памяти, что делает его более энергоэффективным.
    
4. **Совместимость**: Многие современные компьютеры поддерживают различные поколения стандарта DDR, что обеспечивает совместимость с различными типами оперативной памяти.
    
#### Сравнение стандартов памяти
DDR был заменен более новыми стандартами оперативной памяти, такими как DDR2, DDR3, DDR4 и DDR5, каждый из которых предлагает улучшенные характеристики по сравнению с предыдущими версиями.

| Характеристика         | DDR2                       | DDR3                       | DDR3L                      | DDR4                          | DDR5                          |
| ---------------------- | -------------------------- | -------------------------- | -------------------------- | ----------------------------- | ----------------------------- |
| Пропускная способность | До 800-1066 MT/s           | До 800-2133 MT/s           | До 800-2133 MT/s           | До 2133-3200 MT/s             | До 4800-8800MT/s              |
| Напряжение для работы  | 1.8V                       | 1.5V                       | 1.35V                      | 1.2V                          | 1.1V                          |
| Объем хранилища        | Обычно до 8GB на модуль    | Обычно до 16GB на модуль   | Обычно до 16GB на модуль   | Обычно до 16GB на модуль      | Обычно до 32GB на модуль      |
| Год создания           | Запущена в 2003 году       | Запущена в 2007 году       | Запущена в 2010 году       | Запущена в 2014 году          | Запущена в 2020 году          |
| Тип слотов             | 240-pin DIMM               | 240-pin DIMM               | 240-pin DIMM               | 288-pin DIMM / 260-pin SODIMM | 288-pin DIMM / 260-pin SODIMM |
| Примеры производителей | Kingston, Crucial, Corsair | Kingston, Crucial, Corsair | Kingston, Crucial, Corsair | Kingston, Crucial, Corsair    | Kingston, Crucial, Corsair    |

DDR3L (Low Voltage DDR3) имеет такие же характеристики, как DDR3, но работает на сниженном напряжении, что уменьшает энергопотребление и повышает эффективность энергопотребления в сравнении с обычным DDR3.
##### Встроенная интегральная микросхема управления питанием (PMIC)

Модули DDR5 оснащаются встроенными микросхемами управления питанием (PMIC), которые помогают регулировать мощность, необходимую для различных компонентов модуля памяти (DRAM, регистр, концентратор SPD и т. д.). В модулях серверного класса PMIC использует 12 В, а в модулей класса ПК — 5 В. Это обеспечивает лучшее распределение мощности по сравнению с предыдущими поколениями, повышает целостность сигнала и снижает уровень шума.

>[!info]- в aida можно увидеть подробную информацию про ОЗУ компьютера
>- aida > системная плата> cdp>отчет
>- aida > чипсет > объем максимальной ОЗУ

#### Тайминги оперативной памяти (RAM timings)
это параметры, определяющие время задержек между различными операциями чтения/записи памяти. Они измеряются в тактах системной шины или в наносекундах и оказывают влияние на скорость доступа к данным в памяти. Вот основные тайминги оперативной памяти:
- **CAS Latency (CL)**:
-  **RAS-to-CAS Delay (tRCD)**:
-  **Row Precharge Time (tRP)**:
- **Row Active Time (tRAS)**:
Эти параметры влияют на общую производительность оперативной памяти, и чем меньше их значения, тем лучше. Однако, более низкие значения таймингов могут требовать более жестких условий работы для памяти и могут привести к нестабильной работе системы, если они не поддерживаются памятью или материнской платой.


[[storage device]]
[[ram]]