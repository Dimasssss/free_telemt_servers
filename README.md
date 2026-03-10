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

# Server Metrics 2026-03-10 11:45:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 131137.9 (36h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 286543
telemt_connections_bad_total 3462
telemt_handshake_timeouts_total 3053
telemt_upstream_connect_attempt_total 267907
telemt_upstream_connect_success_total 267759
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 267907
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 247412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20261
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 267747
telemt_user_connections_current{user="hello"} 269
telemt_user_octets_from_client{user="hello"} 6402277379 (5.96 GB)
telemt_user_octets_to_client{user="hello"} 168921103164 (157.32 GB)
telemt_user_msgs_from_client{user="hello"} 6457041
telemt_user_msgs_to_client{user="hello"} 10377121
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 131136.7 (36h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87491
telemt_connections_bad_total 3270
telemt_handshake_timeouts_total 1238
telemt_upstream_connect_attempt_total 78431
telemt_upstream_connect_success_total 78387
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 78431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7375
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 78373
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 2752126091 (2.56 GB)
telemt_user_octets_to_client{user="hello"} 34369830992 (32.01 GB)
telemt_user_msgs_from_client{user="hello"} 2153040
telemt_user_msgs_to_client{user="hello"} 9899122
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 131136.9 (36h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124024
telemt_connections_bad_total 1199
telemt_handshake_timeouts_total 6261
telemt_upstream_connect_attempt_total 90231
telemt_upstream_connect_success_total 90229
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 90231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10392
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 90217
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 6468357326 (6.02 GB)
telemt_user_octets_to_client{user="hello"} 65045321568 (60.58 GB)
telemt_user_msgs_from_client{user="hello"} 4265630
telemt_user_msgs_to_client{user="hello"} 10747465
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 131131.7 (36h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128746
telemt_connections_bad_total 1036
telemt_handshake_timeouts_total 2619
telemt_upstream_connect_attempt_total 118637
telemt_upstream_connect_success_total 118384
telemt_upstream_connect_fail_total 253
telemt_upstream_connect_attempts_per_request{bucket="1"} 118637
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13018
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 71
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 288
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 253
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 118372
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 3154436424 (2.94 GB)
telemt_user_octets_to_client{user="hello"} 82442318073 (76.78 GB)
telemt_user_msgs_from_client{user="hello"} 2960489
telemt_user_msgs_to_client{user="hello"} 18932213
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 131137.2 (36h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192462
telemt_connections_bad_total 28533
telemt_handshake_timeouts_total 5045
telemt_upstream_connect_attempt_total 150729
telemt_upstream_connect_success_total 149768
telemt_upstream_connect_fail_total 961
telemt_upstream_connect_attempts_per_request{bucket="1"} 150729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 129560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19998
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 961
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 149754
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 3354147965 (3.12 GB)
telemt_user_octets_to_client{user="hello"} 111804109502 (104.13 GB)
telemt_user_msgs_from_client{user="hello"} 3472875
telemt_user_msgs_to_client{user="hello"} 15229211
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 36
```