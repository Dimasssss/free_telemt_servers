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

# Server Metrics 2026-03-06 03:52:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 20242.5 (5h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70297
telemt_connections_bad_total 51933
telemt_handshake_timeouts_total 2423
telemt_upstream_connect_attempt_total 14585
telemt_upstream_connect_success_total 14583
telemt_upstream_connect_attempts_per_request{bucket="1"} 14581
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 870
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14581
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 192894254 (183.96 MB)
telemt_user_octets_to_client{user="hello"} 13369390713 (12.45 GB)
telemt_user_msgs_from_client{user="hello"} 345029
telemt_user_msgs_to_client{user="hello"} 1974046
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 20240.3 (5h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1917
telemt_connections_bad_total 141
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1751
telemt_upstream_connect_success_total 1750
telemt_upstream_connect_attempts_per_request{bucket="1"} 1749
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1686
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 61
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1748
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 49899812 (47.59 MB)
telemt_user_octets_to_client{user="hello"} 894080982 (852.66 MB)
telemt_user_msgs_from_client{user="hello"} 64012
telemt_user_msgs_to_client{user="hello"} 276049
telemt_user_unique_ips_current{user="hello"} 9
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 20240.7 (5h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1313
telemt_connections_bad_total 194
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1110
telemt_upstream_connect_success_total 1110
telemt_upstream_connect_attempts_per_request{bucket="1"} 1110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 160
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1106
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 36388502 (34.70 MB)
telemt_user_octets_to_client{user="hello"} 1722377283 (1.60 GB)
telemt_user_msgs_from_client{user="hello"} 45709
telemt_user_msgs_to_client{user="hello"} 344475
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 20243.5 (5h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2589
telemt_connections_bad_total 127
telemt_handshake_timeouts_total 298
telemt_upstream_connect_attempt_total 2097
telemt_upstream_connect_success_total 2097
telemt_upstream_connect_attempts_per_request{bucket="1"} 2097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 364
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2093
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 94436087 (90.06 MB)
telemt_user_octets_to_client{user="hello"} 5625740795 (5.24 GB)
telemt_user_msgs_from_client{user="hello"} 132130
telemt_user_msgs_to_client{user="hello"} 1177703
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 20243.2 (5h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6534
telemt_connections_bad_total 3693
telemt_handshake_timeouts_total 142
telemt_upstream_connect_attempt_total 2632
telemt_upstream_connect_success_total 2632
telemt_upstream_connect_attempts_per_request{bucket="1"} 2632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 324
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2630
telemt_user_connections_current{user="hello"} 1
telemt_user_octets_from_client{user="hello"} 50135328 (47.81 MB)
telemt_user_octets_to_client{user="hello"} 11289198664 (10.51 GB)
telemt_user_msgs_from_client{user="hello"} 132564
telemt_user_msgs_to_client{user="hello"} 2051273
telemt_user_unique_ips_current{user="hello"} 1
```