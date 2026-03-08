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

# Server Metrics 2026-03-08 09:26:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 8244.5 (2h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17849
telemt_connections_bad_total 2498
telemt_handshake_timeouts_total 107
telemt_upstream_connect_attempt_total 14564
telemt_upstream_connect_success_total 14552
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 14564
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 853
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14550
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 467657426 (445.99 MB)
telemt_user_octets_to_client{user="hello"} 9220995953 (8.59 GB)
telemt_user_msgs_from_client{user="hello"} 395580
telemt_user_msgs_to_client{user="hello"} 478644
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 8243.5 (2h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3876
telemt_connections_bad_total 50
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 3679
telemt_upstream_connect_success_total 3679
telemt_upstream_connect_attempts_per_request{bucket="1"} 3679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 211
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3677
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 47267671 (45.08 MB)
telemt_user_octets_to_client{user="hello"} 2647289948 (2.47 GB)
telemt_user_msgs_from_client{user="hello"} 89394
telemt_user_msgs_to_client{user="hello"} 673618
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 8243.3 (2h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3166
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 3089
telemt_upstream_connect_success_total 3089
telemt_upstream_connect_attempts_per_request{bucket="1"} 3089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3087
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 30916734 (29.48 MB)
telemt_user_octets_to_client{user="hello"} 572596688 (546.07 MB)
telemt_user_msgs_from_client{user="hello"} 27877
telemt_user_msgs_to_client{user="hello"} 108514
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 8243.1 (2h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3565
telemt_connections_bad_total 30
telemt_handshake_timeouts_total 26
telemt_upstream_connect_attempt_total 3398
telemt_upstream_connect_success_total 3393
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 3398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3153
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 222
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3391
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 80166956 (76.45 MB)
telemt_user_octets_to_client{user="hello"} 1408156740 (1.31 GB)
telemt_user_msgs_from_client{user="hello"} 63459
telemt_user_msgs_to_client{user="hello"} 324802
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 8243.5 (2h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5039
telemt_connections_bad_total 1542
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 3449
telemt_upstream_connect_success_total 3449
telemt_upstream_connect_attempts_per_request{bucket="1"} 3449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 673
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3447
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 43413470 (41.40 MB)
telemt_user_octets_to_client{user="hello"} 3006083717 (2.80 GB)
telemt_user_msgs_from_client{user="hello"} 75341
telemt_user_msgs_to_client{user="hello"} 338995
telemt_user_unique_ips_current{user="hello"} 7
```