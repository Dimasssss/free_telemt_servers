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

# Server Metrics 2026-03-10 19:36:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 18624.6 (5h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71465
telemt_connections_bad_total 2379
telemt_handshake_timeouts_total 1932
telemt_upstream_connect_attempt_total 63752
telemt_upstream_connect_success_total 63739
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 63752
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58048
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5668
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 63737
telemt_user_connections_current{user="hello"} 291
telemt_user_octets_from_client{user="hello"} 2022257711 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 46668614345 (43.46 GB)
telemt_user_msgs_from_client{user="hello"} 1866704
telemt_user_msgs_to_client{user="hello"} 3482504
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 18624.1 (5h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27399
telemt_connections_bad_total 212
telemt_handshake_timeouts_total 451
telemt_upstream_connect_attempt_total 25089
telemt_upstream_connect_success_total 25082
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 25089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3644
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 200
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25080
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 828628218 (790.24 MB)
telemt_user_octets_to_client{user="hello"} 18522638788 (17.25 GB)
telemt_user_msgs_from_client{user="hello"} 820637
telemt_user_msgs_to_client{user="hello"} 5639308
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 18623.7 (5h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42676
telemt_connections_bad_total 138
telemt_handshake_timeouts_total 3585
telemt_upstream_connect_attempt_total 36387
telemt_upstream_connect_success_total 36387
telemt_upstream_connect_attempts_per_request{bucket="1"} 36387
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3467
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 36385
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 579332878 (552.49 MB)
telemt_user_octets_to_client{user="hello"} 35066500280 (32.66 GB)
telemt_user_msgs_from_client{user="hello"} 794144
telemt_user_msgs_to_client{user="hello"} 5256523
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 18622.6 (5h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39348
telemt_connections_bad_total 65
telemt_handshake_timeouts_total 275
telemt_upstream_connect_attempt_total 37730
telemt_upstream_connect_success_total 37621
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 37730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4347
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 37619
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 627898087 (598.81 MB)
telemt_user_octets_to_client{user="hello"} 30161029149 (28.09 GB)
telemt_user_msgs_from_client{user="hello"} 809162
telemt_user_msgs_to_client{user="hello"} 5628146
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 18623.9 (5h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58038
telemt_connections_bad_total 5094
telemt_handshake_timeouts_total 1246
telemt_upstream_connect_attempt_total 49327
telemt_upstream_connect_success_total 49084
telemt_upstream_connect_fail_total 243
telemt_upstream_connect_attempts_per_request{bucket="1"} 49327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5984
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 243
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49082
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 1503367369 (1.40 GB)
telemt_user_octets_to_client{user="hello"} 36925365245 (34.39 GB)
telemt_user_msgs_from_client{user="hello"} 1361945
telemt_user_msgs_to_client{user="hello"} 5290658
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 28
```