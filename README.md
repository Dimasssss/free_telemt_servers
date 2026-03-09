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

# Server Metrics 2026-03-09 02:11:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 10310.0 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8625
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 184
telemt_upstream_connect_attempt_total 7897
telemt_upstream_connect_success_total 7895
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7897
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 676
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7893
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 91649116 (87.40 MB)
telemt_user_octets_to_client{user="hello"} 8246968602 (7.68 GB)
telemt_user_msgs_from_client{user="hello"} 194559
telemt_user_msgs_to_client{user="hello"} 320223
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 10308.2 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 636
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 606
telemt_upstream_connect_success_total 606
telemt_upstream_connect_attempts_per_request{bucket="1"} 606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 604
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 8103458 (7.73 MB)
telemt_user_octets_to_client{user="hello"} 464480851 (442.96 MB)
telemt_user_msgs_from_client{user="hello"} 22543
telemt_user_msgs_to_client{user="hello"} 92382
telemt_user_unique_ips_current{user="hello"} 6
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 10308.5 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 688
telemt_connections_bad_total 73
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 602
telemt_upstream_connect_success_total 602
telemt_upstream_connect_attempts_per_request{bucket="1"} 602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 95
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 600
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 42718479 (40.74 MB)
telemt_user_octets_to_client{user="hello"} 91637819 (87.39 MB)
telemt_user_msgs_from_client{user="hello"} 21753
telemt_user_msgs_to_client{user="hello"} 28533
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 10303.4 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1318
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 116
telemt_upstream_connect_attempt_total 1131
telemt_upstream_connect_success_total 1131
telemt_upstream_connect_attempts_per_request{bucket="1"} 1131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 873
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 253
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1129
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 9183183 (8.76 MB)
telemt_user_octets_to_client{user="hello"} 586750976 (559.57 MB)
telemt_user_msgs_from_client{user="hello"} 23771
telemt_user_msgs_to_client{user="hello"} 167686
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 10308.9 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2866
telemt_connections_bad_total 1853
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 986
telemt_upstream_connect_success_total 986
telemt_upstream_connect_attempts_per_request{bucket="1"} 986
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 134
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 984
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 7385045 (7.04 MB)
telemt_user_octets_to_client{user="hello"} 1302650157 (1.21 GB)
telemt_user_msgs_from_client{user="hello"} 20403
telemt_user_msgs_to_client{user="hello"} 162829
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```