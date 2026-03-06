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

# Server Metrics 2026-03-06 03:42:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 19626.8 (5h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69560
telemt_connections_bad_total 51933
telemt_handshake_timeouts_total 2423
telemt_upstream_connect_attempt_total 13859
telemt_upstream_connect_success_total 13857
telemt_upstream_connect_attempts_per_request{bucket="1"} 13855
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 836
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13855
telemt_user_connections_current{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 188173473 (179.46 MB)
telemt_user_octets_to_client{user="hello"} 13280307749 (12.37 GB)
telemt_user_msgs_from_client{user="hello"} 337230
telemt_user_msgs_to_client{user="hello"} 1956491
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 19624.9 (5h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1834
telemt_connections_bad_total 141
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1668
telemt_upstream_connect_success_total 1667
telemt_upstream_connect_attempts_per_request{bucket="1"} 1666
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1665
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 48148065 (45.92 MB)
telemt_user_octets_to_client{user="hello"} 789368937 (752.80 MB)
telemt_user_msgs_from_client{user="hello"} 59619
telemt_user_msgs_to_client{user="hello"} 247509
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 19625.1 (5h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1276
telemt_connections_bad_total 192
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1075
telemt_upstream_connect_success_total 1075
telemt_upstream_connect_attempts_per_request{bucket="1"} 1075
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 156
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1071
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 36125027 (34.45 MB)
telemt_user_octets_to_client{user="hello"} 1711370242 (1.59 GB)
telemt_user_msgs_from_client{user="hello"} 44982
telemt_user_msgs_to_client{user="hello"} 341060
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 19627.9 (5h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2541
telemt_connections_bad_total 126
telemt_handshake_timeouts_total 298
telemt_upstream_connect_attempt_total 2050
telemt_upstream_connect_success_total 2050
telemt_upstream_connect_attempts_per_request{bucket="1"} 2050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 359
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2046
telemt_user_connections_current{user="hello"} 1
telemt_user_octets_from_client{user="hello"} 94298089 (89.93 MB)
telemt_user_octets_to_client{user="hello"} 5621812840 (5.24 GB)
telemt_user_msgs_from_client{user="hello"} 131856
telemt_user_msgs_to_client{user="hello"} 1176205
telemt_user_unique_ips_current{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 19627.6 (5h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6337
telemt_connections_bad_total 3585
telemt_handshake_timeouts_total 142
telemt_upstream_connect_attempt_total 2549
telemt_upstream_connect_success_total 2549
telemt_upstream_connect_attempts_per_request{bucket="1"} 2549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 315
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2547
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 49736880 (47.43 MB)
telemt_user_octets_to_client{user="hello"} 11283840194 (10.51 GB)
telemt_user_msgs_from_client{user="hello"} 131266
telemt_user_msgs_to_client{user="hello"} 2048992
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```