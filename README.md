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

# Server Metrics 2026-03-11 18:18:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 4665.8 (1h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19291
telemt_connections_bad_total 989
telemt_handshake_timeouts_total 84
telemt_upstream_connect_attempt_total 17356
telemt_upstream_connect_success_total 17353
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 17356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1668
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17351
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 468846402 (447.13 MB)
telemt_user_octets_to_client{user="hello"} 10618495848 (9.89 GB)
telemt_user_msgs_from_client{user="hello"} 423780
telemt_user_msgs_to_client{user="hello"} 796497
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 4653.8 (1h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9749
telemt_connections_bad_total 27
telemt_handshake_timeouts_total 167
telemt_upstream_connect_attempt_total 8876
telemt_upstream_connect_success_total 8875
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8876
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1109
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 214
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8873
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 153442193 (146.33 MB)
telemt_user_octets_to_client{user="hello"} 5969071387 (5.56 GB)
telemt_user_msgs_from_client{user="hello"} 213391
telemt_user_msgs_to_client{user="hello"} 2216753
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 4673.4 (1h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10927
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 102
telemt_upstream_connect_attempt_total 10236
telemt_upstream_connect_success_total 10235
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 942
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10233
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 82196953 (78.39 MB)
telemt_user_octets_to_client{user="hello"} 4156591153 (3.87 GB)
telemt_user_msgs_from_client{user="hello"} 209609
telemt_user_msgs_to_client{user="hello"} 1205627
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 4669.0 (1h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10602
telemt_connections_bad_total 565
telemt_handshake_timeouts_total 186
telemt_upstream_connect_attempt_total 9478
telemt_upstream_connect_success_total 9455
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 9478
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 955
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9453
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 445492977 (424.86 MB)
telemt_user_octets_to_client{user="hello"} 4467857966 (4.16 GB)
telemt_user_msgs_from_client{user="hello"} 276412
telemt_user_msgs_to_client{user="hello"} 1076172
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 4677.4 (1h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11684
telemt_connections_bad_total 954
telemt_handshake_timeouts_total 77
telemt_upstream_connect_attempt_total 10318
telemt_upstream_connect_success_total 10318
telemt_upstream_connect_attempts_per_request{bucket="1"} 10318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1475
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10316
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 69720362 (66.49 MB)
telemt_user_octets_to_client{user="hello"} 1620160044 (1.51 GB)
telemt_user_msgs_from_client{user="hello"} 150022
telemt_user_msgs_to_client{user="hello"} 541367
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 79283.7 (22h 1m)
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