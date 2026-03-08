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

# Server Metrics 2026-03-08 13:07:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 21525.2 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47668
telemt_connections_bad_total 2661
telemt_handshake_timeouts_total 289
telemt_upstream_connect_attempt_total 42765
telemt_upstream_connect_success_total 42744
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 42765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2480
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42740
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 1285527131 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 21037389601 (19.59 GB)
telemt_user_msgs_from_client{user="hello"} 1045471
telemt_user_msgs_to_client{user="hello"} 1288372
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 21525.0 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11142
telemt_connections_bad_total 86
telemt_handshake_timeouts_total 108
telemt_upstream_connect_attempt_total 10733
telemt_upstream_connect_success_total 10732
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 688
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10730
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 428169553 (408.33 MB)
telemt_user_octets_to_client{user="hello"} 7233454572 (6.74 GB)
telemt_user_msgs_from_client{user="hello"} 376122
telemt_user_msgs_to_client{user="hello"} 1855648
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 21523.9 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7543
telemt_connections_bad_total 128
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 7108
telemt_upstream_connect_success_total 7033
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 7108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 420
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7029
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 163858971 (156.27 MB)
telemt_user_octets_to_client{user="hello"} 1972911977 (1.84 GB)
telemt_user_msgs_from_client{user="hello"} 109968
telemt_user_msgs_to_client{user="hello"} 348780
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 21523.9 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9703
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 42
telemt_upstream_connect_attempt_total 9291
telemt_upstream_connect_success_total 9273
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 9291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 599
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9271
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 899908338 (858.22 MB)
telemt_user_octets_to_client{user="hello"} 3736961939 (3.48 GB)
telemt_user_msgs_from_client{user="hello"} 409757
telemt_user_msgs_to_client{user="hello"} 803845
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 21524.1 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12872
telemt_connections_bad_total 4000
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 8645
telemt_upstream_connect_success_total 8642
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 8645
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1636
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8638
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 213604639 (203.71 MB)
telemt_user_octets_to_client{user="hello"} 7625501079 (7.10 GB)
telemt_user_msgs_from_client{user="hello"} 239575
telemt_user_msgs_to_client{user="hello"} 1039856
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```