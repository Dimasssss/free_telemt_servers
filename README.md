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

# Server Metrics 2026-03-11 18:33:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 5587.1 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23052
telemt_connections_bad_total 1278
telemt_handshake_timeouts_total 104
telemt_upstream_connect_attempt_total 20709
telemt_upstream_connect_success_total 20705
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 20709
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18715
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1965
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20703
telemt_user_connections_current{user="hello"} 306
telemt_user_octets_from_client{user="hello"} 605796774 (577.73 MB)
telemt_user_octets_to_client{user="hello"} 13615182814 (12.68 GB)
telemt_user_msgs_from_client{user="hello"} 533538
telemt_user_msgs_to_client{user="hello"} 996940
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 5575.8 (1h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11289
telemt_connections_bad_total 34
telemt_handshake_timeouts_total 228
telemt_upstream_connect_attempt_total 10066
telemt_upstream_connect_success_total 10065
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1205
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 231
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10063
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 161592712 (154.11 MB)
telemt_user_octets_to_client{user="hello"} 6321108065 (5.89 GB)
telemt_user_msgs_from_client{user="hello"} 234188
telemt_user_msgs_to_client{user="hello"} 2358208
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 5595.0 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12738
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 106
telemt_upstream_connect_attempt_total 11849
telemt_upstream_connect_success_total 11846
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 11848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1046
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11844
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 106280190 (101.36 MB)
telemt_user_octets_to_client{user="hello"} 5013463457 (4.67 GB)
telemt_user_msgs_from_client{user="hello"} 247718
telemt_user_msgs_to_client{user="hello"} 1443149
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 5590.8 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12532
telemt_connections_bad_total 566
telemt_handshake_timeouts_total 193
telemt_upstream_connect_attempt_total 11319
telemt_upstream_connect_success_total 11290
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 11319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1094
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11288
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 465028273 (443.49 MB)
telemt_user_octets_to_client{user="hello"} 6415978600 (5.98 GB)
telemt_user_msgs_from_client{user="hello"} 311949
telemt_user_msgs_to_client{user="hello"} 1399345
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 5598.9 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14001
telemt_connections_bad_total 1132
telemt_handshake_timeouts_total 78
telemt_upstream_connect_attempt_total 12395
telemt_upstream_connect_success_total 12395
telemt_upstream_connect_attempts_per_request{bucket="1"} 12395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1737
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12393
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 209581579 (199.87 MB)
telemt_user_octets_to_client{user="hello"} 3057000631 (2.85 GB)
telemt_user_msgs_from_client{user="hello"} 235209
telemt_user_msgs_to_client{user="hello"} 917801
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 80205.3 (22h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 496
telemt_connections_bad_total 472
telemt_handshake_timeouts_total 14
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