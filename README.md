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

# Server Metrics 2026-03-07 12:48:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.7

telemt_uptime_seconds 20461.2 (5h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39264
telemt_connections_bad_total 103
telemt_handshake_timeouts_total 400
telemt_upstream_connect_attempt_total 37489
telemt_upstream_connect_success_total 37478
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 37489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1833
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 37474
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 1418708634 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 23642279085 (22.02 GB)
telemt_user_msgs_from_client{user="hello"} 1070834
telemt_user_msgs_to_client{user="hello"} 3886220
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.7

telemt_uptime_seconds 20460.7 (5h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9652
telemt_connections_bad_total 41
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 9179
telemt_upstream_connect_success_total 9172
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 9179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 563
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9170
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 398916666 (380.44 MB)
telemt_user_octets_to_client{user="hello"} 7418278163 (6.91 GB)
telemt_user_msgs_from_client{user="hello"} 454944
telemt_user_msgs_to_client{user="hello"} 2180389
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.7

telemt_uptime_seconds 20460.7 (5h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6800
telemt_connections_bad_total 163
telemt_handshake_timeouts_total 193
telemt_upstream_connect_attempt_total 6144
telemt_upstream_connect_success_total 6144
telemt_upstream_connect_attempts_per_request{bucket="1"} 6144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 443
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6140
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 73945805 (70.52 MB)
telemt_user_octets_to_client{user="hello"} 3046408215 (2.84 GB)
telemt_user_msgs_from_client{user="hello"} 115213
telemt_user_msgs_to_client{user="hello"} 681824
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.7

telemt_uptime_seconds 20460.4 (5h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8988
telemt_connections_bad_total 26
telemt_handshake_timeouts_total 45
telemt_upstream_connect_attempt_total 8352
telemt_upstream_connect_success_total 8338
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 8352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 494
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8336
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 217858928 (207.77 MB)
telemt_user_octets_to_client{user="hello"} 3181898284 (2.96 GB)
telemt_user_msgs_from_client{user="hello"} 155732
telemt_user_msgs_to_client{user="hello"} 826073
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.7

telemt_uptime_seconds 20460.8 (5h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11407
telemt_connections_bad_total 3976
telemt_handshake_timeouts_total 287
telemt_upstream_connect_attempt_total 6943
telemt_upstream_connect_success_total 6942
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1385
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6940
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 119953532 (114.40 MB)
telemt_user_octets_to_client{user="hello"} 14816062931 (13.80 GB)
telemt_user_msgs_from_client{user="hello"} 182415
telemt_user_msgs_to_client{user="hello"} 2741499
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```