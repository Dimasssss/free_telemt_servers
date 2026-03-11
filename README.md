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

# Server Metrics 2026-03-11 09:55:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 70139.7 (19h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206398
telemt_connections_bad_total 3606
telemt_handshake_timeouts_total 4320
telemt_upstream_connect_attempt_total 189009
telemt_upstream_connect_success_total 188950
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 189009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 172700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16193
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 188942
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 4088628418 (3.81 GB)
telemt_user_octets_to_client{user="hello"} 111710824071 (104.04 GB)
telemt_user_msgs_from_client{user="hello"} 4466768
telemt_user_msgs_to_client{user="hello"} 8343773
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 70138.9 (19h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80544
telemt_connections_bad_total 782
telemt_handshake_timeouts_total 3144
telemt_upstream_connect_attempt_total 72870
telemt_upstream_connect_success_total 72854
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 72870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9848
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 253
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 72846
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 4997454230 (4.65 GB)
telemt_user_octets_to_client{user="hello"} 55738417220 (51.91 GB)
telemt_user_msgs_from_client{user="hello"} 3177166
telemt_user_msgs_to_client{user="hello"} 14361490
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 70139.1 (19h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111539
telemt_connections_bad_total 1075
telemt_handshake_timeouts_total 5235
telemt_upstream_connect_attempt_total 98890
telemt_upstream_connect_success_total 98886
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 98890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 87651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11171
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 98878
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 12010292746 (11.19 GB)
telemt_user_octets_to_client{user="hello"} 81606052540 (76.00 GB)
telemt_user_msgs_from_client{user="hello"} 5681941
telemt_user_msgs_to_client{user="hello"} 15854527
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 70137.4 (19h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122499
telemt_connections_bad_total 251
telemt_handshake_timeouts_total 1128
telemt_upstream_connect_attempt_total 116285
telemt_upstream_connect_success_total 116022
telemt_upstream_connect_fail_total 263
telemt_upstream_connect_attempts_per_request{bucket="1"} 116285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 100188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15458
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 59
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 317
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 263
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 116014
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 5512563288 (5.13 GB)
telemt_user_octets_to_client{user="hello"} 82460323497 (76.80 GB)
telemt_user_msgs_from_client{user="hello"} 3626059
telemt_user_msgs_to_client{user="hello"} 21351648
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 70138.7 (19h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 193712
telemt_connections_bad_total 15282
telemt_handshake_timeouts_total 3353
telemt_upstream_connect_attempt_total 154862
telemt_upstream_connect_success_total 154460
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 154862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 132477
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21696
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 287
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 154452
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 3027116904 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 136387617002 (127.02 GB)
telemt_user_msgs_from_client{user="hello"} 3439923
telemt_user_msgs_to_client{user="hello"} 17832092
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 49108.2 (13h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 422
telemt_connections_bad_total 400
telemt_handshake_timeouts_total 9
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