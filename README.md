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

# Server Metrics 2026-03-04 12:19:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 3140.5 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5104
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 115
telemt_upstream_connect_attempt_total 4873
telemt_upstream_connect_success_total 4873
telemt_upstream_connect_attempts_per_request{bucket="1"} 4873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 244
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4871
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 265368747 (253.08 MB)
telemt_user_octets_to_client{user="hello"} 6417904076 (5.98 GB)
telemt_user_msgs_from_client{user="hello"} 212737
telemt_user_msgs_to_client{user="hello"} 933172
telemt_user_unique_ips_current{user="hello"} 15
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 3143.3 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1267
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 1137
telemt_upstream_connect_success_total 1137
telemt_upstream_connect_attempts_per_request{bucket="1"} 1137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 83
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1135
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 20398445 (19.45 MB)
telemt_user_octets_to_client{user="hello"} 1763064635 (1.64 GB)
telemt_user_msgs_from_client{user="hello"} 36649
telemt_user_msgs_to_client{user="hello"} 569546
telemt_user_unique_ips_current{user="hello"} 5
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 3141.7 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 456
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 441
telemt_upstream_connect_success_total 441
telemt_upstream_connect_attempts_per_request{bucket="1"} 441
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 422
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 439
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 5720678 (5.46 MB)
telemt_user_octets_to_client{user="hello"} 182091029 (173.66 MB)
telemt_user_msgs_from_client{user="hello"} 12612
telemt_user_msgs_to_client{user="hello"} 42652
telemt_user_unique_ips_current{user="hello"} 1
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 3139.3 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1078
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 11
telemt_upstream_connect_attempt_total 993
telemt_upstream_connect_success_total 993
telemt_upstream_connect_attempts_per_request{bucket="1"} 993
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 991
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 6185771 (5.90 MB)
telemt_user_octets_to_client{user="hello"} 280353183 (267.37 MB)
telemt_user_msgs_from_client{user="hello"} 13316
telemt_user_msgs_to_client{user="hello"} 86381
telemt_user_unique_ips_current{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 3141.1 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1389
telemt_connections_bad_total 564
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 820
telemt_upstream_connect_success_total 819
telemt_upstream_connect_attempts_per_request{bucket="1"} 818
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 817
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 16235656 (15.48 MB)
telemt_user_octets_to_client{user="hello"} 2450154353 (2.28 GB)
telemt_user_msgs_from_client{user="hello"} 36628
telemt_user_msgs_to_client{user="hello"} 448992
telemt_user_unique_ips_current{user="hello"} 2
```