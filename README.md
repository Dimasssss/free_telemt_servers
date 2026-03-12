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

# Server Metrics 2026-03-12 06:45:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 32422.4 (9h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89619
telemt_connections_bad_total 2118
telemt_handshake_timeouts_total 2382
telemt_upstream_connect_attempt_total 81270
telemt_upstream_connect_success_total 81135
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 81269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12222
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 81131
telemt_user_connections_current{user="hello"} 309
telemt_user_octets_from_client{user="hello"} 832605397 (794.03 MB)
telemt_user_octets_to_client{user="hello"} 24188805223 (22.53 GB)
telemt_user_msgs_from_client{user="hello"} 1218183
telemt_user_msgs_to_client{user="hello"} 2767236
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 32410.5 (9h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36571
telemt_connections_bad_total 211
telemt_handshake_timeouts_total 554
telemt_upstream_connect_attempt_total 34525
telemt_upstream_connect_success_total 34494
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 34525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4703
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 34490
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 309538586 (295.20 MB)
telemt_user_octets_to_client{user="hello"} 16004382855 (14.91 GB)
telemt_user_msgs_from_client{user="hello"} 611812
telemt_user_msgs_to_client{user="hello"} 5078697
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 32384.2 (8h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54600
telemt_connections_bad_total 676
telemt_handshake_timeouts_total 1138
telemt_upstream_connect_attempt_total 49139
telemt_upstream_connect_success_total 49107
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 49139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8407
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49103
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 5453929353 (5.08 GB)
telemt_user_octets_to_client{user="hello"} 29803486648 (27.76 GB)
telemt_user_msgs_from_client{user="hello"} 2727182
telemt_user_msgs_to_client{user="hello"} 5318445
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 32409.3 (9h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59642
telemt_connections_bad_total 13010
telemt_handshake_timeouts_total 894
telemt_upstream_connect_attempt_total 43321
telemt_upstream_connect_success_total 41572
telemt_upstream_connect_fail_total 1749
telemt_upstream_connect_attempts_per_request{bucket="1"} 43321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7085
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1749
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 41568
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 1404537981 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 31145109518 (29.01 GB)
telemt_user_msgs_from_client{user="hello"} 1134739
telemt_user_msgs_to_client{user="hello"} 12577272
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 2601.7 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3881
telemt_connections_bad_total 465
telemt_handshake_timeouts_total 113
telemt_upstream_connect_attempt_total 3187
telemt_upstream_connect_success_total 3162
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 3187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 330
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3160
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 121114305 (115.50 MB)
telemt_user_octets_to_client{user="hello"} 3550686488 (3.31 GB)
telemt_user_msgs_from_client{user="hello"} 102261
telemt_user_msgs_to_client{user="hello"} 472409
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 32410.2 (9h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56369
telemt_connections_bad_total 889
telemt_handshake_timeouts_total 326
telemt_upstream_connect_attempt_total 52617
telemt_upstream_connect_success_total 52555
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 52617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8684
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 52551
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 949726290 (905.73 MB)
telemt_user_octets_to_client{user="hello"} 49197080513 (45.82 GB)
telemt_user_msgs_from_client{user="hello"} 1349420
telemt_user_msgs_to_client{user="hello"} 6292051
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 33
```