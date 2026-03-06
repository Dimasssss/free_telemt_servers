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

# Server Metrics 2026-03-06 03:57:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 20550.4 (5h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70631
telemt_connections_bad_total 51933
telemt_handshake_timeouts_total 2424
telemt_upstream_connect_attempt_total 14919
telemt_upstream_connect_success_total 14917
telemt_upstream_connect_attempts_per_request{bucket="1"} 14915
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 887
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14915
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 195559651 (186.50 MB)
telemt_user_octets_to_client{user="hello"} 13499339757 (12.57 GB)
telemt_user_msgs_from_client{user="hello"} 350121
telemt_user_msgs_to_client{user="hello"} 1994434
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 20548.3 (5h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1931
telemt_connections_bad_total 141
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1765
telemt_upstream_connect_success_total 1764
telemt_upstream_connect_attempts_per_request{bucket="1"} 1763
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 61
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1762
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 49964037 (47.65 MB)
telemt_user_octets_to_client{user="hello"} 894698456 (853.25 MB)
telemt_user_msgs_from_client{user="hello"} 64237
telemt_user_msgs_to_client{user="hello"} 276588
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 20548.8 (5h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1336
telemt_connections_bad_total 194
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1133
telemt_upstream_connect_success_total 1133
telemt_upstream_connect_attempts_per_request{bucket="1"} 1133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 160
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1129
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 36448180 (34.76 MB)
telemt_user_octets_to_client{user="hello"} 1723440704 (1.61 GB)
telemt_user_msgs_from_client{user="hello"} 45902
telemt_user_msgs_to_client{user="hello"} 344885
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 20551.3 (5h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2599
telemt_connections_bad_total 127
telemt_handshake_timeouts_total 298
telemt_upstream_connect_attempt_total 2107
telemt_upstream_connect_success_total 2107
telemt_upstream_connect_attempts_per_request{bucket="1"} 2107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1732
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 369
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2103
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 94446413 (90.07 MB)
telemt_user_octets_to_client{user="hello"} 5626110808 (5.24 GB)
telemt_user_msgs_from_client{user="hello"} 132157
telemt_user_msgs_to_client{user="hello"} 1177870
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 20551.3 (5h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6622
telemt_connections_bad_total 3748
telemt_handshake_timeouts_total 142
telemt_upstream_connect_attempt_total 2665
telemt_upstream_connect_success_total 2665
telemt_upstream_connect_attempts_per_request{bucket="1"} 2665
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 335
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2663
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 50208278 (47.88 MB)
telemt_user_octets_to_client{user="hello"} 11290166233 (10.51 GB)
telemt_user_msgs_from_client{user="hello"} 132748
telemt_user_msgs_to_client{user="hello"} 2051706
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 2
```