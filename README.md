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

# Server Metrics 2026-03-11 22:38:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 3244.4 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5093
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 53
telemt_upstream_connect_attempt_total 4917
telemt_upstream_connect_success_total 4916
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 559
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4914
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 47313848 (45.12 MB)
telemt_user_octets_to_client{user="hello"} 2397580126 (2.23 GB)
telemt_user_msgs_from_client{user="hello"} 109559
telemt_user_msgs_to_client{user="hello"} 360395
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 3232.5 (0h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2086
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 1991
telemt_upstream_connect_success_total 1991
telemt_upstream_connect_attempts_per_request{bucket="1"} 1991
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1828
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 163
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1989
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 11108117 (10.59 MB)
telemt_user_octets_to_client{user="hello"} 247557451 (236.09 MB)
telemt_user_msgs_from_client{user="hello"} 26881
telemt_user_msgs_to_client{user="hello"} 109899
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 3206.0 (0h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4804
telemt_connections_bad_total 244
telemt_handshake_timeouts_total 80
telemt_upstream_connect_attempt_total 3818
telemt_upstream_connect_success_total 3818
telemt_upstream_connect_attempts_per_request{bucket="1"} 3818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 530
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3816
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 22977993 (21.91 MB)
telemt_user_octets_to_client{user="hello"} 2207926351 (2.06 GB)
telemt_user_msgs_from_client{user="hello"} 72944
telemt_user_msgs_to_client{user="hello"} 595611
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 3231.3 (0h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3311
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 52
telemt_upstream_connect_attempt_total 3149
telemt_upstream_connect_success_total 3146
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 470
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3144
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 28654728 (27.33 MB)
telemt_user_octets_to_client{user="hello"} 967052475 (922.25 MB)
telemt_user_msgs_from_client{user="hello"} 47369
telemt_user_msgs_to_client{user="hello"} 376349
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 3232.7 (0h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3372
telemt_connections_bad_total 615
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 2703
telemt_upstream_connect_success_total 2703
telemt_upstream_connect_attempts_per_request{bucket="1"} 2703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 237
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2701
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 28668563 (27.34 MB)
telemt_user_octets_to_client{user="hello"} 1171005618 (1.09 GB)
telemt_user_msgs_from_client{user="hello"} 36395
telemt_user_msgs_to_client{user="hello"} 216958
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 3232.3 (0h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3564
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 86
telemt_upstream_connect_attempt_total 2944
telemt_upstream_connect_success_total 2944
telemt_upstream_connect_attempts_per_request{bucket="1"} 2944
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 491
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2942
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 63836276 (60.88 MB)
telemt_user_octets_to_client{user="hello"} 10150875028 (9.45 GB)
telemt_user_msgs_from_client{user="hello"} 109324
telemt_user_msgs_to_client{user="hello"} 624709
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 4
```