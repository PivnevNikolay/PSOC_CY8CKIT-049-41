### CY8CKIT-049-41X  

[PSoC® 4 CY8CKIT-049 4xxx Prototyping Kits](https://www.cypress.com/documentation/development-kitsboards/psoc-4-cy8ckit-049-4xxx-prototyping-kits)

Это недорогая платформа для желающих попробовать разрабатывать приложения с использованием семейства устройств PSoC ® 4. 
Данный набор поддерживает подключение к ПК через контроллер Cypress USB-Serial, который также используется для загрузки устройства PSoC 4 через UART с помощью инструмента Bootloader Software Host. Eсть возможность подключить Kitprog on-board Programmer / Debugger.  

![alt-текст](https://github.com/PivnevNikolay/PSOC_CY8CKIT-049-41/blob/master/picture/001.jpg "CY8CKIT-049-41X")  

CY8CKIT-049-41X поддерживает Arm ® 32-битный Cortex-M0 ™ [CY8C4125AXI-483](https://www.cypress.com/part/cy8c4125axi-483)  

|CY8C4125AXI-483|   Product Specs    |
| ------------- |:------------------:|
| CPU Core      | ARM Cortex-M0      |
| Flash (KB)    | 32                 |
| Frequency Max.| 24 MHz             |
| Voltage(Max)  | 5.5 V              |
| Voltage(Min)  | 1.27 V             |
| GPIOs         | 36                 |
| UDB           | 0                  |
| SRAM (KB)     | 4                  |
| Series        | PSoC 4100          |  

![alt-текст](https://github.com/PivnevNikolay/PSOC_CY8CKIT-049-41/blob/master/picture/002.jpg "CY8CKIT-049-42X")  

### CY8CKIT-049-42X    

CY8CKIT-049-42X поддерживает Arm ® 32-битный Cortex-M0 ™ [CY8C4245AXI-483](https://www.cypress.com/part/cy8c4245axi-483)   

|CY8C4125AXI-483|   Product Specs    |
| ------------- |:------------------:|
| CPU Core      | ARM Cortex-M0      |
| Flash (KB)    | 32                 |
| Frequency Max.| 48 MHz             |
| Voltage(Max)  | 5.5 V              |
| Voltage(Min)  | 1.27 V             |
| GPIOs         | 36                 |
| UDB           | 4                  |
| SRAM (KB)     | 4                  |
| Series        | PSoC 4100          |  


## USB-Serial (CY7C6521x)  
CY8CKIT-049-41X предоставляет клиентам подключение к ПК через USB с использованием семейства Cypress USB-Serial (CY7C6521x). Устройство, используемое на CY8CKIT-049-41X, является настраиваемым мостовым контроллером USB CY7C65211. Это устройство USB-Serial поддерживает конфигурации USB-UART, USB-GPIO, USB-I2C и USB-SPI.

## IDE  
PSoC Creator - это интегрированная среда разработки (IDE), которая позволяет одновременно разрабатывать аппаратное и прикладное программное обеспечение систем PSoC 3, PSoC 4, PSoC 4 BLE, PRoC BLE, PSoC 5LP и PSoC 6. PSoC поддерживает 120 графических примитивов. PSoC 4 CY8CKIT-049-41X включает в себя загрузчик UART для программирования через контроллер USB-Serial (конфигурация USB-UART). Программа Bootloader Host, которая устанавливается вместе с PSoC Creator, используется для загрузки устройства через интерфейс USB-UART. 

### AN79953 Getting Started with PSoC 4  
[AN79953 Getting Started with PSoC 4](https://www.cypress.com/documentation/application-notes/an79953-getting-started-psoc-4)  
раздел 4 “PSoC is More than an MCU” (PSoC - больше, чем MCU).
…показывает, что типичный MCU процессор (например, 8051 или Arm Cortex M0) содержит  набор периферийных функций такие как АЦП, ЦАП, UART, SPI и порты ввода вывода, все они связаны с интерфейсом регистров ЦП. Тогда MCU Процессор - это «сердце» устройства - он управляет всем, от настройки до перемещения данных и синхронизации. Без CPU, MCU не может функционировать.  С PSoC процессор, аналоговый, цифровой и порты ввода / вывода являются одинаково важными ресурсами в программируемой системе. В основе PSoC лежит взаимосвязь и программируемость системы, а не процессор. Аналоговые и цифровые периферийные устройства взаимосвязаны с настраиваемой матрицей сигналов и шиной данных, которая позволяет создавать индивидуальные проекты, отвечающие требованиям вашего приложения. Типичный MCU требует микропрограммы ЦП для обработки конечных автоматов, использования таймера для синхронизации и порты ввода вывода. Таким образом, функциональный путь почти всегда проходит через процессор. Однако с PSoC возможна асинхронная параллельная обработка. Вы можете настроить PSoC так, чтобы элементы работали независимо от процессора.   
**_Проекты, которые будут представлены здесь, демонстрируют эту концепцию_**.   
PSoC может быть настроен на мигание светодиода без записи кода для процессора. Различные ресурсы PSoC организованы в виде графических элементов, называемых Компонентами, при помощи которых можно создать схему для быстрого построения проекта. Каждое периферийное устройство в PSoC доступно в виде предварительно проверенного компонента например  компонента PWM, компонента ADC, компонента DAC, компонента CapSense, компонента UART и так далее. Наличие предварительно настроенного Компонента в PSoC Creator значительно сокращает время разработки. Это также позволяет быстро вносить изменения в дизайн, используя графические опции. 





