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

# Server Metrics 2026-03-07 03:19:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 33063.2 (9h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37531
telemt_connections_bad_total 211
telemt_handshake_timeouts_total 520
telemt_upstream_connect_attempt_total 35157
telemt_upstream_connect_success_total 35149
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 35157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2082
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 35145
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 2122969610 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 36599115281 (34.09 GB)
telemt_user_msgs_from_client{user="hello"} 1465616
telemt_user_msgs_to_client{user="hello"} 5724471
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 33061.5 (9h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6974
telemt_connections_bad_total 216
telemt_handshake_timeouts_total 107
telemt_upstream_connect_attempt_total 6495
telemt_upstream_connect_success_total 6492
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 351
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6488
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 217341458 (207.27 MB)
telemt_user_octets_to_client{user="hello"} 3953906422 (3.68 GB)
telemt_user_msgs_from_client{user="hello"} 206796
telemt_user_msgs_to_client{user="hello"} 1108226
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 33061.5 (9h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3604
telemt_connections_bad_total 191
telemt_handshake_timeouts_total 27
telemt_upstream_connect_attempt_total 3283
telemt_upstream_connect_success_total 3283
telemt_upstream_connect_attempts_per_request{bucket="1"} 3283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2943
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 340
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3279
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 67696343 (64.56 MB)
telemt_user_octets_to_client{user="hello"} 2046990630 (1.91 GB)
telemt_user_msgs_from_client{user="hello"} 71037
telemt_user_msgs_to_client{user="hello"} 438426
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 33061.6 (9h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4985
telemt_connections_bad_total 174
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 4736
telemt_upstream_connect_success_total 4729
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 510
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4725
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 104055897 (99.24 MB)
telemt_user_octets_to_client{user="hello"} 1599635838 (1.49 GB)
telemt_user_msgs_from_client{user="hello"} 94460
telemt_user_msgs_to_client{user="hello"} 441110
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 33061.9 (9h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14524
telemt_connections_bad_total 6896
telemt_handshake_timeouts_total 135
telemt_upstream_connect_attempt_total 7360
telemt_upstream_connect_success_total 7359
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7360
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1095
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7355
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 239688589 (228.58 MB)
telemt_user_octets_to_client{user="hello"} 9401453027 (8.76 GB)
telemt_user_msgs_from_client{user="hello"} 244117
telemt_user_msgs_to_client{user="hello"} 1883097
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```