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

# Server Metrics 2026-03-10 17:44:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 11875.2 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48101
telemt_connections_bad_total 772
telemt_handshake_timeouts_total 1382
telemt_upstream_connect_attempt_total 43341
telemt_upstream_connect_success_total 43331
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 43341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39720
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3604
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 43329
telemt_user_connections_current{user="hello"} 302
telemt_user_octets_from_client{user="hello"} 1348000461 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 31781007189 (29.60 GB)
telemt_user_msgs_from_client{user="hello"} 1225537
telemt_user_msgs_to_client{user="hello"} 2443986
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 11874.6 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17527
telemt_connections_bad_total 142
telemt_handshake_timeouts_total 321
telemt_upstream_connect_attempt_total 15963
telemt_upstream_connect_success_total 15960
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 15963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15958
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 468295792 (446.60 MB)
telemt_user_octets_to_client{user="hello"} 8471320912 (7.89 GB)
telemt_user_msgs_from_client{user="hello"} 459729
telemt_user_msgs_to_client{user="hello"} 2645642
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 11874.3 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27021
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 2406
telemt_upstream_connect_attempt_total 22943
telemt_upstream_connect_success_total 22943
telemt_upstream_connect_attempts_per_request{bucket="1"} 22943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2365
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22941
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 277313745 (264.47 MB)
telemt_user_octets_to_client{user="hello"} 15140542898 (14.10 GB)
telemt_user_msgs_from_client{user="hello"} 461819
telemt_user_msgs_to_client{user="hello"} 2760835
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 11873.1 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26527
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 255
telemt_upstream_connect_attempt_total 25302
telemt_upstream_connect_success_total 25232
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 25302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2969
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25230
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 357639119 (341.07 MB)
telemt_user_octets_to_client{user="hello"} 24054015714 (22.40 GB)
telemt_user_msgs_from_client{user="hello"} 526217
telemt_user_msgs_to_client{user="hello"} 4228760
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 11874.6 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36514
telemt_connections_bad_total 2595
telemt_handshake_timeouts_total 636
telemt_upstream_connect_attempt_total 31826
telemt_upstream_connect_success_total 31589
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 31826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3791
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31587
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 1293939604 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 20516783768 (19.11 GB)
telemt_user_msgs_from_client{user="hello"} 953667
telemt_user_msgs_to_client{user="hello"} 2957684
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 21
```