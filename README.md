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

# Server Metrics 2026-03-09 01:25:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 7558.9 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6325
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 176
telemt_upstream_connect_attempt_total 5708
telemt_upstream_connect_success_total 5706
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 537
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5704
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 62613237 (59.71 MB)
telemt_user_octets_to_client{user="hello"} 6900182288 (6.43 GB)
telemt_user_msgs_from_client{user="hello"} 149447
telemt_user_msgs_to_client{user="hello"} 250376
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 7557.2 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 464
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 443
telemt_upstream_connect_success_total 443
telemt_upstream_connect_attempts_per_request{bucket="1"} 443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 441
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 6480558 (6.18 MB)
telemt_user_octets_to_client{user="hello"} 422032945 (402.48 MB)
telemt_user_msgs_from_client{user="hello"} 18180
telemt_user_msgs_to_client{user="hello"} 81633
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 7557.8 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 552
telemt_connections_bad_total 53
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 487
telemt_upstream_connect_success_total 487
telemt_upstream_connect_attempts_per_request{bucket="1"} 487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 485
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 29777544 (28.40 MB)
telemt_user_octets_to_client{user="hello"} 80666325 (76.93 MB)
telemt_user_msgs_from_client{user="hello"} 16361
telemt_user_msgs_to_client{user="hello"} 25577
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 7552.6 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 886
telemt_connections_bad_total 5
telemt_upstream_connect_attempt_total 872
telemt_upstream_connect_success_total 872
telemt_upstream_connect_attempts_per_request{bucket="1"} 872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 178
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 870
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 7195238 (6.86 MB)
telemt_user_octets_to_client{user="hello"} 502895599 (479.60 MB)
telemt_user_msgs_from_client{user="hello"} 18771
telemt_user_msgs_to_client{user="hello"} 136532
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 7558.1 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2190
telemt_connections_bad_total 1358
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 813
telemt_upstream_connect_success_total 813
telemt_upstream_connect_attempts_per_request{bucket="1"} 813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 699
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 114
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 811
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 6864817 (6.55 MB)
telemt_user_octets_to_client{user="hello"} 1285398478 (1.20 GB)
telemt_user_msgs_from_client{user="hello"} 19153
telemt_user_msgs_to_client{user="hello"} 158898
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```