# Embedded C/C++

- Ik heb 1.5 jaar voor Philips Semiconductors delen van een Java-library voor chips in settop-boxes geprogrammeerd, in **C**. Het betrof de **Fixed Point Math library**, de **DirtyArea** library en een deel van de **Font** library. De (bedrijfs-) code daarvan kan ik natuurlijk niet laten zien.

- Voor Philips heb ik ook (in c++) **profiling software** geschreven, om die C code op performance te kunnen profilen.

- Op Hogeschool Utrecht heb ik als hogeschooldocent Technisch Informatica onder andere c++ en embedded c++ gerelateerde **cursussen** gegeven. Een groot deel van het lesprogramma en het lesmateriaal voor [semester 2](https://github.com/HU-TI-DEV/TI-S2) en [semester 3](https://github.com/HU-TI-DEV/TI-S3) is door mij geschreven.

- Voor de **ESP32** heb ik diverse **c++ libraries** geprogrammeerd die het programmeren ervan vergemakkelijken:
  
  - [**CleanRTOS**](https://github.com/TheMave/test_lasergame_2_rework_CleanGUI/tree/main/libs/CleanRTOS), een wrapper om freeRTOS. Featuring: eenvoudig combineren van Flags en Queues, automatisch voorkomen van Deadlocks en veel meer ([zie hier](https://github.com/HU-TI-DEV/TI-S3/blob/main/infrastructuur/CleanRTOS/README.md)). Het is ook in de Arduino-IDE te selecteren als officiele library voor de ESP32.
  - [**CleanGUI**](https://github.com/TheMave/test_lasergame_2_rework_CleanGUI/blob/main/libs/CleanGUI/Examples.txt), multi-threaded display support.
  - [**CleanCore**](https://github.com/TheMave/test_lasergame_2_rework_CleanGUI/blob/main/libs/CleanCore/src/_crt_CleanCore_Readme.txt), een aantal handige basisklassen voor elk project.
