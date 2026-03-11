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

# Server Metrics 2026-03-11 06:41:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 58498.9 (16h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157645
telemt_connections_bad_total 3502
telemt_handshake_timeouts_total 3938
telemt_upstream_connect_attempt_total 142215
telemt_upstream_connect_success_total 142170
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 142214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 129716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12398
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 142164
telemt_user_connections_current{user="hello"} 300
telemt_user_octets_from_client{user="hello"} 3435354162 (3.20 GB)
telemt_user_octets_to_client{user="hello"} 94606322149 (88.11 GB)
telemt_user_msgs_from_client{user="hello"} 3604759
telemt_user_msgs_to_client{user="hello"} 6712568
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 58498.2 (16h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62094
telemt_connections_bad_total 448
telemt_handshake_timeouts_total 3034
telemt_upstream_connect_attempt_total 55505
telemt_upstream_connect_success_total 55493
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 55505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7965
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 231
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 55487
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 4622937385 (4.31 GB)
telemt_user_octets_to_client{user="hello"} 48976572147 (45.61 GB)
telemt_user_msgs_from_client{user="hello"} 2837409
telemt_user_msgs_to_client{user="hello"} 11731008
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 58498.0 (16h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83713
telemt_connections_bad_total 740
telemt_handshake_timeouts_total 4413
telemt_upstream_connect_attempt_total 73887
telemt_upstream_connect_success_total 73879
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 73882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8278
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 73873
telemt_user_connections_current{user="hello"} 64
telemt_user_octets_from_client{user="hello"} 11828722199 (11.02 GB)
telemt_user_octets_to_client{user="hello"} 72922892172 (67.91 GB)
telemt_user_msgs_from_client{user="hello"} 5277838
telemt_user_msgs_to_client{user="hello"} 13833105
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 58497.1 (16h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90134
telemt_connections_bad_total 199
telemt_handshake_timeouts_total 639
telemt_upstream_connect_attempt_total 86311
telemt_upstream_connect_success_total 86120
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 86311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11289
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 86114
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 1959742483 (1.83 GB)
telemt_user_octets_to_client{user="hello"} 58446994282 (54.43 GB)
telemt_user_msgs_from_client{user="hello"} 1954310
telemt_user_msgs_to_client{user="hello"} 14235423
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 58498.3 (16h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153491
telemt_connections_bad_total 12939
telemt_handshake_timeouts_total 1809
telemt_upstream_connect_attempt_total 121133
telemt_upstream_connect_success_total 120884
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 121133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 103596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17051
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 237
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 120878
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 2505707385 (2.33 GB)
telemt_user_octets_to_client{user="hello"} 116269769221 (108.28 GB)
telemt_user_msgs_from_client{user="hello"} 2844398
telemt_user_msgs_to_client{user="hello"} 15131284
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 37467.7 (10h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167
telemt_connections_bad_total 147
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 15
telemt_upstream_connect_success_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```