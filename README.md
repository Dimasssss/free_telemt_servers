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

# Server Metrics 2026-03-10 15:00:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 2034.9 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10309
telemt_connections_bad_total 170
telemt_handshake_timeouts_total 38
telemt_upstream_connect_attempt_total 9624
telemt_upstream_connect_success_total 9623
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9624
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8929
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 693
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9621
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 112032318 (106.84 MB)
telemt_user_octets_to_client{user="hello"} 4679764081 (4.36 GB)
telemt_user_msgs_from_client{user="hello"} 168228
telemt_user_msgs_to_client{user="hello"} 283784
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 2034.2 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2938
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 71
telemt_upstream_connect_attempt_total 2727
telemt_upstream_connect_success_total 2727
telemt_upstream_connect_attempts_per_request{bucket="1"} 2727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2725
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 43542956 (41.53 MB)
telemt_user_octets_to_client{user="hello"} 2373384059 (2.21 GB)
telemt_user_msgs_from_client{user="hello"} 77955
telemt_user_msgs_to_client{user="hello"} 696384
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 2033.8 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4631
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 123
telemt_upstream_connect_attempt_total 4288
telemt_upstream_connect_success_total 4288
telemt_upstream_connect_attempts_per_request{bucket="1"} 4288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3939
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 349
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4286
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 33657521 (32.10 MB)
telemt_user_octets_to_client{user="hello"} 519009159 (494.97 MB)
telemt_user_msgs_from_client{user="hello"} 60025
telemt_user_msgs_to_client{user="hello"} 156532
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 2032.7 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4252
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 98
telemt_upstream_connect_attempt_total 3987
telemt_upstream_connect_success_total 3974
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 3987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 501
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3972
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 71206160 (67.91 MB)
telemt_user_octets_to_client{user="hello"} 2680496881 (2.50 GB)
telemt_user_msgs_from_client{user="hello"} 81511
telemt_user_msgs_to_client{user="hello"} 485269
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 2034.1 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6546
telemt_connections_bad_total 610
telemt_handshake_timeouts_total 97
telemt_upstream_connect_attempt_total 5610
telemt_upstream_connect_success_total 5608
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 631
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5606
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 127661810 (121.75 MB)
telemt_user_octets_to_client{user="hello"} 1853260550 (1.73 GB)
telemt_user_msgs_from_client{user="hello"} 118313
telemt_user_msgs_to_client{user="hello"} 297717
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 24
```