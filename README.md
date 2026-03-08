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

# Server Metrics 2026-03-08 02:35:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 35420.1 (9h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50299
telemt_connections_bad_total 5172
telemt_handshake_timeouts_total 282
telemt_upstream_connect_attempt_total 42851
telemt_upstream_connect_success_total 42844
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 42851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42840
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 2271765369 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 31385598139 (29.23 GB)
telemt_user_msgs_from_client{user="hello"} 1422724
telemt_user_msgs_to_client{user="hello"} 4875997
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 35419.3 (9h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7426
telemt_connections_bad_total 274
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 7019
telemt_upstream_connect_success_total 7012
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 7019
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 593
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7008
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 176456420 (168.28 MB)
telemt_user_octets_to_client{user="hello"} 10547792745 (9.82 GB)
telemt_user_msgs_from_client{user="hello"} 330900
telemt_user_msgs_to_client{user="hello"} 2453690
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 35419.1 (9h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4516
telemt_connections_bad_total 230
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 4206
telemt_upstream_connect_success_total 4206
telemt_upstream_connect_attempts_per_request{bucket="1"} 4206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 631
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4202
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 117223508 (111.79 MB)
telemt_user_octets_to_client{user="hello"} 13903371637 (12.95 GB)
telemt_user_msgs_from_client{user="hello"} 209348
telemt_user_msgs_to_client{user="hello"} 2938200
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 35247.5 (9h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12681
telemt_connections_bad_total 185
telemt_handshake_timeouts_total 44
telemt_upstream_connect_attempt_total 12167
telemt_upstream_connect_success_total 12141
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 12167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1923
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12137
telemt_user_connections_current{user="hello"} 46
telemt_user_octets_from_client{user="hello"} 327460062 (312.29 MB)
telemt_user_octets_to_client{user="hello"} 10722181104 (9.99 GB)
telemt_user_msgs_from_client{user="hello"} 342622
telemt_user_msgs_to_client{user="hello"} 3150160
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 35419.3 (9h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14654
telemt_connections_bad_total 6523
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 7899
telemt_upstream_connect_success_total 7891
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 7899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7887
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 1619522021 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 7711274110 (7.18 GB)
telemt_user_msgs_from_client{user="hello"} 802194
telemt_user_msgs_to_client{user="hello"} 1719832
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```