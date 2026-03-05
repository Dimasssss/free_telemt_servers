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

# Server Metrics 2026-03-05 01:51:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 51895.0 (14h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71978
telemt_connections_bad_total 167
telemt_handshake_timeouts_total 1565
telemt_upstream_connect_attempt_total 65270
telemt_upstream_connect_success_total 65255
telemt_upstream_connect_attempts_per_request{bucket="1"} 65240
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4235
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 65249
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 2375069521 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 49049871112 (45.68 GB)
telemt_user_msgs_from_client{user="hello"} 2062454
telemt_user_msgs_to_client{user="hello"} 7815247
telemt_user_unique_ips_current{user="hello"} 10
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 51897.8 (14h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16104
telemt_connections_bad_total 254
telemt_handshake_timeouts_total 41
telemt_upstream_connect_attempt_total 11591
telemt_upstream_connect_success_total 11589
telemt_upstream_connect_attempts_per_request{bucket="1"} 11587
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11583
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 1057144527 (1008.17 MB)
telemt_user_octets_to_client{user="hello"} 11107202135 (10.34 GB)
telemt_user_msgs_from_client{user="hello"} 651877
telemt_user_msgs_to_client{user="hello"} 3741826
telemt_user_unique_ips_current{user="hello"} 2
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 51895.9 (14h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11462
telemt_connections_bad_total 187
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 7554
telemt_upstream_connect_success_total 7554
telemt_upstream_connect_attempts_per_request{bucket="1"} 7554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 513
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7548
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 315075142 (300.48 MB)
telemt_user_octets_to_client{user="hello"} 5391720088 (5.02 GB)
telemt_user_msgs_from_client{user="hello"} 276062
telemt_user_msgs_to_client{user="hello"} 1166923
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 51893.9 (14h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17686
telemt_connections_bad_total 761
telemt_handshake_timeouts_total 88
telemt_upstream_connect_attempt_total 15371
telemt_upstream_connect_success_total 15366
telemt_upstream_connect_attempts_per_request{bucket="1"} 15361
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1158
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15360
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 402375333 (383.74 MB)
telemt_user_octets_to_client{user="hello"} 5730594971 (5.34 GB)
telemt_user_msgs_from_client{user="hello"} 318496
telemt_user_msgs_to_client{user="hello"} 1450751
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 51895.7 (14h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19690
telemt_connections_bad_total 9341
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 9975
telemt_upstream_connect_success_total 9971
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9969
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1570
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9965
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 521510973 (497.35 MB)
telemt_user_octets_to_client{user="hello"} 22466255227 (20.92 GB)
telemt_user_msgs_from_client{user="hello"} 564574
telemt_user_msgs_to_client{user="hello"} 4266758
telemt_user_unique_ips_current{user="hello"} 1
```