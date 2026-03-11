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

# Server Metrics 2026-03-11 05:04:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 52691.1 (14h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133770
telemt_connections_bad_total 3386
telemt_handshake_timeouts_total 2835
telemt_upstream_connect_attempt_total 121473
telemt_upstream_connect_success_total 121429
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 121473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110775
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10599
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 121423
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 3066139968 (2.86 GB)
telemt_user_octets_to_client{user="hello"} 86700804460 (80.75 GB)
telemt_user_msgs_from_client{user="hello"} 3189576
telemt_user_msgs_to_client{user="hello"} 6027785
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 52690.5 (14h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54974
telemt_connections_bad_total 421
telemt_handshake_timeouts_total 2966
telemt_upstream_connect_attempt_total 48733
telemt_upstream_connect_success_total 48723
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 48733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 48717
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 4475337319 (4.17 GB)
telemt_user_octets_to_client{user="hello"} 45005969259 (41.92 GB)
telemt_user_msgs_from_client{user="hello"} 2626538
telemt_user_msgs_to_client{user="hello"} 10772521
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 52690.1 (14h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75812
telemt_connections_bad_total 688
telemt_handshake_timeouts_total 4317
telemt_upstream_connect_attempt_total 66489
telemt_upstream_connect_success_total 66486
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 66489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58938
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7496
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 66480
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 11779857201 (10.97 GB)
telemt_user_octets_to_client{user="hello"} 71199069251 (66.31 GB)
telemt_user_msgs_from_client{user="hello"} 5188856
telemt_user_msgs_to_client{user="hello"} 13382171
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 52689.1 (14h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78666
telemt_connections_bad_total 157
telemt_handshake_timeouts_total 580
telemt_upstream_connect_attempt_total 75314
telemt_upstream_connect_success_total 75150
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 75314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9758
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 200
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 75144
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 1826261633 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 48927898444 (45.57 GB)
telemt_user_msgs_from_client{user="hello"} 1730865
telemt_user_msgs_to_client{user="hello"} 10755259
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 52690.4 (14h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125005
telemt_connections_bad_total 11860
telemt_handshake_timeouts_total 1698
telemt_upstream_connect_attempt_total 106122
telemt_upstream_connect_success_total 105873
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 106122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 92488
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 105867
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 2392286465 (2.23 GB)
telemt_user_octets_to_client{user="hello"} 100738345033 (93.82 GB)
telemt_user_msgs_from_client{user="hello"} 2592399
telemt_user_msgs_to_client{user="hello"} 12958386
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 31659.7 (8h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129
telemt_connections_bad_total 120
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```