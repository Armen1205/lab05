Lab05

Общая информация:
Coveralls.io - это веб сервис, который помогает отслеживать покрытие кода и его будущих исправлений. Для исправной работы веб сервиса требуется, чтобы код был размещен на GitHub, BitBuckets или GitLab. Coveralls не зависит от языка программирования или Cl.

Ход работы:
  1) Написать CMakeList.txt 
  ![image](https://user-images.githubusercontent.com/91755900/170662556-68e5ee3f-6c9c-4e5c-b84a-f289382b2d22.png)

  2) Написать тесты
  ![image](https://user-images.githubusercontent.com/91755900/170662737-5e7201d7-1f03-43bc-b5dc-6523a195e2e2.png)

  P.s. В коде была ошибка в файле transactions.cpp в 39 строчке в аргументе поменять to на from из-за чего не работали тесты...
  
  3) Настроить сборку при помощи GitHub actions
  
