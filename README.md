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

# Server Metrics 2026-03-06 15:30:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 18524.1 (5h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43971
telemt_connections_bad_total 3096
telemt_handshake_timeouts_total 173
telemt_upstream_connect_attempt_total 37302
telemt_upstream_connect_success_total 37292
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 37302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1998
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 37290
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 2048129697 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 23830887727 (22.19 GB)
telemt_user_msgs_from_client{user="hello"} 1352502
telemt_user_msgs_to_client{user="hello"} 3775013
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 18523.3 (5h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8197
telemt_connections_bad_total 167
telemt_handshake_timeouts_total 94
telemt_upstream_connect_attempt_total 7719
telemt_upstream_connect_success_total 7700
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 7718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 448
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7698
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 88857386 (84.74 MB)
telemt_user_octets_to_client{user="hello"} 4709818614 (4.39 GB)
telemt_user_msgs_from_client{user="hello"} 162568
telemt_user_msgs_to_client{user="hello"} 1472948
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 18522.6 (5h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6872
telemt_connections_bad_total 66
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 6663
telemt_upstream_connect_success_total 6662
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 364
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6660
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 99526494 (94.92 MB)
telemt_user_octets_to_client{user="hello"} 4174252951 (3.89 GB)
telemt_user_msgs_from_client{user="hello"} 147893
telemt_user_msgs_to_client{user="hello"} 978159
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 18521.8 (5h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9909
telemt_connections_bad_total 112
telemt_handshake_timeouts_total 50
telemt_upstream_connect_attempt_total 9161
telemt_upstream_connect_success_total 9131
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 9161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 522
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9129
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 137650094 (131.27 MB)
telemt_user_octets_to_client{user="hello"} 3114389483 (2.90 GB)
telemt_user_msgs_from_client{user="hello"} 164343
telemt_user_msgs_to_client{user="hello"} 802960
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 18523.1 (5h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13793
telemt_connections_bad_total 4856
telemt_handshake_timeouts_total 540
telemt_upstream_connect_attempt_total 8177
telemt_upstream_connect_success_total 8177
telemt_upstream_connect_attempts_per_request{bucket="1"} 8177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1066
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8175
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 213264470 (203.38 MB)
telemt_user_octets_to_client{user="hello"} 19521176692 (18.18 GB)
telemt_user_msgs_from_client{user="hello"} 341755
telemt_user_msgs_to_client{user="hello"} 3492792
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 7
```