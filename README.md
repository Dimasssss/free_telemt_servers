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

# Server Metrics 2026-03-09 16:29:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 61751.1 (17h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113390
telemt_connections_bad_total 1656
telemt_handshake_timeouts_total 974
telemt_upstream_connect_attempt_total 106101
telemt_upstream_connect_success_total 106062
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 106101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 97944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8059
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 106056
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 2827374277 (2.63 GB)
telemt_user_octets_to_client{user="hello"} 55704957134 (51.88 GB)
telemt_user_msgs_from_client{user="hello"} 2620492
telemt_user_msgs_to_client{user="hello"} 3700428
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 61750.0 (17h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30017
telemt_connections_bad_total 220
telemt_handshake_timeouts_total 350
telemt_upstream_connect_attempt_total 28302
telemt_upstream_connect_success_total 28284
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 28302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25712
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2351
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28278
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 987856218 (942.09 MB)
telemt_user_octets_to_client{user="hello"} 15615786614 (14.54 GB)
telemt_user_msgs_from_client{user="hello"} 830815
telemt_user_msgs_to_client{user="hello"} 4305608
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 61751.1 (17h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37485
telemt_connections_bad_total 655
telemt_handshake_timeouts_total 1654
telemt_upstream_connect_attempt_total 28300
telemt_upstream_connect_success_total 28300
telemt_upstream_connect_attempts_per_request{bucket="1"} 28300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2979
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28294
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 4413420306 (4.11 GB)
telemt_user_octets_to_client{user="hello"} 17655548606 (16.44 GB)
telemt_user_msgs_from_client{user="hello"} 1945249
telemt_user_msgs_to_client{user="hello"} 2333808
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 61745.4 (17h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42944
telemt_connections_bad_total 198
telemt_handshake_timeouts_total 873
telemt_upstream_connect_attempt_total 39438
telemt_upstream_connect_success_total 39342
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 39438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5559
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 39334
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 1945987903 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 30954165542 (28.83 GB)
telemt_user_msgs_from_client{user="hello"} 1264802
telemt_user_msgs_to_client{user="hello"} 7820028
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 61750.8 (17h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71228
telemt_connections_bad_total 15031
telemt_handshake_timeouts_total 1598
telemt_upstream_connect_attempt_total 51302
telemt_upstream_connect_success_total 51300
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 51302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7858
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51294
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 865632954 (825.53 MB)
telemt_user_octets_to_client{user="hello"} 54128718825 (50.41 GB)
telemt_user_msgs_from_client{user="hello"} 1192838
telemt_user_msgs_to_client{user="hello"} 6612652
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 12
```