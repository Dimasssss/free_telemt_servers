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

# Server Metrics 2026-03-08 16:22:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 33237.1 (9h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80508
telemt_connections_bad_total 5039
telemt_handshake_timeouts_total 1071
telemt_upstream_connect_attempt_total 71651
telemt_upstream_connect_success_total 71628
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 71651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4211
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 71624
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 1774461830 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 38487106146 (35.84 GB)
telemt_user_msgs_from_client{user="hello"} 1670086
telemt_user_msgs_to_client{user="hello"} 2327769
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 33236.1 (9h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17205
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 122
telemt_upstream_connect_attempt_total 16636
telemt_upstream_connect_success_total 16634
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 16636
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1185
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16630
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 620322437 (591.59 MB)
telemt_user_octets_to_client{user="hello"} 16937662663 (15.77 GB)
telemt_user_msgs_from_client{user="hello"} 670824
telemt_user_msgs_to_client{user="hello"} 4577946
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 33235.9 (9h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10668
telemt_connections_bad_total 150
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 10033
telemt_upstream_connect_success_total 9957
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 10033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9196
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 689
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9953
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 221760066 (211.49 MB)
telemt_user_octets_to_client{user="hello"} 3467050049 (3.23 GB)
telemt_user_msgs_from_client{user="hello"} 172414
telemt_user_msgs_to_client{user="hello"} 604635
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 33235.7 (9h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14259
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 54
telemt_upstream_connect_attempt_total 13587
telemt_upstream_connect_success_total 13557
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 13587
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 982
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13553
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 977684896 (932.39 MB)
telemt_user_octets_to_client{user="hello"} 4969376367 (4.63 GB)
telemt_user_msgs_from_client{user="hello"} 490061
telemt_user_msgs_to_client{user="hello"} 1122607
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 33236.0 (9h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18791
telemt_connections_bad_total 6102
telemt_handshake_timeouts_total 144
telemt_upstream_connect_attempt_total 12268
telemt_upstream_connect_success_total 12264
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 12268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1941
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12260
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 245815018 (234.43 MB)
telemt_user_octets_to_client{user="hello"} 10657914483 (9.93 GB)
telemt_user_msgs_from_client{user="hello"} 315387
telemt_user_msgs_to_client{user="hello"} 1378228
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```