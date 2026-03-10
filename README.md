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

# Server Metrics 2026-03-10 23:38:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 33135.0 (9h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99374
telemt_connections_bad_total 3322
telemt_handshake_timeouts_total 2220
telemt_upstream_connect_attempt_total 89438
telemt_upstream_connect_success_total 89406
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 89438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8013
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 89402
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 2620396212 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 73229867156 (68.20 GB)
telemt_user_msgs_from_client{user="hello"} 2603666
telemt_user_msgs_to_client{user="hello"} 5001018
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 33134.2 (9h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38803
telemt_connections_bad_total 335
telemt_handshake_timeouts_total 901
telemt_upstream_connect_attempt_total 35275
telemt_upstream_connect_success_total 35266
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 35275
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5252
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 35262
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 1960453502 (1.83 GB)
telemt_user_octets_to_client{user="hello"} 36999024642 (34.46 GB)
telemt_user_msgs_from_client{user="hello"} 1530773
telemt_user_msgs_to_client{user="hello"} 9201526
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 33134.0 (9h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61603
telemt_connections_bad_total 454
telemt_handshake_timeouts_total 4083
telemt_upstream_connect_attempt_total 53532
telemt_upstream_connect_success_total 53530
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 53532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5301
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53526
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 1078649294 (1.00 GB)
telemt_user_octets_to_client{user="hello"} 54163360923 (50.44 GB)
telemt_user_msgs_from_client{user="hello"} 1248408
telemt_user_msgs_to_client{user="hello"} 8010619
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 33132.9 (9h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57622
telemt_connections_bad_total 89
telemt_handshake_timeouts_total 340
telemt_upstream_connect_attempt_total 55311
telemt_upstream_connect_success_total 55159
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 55311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6545
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 55155
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 835153021 (796.46 MB)
telemt_user_octets_to_client{user="hello"} 37630206522 (35.05 GB)
telemt_user_msgs_from_client{user="hello"} 1147543
telemt_user_msgs_to_client{user="hello"} 7229921
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 33134.2 (9h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84023
telemt_connections_bad_total 7993
telemt_handshake_timeouts_total 1468
telemt_upstream_connect_attempt_total 71363
telemt_upstream_connect_success_total 71115
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 71363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9397
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 214
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 71111
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 2084905091 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 57379705624 (53.44 GB)
telemt_user_msgs_from_client{user="hello"} 1985148
telemt_user_msgs_to_client{user="hello"} 8336043
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 12103.6 (3h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```