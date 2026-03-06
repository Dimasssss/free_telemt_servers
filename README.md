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

# Server Metrics 2026-03-06 17:08:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 24375.0 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57437
telemt_connections_bad_total 3117
telemt_handshake_timeouts_total 241
telemt_upstream_connect_attempt_total 50282
telemt_upstream_connect_success_total 50270
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 50282
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2846
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50266
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 2659875366 (2.48 GB)
telemt_user_octets_to_client{user="hello"} 33252711277 (30.97 GB)
telemt_user_msgs_from_client{user="hello"} 1794138
telemt_user_msgs_to_client{user="hello"} 5252480
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 24374.6 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10776
telemt_connections_bad_total 176
telemt_handshake_timeouts_total 101
telemt_upstream_connect_attempt_total 10248
telemt_upstream_connect_success_total 10229
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 10248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 639
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10227
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 134085148 (127.87 MB)
telemt_user_octets_to_client{user="hello"} 5929828850 (5.52 GB)
telemt_user_msgs_from_client{user="hello"} 221657
telemt_user_msgs_to_client{user="hello"} 1828113
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 24373.7 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8917
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 8588
telemt_upstream_connect_success_total 8586
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 520
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8584
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 126457554 (120.60 MB)
telemt_user_octets_to_client{user="hello"} 5170977818 (4.82 GB)
telemt_user_msgs_from_client{user="hello"} 194905
telemt_user_msgs_to_client{user="hello"} 1220205
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 24373.1 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12523
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 117
telemt_upstream_connect_attempt_total 11613
telemt_upstream_connect_success_total 11573
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 11613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10755
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 769
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11571
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 157401209 (150.11 MB)
telemt_user_octets_to_client{user="hello"} 3884755395 (3.62 GB)
telemt_user_msgs_from_client{user="hello"} 199286
telemt_user_msgs_to_client{user="hello"} 989641
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 24374.3 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17542
telemt_connections_bad_total 5943
telemt_handshake_timeouts_total 560
telemt_upstream_connect_attempt_total 10734
telemt_upstream_connect_success_total 10734
telemt_upstream_connect_attempts_per_request{bucket="1"} 10734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1610
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10732
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 244154449 (232.84 MB)
telemt_user_octets_to_client{user="hello"} 21930917694 (20.42 GB)
telemt_user_msgs_from_client{user="hello"} 408146
telemt_user_msgs_to_client{user="hello"} 3970894
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```