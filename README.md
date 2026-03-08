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

# Server Metrics 2026-03-08 12:00:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 17520.9 (4h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37727
telemt_connections_bad_total 2581
telemt_handshake_timeouts_total 266
telemt_upstream_connect_attempt_total 33300
telemt_upstream_connect_success_total 33281
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 33300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1919
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33277
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 1038014416 (989.93 MB)
telemt_user_octets_to_client{user="hello"} 17532650774 (16.33 GB)
telemt_user_msgs_from_client{user="hello"} 853507
telemt_user_msgs_to_client{user="hello"} 1042178
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 17520.4 (4h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9526
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 100
telemt_upstream_connect_attempt_total 9146
telemt_upstream_connect_success_total 9146
telemt_upstream_connect_attempts_per_request{bucket="1"} 9146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8494
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 587
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9144
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 368951225 (351.86 MB)
telemt_user_octets_to_client{user="hello"} 5974394582 (5.56 GB)
telemt_user_msgs_from_client{user="hello"} 317262
telemt_user_msgs_to_client{user="hello"} 1551326
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 17519.8 (4h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6339
telemt_connections_bad_total 36
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 6046
telemt_upstream_connect_success_total 5971
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 6046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 360
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5969
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 151399949 (144.39 MB)
telemt_user_octets_to_client{user="hello"} 1668032618 (1.55 GB)
telemt_user_msgs_from_client{user="hello"} 93728
telemt_user_msgs_to_client{user="hello"} 283472
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 17519.7 (4h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7944
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 39
telemt_upstream_connect_attempt_total 7593
telemt_upstream_connect_success_total 7577
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 7593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 467
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7575
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 885464075 (844.44 MB)
telemt_user_octets_to_client{user="hello"} 2976544870 (2.77 GB)
telemt_user_msgs_from_client{user="hello"} 382455
telemt_user_msgs_to_client{user="hello"} 658168
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 17520.0 (4h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10644
telemt_connections_bad_total 3268
telemt_handshake_timeouts_total 19
telemt_upstream_connect_attempt_total 7214
telemt_upstream_connect_success_total 7213
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1505
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7211
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 153992457 (146.86 MB)
telemt_user_octets_to_client{user="hello"} 6465869595 (6.02 GB)
telemt_user_msgs_from_client{user="hello"} 196162
telemt_user_msgs_to_client{user="hello"} 891533
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```