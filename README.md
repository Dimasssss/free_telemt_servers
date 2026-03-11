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

# Server Metrics 2026-03-11 16:35:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 1242.1 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6341
telemt_connections_bad_total 329
telemt_handshake_timeouts_total 43
telemt_upstream_connect_attempt_total 5591
telemt_upstream_connect_success_total 5590
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 423
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5588
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 53520981 (51.04 MB)
telemt_user_octets_to_client{user="hello"} 1598067492 (1.49 GB)
telemt_user_msgs_from_client{user="hello"} 80086
telemt_user_msgs_to_client{user="hello"} 156756
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 94133.3 (26h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129498
telemt_connections_bad_total 974
telemt_handshake_timeouts_total 3463
telemt_upstream_connect_attempt_total 119613
telemt_upstream_connect_success_total 119590
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 119613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 104226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14753
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 611
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 119580
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 6117258963 (5.70 GB)
telemt_user_octets_to_client{user="hello"} 73011811196 (68.00 GB)
telemt_user_msgs_from_client{user="hello"} 4184212
telemt_user_msgs_to_client{user="hello"} 21386600
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 94133.0 (26h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175437
telemt_connections_bad_total 1446
telemt_handshake_timeouts_total 7862
telemt_upstream_connect_attempt_total 156610
telemt_upstream_connect_success_total 156596
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 156610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 138883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17604
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 156586
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 12796436769 (11.92 GB)
telemt_user_octets_to_client{user="hello"} 135531687085 (126.22 GB)
telemt_user_msgs_from_client{user="hello"} 7017123
telemt_user_msgs_to_client{user="hello"} 30773028
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 94132.1 (26h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198626
telemt_connections_bad_total 10273
telemt_handshake_timeouts_total 3245
telemt_upstream_connect_attempt_total 177188
telemt_upstream_connect_success_total 176758
telemt_upstream_connect_fail_total 430
telemt_upstream_connect_attempts_per_request{bucket="1"} 177188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21904
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 98
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 484
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 430
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 176748
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 10455782361 (9.74 GB)
telemt_user_octets_to_client{user="hello"} 121731619158 (113.37 GB)
telemt_user_msgs_from_client{user="hello"} 6234390
telemt_user_msgs_to_client{user="hello"} 36383253
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 73102.6 (20h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 473
telemt_connections_bad_total 450
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 19
telemt_upstream_connect_success_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```