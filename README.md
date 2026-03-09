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

# Server Metrics 2026-03-09 06:46:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 26823.9 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27586
telemt_connections_bad_total 36
telemt_handshake_timeouts_total 568
telemt_upstream_connect_attempt_total 25410
telemt_upstream_connect_success_total 25402
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 25410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1832
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25398
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 235067208 (224.18 MB)
telemt_user_octets_to_client{user="hello"} 14368817369 (13.38 GB)
telemt_user_msgs_from_client{user="hello"} 485235
telemt_user_msgs_to_client{user="hello"} 740299
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 26822.4 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3848
telemt_connections_bad_total 85
telemt_handshake_timeouts_total 75
telemt_upstream_connect_attempt_total 3635
telemt_upstream_connect_success_total 3635
telemt_upstream_connect_attempts_per_request{bucket="1"} 3635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 256
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3631
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 52065082 (49.65 MB)
telemt_user_octets_to_client{user="hello"} 3198561325 (2.98 GB)
telemt_user_msgs_from_client{user="hello"} 113757
telemt_user_msgs_to_client{user="hello"} 618903
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 26822.7 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2050
telemt_connections_bad_total 107
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1915
telemt_upstream_connect_success_total 1915
telemt_upstream_connect_attempts_per_request{bucket="1"} 1915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 307
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1911
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 908331508 (866.25 MB)
telemt_user_octets_to_client{user="hello"} 1201096604 (1.12 GB)
telemt_user_msgs_from_client{user="hello"} 351190
telemt_user_msgs_to_client{user="hello"} 235935
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 26817.6 (7h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4717
telemt_connections_bad_total 69
telemt_handshake_timeouts_total 351
telemt_upstream_connect_attempt_total 3799
telemt_upstream_connect_success_total 3797
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 705
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3793
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 129793421 (123.78 MB)
telemt_user_octets_to_client{user="hello"} 2817050054 (2.62 GB)
telemt_user_msgs_from_client{user="hello"} 81449
telemt_user_msgs_to_client{user="hello"} 610273
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 26823.1 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9761
telemt_connections_bad_total 5302
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 4228
telemt_upstream_connect_success_total 4228
telemt_upstream_connect_attempts_per_request{bucket="1"} 4228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3514
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 708
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4224
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 58191402 (55.50 MB)
telemt_user_octets_to_client{user="hello"} 2891569438 (2.69 GB)
telemt_user_msgs_from_client{user="hello"} 86605
telemt_user_msgs_to_client{user="hello"} 397456
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 3
```