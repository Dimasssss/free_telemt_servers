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

# Server Metrics 2026-03-05 11:01:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 84849.5 (23h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120363
telemt_connections_bad_total 483
telemt_handshake_timeouts_total 4109
telemt_upstream_connect_attempt_total 107256
telemt_upstream_connect_success_total 107231
telemt_upstream_connect_attempts_per_request{bucket="1"} 107206
telemt_upstream_connect_attempts_per_request{bucket="2"} 25
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 100265
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6906
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 107221
telemt_user_connections_current{user="hello"} 218
telemt_user_octets_from_client{user="hello"} 3196648896 (2.98 GB)
telemt_user_octets_to_client{user="hello"} 74932792828 (69.79 GB)
telemt_user_msgs_from_client{user="hello"} 3114153
telemt_user_msgs_to_client{user="hello"} 12223489
telemt_user_unique_ips_current{user="hello"} 11
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 84851.9 (23h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22584
telemt_connections_bad_total 476
telemt_handshake_timeouts_total 72
telemt_upstream_connect_attempt_total 17711
telemt_upstream_connect_success_total 17709
telemt_upstream_connect_attempts_per_request{bucket="1"} 17707
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1181
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17701
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 1171726449 (1.09 GB)
telemt_user_octets_to_client{user="hello"} 14803346121 (13.79 GB)
telemt_user_msgs_from_client{user="hello"} 820784
telemt_user_msgs_to_client{user="hello"} 4718817
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 84850.6 (23h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18639
telemt_connections_bad_total 393
telemt_handshake_timeouts_total 32
telemt_upstream_connect_attempt_total 14376
telemt_upstream_connect_success_total 14376
telemt_upstream_connect_attempts_per_request{bucket="1"} 14376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 869
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14366
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 440821170 (420.40 MB)
telemt_user_octets_to_client{user="hello"} 9536802475 (8.88 GB)
telemt_user_msgs_from_client{user="hello"} 442084
telemt_user_msgs_to_client{user="hello"} 2020363
telemt_user_unique_ips_current{user="hello"} 1
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 84848.1 (23h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31559
telemt_connections_bad_total 999
telemt_handshake_timeouts_total 629
telemt_upstream_connect_attempt_total 27609
telemt_upstream_connect_success_total 27599
telemt_upstream_connect_attempts_per_request{bucket="1"} 27589
telemt_upstream_connect_attempts_per_request{bucket="2"} 10
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1839
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27591
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 510533036 (486.88 MB)
telemt_user_octets_to_client{user="hello"} 17509923080 (16.31 GB)
telemt_user_msgs_from_client{user="hello"} 540629
telemt_user_msgs_to_client{user="hello"} 3900487
telemt_user_unique_ips_current{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 84849.7 (23h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32693
telemt_connections_bad_total 15347
telemt_handshake_timeouts_total 65
telemt_upstream_connect_attempt_total 16797
telemt_upstream_connect_success_total 16793
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 16791
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2312
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16785
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 647984239 (617.97 MB)
telemt_user_octets_to_client{user="hello"} 27871683733 (25.96 GB)
telemt_user_msgs_from_client{user="hello"} 740075
telemt_user_msgs_to_client{user="hello"} 5324996
telemt_user_unique_ips_current{user="hello"} 2
```