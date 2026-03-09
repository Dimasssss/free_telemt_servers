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

# Server Metrics 2026-03-09 02:52:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 12755.6 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10326
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 186
telemt_upstream_connect_attempt_total 9491
telemt_upstream_connect_success_total 9488
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 9491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 787
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9486
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 109583527 (104.51 MB)
telemt_user_octets_to_client{user="hello"} 8461993060 (7.88 GB)
telemt_user_msgs_from_client{user="hello"} 216792
telemt_user_msgs_to_client{user="hello"} 346745
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 12753.8 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 718
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 682
telemt_upstream_connect_success_total 682
telemt_upstream_connect_attempts_per_request{bucket="1"} 682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 680
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 8532913 (8.14 MB)
telemt_user_octets_to_client{user="hello"} 467560516 (445.90 MB)
telemt_user_msgs_from_client{user="hello"} 24097
telemt_user_msgs_to_client{user="hello"} 94825
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 12754.4 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 838
telemt_connections_bad_total 75
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 750
telemt_upstream_connect_success_total 750
telemt_upstream_connect_attempts_per_request{bucket="1"} 750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 748
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 314743874 (300.16 MB)
telemt_user_octets_to_client{user="hello"} 229024878 (218.42 MB)
telemt_user_msgs_from_client{user="hello"} 120275
telemt_user_msgs_to_client{user="hello"} 65907
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 12749.1 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1748
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 198
telemt_upstream_connect_attempt_total 1415
telemt_upstream_connect_success_total 1415
telemt_upstream_connect_attempts_per_request{bucket="1"} 1415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 348
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1413
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 11775726 (11.23 MB)
telemt_user_octets_to_client{user="hello"} 770409244 (734.72 MB)
telemt_user_msgs_from_client{user="hello"} 30290
telemt_user_msgs_to_client{user="hello"} 220007
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 12754.7 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3479
telemt_connections_bad_total 2323
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1127
telemt_upstream_connect_success_total 1127
telemt_upstream_connect_attempts_per_request{bucket="1"} 1127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 147
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1125
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 8992652 (8.58 MB)
telemt_user_octets_to_client{user="hello"} 1546538139 (1.44 GB)
telemt_user_msgs_from_client{user="hello"} 23830
telemt_user_msgs_to_client{user="hello"} 186119
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```