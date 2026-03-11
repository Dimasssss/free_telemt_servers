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

# Server Metrics 2026-03-11 23:35:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 6636.6 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10907
telemt_connections_bad_total 131
telemt_handshake_timeouts_total 72
telemt_upstream_connect_attempt_total 10438
telemt_upstream_connect_success_total 10434
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 10438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9207
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10432
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 151508145 (144.49 MB)
telemt_user_octets_to_client{user="hello"} 5272218199 (4.91 GB)
telemt_user_msgs_from_client{user="hello"} 259318
telemt_user_msgs_to_client{user="hello"} 685010
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 6624.9 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4582
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 19
telemt_upstream_connect_attempt_total 4402
telemt_upstream_connect_success_total 4402
telemt_upstream_connect_attempts_per_request{bucket="1"} 4402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 572
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4400
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 20577713 (19.62 MB)
telemt_user_octets_to_client{user="hello"} 527452620 (503.02 MB)
telemt_user_msgs_from_client{user="hello"} 49172
telemt_user_msgs_to_client{user="hello"} 234452
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 6598.4 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8396
telemt_connections_bad_total 255
telemt_handshake_timeouts_total 731
telemt_upstream_connect_attempt_total 6607
telemt_upstream_connect_success_total 6607
telemt_upstream_connect_attempts_per_request{bucket="1"} 6607
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 863
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6605
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 45390611 (43.29 MB)
telemt_user_octets_to_client{user="hello"} 4710563291 (4.39 GB)
telemt_user_msgs_from_client{user="hello"} 140386
telemt_user_msgs_to_client{user="hello"} 1137537
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 6623.7 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6240
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 58
telemt_upstream_connect_attempt_total 5983
telemt_upstream_connect_success_total 5976
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 5983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 741
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5974
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 46323918 (44.18 MB)
telemt_user_octets_to_client{user="hello"} 2349050727 (2.19 GB)
telemt_user_msgs_from_client{user="hello"} 92512
telemt_user_msgs_to_client{user="hello"} 888763
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 6624.6 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6344
telemt_connections_bad_total 58
telemt_handshake_timeouts_total 99
telemt_upstream_connect_attempt_total 5477
telemt_upstream_connect_success_total 5477
telemt_upstream_connect_attempts_per_request{bucket="1"} 5477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 908
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5475
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 89966217 (85.80 MB)
telemt_user_octets_to_client{user="hello"} 11776495579 (10.97 GB)
telemt_user_msgs_from_client{user="hello"} 168334
telemt_user_msgs_to_client{user="hello"} 895298
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 6
```