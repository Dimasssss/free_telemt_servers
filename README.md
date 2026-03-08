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

# Server Metrics 2026-03-08 05:04:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 44349.2 (12h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63278
telemt_connections_bad_total 6038
telemt_handshake_timeouts_total 459
telemt_upstream_connect_attempt_total 53542
telemt_upstream_connect_success_total 53534
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 53542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2798
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53528
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 2452522622 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 35450950711 (33.02 GB)
telemt_user_msgs_from_client{user="hello"} 1635091
telemt_user_msgs_to_client{user="hello"} 5547271
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 44348.4 (12h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8716
telemt_connections_bad_total 370
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 8196
telemt_upstream_connect_success_total 8188
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 8196
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8182
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 205181720 (195.68 MB)
telemt_user_octets_to_client{user="hello"} 11539560590 (10.75 GB)
telemt_user_msgs_from_client{user="hello"} 375937
telemt_user_msgs_to_client{user="hello"} 2721232
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 44348.1 (12h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5397
telemt_connections_bad_total 286
telemt_handshake_timeouts_total 174
telemt_upstream_connect_attempt_total 4852
telemt_upstream_connect_success_total 4852
telemt_upstream_connect_attempts_per_request{bucket="1"} 4852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 729
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4848
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 127015186 (121.13 MB)
telemt_user_octets_to_client{user="hello"} 14536937319 (13.54 GB)
telemt_user_msgs_from_client{user="hello"} 230892
telemt_user_msgs_to_client{user="hello"} 3091219
telemt_user_unique_ips_current{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 44176.4 (12h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14249
telemt_connections_bad_total 226
telemt_handshake_timeouts_total 53
telemt_upstream_connect_attempt_total 13663
telemt_upstream_connect_success_total 13637
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 13663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2149
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13633
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 357213920 (340.67 MB)
telemt_user_octets_to_client{user="hello"} 12787767246 (11.91 GB)
telemt_user_msgs_from_client{user="hello"} 395088
telemt_user_msgs_to_client{user="hello"} 3594614
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 44348.3 (12h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17700
telemt_connections_bad_total 8234
telemt_handshake_timeouts_total 39
telemt_upstream_connect_attempt_total 9204
telemt_upstream_connect_success_total 9196
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 9204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1953
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9192
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 1637170670 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 9707811564 (9.04 GB)
telemt_user_msgs_from_client{user="hello"} 845722
telemt_user_msgs_to_client{user="hello"} 2098415
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 3
```