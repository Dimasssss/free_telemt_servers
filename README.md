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

# Server Metrics 2026-03-08 15:31:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 30154.7 (8h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73888
telemt_connections_bad_total 5026
telemt_handshake_timeouts_total 1053
telemt_upstream_connect_attempt_total 65190
telemt_upstream_connect_success_total 65167
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 65190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3809
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 65163
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 1699417198 (1.58 GB)
telemt_user_octets_to_client{user="hello"} 34504639421 (32.13 GB)
telemt_user_msgs_from_client{user="hello"} 1538562
telemt_user_msgs_to_client{user="hello"} 2057313
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 30153.7 (8h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15586
telemt_connections_bad_total 129
telemt_handshake_timeouts_total 119
telemt_upstream_connect_attempt_total 15050
telemt_upstream_connect_success_total 15049
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 15050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1073
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15045
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 567234909 (540.96 MB)
telemt_user_octets_to_client{user="hello"} 12953131994 (12.06 GB)
telemt_user_msgs_from_client{user="hello"} 576278
telemt_user_msgs_to_client{user="hello"} 3405862
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 30153.4 (8h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10012
telemt_connections_bad_total 146
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 9385
telemt_upstream_connect_success_total 9309
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 9385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 638
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9305
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 216621800 (206.59 MB)
telemt_user_octets_to_client{user="hello"} 3186587383 (2.97 GB)
telemt_user_msgs_from_client{user="hello"} 159595
telemt_user_msgs_to_client{user="hello"} 547073
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 30153.2 (8h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12935
telemt_connections_bad_total 155
telemt_handshake_timeouts_total 53
telemt_upstream_connect_attempt_total 12327
telemt_upstream_connect_success_total 12299
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 12327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 908
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12295
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 947926361 (904.01 MB)
telemt_user_octets_to_client{user="hello"} 4615159656 (4.30 GB)
telemt_user_msgs_from_client{user="hello"} 467817
telemt_user_msgs_to_client{user="hello"} 1041286
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 30153.6 (8h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17138
telemt_connections_bad_total 5550
telemt_handshake_timeouts_total 119
telemt_upstream_connect_attempt_total 11218
telemt_upstream_connect_success_total 11214
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 11218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1865
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11210
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 233150546 (222.35 MB)
telemt_user_octets_to_client{user="hello"} 8414008710 (7.84 GB)
telemt_user_msgs_from_client{user="hello"} 282233
telemt_user_msgs_to_client{user="hello"} 1180638
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 4
```