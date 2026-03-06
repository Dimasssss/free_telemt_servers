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

# Server Metrics 2026-03-06 17:23:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 25301.4 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59281
telemt_connections_bad_total 3257
telemt_handshake_timeouts_total 247
telemt_upstream_connect_attempt_total 51899
telemt_upstream_connect_success_total 51887
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 51899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2928
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51883
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 2697993922 (2.51 GB)
telemt_user_octets_to_client{user="hello"} 34958729282 (32.56 GB)
telemt_user_msgs_from_client{user="hello"} 1844491
telemt_user_msgs_to_client{user="hello"} 5500165
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 25301.0 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11186
telemt_connections_bad_total 201
telemt_handshake_timeouts_total 101
telemt_upstream_connect_attempt_total 10632
telemt_upstream_connect_success_total 10613
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 10632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 653
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10609
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 144251958 (137.57 MB)
telemt_user_octets_to_client{user="hello"} 6011662328 (5.60 GB)
telemt_user_msgs_from_client{user="hello"} 230600
telemt_user_msgs_to_client{user="hello"} 1856453
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 25300.3 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9133
telemt_connections_bad_total 146
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 8798
telemt_upstream_connect_success_total 8796
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 528
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8794
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 127795713 (121.88 MB)
telemt_user_octets_to_client{user="hello"} 5247422731 (4.89 GB)
telemt_user_msgs_from_client{user="hello"} 198397
telemt_user_msgs_to_client{user="hello"} 1238932
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 25299.6 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12986
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 118
telemt_upstream_connect_attempt_total 12072
telemt_upstream_connect_success_total 12031
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 12072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 805
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12027
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 173508970 (165.47 MB)
telemt_user_octets_to_client{user="hello"} 5180257163 (4.82 GB)
telemt_user_msgs_from_client{user="hello"} 217345
telemt_user_msgs_to_client{user="hello"} 1225663
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 25300.9 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18168
telemt_connections_bad_total 6110
telemt_handshake_timeouts_total 573
telemt_upstream_connect_attempt_total 11159
telemt_upstream_connect_success_total 11159
telemt_upstream_connect_attempts_per_request{bucket="1"} 11159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1720
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11155
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 253336190 (241.60 MB)
telemt_user_octets_to_client{user="hello"} 23201828333 (21.61 GB)
telemt_user_msgs_from_client{user="hello"} 429324
telemt_user_msgs_to_client{user="hello"} 4206897
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 6
```