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

# Server Metrics 2026-03-11 23:46:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 7285.1 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12012
telemt_connections_bad_total 175
telemt_handshake_timeouts_total 76
telemt_upstream_connect_attempt_total 11465
telemt_upstream_connect_success_total 11461
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 11465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1302
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11459
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 160495721 (153.06 MB)
telemt_user_octets_to_client{user="hello"} 5554395129 (5.17 GB)
telemt_user_msgs_from_client{user="hello"} 276166
telemt_user_msgs_to_client{user="hello"} 716438
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 7273.1 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5131
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 4918
telemt_upstream_connect_success_total 4918
telemt_upstream_connect_attempts_per_request{bucket="1"} 4918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4279
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 639
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4916
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 24311736 (23.19 MB)
telemt_user_octets_to_client{user="hello"} 713349012 (680.30 MB)
telemt_user_msgs_from_client{user="hello"} 58710
telemt_user_msgs_to_client{user="hello"} 305164
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 7246.8 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9495
telemt_connections_bad_total 268
telemt_handshake_timeouts_total 751
telemt_upstream_connect_attempt_total 7149
telemt_upstream_connect_success_total 7149
telemt_upstream_connect_attempts_per_request{bucket="1"} 7149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 936
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7147
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 49442789 (47.15 MB)
telemt_user_octets_to_client{user="hello"} 5279159861 (4.92 GB)
telemt_user_msgs_from_client{user="hello"} 154087
telemt_user_msgs_to_client{user="hello"} 1243594
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 7272.2 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7198
telemt_connections_bad_total 250
telemt_handshake_timeouts_total 169
telemt_upstream_connect_attempt_total 6487
telemt_upstream_connect_success_total 6479
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 6487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 786
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6477
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 49045422 (46.77 MB)
telemt_user_octets_to_client{user="hello"} 2473151752 (2.30 GB)
telemt_user_msgs_from_client{user="hello"} 99395
telemt_user_msgs_to_client{user="hello"} 943342
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 7273.0 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7030
telemt_connections_bad_total 58
telemt_handshake_timeouts_total 99
telemt_upstream_connect_attempt_total 6133
telemt_upstream_connect_success_total 6133
telemt_upstream_connect_attempts_per_request{bucket="1"} 6133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1060
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6131
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 94175539 (89.81 MB)
telemt_user_octets_to_client{user="hello"} 12004570369 (11.18 GB)
telemt_user_msgs_from_client{user="hello"} 179200
telemt_user_msgs_to_client{user="hello"} 946528
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 8
```