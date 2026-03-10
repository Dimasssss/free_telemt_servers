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

# Server Metrics 2026-03-10 08:00:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 117632.1 (32h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231747
telemt_connections_bad_total 2460
telemt_handshake_timeouts_total 2043
telemt_upstream_connect_attempt_total 218108
telemt_upstream_connect_success_total 218042
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 218108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 201047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16929
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 218030
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 5592461176 (5.21 GB)
telemt_user_octets_to_client{user="hello"} 131091601280 (122.09 GB)
telemt_user_msgs_from_client{user="hello"} 5369688
telemt_user_msgs_to_client{user="hello"} 8230510
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 117630.7 (32h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69605
telemt_connections_bad_total 3219
telemt_handshake_timeouts_total 1000
telemt_upstream_connect_attempt_total 61727
telemt_upstream_connect_success_total 61686
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 61727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5895
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 372
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 61674
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 2252860197 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 27199805385 (25.33 GB)
telemt_user_msgs_from_client{user="hello"} 1751624
telemt_user_msgs_to_client{user="hello"} 7920413
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 117631.4 (32h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102263
telemt_connections_bad_total 1122
telemt_handshake_timeouts_total 4945
telemt_upstream_connect_attempt_total 70835
telemt_upstream_connect_success_total 70833
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 70835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8189
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 70821
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 6244810010 (5.82 GB)
telemt_user_octets_to_client{user="hello"} 59743631810 (55.64 GB)
telemt_user_msgs_from_client{user="hello"} 3884147
telemt_user_msgs_to_client{user="hello"} 9445136
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 117625.7 (32h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99722
telemt_connections_bad_total 900
telemt_handshake_timeouts_total 1215
telemt_upstream_connect_attempt_total 92567
telemt_upstream_connect_success_total 92370
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 92567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10668
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 53
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 92358
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 2555353179 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 66932848463 (62.34 GB)
telemt_user_msgs_from_client{user="hello"} 2370036
telemt_user_msgs_to_client{user="hello"} 15353743
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 117631.2 (32h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156835
telemt_connections_bad_total 25602
telemt_handshake_timeouts_total 4067
telemt_upstream_connect_attempt_total 120548
telemt_upstream_connect_success_total 119754
telemt_upstream_connect_fail_total 794
telemt_upstream_connect_attempts_per_request{bucket="1"} 120548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 102931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 794
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 119742
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 1862331605 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 102814287924 (95.75 GB)
telemt_user_msgs_from_client{user="hello"} 2603635
telemt_user_msgs_to_client{user="hello"} 13844188
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 17
```