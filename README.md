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

# Server Metrics 2026-03-10 20:50:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 23037.2 (6h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85112
telemt_connections_bad_total 3263
telemt_handshake_timeouts_total 2136
telemt_upstream_connect_attempt_total 75847
telemt_upstream_connect_success_total 75817
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 75847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6623
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 75813
telemt_user_connections_current{user="hello"} 236
telemt_user_octets_from_client{user="hello"} 2445330633 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 58779062200 (54.74 GB)
telemt_user_msgs_from_client{user="hello"} 2248872
telemt_user_msgs_to_client{user="hello"} 4035436
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 23036.4 (6h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32583
telemt_connections_bad_total 302
telemt_handshake_timeouts_total 569
telemt_upstream_connect_attempt_total 29745
telemt_upstream_connect_success_total 29737
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 29745
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4412
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29733
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 1521086995 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 25295675684 (23.56 GB)
telemt_user_msgs_from_client{user="hello"} 1182675
telemt_user_msgs_to_client{user="hello"} 7346666
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 23036.4 (6h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52186
telemt_connections_bad_total 291
telemt_handshake_timeouts_total 3704
telemt_upstream_connect_attempt_total 45210
telemt_upstream_connect_success_total 45209
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 45210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4264
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 45205
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 680471754 (648.95 MB)
telemt_user_octets_to_client{user="hello"} 42024703953 (39.14 GB)
telemt_user_msgs_from_client{user="hello"} 962033
telemt_user_msgs_to_client{user="hello"} 6302765
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 23035.1 (6h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46487
telemt_connections_bad_total 70
telemt_handshake_timeouts_total 314
telemt_upstream_connect_attempt_total 44610
telemt_upstream_connect_success_total 44478
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 44610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5162
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44474
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 753512652 (718.61 MB)
telemt_user_octets_to_client{user="hello"} 34199081867 (31.85 GB)
telemt_user_msgs_from_client{user="hello"} 985212
telemt_user_msgs_to_client{user="hello"} 6512105
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 23036.4 (6h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65950
telemt_connections_bad_total 5981
telemt_handshake_timeouts_total 1375
telemt_upstream_connect_attempt_total 55835
telemt_upstream_connect_success_total 55591
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 55835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6841
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 55587
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 1748302657 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 43964366120 (40.95 GB)
telemt_user_msgs_from_client{user="hello"} 1593199
telemt_user_msgs_to_client{user="hello"} 6066846
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 2005.7 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16
telemt_connections_bad_total 16
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```