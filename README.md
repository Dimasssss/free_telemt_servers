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

# Server Metrics 2026-03-08 12:05:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 17829.5 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38469
telemt_connections_bad_total 2581
telemt_handshake_timeouts_total 269
telemt_upstream_connect_attempt_total 34029
telemt_upstream_connect_success_total 34010
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 34029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1983
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 34006
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 1048425313 (999.86 MB)
telemt_user_octets_to_client{user="hello"} 17841173967 (16.62 GB)
telemt_user_msgs_from_client{user="hello"} 868285
telemt_user_msgs_to_client{user="hello"} 1064002
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 17828.3 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9732
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 101
telemt_upstream_connect_attempt_total 9344
telemt_upstream_connect_success_total 9344
telemt_upstream_connect_attempts_per_request{bucket="1"} 9344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 600
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9342
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 371138218 (353.94 MB)
telemt_user_octets_to_client{user="hello"} 6098837397 (5.68 GB)
telemt_user_msgs_from_client{user="hello"} 321309
telemt_user_msgs_to_client{user="hello"} 1587141
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 17828.2 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6565
telemt_connections_bad_total 36
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 6262
telemt_upstream_connect_success_total 6187
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 6262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 385
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6185
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 159035978 (151.67 MB)
telemt_user_octets_to_client{user="hello"} 1746759430 (1.63 GB)
telemt_user_msgs_from_client{user="hello"} 98054
telemt_user_msgs_to_client{user="hello"} 301218
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 17828.0 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8003
telemt_connections_bad_total 83
telemt_handshake_timeouts_total 39
telemt_upstream_connect_attempt_total 7650
telemt_upstream_connect_success_total 7634
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 7650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 472
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7632
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 885857360 (844.82 MB)
telemt_user_octets_to_client{user="hello"} 3012945451 (2.81 GB)
telemt_user_msgs_from_client{user="hello"} 383249
telemt_user_msgs_to_client{user="hello"} 662027
telemt_user_unique_ips_current{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 17828.3 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10878
telemt_connections_bad_total 3323
telemt_handshake_timeouts_total 19
telemt_upstream_connect_attempt_total 7374
telemt_upstream_connect_success_total 7373
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7371
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 188404968 (179.68 MB)
telemt_user_octets_to_client{user="hello"} 6668399177 (6.21 GB)
telemt_user_msgs_from_client{user="hello"} 203483
telemt_user_msgs_to_client{user="hello"} 915221
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 5
```