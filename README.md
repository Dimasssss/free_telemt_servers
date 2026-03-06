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

# Server Metrics 2026-03-06 16:32:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 22219.9 (6h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52518
telemt_connections_bad_total 3109
telemt_handshake_timeouts_total 215
telemt_upstream_connect_attempt_total 45597
telemt_upstream_connect_success_total 45585
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 45597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2571
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 45583
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 2398589210 (2.23 GB)
telemt_user_octets_to_client{user="hello"} 29161880522 (27.16 GB)
telemt_user_msgs_from_client{user="hello"} 1615571
telemt_user_msgs_to_client{user="hello"} 4619208
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 22219.3 (6h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9918
telemt_connections_bad_total 174
telemt_handshake_timeouts_total 97
telemt_upstream_connect_attempt_total 9398
telemt_upstream_connect_success_total 9380
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 9398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 558
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9378
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 112231402 (107.03 MB)
telemt_user_octets_to_client{user="hello"} 5378232983 (5.01 GB)
telemt_user_msgs_from_client{user="hello"} 193008
telemt_user_msgs_to_client{user="hello"} 1661680
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 22218.5 (6h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8091
telemt_connections_bad_total 138
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 7789
telemt_upstream_connect_success_total 7787
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7789
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 423
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7785
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 118626405 (113.13 MB)
telemt_user_octets_to_client{user="hello"} 4811349122 (4.48 GB)
telemt_user_msgs_from_client{user="hello"} 176911
telemt_user_msgs_to_client{user="hello"} 1130189
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 22217.8 (6h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11678
telemt_connections_bad_total 120
telemt_handshake_timeouts_total 111
telemt_upstream_connect_attempt_total 10778
telemt_upstream_connect_success_total 10741
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 10778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 684
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10739
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 148271513 (141.40 MB)
telemt_user_octets_to_client{user="hello"} 3486374574 (3.25 GB)
telemt_user_msgs_from_client{user="hello"} 186717
telemt_user_msgs_to_client{user="hello"} 910096
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 22219.1 (6h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16150
telemt_connections_bad_total 5556
telemt_handshake_timeouts_total 556
telemt_upstream_connect_attempt_total 9756
telemt_upstream_connect_success_total 9756
telemt_upstream_connect_attempts_per_request{bucket="1"} 9756
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1375
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9754
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 235137563 (224.24 MB)
telemt_user_octets_to_client{user="hello"} 21402989932 (19.93 GB)
telemt_user_msgs_from_client{user="hello"} 388665
telemt_user_msgs_to_client{user="hello"} 3858677
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 5
```