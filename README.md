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

# Server Metrics 2026-03-09 14:31:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 54709.6 (15h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95934
telemt_connections_bad_total 1479
telemt_handshake_timeouts_total 940
telemt_upstream_connect_attempt_total 89261
telemt_upstream_connect_success_total 89223
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 89261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 82320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 89217
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 2268279771 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 44434095083 (41.38 GB)
telemt_user_msgs_from_client{user="hello"} 2139585
telemt_user_msgs_to_client{user="hello"} 2979867
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 54708.4 (15h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23078
telemt_connections_bad_total 207
telemt_handshake_timeouts_total 288
telemt_upstream_connect_attempt_total 21778
telemt_upstream_connect_success_total 21761
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 21778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1476
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21755
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 800833446 (763.73 MB)
telemt_user_octets_to_client{user="hello"} 12287551527 (11.44 GB)
telemt_user_msgs_from_client{user="hello"} 668072
telemt_user_msgs_to_client{user="hello"} 3304053
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 54709.2 (15h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28577
telemt_connections_bad_total 189
telemt_handshake_timeouts_total 1490
telemt_upstream_connect_attempt_total 20549
telemt_upstream_connect_success_total 20549
telemt_upstream_connect_attempts_per_request{bucket="1"} 20549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2011
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20543
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 4322206495 (4.03 GB)
telemt_user_octets_to_client{user="hello"} 10408209211 (9.69 GB)
telemt_user_msgs_from_client{user="hello"} 1791026
telemt_user_msgs_to_client{user="hello"} 1527386
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 54703.5 (15h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30020
telemt_connections_bad_total 139
telemt_handshake_timeouts_total 617
telemt_upstream_connect_attempt_total 27698
telemt_upstream_connect_success_total 27629
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 27698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3290
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27623
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 1774084707 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 19984458208 (18.61 GB)
telemt_user_msgs_from_client{user="hello"} 1009726
telemt_user_msgs_to_client{user="hello"} 4810209
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 54709.0 (15h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56278
telemt_connections_bad_total 13334
telemt_handshake_timeouts_total 1431
telemt_upstream_connect_attempt_total 38781
telemt_upstream_connect_success_total 38779
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 38781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6045
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 38773
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 692650271 (660.56 MB)
telemt_user_octets_to_client{user="hello"} 39082087459 (36.40 GB)
telemt_user_msgs_from_client{user="hello"} 885309
telemt_user_msgs_to_client{user="hello"} 4798877
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 26
```