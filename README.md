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

# Server Metrics 2026-03-08 06:41:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 50201.4 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74176
telemt_connections_bad_total 6650
telemt_handshake_timeouts_total 753
telemt_upstream_connect_attempt_total 63277
telemt_upstream_connect_success_total 63158
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 63277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3272
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 63152
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 2616000810 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 40106501849 (37.35 GB)
telemt_user_msgs_from_client{user="hello"} 1846722
telemt_user_msgs_to_client{user="hello"} 6310097
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 50200.9 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10955
telemt_connections_bad_total 372
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 10384
telemt_upstream_connect_success_total 10375
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 10384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 807
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10369
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 284867590 (271.67 MB)
telemt_user_octets_to_client{user="hello"} 15664879484 (14.59 GB)
telemt_user_msgs_from_client{user="hello"} 513467
telemt_user_msgs_to_client{user="hello"} 3631828
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 50200.6 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7188
telemt_connections_bad_total 351
telemt_handshake_timeouts_total 297
telemt_upstream_connect_attempt_total 6407
telemt_upstream_connect_success_total 6407
telemt_upstream_connect_attempts_per_request{bucket="1"} 6407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 813
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6401
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 136727811 (130.39 MB)
telemt_user_octets_to_client{user="hello"} 14758415358 (13.74 GB)
telemt_user_msgs_from_client{user="hello"} 247879
telemt_user_msgs_to_client{user="hello"} 3162400
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 50028.7 (13h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15869
telemt_connections_bad_total 245
telemt_handshake_timeouts_total 66
telemt_upstream_connect_attempt_total 15212
telemt_upstream_connect_success_total 15184
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 15212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2275
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15178
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 482864635 (460.50 MB)
telemt_user_octets_to_client{user="hello"} 13775769585 (12.83 GB)
telemt_user_msgs_from_client{user="hello"} 468921
telemt_user_msgs_to_client{user="hello"} 3846635
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 50200.7 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20920
telemt_connections_bad_total 9283
telemt_handshake_timeouts_total 43
telemt_upstream_connect_attempt_total 11346
telemt_upstream_connect_success_total 11338
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 11346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2439
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11332
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 1659481418 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 10852963751 (10.11 GB)
telemt_user_msgs_from_client{user="hello"} 890789
telemt_user_msgs_to_client{user="hello"} 2360221
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 5
```