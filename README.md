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

# Server Metrics 2026-03-09 15:02:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 56546.8 (15h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100779
telemt_connections_bad_total 1650
telemt_handshake_timeouts_total 945
telemt_upstream_connect_attempt_total 93849
telemt_upstream_connect_success_total 93811
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 93849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 86562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7190
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 93805
telemt_user_connections_current{user="hello"} 279
telemt_user_octets_from_client{user="hello"} 2468165259 (2.30 GB)
telemt_user_octets_to_client{user="hello"} 48681131417 (45.34 GB)
telemt_user_msgs_from_client{user="hello"} 2290562
telemt_user_msgs_to_client{user="hello"} 3225817
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 56545.3 (15h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24963
telemt_connections_bad_total 208
telemt_handshake_timeouts_total 321
telemt_upstream_connect_attempt_total 23438
telemt_upstream_connect_success_total 23421
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 23438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1753
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23415
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 812995301 (775.33 MB)
telemt_user_octets_to_client{user="hello"} 13350699218 (12.43 GB)
telemt_user_msgs_from_client{user="hello"} 699488
telemt_user_msgs_to_client{user="hello"} 3634504
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 56546.3 (15h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31282
telemt_connections_bad_total 643
telemt_handshake_timeouts_total 1540
telemt_upstream_connect_attempt_total 22532
telemt_upstream_connect_success_total 22532
telemt_upstream_connect_attempts_per_request{bucket="1"} 22532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2225
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22526
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 4350297583 (4.05 GB)
telemt_user_octets_to_client{user="hello"} 13495751542 (12.57 GB)
telemt_user_msgs_from_client{user="hello"} 1844286
telemt_user_msgs_to_client{user="hello"} 1835105
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 56540.8 (15h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33657
telemt_connections_bad_total 186
telemt_handshake_timeouts_total 810
telemt_upstream_connect_attempt_total 30906
telemt_upstream_connect_success_total 30826
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 30906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3795
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30820
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 1832681604 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 23582143846 (21.96 GB)
telemt_user_msgs_from_client{user="hello"} 1086776
telemt_user_msgs_to_client{user="hello"} 5906167
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 56546.1 (15h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61115
telemt_connections_bad_total 13683
telemt_handshake_timeouts_total 1537
telemt_upstream_connect_attempt_total 43001
telemt_upstream_connect_success_total 42999
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 43001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6787
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42993
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 723610805 (690.09 MB)
telemt_user_octets_to_client{user="hello"} 41174534658 (38.35 GB)
telemt_user_msgs_from_client{user="hello"} 943796
telemt_user_msgs_to_client{user="hello"} 5083985
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 19
```