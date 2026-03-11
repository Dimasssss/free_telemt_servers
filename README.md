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

# Server Metrics 2026-03-11 16:45:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 1861.5 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9647
telemt_connections_bad_total 502
telemt_handshake_timeouts_total 336
telemt_upstream_connect_attempt_total 8236
telemt_upstream_connect_success_total 8232
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 8236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 648
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8230
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 79267794 (75.60 MB)
telemt_user_octets_to_client{user="hello"} 3860659750 (3.60 GB)
telemt_user_msgs_from_client{user="hello"} 125937
telemt_user_msgs_to_client{user="hello"} 313444
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 94752.6 (26h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130895
telemt_connections_bad_total 975
telemt_handshake_timeouts_total 3472
telemt_upstream_connect_attempt_total 120915
telemt_upstream_connect_success_total 120891
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 120915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14856
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 623
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 120881
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 6125398112 (5.70 GB)
telemt_user_octets_to_client{user="hello"} 73393310853 (68.35 GB)
telemt_user_msgs_from_client{user="hello"} 4205248
telemt_user_msgs_to_client{user="hello"} 21553327
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 94752.1 (26h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176709
telemt_connections_bad_total 1447
telemt_handshake_timeouts_total 7883
telemt_upstream_connect_attempt_total 157825
telemt_upstream_connect_success_total 157811
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 157825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 139996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17705
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 157801
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 12803777849 (11.92 GB)
telemt_user_octets_to_client{user="hello"} 136138789492 (126.79 GB)
telemt_user_msgs_from_client{user="hello"} 7039203
telemt_user_msgs_to_client{user="hello"} 30961868
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 94751.0 (26h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 200863
telemt_connections_bad_total 10808
telemt_handshake_timeouts_total 3512
telemt_upstream_connect_attempt_total 178585
telemt_upstream_connect_success_total 178153
telemt_upstream_connect_fail_total 432
telemt_upstream_connect_attempts_per_request{bucket="1"} 178585
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22044
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 490
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 432
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 178143
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 10469022267 (9.75 GB)
telemt_user_octets_to_client{user="hello"} 124059567958 (115.54 GB)
telemt_user_msgs_from_client{user="hello"} 6264629
telemt_user_msgs_to_client{user="hello"} 36950217
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 73721.5 (20h 28m)
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