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

# Server Metrics 2026-03-09 20:55:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 77710.5 (21h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151386
telemt_connections_bad_total 2133
telemt_handshake_timeouts_total 1677
telemt_upstream_connect_attempt_total 141413
telemt_upstream_connect_success_total 141367
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 141413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11240
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 141359
telemt_user_connections_current{user="hello"} 288
telemt_user_octets_from_client{user="hello"} 4560477083 (4.25 GB)
telemt_user_octets_to_client{user="hello"} 83083237450 (77.38 GB)
telemt_user_msgs_from_client{user="hello"} 3888585
telemt_user_msgs_to_client{user="hello"} 5281400
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 77709.5 (21h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44754
telemt_connections_bad_total 242
telemt_handshake_timeouts_total 555
telemt_upstream_connect_attempt_total 41991
telemt_upstream_connect_success_total 41950
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 41991
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37755
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3838
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 41942
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 2070463331 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 21169964996 (19.72 GB)
telemt_user_msgs_from_client{user="hello"} 1435548
telemt_user_msgs_to_client{user="hello"} 6052952
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 77710.0 (21h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56451
telemt_connections_bad_total 742
telemt_handshake_timeouts_total 3158
telemt_upstream_connect_attempt_total 44254
telemt_upstream_connect_success_total 44252
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 44254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4977
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44244
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 4818327263 (4.49 GB)
telemt_user_octets_to_client{user="hello"} 35233005538 (32.81 GB)
telemt_user_msgs_from_client{user="hello"} 2671205
telemt_user_msgs_to_client{user="hello"} 5287114
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 77704.7 (21h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61770
telemt_connections_bad_total 277
telemt_handshake_timeouts_total 989
telemt_upstream_connect_attempt_total 56780
telemt_upstream_connect_success_total 56632
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 56780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7183
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 56624
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 2196676338 (2.05 GB)
telemt_user_octets_to_client{user="hello"} 43564867836 (40.57 GB)
telemt_user_msgs_from_client{user="hello"} 1673064
telemt_user_msgs_to_client{user="hello"} 10487630
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 77710.2 (21h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100668
telemt_connections_bad_total 17907
telemt_handshake_timeouts_total 2542
telemt_upstream_connect_attempt_total 75897
telemt_upstream_connect_success_total 75889
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 75897
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11351
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 75881
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 1301228079 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 69436109824 (64.67 GB)
telemt_user_msgs_from_client{user="hello"} 1754365
telemt_user_msgs_to_client{user="hello"} 9259148
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 9
```