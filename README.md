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

# Server Metrics 2026-03-08 09:46:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 9476.8 (2h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20079
telemt_connections_bad_total 2558
telemt_handshake_timeouts_total 128
telemt_upstream_connect_attempt_total 16649
telemt_upstream_connect_success_total 16636
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 16649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 945
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16634
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 528181478 (503.71 MB)
telemt_user_octets_to_client{user="hello"} 10500282092 (9.78 GB)
telemt_user_msgs_from_client{user="hello"} 457824
telemt_user_msgs_to_client{user="hello"} 556532
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 9476.0 (2h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4328
telemt_connections_bad_total 64
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 4106
telemt_upstream_connect_success_total 4106
telemt_upstream_connect_attempts_per_request{bucket="1"} 4106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 239
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4104
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 52348333 (49.92 MB)
telemt_user_octets_to_client{user="hello"} 2870387181 (2.67 GB)
telemt_user_msgs_from_client{user="hello"} 99912
telemt_user_msgs_to_client{user="hello"} 745740
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 9475.8 (2h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3560
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 3478
telemt_upstream_connect_success_total 3478
telemt_upstream_connect_attempts_per_request{bucket="1"} 3478
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 282
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3476
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 34179841 (32.60 MB)
telemt_user_octets_to_client{user="hello"} 1156249289 (1.08 GB)
telemt_user_msgs_from_client{user="hello"} 37150
telemt_user_msgs_to_client{user="hello"} 183478
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 9475.7 (2h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4048
telemt_connections_bad_total 40
telemt_handshake_timeouts_total 26
telemt_upstream_connect_attempt_total 3863
telemt_upstream_connect_success_total 3857
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 3863
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3855
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 96962397 (92.47 MB)
telemt_user_octets_to_client{user="hello"} 1639826519 (1.53 GB)
telemt_user_msgs_from_client{user="hello"} 74892
telemt_user_msgs_to_client{user="hello"} 382346
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 9475.9 (2h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5819
telemt_connections_bad_total 1797
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 3963
telemt_upstream_connect_success_total 3963
telemt_upstream_connect_attempts_per_request{bucket="1"} 3963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 707
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3961
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 50403761 (48.07 MB)
telemt_user_octets_to_client{user="hello"} 3386855859 (3.15 GB)
telemt_user_msgs_from_client{user="hello"} 92788
telemt_user_msgs_to_client{user="hello"} 403701
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 5
```