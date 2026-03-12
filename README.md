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

# Server Metrics 2026-03-12 03:38:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 21226.5 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43508
telemt_connections_bad_total 1933
telemt_handshake_timeouts_total 336
telemt_upstream_connect_attempt_total 39277
telemt_upstream_connect_success_total 39267
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 39277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4775
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 39263
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 360957703 (344.24 MB)
telemt_user_octets_to_client{user="hello"} 11463806377 (10.68 GB)
telemt_user_msgs_from_client{user="hello"} 608427
telemt_user_msgs_to_client{user="hello"} 1445430
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 21214.7 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17372
telemt_connections_bad_total 108
telemt_handshake_timeouts_total 76
telemt_upstream_connect_attempt_total 16591
telemt_upstream_connect_success_total 16591
telemt_upstream_connect_attempts_per_request{bucket="1"} 16591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1912
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16587
telemt_user_connections_current{user="hello"} 64
telemt_user_octets_from_client{user="hello"} 146259283 (139.48 MB)
telemt_user_octets_to_client{user="hello"} 9303549500 (8.66 GB)
telemt_user_msgs_from_client{user="hello"} 317420
telemt_user_msgs_to_client{user="hello"} 2559177
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 21188.5 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30173
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 917
telemt_upstream_connect_attempt_total 26589
telemt_upstream_connect_success_total 26589
telemt_upstream_connect_attempts_per_request{bucket="1"} 26589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4381
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26585
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 5248072575 (4.89 GB)
telemt_user_octets_to_client{user="hello"} 16802954850 (15.65 GB)
telemt_user_msgs_from_client{user="hello"} 2305624
telemt_user_msgs_to_client{user="hello"} 3387280
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 21213.8 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31773
telemt_connections_bad_total 8600
telemt_handshake_timeouts_total 720
telemt_upstream_connect_attempt_total 21483
telemt_upstream_connect_success_total 19785
telemt_upstream_connect_fail_total 1698
telemt_upstream_connect_attempts_per_request{bucket="1"} 21483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2961
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1698
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19781
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 180343308 (171.99 MB)
telemt_user_octets_to_client{user="hello"} 15011647999 (13.98 GB)
telemt_user_msgs_from_client{user="hello"} 365158
telemt_user_msgs_to_client{user="hello"} 6192408
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 21214.5 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24574
telemt_connections_bad_total 144
telemt_handshake_timeouts_total 154
telemt_upstream_connect_attempt_total 22782
telemt_upstream_connect_success_total 22781
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 22782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3684
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22779
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 543046966 (517.89 MB)
telemt_user_octets_to_client{user="hello"} 30113590487 (28.05 GB)
telemt_user_msgs_from_client{user="hello"} 735113
telemt_user_msgs_to_client{user="hello"} 3787132
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 15
```