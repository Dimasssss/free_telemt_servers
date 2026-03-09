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

# Server Metrics 2026-03-09 06:31:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 25906.4 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26189
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 566
telemt_upstream_connect_attempt_total 24073
telemt_upstream_connect_success_total 24065
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 24073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1694
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24061
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 223506750 (213.15 MB)
telemt_user_octets_to_client{user="hello"} 13628368260 (12.69 GB)
telemt_user_msgs_from_client{user="hello"} 455804
telemt_user_msgs_to_client{user="hello"} 691150
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 25904.7 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3494
telemt_connections_bad_total 85
telemt_handshake_timeouts_total 70
telemt_upstream_connect_attempt_total 3296
telemt_upstream_connect_success_total 3296
telemt_upstream_connect_attempts_per_request{bucket="1"} 3296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 233
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3292
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 49823976 (47.52 MB)
telemt_user_octets_to_client{user="hello"} 3073305813 (2.86 GB)
telemt_user_msgs_from_client{user="hello"} 108916
telemt_user_msgs_to_client{user="hello"} 594182
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 25905.3 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1998
telemt_connections_bad_total 106
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1866
telemt_upstream_connect_success_total 1866
telemt_upstream_connect_attempts_per_request{bucket="1"} 1866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 303
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1862
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 908102139 (866.03 MB)
telemt_user_octets_to_client{user="hello"} 1147437158 (1.07 GB)
telemt_user_msgs_from_client{user="hello"} 350512
telemt_user_msgs_to_client{user="hello"} 229657
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 25900.0 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4484
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 351
telemt_upstream_connect_attempt_total 3571
telemt_upstream_connect_success_total 3569
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 667
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3565
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 128788561 (122.82 MB)
telemt_user_octets_to_client{user="hello"} 2769375701 (2.58 GB)
telemt_user_msgs_from_client{user="hello"} 79251
telemt_user_msgs_to_client{user="hello"} 597178
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 25905.6 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9249
telemt_connections_bad_total 5139
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 3893
telemt_upstream_connect_success_total 3893
telemt_upstream_connect_attempts_per_request{bucket="1"} 3893
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 655
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3889
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 56546971 (53.93 MB)
telemt_user_octets_to_client{user="hello"} 2836752578 (2.64 GB)
telemt_user_msgs_from_client{user="hello"} 83004
telemt_user_msgs_to_client{user="hello"} 383963
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```