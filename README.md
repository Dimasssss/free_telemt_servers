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

# Server Metrics 2026-03-09 00:29:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 4195.6 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3532
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 166
telemt_upstream_connect_attempt_total 3041
telemt_upstream_connect_success_total 3040
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3041
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 298
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3038
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 38192333 (36.42 MB)
telemt_user_octets_to_client{user="hello"} 4991164011 (4.65 GB)
telemt_user_msgs_from_client{user="hello"} 92938
telemt_user_msgs_to_client{user="hello"} 165960
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 4193.8 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 264
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 256
telemt_upstream_connect_success_total 256
telemt_upstream_connect_attempts_per_request{bucket="1"} 256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 254
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 1790930 (1.71 MB)
telemt_user_octets_to_client{user="hello"} 46107619 (43.97 MB)
telemt_user_msgs_from_client{user="hello"} 5000
telemt_user_msgs_to_client{user="hello"} 14374
telemt_user_unique_ips_current{user="hello"} 5
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 4194.6 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 322
telemt_connections_bad_total 28
telemt_upstream_connect_attempt_total 291
telemt_upstream_connect_success_total 291
telemt_upstream_connect_attempts_per_request{bucket="1"} 291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 289
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 15864776 (15.13 MB)
telemt_user_octets_to_client{user="hello"} 26947424 (25.70 MB)
telemt_user_msgs_from_client{user="hello"} 8651
telemt_user_msgs_to_client{user="hello"} 10321
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 4189.3 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 555
telemt_connections_bad_total 3
telemt_upstream_connect_attempt_total 546
telemt_upstream_connect_success_total 546
telemt_upstream_connect_attempts_per_request{bucket="1"} 546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 457
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 85
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 544
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 3672105 (3.50 MB)
telemt_user_octets_to_client{user="hello"} 179913830 (171.58 MB)
telemt_user_msgs_from_client{user="hello"} 9015
telemt_user_msgs_to_client{user="hello"} 35140
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 4194.8 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1355
telemt_connections_bad_total 751
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 593
telemt_upstream_connect_success_total 593
telemt_upstream_connect_attempts_per_request{bucket="1"} 593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 92
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 591
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 6100284 (5.82 MB)
telemt_user_octets_to_client{user="hello"} 1258987703 (1.17 GB)
telemt_user_msgs_from_client{user="hello"} 17327
telemt_user_msgs_to_client{user="hello"} 152586
telemt_user_unique_ips_current{user="hello"} 6
```