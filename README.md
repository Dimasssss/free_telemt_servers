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

# Server Metrics 2026-03-06 17:03:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 24067.2 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56790
telemt_connections_bad_total 3113
telemt_handshake_timeouts_total 241
telemt_upstream_connect_attempt_total 49654
telemt_upstream_connect_success_total 49642
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 49654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2814
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49638
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 2584402045 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 32618612386 (30.38 GB)
telemt_user_msgs_from_client{user="hello"} 1760170
telemt_user_msgs_to_client{user="hello"} 5159714
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 24066.6 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10662
telemt_connections_bad_total 176
telemt_handshake_timeouts_total 101
telemt_upstream_connect_attempt_total 10134
telemt_upstream_connect_success_total 10115
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 10134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 628
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10113
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 132658448 (126.51 MB)
telemt_user_octets_to_client{user="hello"} 5868831400 (5.47 GB)
telemt_user_msgs_from_client{user="hello"} 218417
telemt_user_msgs_to_client{user="hello"} 1809277
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 24065.8 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8859
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 8532
telemt_upstream_connect_success_total 8530
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8528
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 125857429 (120.03 MB)
telemt_user_octets_to_client{user="hello"} 5128916044 (4.78 GB)
telemt_user_msgs_from_client{user="hello"} 193187
telemt_user_msgs_to_client{user="hello"} 1211312
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 24065.1 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12449
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 117
telemt_upstream_connect_attempt_total 11539
telemt_upstream_connect_success_total 11499
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 11539
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 755
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11497
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 156743288 (149.48 MB)
telemt_user_octets_to_client{user="hello"} 3851579827 (3.59 GB)
telemt_user_msgs_from_client{user="hello"} 197379
telemt_user_msgs_to_client{user="hello"} 980202
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 24066.4 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17239
telemt_connections_bad_total 5889
telemt_handshake_timeouts_total 559
telemt_upstream_connect_attempt_total 10491
telemt_upstream_connect_success_total 10491
telemt_upstream_connect_attempts_per_request{bucket="1"} 10491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10489
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 242931330 (231.68 MB)
telemt_user_octets_to_client{user="hello"} 21868387774 (20.37 GB)
telemt_user_msgs_from_client{user="hello"} 405489
telemt_user_msgs_to_client{user="hello"} 3952668
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```