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

# Server Metrics 2026-03-11 04:28:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 50550.3 (14h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129276
telemt_connections_bad_total 3385
telemt_handshake_timeouts_total 2783
telemt_upstream_connect_attempt_total 117164
telemt_upstream_connect_success_total 117121
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 117164
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10202
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 117115
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 3021871132 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 84782540935 (78.96 GB)
telemt_user_msgs_from_client{user="hello"} 3105497
telemt_user_msgs_to_client{user="hello"} 5899164
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 50549.7 (14h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52791
telemt_connections_bad_total 412
telemt_handshake_timeouts_total 2943
telemt_upstream_connect_attempt_total 46654
telemt_upstream_connect_success_total 46644
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 46654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7029
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 46638
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 3572988179 (3.33 GB)
telemt_user_octets_to_client{user="hello"} 44415403120 (41.37 GB)
telemt_user_msgs_from_client{user="hello"} 2274900
telemt_user_msgs_to_client{user="hello"} 10590183
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 50549.4 (14h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73724
telemt_connections_bad_total 673
telemt_handshake_timeouts_total 4299
telemt_upstream_connect_attempt_total 64662
telemt_upstream_connect_success_total 64659
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 64662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7323
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 64653
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 11768696289 (10.96 GB)
telemt_user_octets_to_client{user="hello"} 70882205057 (66.01 GB)
telemt_user_msgs_from_client{user="hello"} 5168894
telemt_user_msgs_to_client{user="hello"} 13309029
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 50548.5 (14h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75736
telemt_connections_bad_total 155
telemt_handshake_timeouts_total 566
telemt_upstream_connect_attempt_total 72524
telemt_upstream_connect_success_total 72361
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 72524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9351
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 190
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 72355
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 1804734711 (1.68 GB)
telemt_user_octets_to_client{user="hello"} 47635992746 (44.36 GB)
telemt_user_msgs_from_client{user="hello"} 1690614
telemt_user_msgs_to_client{user="hello"} 10488458
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 50549.6 (14h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120288
telemt_connections_bad_total 11449
telemt_handshake_timeouts_total 1664
telemt_upstream_connect_attempt_total 102331
telemt_upstream_connect_success_total 102082
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 102331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 89382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12471
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 102076
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 2337725678 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 95594324253 (89.03 GB)
telemt_user_msgs_from_client{user="hello"} 2507787
telemt_user_msgs_to_client{user="hello"} 12306554
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 29519.0 (8h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```