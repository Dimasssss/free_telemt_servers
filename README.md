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

# Server Metrics 2026-03-09 02:01:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 9698.5 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8146
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 181
telemt_upstream_connect_attempt_total 7459
telemt_upstream_connect_success_total 7457
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 644
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7455
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 83161071 (79.31 MB)
telemt_user_octets_to_client{user="hello"} 7939106626 (7.39 GB)
telemt_user_msgs_from_client{user="hello"} 183184
telemt_user_msgs_to_client{user="hello"} 301553
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 9696.6 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 594
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 566
telemt_upstream_connect_success_total 566
telemt_upstream_connect_attempts_per_request{bucket="1"} 566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 564
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 7990514 (7.62 MB)
telemt_user_octets_to_client{user="hello"} 464096243 (442.60 MB)
telemt_user_msgs_from_client{user="hello"} 22107
telemt_user_msgs_to_client{user="hello"} 91931
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 9697.1 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 650
telemt_connections_bad_total 72
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 566
telemt_upstream_connect_success_total 566
telemt_upstream_connect_attempts_per_request{bucket="1"} 566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 88
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 564
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 29948768 (28.56 MB)
telemt_user_octets_to_client{user="hello"} 83535525 (79.67 MB)
telemt_user_msgs_from_client{user="hello"} 16891
telemt_user_msgs_to_client{user="hello"} 26819
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 9692.0 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1252
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 116
telemt_upstream_connect_attempt_total 1066
telemt_upstream_connect_success_total 1066
telemt_upstream_connect_attempts_per_request{bucket="1"} 1066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 236
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1064
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 8582101 (8.18 MB)
telemt_user_octets_to_client{user="hello"} 574062215 (547.47 MB)
telemt_user_msgs_from_client{user="hello"} 22107
telemt_user_msgs_to_client{user="hello"} 162288
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 9697.5 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2703
telemt_connections_bad_total 1744
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 934
telemt_upstream_connect_success_total 934
telemt_upstream_connect_attempts_per_request{bucket="1"} 934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 807
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 127
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 932
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 7082658 (6.75 MB)
telemt_user_octets_to_client{user="hello"} 1290961673 (1.20 GB)
telemt_user_msgs_from_client{user="hello"} 19675
telemt_user_msgs_to_client{user="hello"} 160224
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```