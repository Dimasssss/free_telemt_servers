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

# Server Metrics 2026-03-12 01:39:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 14092.4 (3h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26695
telemt_connections_bad_total 1848
telemt_handshake_timeouts_total 164
telemt_upstream_connect_attempt_total 23775
telemt_upstream_connect_success_total 23769
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 23775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2297
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23767
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 255861454 (244.01 MB)
telemt_user_octets_to_client{user="hello"} 8625477902 (8.03 GB)
telemt_user_msgs_from_client{user="hello"} 436809
telemt_user_msgs_to_client{user="hello"} 1073131
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 14080.5 (3h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11436
telemt_connections_bad_total 45
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 10983
telemt_upstream_connect_success_total 10983
telemt_upstream_connect_attempts_per_request{bucket="1"} 10983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1301
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10981
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 72012637 (68.68 MB)
telemt_user_octets_to_client{user="hello"} 3719877123 (3.46 GB)
telemt_user_msgs_from_client{user="hello"} 178280
telemt_user_msgs_to_client{user="hello"} 1233884
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 14054.0 (3h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18571
telemt_connections_bad_total 288
telemt_handshake_timeouts_total 868
telemt_upstream_connect_attempt_total 15579
telemt_upstream_connect_success_total 15579
telemt_upstream_connect_attempts_per_request{bucket="1"} 15579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2191
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15577
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 2706971132 (2.52 GB)
telemt_user_octets_to_client{user="hello"} 8341560919 (7.77 GB)
telemt_user_msgs_from_client{user="hello"} 1215707
telemt_user_msgs_to_client{user="hello"} 1765193
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 14079.4 (3h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20659
telemt_connections_bad_total 6334
telemt_handshake_timeouts_total 691
telemt_upstream_connect_attempt_total 13010
telemt_upstream_connect_success_total 12998
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 13010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1700
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12996
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 102561922 (97.81 MB)
telemt_user_octets_to_client{user="hello"} 6210707938 (5.78 GB)
telemt_user_msgs_from_client{user="hello"} 206387
telemt_user_msgs_to_client{user="hello"} 2363784
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 14080.1 (3h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15325
telemt_connections_bad_total 125
telemt_handshake_timeouts_total 127
telemt_upstream_connect_attempt_total 13902
telemt_upstream_connect_success_total 13902
telemt_upstream_connect_attempts_per_request{bucket="1"} 13902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11732
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2166
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13900
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 210160004 (200.42 MB)
telemt_user_octets_to_client{user="hello"} 20357503593 (18.96 GB)
telemt_user_msgs_from_client{user="hello"} 398041
telemt_user_msgs_to_client{user="hello"} 1943999
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 10
```