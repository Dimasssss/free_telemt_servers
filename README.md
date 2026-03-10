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

# Server Metrics 2026-03-10 12:52:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 135130.9 (37h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 302600
telemt_connections_bad_total 3468
telemt_handshake_timeouts_total 3107
telemt_upstream_connect_attempt_total 283400
telemt_upstream_connect_success_total 283247
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 283400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 261964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21194
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 283233
telemt_user_connections_current{user="hello"} 324
telemt_user_octets_from_client{user="hello"} 6634028656 (6.18 GB)
telemt_user_octets_to_client{user="hello"} 188881813416 (175.91 GB)
telemt_user_msgs_from_client{user="hello"} 6852033
telemt_user_msgs_to_client{user="hello"} 11091179
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 135129.8 (37h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93164
telemt_connections_bad_total 3271
telemt_handshake_timeouts_total 1276
telemt_upstream_connect_attempt_total 83801
telemt_upstream_connect_success_total 83757
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 83801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 75343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7990
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 423
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 83743
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 2789256114 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 35512434797 (33.07 GB)
telemt_user_msgs_from_client{user="hello"} 2232952
telemt_user_msgs_to_client{user="hello"} 10281842
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 135130.3 (37h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132205
telemt_connections_bad_total 1222
telemt_handshake_timeouts_total 6312
telemt_upstream_connect_attempt_total 97918
telemt_upstream_connect_success_total 97915
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 97918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 86746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 97903
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 6631929758 (6.18 GB)
telemt_user_octets_to_client{user="hello"} 67331906121 (62.71 GB)
telemt_user_msgs_from_client{user="hello"} 4423404
telemt_user_msgs_to_client{user="hello"} 11262117
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 135125.2 (37h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137004
telemt_connections_bad_total 1053
telemt_handshake_timeouts_total 2916
telemt_upstream_connect_attempt_total 126346
telemt_upstream_connect_success_total 126069
telemt_upstream_connect_fail_total 277
telemt_upstream_connect_attempts_per_request{bucket="1"} 126346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13670
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 80
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 320
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 277
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 126055
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 4251922166 (3.96 GB)
telemt_user_octets_to_client{user="hello"} 87373233993 (81.37 GB)
telemt_user_msgs_from_client{user="hello"} 3470279
telemt_user_msgs_to_client{user="hello"} 19910768
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 135130.5 (37h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203227
telemt_connections_bad_total 30242
telemt_handshake_timeouts_total 5540
telemt_upstream_connect_attempt_total 158916
telemt_upstream_connect_success_total 157954
telemt_upstream_connect_fail_total 962
telemt_upstream_connect_attempts_per_request{bucket="1"} 158916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 136889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 962
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 157940
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 3457182907 (3.22 GB)
telemt_user_octets_to_client{user="hello"} 116385917621 (108.39 GB)
telemt_user_msgs_from_client{user="hello"} 3649083
telemt_user_msgs_to_client{user="hello"} 15845848
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 18
```