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

# Server Metrics 2026-03-11 06:36:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 58193.3 (16h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156325
telemt_connections_bad_total 3502
telemt_handshake_timeouts_total 3934
telemt_upstream_connect_attempt_total 140966
telemt_upstream_connect_success_total 140922
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 140966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 128535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12331
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 140916
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 3424527888 (3.19 GB)
telemt_user_octets_to_client{user="hello"} 93841202084 (87.40 GB)
telemt_user_msgs_from_client{user="hello"} 3582348
telemt_user_msgs_to_client{user="hello"} 6670273
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 58192.7 (16h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61511
telemt_connections_bad_total 447
telemt_handshake_timeouts_total 3032
telemt_upstream_connect_attempt_total 54945
telemt_upstream_connect_success_total 54933
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 54945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46791
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7911
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 231
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 54927
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 4616494715 (4.30 GB)
telemt_user_octets_to_client{user="hello"} 48550891318 (45.22 GB)
telemt_user_msgs_from_client{user="hello"} 2824305
telemt_user_msgs_to_client{user="hello"} 11582594
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 58192.5 (16h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83307
telemt_connections_bad_total 738
telemt_handshake_timeouts_total 4408
telemt_upstream_connect_attempt_total 73513
telemt_upstream_connect_success_total 73510
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 73513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65211
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8244
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 73504
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 11825693068 (11.01 GB)
telemt_user_octets_to_client{user="hello"} 72732962125 (67.74 GB)
telemt_user_msgs_from_client{user="hello"} 5270736
telemt_user_msgs_to_client{user="hello"} 13779534
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 58191.5 (16h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89611
telemt_connections_bad_total 199
telemt_handshake_timeouts_total 638
telemt_upstream_connect_attempt_total 85803
telemt_upstream_connect_success_total 85612
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 85803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11231
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 85606
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 1950428260 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 57569729661 (53.62 GB)
telemt_user_msgs_from_client{user="hello"} 1937366
telemt_user_msgs_to_client{user="hello"} 13892453
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 58192.7 (16h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152346
telemt_connections_bad_total 12884
telemt_handshake_timeouts_total 1808
telemt_upstream_connect_attempt_total 120092
telemt_upstream_connect_success_total 119842
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 120091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 102619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 235
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 119836
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 2496963740 (2.33 GB)
telemt_user_octets_to_client{user="hello"} 114951384927 (107.06 GB)
telemt_user_msgs_from_client{user="hello"} 2828016
telemt_user_msgs_to_client{user="hello"} 15022352
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 37162.1 (10h 19m)
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