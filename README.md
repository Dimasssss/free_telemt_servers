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

# Server Metrics 2026-03-11 12:44:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 80278.4 (22h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254769
telemt_connections_bad_total 3635
telemt_handshake_timeouts_total 4634
telemt_upstream_connect_attempt_total 235167
telemt_upstream_connect_success_total 235094
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 235167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 215225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19812
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 235086
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 4729777182 (4.40 GB)
telemt_user_octets_to_client{user="hello"} 125691906194 (117.06 GB)
telemt_user_msgs_from_client{user="hello"} 5325386
telemt_user_msgs_to_client{user="hello"} 9789975
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 80277.7 (22h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99332
telemt_connections_bad_total 906
telemt_handshake_timeouts_total 3320
telemt_upstream_connect_attempt_total 90694
telemt_upstream_connect_success_total 90677
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 90694
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 78608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11783
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 286
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 90669
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 5192400656 (4.84 GB)
telemt_user_octets_to_client{user="hello"} 60468033595 (56.32 GB)
telemt_user_msgs_from_client{user="hello"} 3464584
telemt_user_msgs_to_client{user="hello"} 16576767
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 80277.5 (22h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137509
telemt_connections_bad_total 1103
telemt_handshake_timeouts_total 6704
telemt_upstream_connect_attempt_total 122067
telemt_upstream_connect_success_total 122051
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 122065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13690
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 122043
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 12471076737 (11.61 GB)
telemt_user_octets_to_client{user="hello"} 93897282122 (87.45 GB)
telemt_user_msgs_from_client{user="hello"} 6232803
telemt_user_msgs_to_client{user="hello"} 19196921
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 80276.3 (22h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150761
telemt_connections_bad_total 353
telemt_handshake_timeouts_total 1886
telemt_upstream_connect_attempt_total 142313
telemt_upstream_connect_success_total 141977
telemt_upstream_connect_fail_total 336
telemt_upstream_connect_attempts_per_request{bucket="1"} 142313
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 123237
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18291
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 75
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 374
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 336
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 141969
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 8049074177 (7.50 GB)
telemt_user_octets_to_client{user="hello"} 106678926009 (99.35 GB)
telemt_user_msgs_from_client{user="hello"} 4928799
telemt_user_msgs_to_client{user="hello"} 31245969
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 80277.6 (22h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 226688
telemt_connections_bad_total 17665
telemt_handshake_timeouts_total 4282
telemt_upstream_connect_attempt_total 183546
telemt_upstream_connect_success_total 183046
telemt_upstream_connect_fail_total 500
telemt_upstream_connect_attempts_per_request{bucket="1"} 183546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 158120
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24593
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 333
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 500
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 183038
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 4708382913 (4.39 GB)
telemt_user_octets_to_client{user="hello"} 150118911996 (139.81 GB)
telemt_user_msgs_from_client{user="hello"} 4400814
telemt_user_msgs_to_client{user="hello"} 20692822
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 59247.0 (16h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 429
telemt_connections_bad_total 407
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 17
telemt_upstream_connect_success_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```