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

# Server Metrics 2026-03-09 16:34:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 62057.9 (17h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114155
telemt_connections_bad_total 1656
telemt_handshake_timeouts_total 974
telemt_upstream_connect_attempt_total 106842
telemt_upstream_connect_success_total 106803
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 106842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 98635
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8109
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 106797
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 2838552070 (2.64 GB)
telemt_user_octets_to_client{user="hello"} 56066082004 (52.22 GB)
telemt_user_msgs_from_client{user="hello"} 2637519
telemt_user_msgs_to_client{user="hello"} 3724460
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 62056.3 (17h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30399
telemt_connections_bad_total 220
telemt_handshake_timeouts_total 353
telemt_upstream_connect_attempt_total 28670
telemt_upstream_connect_success_total 28652
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 28670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2439
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28646
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 990192829 (944.32 MB)
telemt_user_octets_to_client{user="hello"} 15702799028 (14.62 GB)
telemt_user_msgs_from_client{user="hello"} 836349
telemt_user_msgs_to_client{user="hello"} 4333107
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 62057.7 (17h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38082
telemt_connections_bad_total 655
telemt_handshake_timeouts_total 1656
telemt_upstream_connect_attempt_total 28818
telemt_upstream_connect_success_total 28818
telemt_upstream_connect_attempts_per_request{bucket="1"} 28818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3085
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28812
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 4419322801 (4.12 GB)
telemt_user_octets_to_client{user="hello"} 18214957729 (16.96 GB)
telemt_user_msgs_from_client{user="hello"} 1956234
telemt_user_msgs_to_client{user="hello"} 2394575
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 62051.7 (17h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43804
telemt_connections_bad_total 198
telemt_handshake_timeouts_total 875
telemt_upstream_connect_attempt_total 40032
telemt_upstream_connect_success_total 39933
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 40032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5658
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 39925
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 1948885125 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 31038474948 (28.91 GB)
telemt_user_msgs_from_client{user="hello"} 1271085
telemt_user_msgs_to_client{user="hello"} 7843806
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 62057.1 (17h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71900
telemt_connections_bad_total 15086
telemt_handshake_timeouts_total 1636
telemt_upstream_connect_attempt_total 51842
telemt_upstream_connect_success_total 51840
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 51842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7924
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51834
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 869601266 (829.32 MB)
telemt_user_octets_to_client{user="hello"} 54659795254 (50.91 GB)
telemt_user_msgs_from_client{user="hello"} 1202445
telemt_user_msgs_to_client{user="hello"} 6665521
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 16
```