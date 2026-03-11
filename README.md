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

# Server Metrics 2026-03-11 13:09:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 81814.2 (22h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 263277
telemt_connections_bad_total 3638
telemt_handshake_timeouts_total 4670
telemt_upstream_connect_attempt_total 243282
telemt_upstream_connect_success_total 243207
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 243281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 222665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20483
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 243199
telemt_user_connections_current{user="hello"} 341
telemt_user_octets_from_client{user="hello"} 4825677588 (4.49 GB)
telemt_user_octets_to_client{user="hello"} 127573152430 (118.81 GB)
telemt_user_msgs_from_client{user="hello"} 5461445
telemt_user_msgs_to_client{user="hello"} 10030023
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 81813.1 (22h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102510
telemt_connections_bad_total 906
telemt_handshake_timeouts_total 3328
telemt_upstream_connect_attempt_total 93783
telemt_upstream_connect_success_total 93765
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 93783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12168
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 315
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 93757
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 5216421876 (4.86 GB)
telemt_user_octets_to_client{user="hello"} 62716132206 (58.41 GB)
telemt_user_msgs_from_client{user="hello"} 3519425
telemt_user_msgs_to_client{user="hello"} 17616312
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 81812.9 (22h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142553
telemt_connections_bad_total 1104
telemt_handshake_timeouts_total 6786
telemt_upstream_connect_attempt_total 126861
telemt_upstream_connect_success_total 126846
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 126860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14172
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 126838
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 12521681133 (11.66 GB)
telemt_user_octets_to_client{user="hello"} 103745398195 (96.62 GB)
telemt_user_msgs_from_client{user="hello"} 6356519
telemt_user_msgs_to_client{user="hello"} 21817307
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 81811.8 (22h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156425
telemt_connections_bad_total 2101
telemt_handshake_timeouts_total 1896
telemt_upstream_connect_attempt_total 146048
telemt_upstream_connect_success_total 145705
telemt_upstream_connect_fail_total 343
telemt_upstream_connect_attempts_per_request{bucket="1"} 146048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 126533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18698
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 84
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 390
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 343
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 145697
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 8509456063 (7.93 GB)
telemt_user_octets_to_client{user="hello"} 108329661994 (100.89 GB)
telemt_user_msgs_from_client{user="hello"} 5144402
telemt_user_msgs_to_client{user="hello"} 31904352
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 81813.1 (22h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233658
telemt_connections_bad_total 18226
telemt_handshake_timeouts_total 5846
telemt_upstream_connect_attempt_total 188210
telemt_upstream_connect_success_total 187708
telemt_upstream_connect_fail_total 502
telemt_upstream_connect_attempts_per_request{bucket="1"} 188210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 162249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25121
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 338
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 502
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 187700
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 4749709566 (4.42 GB)
telemt_user_octets_to_client{user="hello"} 154371384647 (143.77 GB)
telemt_user_msgs_from_client{user="hello"} 4490997
telemt_user_msgs_to_client{user="hello"} 21302844
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 60782.4 (16h 53m)
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