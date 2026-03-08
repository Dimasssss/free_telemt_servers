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

# Server Metrics 2026-03-08 19:58:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 46178.1 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105399
telemt_connections_bad_total 5066
telemt_handshake_timeouts_total 1273
telemt_upstream_connect_attempt_total 95690
telemt_upstream_connect_success_total 95657
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 95690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 90088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5507
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 95651
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 2286280345 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 60419191087 (56.27 GB)
telemt_user_msgs_from_client{user="hello"} 2319499
telemt_user_msgs_to_client{user="hello"} 3258736
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 46176.8 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24448
telemt_connections_bad_total 232
telemt_handshake_timeouts_total 129
telemt_upstream_connect_attempt_total 23661
telemt_upstream_connect_success_total 23656
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 23661
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1507
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23650
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 796138315 (759.26 MB)
telemt_user_octets_to_client{user="hello"} 21396741835 (19.93 GB)
telemt_user_msgs_from_client{user="hello"} 917716
telemt_user_msgs_to_client{user="hello"} 5811308
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 46176.6 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14468
telemt_connections_bad_total 178
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 13125
telemt_upstream_connect_success_total 13049
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 956
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13043
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 1084377214 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 5481287856 (5.10 GB)
telemt_user_msgs_from_client{user="hello"} 522991
telemt_user_msgs_to_client{user="hello"} 919568
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 46176.3 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18783
telemt_connections_bad_total 186
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 17975
telemt_upstream_connect_success_total 17938
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 17975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1321
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17934
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 1057830028 (1008.83 MB)
telemt_user_octets_to_client{user="hello"} 6292515191 (5.86 GB)
telemt_user_msgs_from_client{user="hello"} 557995
telemt_user_msgs_to_client{user="hello"} 1414443
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 46176.6 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27246
telemt_connections_bad_total 8717
telemt_handshake_timeouts_total 237
telemt_upstream_connect_attempt_total 17862
telemt_upstream_connect_success_total 17855
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 17862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14717
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17849
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 336137693 (320.57 MB)
telemt_user_octets_to_client{user="hello"} 15304478440 (14.25 GB)
telemt_user_msgs_from_client{user="hello"} 462240
telemt_user_msgs_to_client{user="hello"} 1995661
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 6
```