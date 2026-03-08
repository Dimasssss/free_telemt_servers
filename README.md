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

# Server Metrics 2026-03-08 16:32:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 33853.2 (9h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81682
telemt_connections_bad_total 5039
telemt_handshake_timeouts_total 1097
telemt_upstream_connect_attempt_total 72776
telemt_upstream_connect_success_total 72753
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 72776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4303
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 72749
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 1881946463 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 39118514253 (36.43 GB)
telemt_user_msgs_from_client{user="hello"} 1725507
telemt_user_msgs_to_client{user="hello"} 2369659
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 33852.4 (9h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17516
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 122
telemt_upstream_connect_attempt_total 16942
telemt_upstream_connect_success_total 16940
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 16942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1204
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16936
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 637686399 (608.15 MB)
telemt_user_octets_to_client{user="hello"} 17201051463 (16.02 GB)
telemt_user_msgs_from_client{user="hello"} 685922
telemt_user_msgs_to_client{user="hello"} 4633422
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 33852.3 (9h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10769
telemt_connections_bad_total 150
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 10134
telemt_upstream_connect_success_total 10058
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 10134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 697
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10054
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 222686226 (212.37 MB)
telemt_user_octets_to_client{user="hello"} 3576530338 (3.33 GB)
telemt_user_msgs_from_client{user="hello"} 174877
telemt_user_msgs_to_client{user="hello"} 620327
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 33852.1 (9h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14588
telemt_connections_bad_total 165
telemt_handshake_timeouts_total 54
telemt_upstream_connect_attempt_total 13896
telemt_upstream_connect_success_total 13866
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 13896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1004
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13862
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 1000469868 (954.12 MB)
telemt_user_octets_to_client{user="hello"} 5104575411 (4.75 GB)
telemt_user_msgs_from_client{user="hello"} 501449
telemt_user_msgs_to_client{user="hello"} 1149598
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 33852.3 (9h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19214
telemt_connections_bad_total 6248
telemt_handshake_timeouts_total 166
telemt_upstream_connect_attempt_total 12507
telemt_upstream_connect_success_total 12503
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 12507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1974
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12499
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 246769467 (235.34 MB)
telemt_user_octets_to_client{user="hello"} 10692728027 (9.96 GB)
telemt_user_msgs_from_client{user="hello"} 317467
telemt_user_msgs_to_client{user="hello"} 1383818
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 4
```