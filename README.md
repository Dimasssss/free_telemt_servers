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

# Server Metrics 2026-03-11 21:22:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 15710.2 (4h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52211
telemt_connections_bad_total 2581
telemt_handshake_timeouts_total 237
telemt_upstream_connect_attempt_total 47284
telemt_upstream_connect_success_total 47272
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 47284
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4569
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 47270
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 1490488274 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 27930846583 (26.01 GB)
telemt_user_msgs_from_client{user="hello"} 1301207
telemt_user_msgs_to_client{user="hello"} 2708506
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 15698.5 (4h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24186
telemt_connections_bad_total 42
telemt_handshake_timeouts_total 262
telemt_upstream_connect_attempt_total 22394
telemt_upstream_connect_success_total 22355
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 22394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2688
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22353
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 265067538 (252.79 MB)
telemt_user_octets_to_client{user="hello"} 11424364683 (10.64 GB)
telemt_user_msgs_from_client{user="hello"} 463261
telemt_user_msgs_to_client{user="hello"} 4698100
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 15718.4 (4h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29751
telemt_connections_bad_total 49
telemt_handshake_timeouts_total 254
telemt_upstream_connect_attempt_total 27893
telemt_upstream_connect_success_total 27891
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 27893
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2560
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27889
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 321841196 (306.93 MB)
telemt_user_octets_to_client{user="hello"} 10481521059 (9.76 GB)
telemt_user_msgs_from_client{user="hello"} 537161
telemt_user_msgs_to_client{user="hello"} 2642189
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 15713.9 (4h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31783
telemt_connections_bad_total 1803
telemt_handshake_timeouts_total 478
telemt_upstream_connect_attempt_total 28105
telemt_upstream_connect_success_total 28023
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 28105
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2722
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28021
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 724437057 (690.88 MB)
telemt_user_octets_to_client{user="hello"} 17820132724 (16.60 GB)
telemt_user_msgs_from_client{user="hello"} 667767
telemt_user_msgs_to_client{user="hello"} 5722616
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 15722.0 (4h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34859
telemt_connections_bad_total 3020
telemt_handshake_timeouts_total 183
telemt_upstream_connect_attempt_total 30643
telemt_upstream_connect_success_total 30640
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 30643
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3565
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30638
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 539304065 (514.32 MB)
telemt_user_octets_to_client{user="hello"} 11375323850 (10.59 GB)
telemt_user_msgs_from_client{user="hello"} 685209
telemt_user_msgs_to_client{user="hello"} 4135839
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 90328.4 (25h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3178
telemt_connections_bad_total 495
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 2597
telemt_upstream_connect_success_total 2597
telemt_upstream_connect_attempts_per_request{bucket="1"} 2597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 398
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2587
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 29131719 (27.78 MB)
telemt_user_octets_to_client{user="hello"} 2624110032 (2.44 GB)
telemt_user_msgs_from_client{user="hello"} 77859
telemt_user_msgs_to_client{user="hello"} 315583
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 8
```