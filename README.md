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

# Server Metrics 2026-03-05 14:00:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 95632.5 (26h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142339
telemt_connections_bad_total 550
telemt_handshake_timeouts_total 4252
telemt_upstream_connect_attempt_total 126734
telemt_upstream_connect_success_total 126701
telemt_upstream_connect_attempts_per_request{bucket="1"} 126668
telemt_upstream_connect_attempts_per_request{bucket="2"} 33
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 118639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7987
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 126691
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 3536428021 (3.29 GB)
telemt_user_octets_to_client{user="hello"} 84632299465 (78.82 GB)
telemt_user_msgs_from_client{user="hello"} 3563027
telemt_user_msgs_to_client{user="hello"} 13851555
telemt_user_unique_ips_current{user="hello"} 13
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 95635.4 (26h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26451
telemt_connections_bad_total 500
telemt_handshake_timeouts_total 83
telemt_upstream_connect_attempt_total 21486
telemt_upstream_connect_success_total 21482
telemt_upstream_connect_attempts_per_request{bucket="1"} 21478
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19893
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1482
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21472
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 1239793222 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 16733360618 (15.58 GB)
telemt_user_msgs_from_client{user="hello"} 922394
telemt_user_msgs_to_client{user="hello"} 5339776
telemt_user_unique_ips_current{user="hello"} 2
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 95633.6 (26h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23477
telemt_connections_bad_total 427
telemt_handshake_timeouts_total 49
telemt_upstream_connect_attempt_total 19027
telemt_upstream_connect_success_total 19027
telemt_upstream_connect_attempts_per_request{bucket="1"} 19027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17993
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1022
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19017
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 480053011 (457.81 MB)
telemt_user_octets_to_client{user="hello"} 11287656632 (10.51 GB)
telemt_user_msgs_from_client{user="hello"} 527991
telemt_user_msgs_to_client{user="hello"} 2468273
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 95631.5 (26h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37908
telemt_connections_bad_total 1067
telemt_handshake_timeouts_total 647
telemt_upstream_connect_attempt_total 33558
telemt_upstream_connect_success_total 33539
telemt_upstream_connect_attempts_per_request{bucket="1"} 33520
telemt_upstream_connect_attempts_per_request{bucket="2"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2158
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 209
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33529
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 544368308 (519.15 MB)
telemt_user_octets_to_client{user="hello"} 19313866098 (17.99 GB)
telemt_user_msgs_from_client{user="hello"} 612857
telemt_user_msgs_to_client{user="hello"} 4341440
telemt_user_unique_ips_current{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 95633.1 (26h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38007
telemt_connections_bad_total 17248
telemt_handshake_timeouts_total 76
telemt_upstream_connect_attempt_total 20112
telemt_upstream_connect_success_total 20107
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 20104
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2735
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20097
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 682894105 (651.26 MB)
telemt_user_octets_to_client{user="hello"} 29685217986 (27.65 GB)
telemt_user_msgs_from_client{user="hello"} 814277
telemt_user_msgs_to_client{user="hello"} 5733452
telemt_user_unique_ips_current{user="hello"} 4
```