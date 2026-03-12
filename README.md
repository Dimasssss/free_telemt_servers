# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

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

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-12 03:33:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 20902.3 (5h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42529
telemt_connections_bad_total 1933
telemt_handshake_timeouts_total 332
telemt_upstream_connect_attempt_total 38331
telemt_upstream_connect_success_total 38321
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 38331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4579
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 38317
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 356957552 (340.42 MB)
telemt_user_octets_to_client{user="hello"} 11414888837 (10.63 GB)
telemt_user_msgs_from_client{user="hello"} 600252
telemt_user_msgs_to_client{user="hello"} 1429779
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 20890.5 (5h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17104
telemt_connections_bad_total 108
telemt_handshake_timeouts_total 73
telemt_upstream_connect_attempt_total 16342
telemt_upstream_connect_success_total 16342
telemt_upstream_connect_attempts_per_request{bucket="1"} 16342
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1896
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16338
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 144078803 (137.40 MB)
telemt_user_octets_to_client{user="hello"} 9232039622 (8.60 GB)
telemt_user_msgs_from_client{user="hello"} 312235
telemt_user_msgs_to_client{user="hello"} 2528057
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 20864.2 (5h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29712
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 916
telemt_upstream_connect_attempt_total 26142
telemt_upstream_connect_success_total 26142
telemt_upstream_connect_attempts_per_request{bucket="1"} 26142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4304
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26138
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 5244574374 (4.88 GB)
telemt_user_octets_to_client{user="hello"} 16588558196 (15.45 GB)
telemt_user_msgs_from_client{user="hello"} 2295127
telemt_user_msgs_to_client{user="hello"} 3329418
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 20889.5 (5h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31331
telemt_connections_bad_total 8599
telemt_handshake_timeouts_total 718
telemt_upstream_connect_attempt_total 21081
telemt_upstream_connect_success_total 19383
telemt_upstream_connect_fail_total 1698
telemt_upstream_connect_attempts_per_request{bucket="1"} 21081
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2894
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1698
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19379
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 177431643 (169.21 MB)
telemt_user_octets_to_client{user="hello"} 14830251100 (13.81 GB)
telemt_user_msgs_from_client{user="hello"} 358526
telemt_user_msgs_to_client{user="hello"} 6126185
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 20890.4 (5h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23958
telemt_connections_bad_total 144
telemt_handshake_timeouts_total 152
telemt_upstream_connect_attempt_total 22198
telemt_upstream_connect_success_total 22197
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 22198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3559
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22195
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 540307838 (515.28 MB)
telemt_user_octets_to_client{user="hello"} 30079886911 (28.01 GB)
telemt_user_msgs_from_client{user="hello"} 728155
telemt_user_msgs_to_client{user="hello"} 3776031
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 14
```