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

# Server Metrics 2026-03-07 17:31:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 2765.3 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5904
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 52
telemt_upstream_connect_attempt_total 5617
telemt_upstream_connect_success_total 5616
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 326
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5614
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 64879671 (61.87 MB)
telemt_user_octets_to_client{user="hello"} 2203734355 (2.05 GB)
telemt_user_msgs_from_client{user="hello"} 106014
telemt_user_msgs_to_client{user="hello"} 369132
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 2764.4 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1395
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 1363
telemt_upstream_connect_success_total 1362
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 79
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1360
telemt_user_connections_current{user="hello"} 50
telemt_user_octets_from_client{user="hello"} 21567839 (20.57 MB)
telemt_user_octets_to_client{user="hello"} 962360943 (917.78 MB)
telemt_user_msgs_from_client{user="hello"} 36395
telemt_user_msgs_to_client{user="hello"} 286077
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 2764.2 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 477
telemt_connections_bad_total 8
telemt_upstream_connect_attempt_total 467
telemt_upstream_connect_success_total 467
telemt_upstream_connect_attempts_per_request{bucket="1"} 467
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 465
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 2495764 (2.38 MB)
telemt_user_octets_to_client{user="hello"} 170997181 (163.08 MB)
telemt_user_msgs_from_client{user="hello"} 6706
telemt_user_msgs_to_client{user="hello"} 38158
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 2592.4 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 866
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 839
telemt_upstream_connect_success_total 837
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 88
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 835
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 12034701 (11.48 MB)
telemt_user_octets_to_client{user="hello"} 321213808 (306.33 MB)
telemt_user_msgs_from_client{user="hello"} 12886
telemt_user_msgs_to_client{user="hello"} 89300
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 2764.4 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1771
telemt_connections_bad_total 548
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 1182
telemt_upstream_connect_success_total 1182
telemt_upstream_connect_attempts_per_request{bucket="1"} 1182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 359
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1180
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 31210625 (29.76 MB)
telemt_user_octets_to_client{user="hello"} 683801614 (652.12 MB)
telemt_user_msgs_from_client{user="hello"} 37890
telemt_user_msgs_to_client{user="hello"} 151930
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 7
```