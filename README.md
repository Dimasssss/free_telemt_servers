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

# Server Metrics 2026-03-11 23:51:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 7609.2 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12532
telemt_connections_bad_total 175
telemt_handshake_timeouts_total 76
telemt_upstream_connect_attempt_total 11970
telemt_upstream_connect_success_total 11966
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 11970
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1346
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11964
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 162949559 (155.40 MB)
telemt_user_octets_to_client{user="hello"} 5605798363 (5.22 GB)
telemt_user_msgs_from_client{user="hello"} 281566
telemt_user_msgs_to_client{user="hello"} 725171
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 7597.4 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5414
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 5193
telemt_upstream_connect_success_total 5193
telemt_upstream_connect_attempts_per_request{bucket="1"} 5193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 663
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5191
telemt_user_connections_current{user="hello"} 52
telemt_user_octets_from_client{user="hello"} 24966575 (23.81 MB)
telemt_user_octets_to_client{user="hello"} 729560583 (695.76 MB)
telemt_user_msgs_from_client{user="hello"} 60474
telemt_user_msgs_to_client{user="hello"} 315003
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 7571.0 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9815
telemt_connections_bad_total 268
telemt_handshake_timeouts_total 752
telemt_upstream_connect_attempt_total 7456
telemt_upstream_connect_success_total 7456
telemt_upstream_connect_attempts_per_request{bucket="1"} 7456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 980
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7454
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 51566586 (49.18 MB)
telemt_user_octets_to_client{user="hello"} 5532640202 (5.15 GB)
telemt_user_msgs_from_client{user="hello"} 160779
telemt_user_msgs_to_client{user="hello"} 1276215
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 7596.3 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7947
telemt_connections_bad_total 651
telemt_handshake_timeouts_total 236
telemt_upstream_connect_attempt_total 6815
telemt_upstream_connect_success_total 6806
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 6815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 810
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6804
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 50359400 (48.03 MB)
telemt_user_octets_to_client{user="hello"} 2600717501 (2.42 GB)
telemt_user_msgs_from_client{user="hello"} 102537
telemt_user_msgs_to_client{user="hello"} 990909
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 7597.3 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7249
telemt_connections_bad_total 58
telemt_handshake_timeouts_total 99
telemt_upstream_connect_attempt_total 6346
telemt_upstream_connect_success_total 6346
telemt_upstream_connect_attempts_per_request{bucket="1"} 6346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1101
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6344
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 96729301 (92.25 MB)
telemt_user_octets_to_client{user="hello"} 12507938925 (11.65 GB)
telemt_user_msgs_from_client{user="hello"} 186535
telemt_user_msgs_to_client{user="hello"} 1020308
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 8
```