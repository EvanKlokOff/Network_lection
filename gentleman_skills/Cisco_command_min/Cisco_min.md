## Режимы работы в Cisco
* **User EXEC Mode**: Начальный режим, предоставляющий ограниченный набор команд.
* **Privileged EXEC Mode**: Режим с расширенными привилегиями, позволяющий выполнять команды конфигурации.
* **Global Configuration Mode**: Режим для внесения глобальных изменений в конфигурацию устройства.
  * > чтобы перейти используется config terminal
  * > > можно сократить до config t
* **Interface Configuration Mode**: Режим для настройки отдельных интерфейсов коммутатора.
  * > команда no shutdown включает интерфейс
  * > > можно сократить до no shut

## Команды для просмотра конфигурации и статуса

* **Просмотр текущей конфигурации**:
  * > show running-config
  * > > можно сократить до sh run
  * > > Running-configuration – это конфигурация, загруженная в данный момент в оперативную память роутера. Когда вы вносите изменения в оборудование, как раз эта конфигурация изменяется.
Важно помнить, что конфигурация не сохраняется пока не выполнить copy running-configuration startup-configuration.

* **Просмотр сохраненной конфигурации**:
  * > show startup-config

* **Просмотр информации об интерфейсах**:
  * > show interfaces
  * > > Можно сократить до sh int [название интерфейса]

* **Просмотр информации о настройке IP на интерфейсе**
  * > show ip interface

* **Краткий обзор интерфейсов, включая IP-адрес, статусы Layer 2 и Layer 3**
  * > show ip interface brief
  
* **Просмотр таблицы MAC-адресов**:
  * > show mac address-table

* **Просмотр состояния VLAN**:
  * > show vlan

* **Просмотр таблицы маршрутизации**
  * > show ip route
  * > > можно сократить до sh ip ro

## Полезные хоткеи

## Про полезные команды
* [1](https://www.linuxshop.ru/articles/a26710803-cisco_bazovye_komandy_i_nastroyki)
* [2](https://doc.s-terra.ru/rh_output/4.1/Gate/output/mergedProjects/Console/cisco-like_%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B1.htm)
* [3](https://www.netwrix.com/cisco-commands-cheat-sheet.html)