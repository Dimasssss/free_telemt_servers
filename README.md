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

# Server Metrics 2026-03-10 14:03:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 139432.4 (38h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 320263
telemt_connections_bad_total 3673
telemt_handshake_timeouts_total 3370
telemt_upstream_connect_attempt_total 299814
telemt_upstream_connect_success_total 299654
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 299814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 277068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 299640
telemt_user_connections_current{user="hello"} 367
telemt_user_octets_from_client{user="hello"} 6859713623 (6.39 GB)
telemt_user_octets_to_client{user="hello"} 197439387603 (183.88 GB)
telemt_user_msgs_from_client{user="hello"} 7157681
telemt_user_msgs_to_client{user="hello"} 11771339
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 139431.1 (38h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99073
telemt_connections_bad_total 3275
telemt_handshake_timeouts_total 1308
telemt_upstream_connect_attempt_total 89429
telemt_upstream_connect_success_total 89382
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 89428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8576
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 89368
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 2876095293 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 38011399795 (35.40 GB)
telemt_user_msgs_from_client{user="hello"} 2339521
telemt_user_msgs_to_client{user="hello"} 11014572
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 139431.6 (38h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141795
telemt_connections_bad_total 1240
telemt_handshake_timeouts_total 6740
telemt_upstream_connect_attempt_total 106505
telemt_upstream_connect_success_total 106501
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 106504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 94228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12232
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 106487
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 6689887212 (6.23 GB)
telemt_user_octets_to_client{user="hello"} 69400696338 (64.63 GB)
telemt_user_msgs_from_client{user="hello"} 4573557
telemt_user_msgs_to_client{user="hello"} 11786329
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 139426.4 (38h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145466
telemt_connections_bad_total 1064
telemt_handshake_timeouts_total 3060
telemt_upstream_connect_attempt_total 134426
telemt_upstream_connect_success_total 134124
telemt_upstream_connect_fail_total 302
telemt_upstream_connect_attempts_per_request{bucket="1"} 134426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 119208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14487
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 83
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 346
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 302
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 134110
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 5061192291 (4.71 GB)
telemt_user_octets_to_client{user="hello"} 94226231245 (87.76 GB)
telemt_user_msgs_from_client{user="hello"} 3897344
telemt_user_msgs_to_client{user="hello"} 21342079
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 139431.7 (38h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215847
telemt_connections_bad_total 31181
telemt_handshake_timeouts_total 6175
telemt_upstream_connect_attempt_total 169520
telemt_upstream_connect_success_total 168558
telemt_upstream_connect_fail_total 962
telemt_upstream_connect_attempts_per_request{bucket="1"} 169520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 145820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22513
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 962
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 168544
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 3645041342 (3.39 GB)
telemt_user_octets_to_client{user="hello"} 119996838944 (111.76 GB)
telemt_user_msgs_from_client{user="hello"} 3854543
telemt_user_msgs_to_client{user="hello"} 16495563
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 20
```