# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

-----

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-05 14:26:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 97173.4 (26h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145097
telemt_connections_bad_total 552
telemt_handshake_timeouts_total 4255
telemt_upstream_connect_attempt_total 129462
telemt_upstream_connect_success_total 129428
telemt_upstream_connect_attempts_per_request{bucket="1"} 129394
telemt_upstream_connect_attempts_per_request{bucket="2"} 34
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8082
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 129418
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 3574148212 (3.33 GB)
telemt_user_octets_to_client{user="hello"} 86135451433 (80.22 GB)
telemt_user_msgs_from_client{user="hello"} 3633370
telemt_user_msgs_to_client{user="hello"} 14107415
telemt_user_unique_ips_current{user="hello"} 12
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 97176.4 (26h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27076
telemt_connections_bad_total 503
telemt_handshake_timeouts_total 84
telemt_upstream_connect_attempt_total 22099
telemt_upstream_connect_success_total 22095
telemt_upstream_connect_attempts_per_request{bucket="1"} 22091
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1522
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22085
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 1253608609 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 16926713754 (15.76 GB)
telemt_user_msgs_from_client{user="hello"} 937817
telemt_user_msgs_to_client{user="hello"} 5404315
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 97174.6 (26h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24340
telemt_connections_bad_total 432
telemt_handshake_timeouts_total 49
telemt_upstream_connect_attempt_total 19832
telemt_upstream_connect_success_total 19832
telemt_upstream_connect_attempts_per_request{bucket="1"} 19832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1076
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19820
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 486793869 (464.24 MB)
telemt_user_octets_to_client{user="hello"} 12114833763 (11.28 GB)
telemt_user_msgs_from_client{user="hello"} 545115
telemt_user_msgs_to_client{user="hello"} 2641136
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 97172.2 (26h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38594
telemt_connections_bad_total 1069
telemt_handshake_timeouts_total 654
telemt_upstream_connect_attempt_total 34205
telemt_upstream_connect_success_total 34186
telemt_upstream_connect_attempts_per_request{bucket="1"} 34167
telemt_upstream_connect_attempts_per_request{bucket="2"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2190
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 218
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 34176
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 555002290 (529.29 MB)
telemt_user_octets_to_client{user="hello"} 19715033235 (18.36 GB)
telemt_user_msgs_from_client{user="hello"} 624913
telemt_user_msgs_to_client{user="hello"} 4460889
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 97173.8 (26h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38915
telemt_connections_bad_total 17519
telemt_handshake_timeouts_total 76
telemt_upstream_connect_attempt_total 20710
telemt_upstream_connect_success_total 20705
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 20702
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2803
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20695
telemt_user_connections_current{user="hello"} 46
telemt_user_octets_from_client{user="hello"} 689088781 (657.17 MB)
telemt_user_octets_to_client{user="hello"} 30098263445 (28.03 GB)
telemt_user_msgs_from_client{user="hello"} 830747
telemt_user_msgs_to_client{user="hello"} 5830461
telemt_user_unique_ips_current{user="hello"} 4
```