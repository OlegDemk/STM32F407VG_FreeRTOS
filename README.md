# STM32F407VG_FreeRTOS

It is test project for show how work task resources monitor.
Project has tasks:
1. StartDefaultTask (This task make test payload for test).
2. StartLED_BLUE_BLINK (Blink Blue LED task).
3. StartLED_YELLOW_ADC (Toggling Yellow LED if User button was pressed).
4. StartUART_Task (Task created for transmit data ower virtual COM port using QUEUE) (Tast transmit User button status and task resources data).
5. StartADC_Task (Task using ADC for measure voltage from potentiometer connected to board).
6. StartTeadBtn_Task (If button pressed:  1. Set semaphore 2. Send message in queue, thatbutton was pressed).
7. StartShowResources (The main task. In this task takes data about all tasks).

Sourses:
1. https://www.youtube.com/watch?v=wTK11IDpg7s&list=RDCMUC2vcuP7iWaX0MVG6hJ-cOkg&index=5
2. https://www.youtube.com/watch?v=JKkyF53AAM4&t=771s

![alt text].(https://github.com/OlegDemk/STM32F407VG_FreeRTOS/blob/TASKS_RESOURCES_MONITOR/photo.jpg)

