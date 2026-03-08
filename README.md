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

# Server Metrics 2026-03-08 07:28:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 1160.7 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1976
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 1893
telemt_upstream_connect_success_total 1892
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1893
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 98
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1890
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 37703608 (35.96 MB)
telemt_user_octets_to_client{user="hello"} 648632673 (618.58 MB)
telemt_user_msgs_from_client{user="hello"} 46101
telemt_user_msgs_to_client{user="hello"} 52226
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 1159.7 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 358
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 346
telemt_upstream_connect_success_total 346
telemt_upstream_connect_attempts_per_request{bucket="1"} 346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 344
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 5847194 (5.58 MB)
telemt_user_octets_to_client{user="hello"} 250342613 (238.75 MB)
telemt_user_msgs_from_client{user="hello"} 10059
telemt_user_msgs_to_client{user="hello"} 57638
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 1159.4 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331
telemt_connections_bad_total 3
telemt_upstream_connect_attempt_total 319
telemt_upstream_connect_success_total 319
telemt_upstream_connect_attempts_per_request{bucket="1"} 319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 317
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 1460210 (1.39 MB)
telemt_user_octets_to_client{user="hello"} 162195114 (154.68 MB)
telemt_user_msgs_from_client{user="hello"} 3630
telemt_user_msgs_to_client{user="hello"} 21024
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 1159.4 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 483
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 464
telemt_upstream_connect_success_total 464
telemt_upstream_connect_attempts_per_request{bucket="1"} 464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 462
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 22197830 (21.17 MB)
telemt_user_octets_to_client{user="hello"} 82934020 (79.09 MB)
telemt_user_msgs_from_client{user="hello"} 6209
telemt_user_msgs_to_client{user="hello"} 24856
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 1159.7 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 920
telemt_connections_bad_total 208
telemt_upstream_connect_attempt_total 706
telemt_upstream_connect_success_total 706
telemt_upstream_connect_attempts_per_request{bucket="1"} 706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 704
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 3253631 (3.10 MB)
telemt_user_octets_to_client{user="hello"} 162865321 (155.32 MB)
telemt_user_msgs_from_client{user="hello"} 7846
telemt_user_msgs_to_client{user="hello"} 25140
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 5
```