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

# Server Metrics 2026-03-07 07:46:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.7

telemt_uptime_seconds 2290.0 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2873
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 2775
telemt_upstream_connect_success_total 2775
telemt_upstream_connect_attempts_per_request{bucket="1"} 2775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2773
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 51968413 (49.56 MB)
telemt_user_octets_to_client{user="hello"} 3336326789 (3.11 GB)
telemt_user_msgs_from_client{user="hello"} 73584
telemt_user_msgs_to_client{user="hello"} 641561
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.7

telemt_uptime_seconds 2289.4 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 747
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 687
telemt_upstream_connect_success_total 686
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 684
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 4680754 (4.46 MB)
telemt_user_octets_to_client{user="hello"} 296905921 (283.15 MB)
telemt_user_msgs_from_client{user="hello"} 10639
telemt_user_msgs_to_client{user="hello"} 76553
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.7

telemt_uptime_seconds 2288.9 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 630
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 623
telemt_upstream_connect_success_total 623
telemt_upstream_connect_attempts_per_request{bucket="1"} 623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 554
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 68
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 621
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 26193343 (24.98 MB)
telemt_user_octets_to_client{user="hello"} 182296588 (173.85 MB)
telemt_user_msgs_from_client{user="hello"} 15063
telemt_user_msgs_to_client{user="hello"} 47340
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.7

telemt_uptime_seconds 2289.0 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 851
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 824
telemt_upstream_connect_success_total 823
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 824
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 821
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 6715752 (6.40 MB)
telemt_user_octets_to_client{user="hello"} 226243754 (215.76 MB)
telemt_user_msgs_from_client{user="hello"} 12929
telemt_user_msgs_to_client{user="hello"} 62087
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.7

telemt_uptime_seconds 2289.3 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1609
telemt_connections_bad_total 411
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 1107
telemt_upstream_connect_success_total 1107
telemt_upstream_connect_attempts_per_request{bucket="1"} 1107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 212
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1105
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 18259175 (17.41 MB)
telemt_user_octets_to_client{user="hello"} 1953054481 (1.82 GB)
telemt_user_msgs_from_client{user="hello"} 24749
telemt_user_msgs_to_client{user="hello"} 351895
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 6
```