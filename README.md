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

# Server Metrics 2026-03-09 17:25:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 65133.6 (18h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121552
telemt_connections_bad_total 1662
telemt_handshake_timeouts_total 1020
telemt_upstream_connect_attempt_total 113879
telemt_upstream_connect_success_total 113838
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 113879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8773
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 113832
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 3024127763 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 62173135565 (57.90 GB)
telemt_user_msgs_from_client{user="hello"} 2831973
telemt_user_msgs_to_client{user="hello"} 3999173
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 65132.5 (18h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33520
telemt_connections_bad_total 232
telemt_handshake_timeouts_total 373
telemt_upstream_connect_attempt_total 31603
telemt_upstream_connect_success_total 31585
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 31603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2797
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 259
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31579
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 1017441933 (970.31 MB)
telemt_user_octets_to_client{user="hello"} 16478494604 (15.35 GB)
telemt_user_msgs_from_client{user="hello"} 883019
telemt_user_msgs_to_client{user="hello"} 4618048
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 65133.1 (18h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42716
telemt_connections_bad_total 658
telemt_handshake_timeouts_total 1948
telemt_upstream_connect_attempt_total 32930
telemt_upstream_connect_success_total 32930
telemt_upstream_connect_attempts_per_request{bucket="1"} 32930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3591
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32922
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 4497266683 (4.19 GB)
telemt_user_octets_to_client{user="hello"} 20595986380 (19.18 GB)
telemt_user_msgs_from_client{user="hello"} 2044475
telemt_user_msgs_to_client{user="hello"} 2775687
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 65127.8 (18h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48422
telemt_connections_bad_total 199
telemt_handshake_timeouts_total 899
telemt_upstream_connect_attempt_total 44115
telemt_upstream_connect_success_total 44009
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 44115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6081
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44001
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 2001589126 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 32840715824 (30.59 GB)
telemt_user_msgs_from_client{user="hello"} 1351585
telemt_user_msgs_to_client{user="hello"} 8281666
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 65133.3 (18h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78221
telemt_connections_bad_total 15636
telemt_handshake_timeouts_total 2026
telemt_upstream_connect_attempt_total 57002
telemt_upstream_connect_success_total 57000
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 57002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8717
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 56992
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 946638039 (902.78 MB)
telemt_user_octets_to_client{user="hello"} 56794182064 (52.89 GB)
telemt_user_msgs_from_client{user="hello"} 1312087
telemt_user_msgs_to_client{user="hello"} 7105415
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 18
```