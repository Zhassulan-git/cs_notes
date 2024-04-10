"Цикл FDE" - "Fetch-Decode-Execute cycle" (цикл Извлечение-Декодирование-Выполнение). Это базовый цикл работы процессора в компьютере.

Вот как обычно работает этот цикл:

1. **Извлечение (Fetch):** Процессор извлекает инструкцию из памяти (обычно из оперативной памяти или кэш-памяти) по адресу, указанному в специальном регистре, называемом счетчиком команд (instruction pointer). Эта инструкция загружается во внутренние регистры процессора для дальнейшей обработки.
    
2. **Декодирование (Decode):** Извлеченная инструкция декодируется, т.е. процессор определяет, какую операцию нужно выполнить и над какими данными. Это включает определение типа инструкции, идентификацию операндов и определение операции, которую нужно выполнить. Декодирование инструкции обычно выполняется специализированным устройством, называемым устройством декодирования (decoder). Это может быть часть управляющего блока (Control Unit) процессора.
    
3. **Выполнение (Execute):** После декодирования процессор выполняет фактическую операцию, указанную в инструкции. Это может быть арифметическая операция, операция загрузки/сохранения данных в память, операция перехода (прыжок) к другому адресу в программе и т. д. Выполнение операции обычно осуществляется арифметико-логическим устройством [[ CPU#АЛУ (Арифметико-логическое устройство):| ALU]]  процессора.
    

После завершения выполнения инструкции процессор переходит к следующей инструкции, инкрементируя счетчик команд и начиная новый цикл FDE с извлечения следующей инструкции. Этот цикл повторяется снова и снова, пока процессор исполняет инструкции программы.

Цикл FDE является основой для работы процессора и формирует основу для выполнения программ и обработки данных в компьютере.

![[Pasted image 20240316185349.png]]



[[CPU]]