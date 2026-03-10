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

# Server Metrics 2026-03-10 21:36:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 25791.7 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90483
telemt_connections_bad_total 3272
telemt_handshake_timeouts_total 2172
telemt_upstream_connect_attempt_total 81007
telemt_upstream_connect_success_total 80975
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 81007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7042
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 80971
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 2495768445 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 63358332816 (59.01 GB)
telemt_user_msgs_from_client{user="hello"} 2359519
telemt_user_msgs_to_client{user="hello"} 4234253
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 25790.8 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34377
telemt_connections_bad_total 319
telemt_handshake_timeouts_total 644
telemt_upstream_connect_attempt_total 31352
telemt_upstream_connect_success_total 31343
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 31352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26486
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4637
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31339
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 1630548229 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 30618451749 (28.52 GB)
telemt_user_msgs_from_client{user="hello"} 1287596
telemt_user_msgs_to_client{user="hello"} 8110194
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 25790.5 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55811
telemt_connections_bad_total 407
telemt_handshake_timeouts_total 3964
telemt_upstream_connect_attempt_total 48315
telemt_upstream_connect_success_total 48313
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 48315
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4612
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 48309
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 749375308 (714.66 MB)
telemt_user_octets_to_client{user="hello"} 43099925746 (40.14 GB)
telemt_user_msgs_from_client{user="hello"} 1018438
telemt_user_msgs_to_client{user="hello"} 6526297
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 25789.5 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50413
telemt_connections_bad_total 76
telemt_handshake_timeouts_total 321
telemt_upstream_connect_attempt_total 48386
telemt_upstream_connect_success_total 48248
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 48386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5604
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 48244
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 797321483 (760.39 MB)
telemt_user_octets_to_client{user="hello"} 36471807466 (33.97 GB)
telemt_user_msgs_from_client{user="hello"} 1068646
telemt_user_msgs_to_client{user="hello"} 6918155
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 25790.8 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73210
telemt_connections_bad_total 6538
telemt_handshake_timeouts_total 1402
telemt_upstream_connect_attempt_total 62319
telemt_upstream_connect_success_total 62075
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 62319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8070
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 202
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 62071
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 1858186212 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 46441564344 (43.25 GB)
telemt_user_msgs_from_client{user="hello"} 1710613
telemt_user_msgs_to_client{user="hello"} 6555599
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 4760.2 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19
telemt_connections_bad_total 19
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```