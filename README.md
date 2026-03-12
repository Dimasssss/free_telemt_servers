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

# Server Metrics 2026-03-12 07:26:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 34882.4 (9h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103593
telemt_connections_bad_total 2194
telemt_handshake_timeouts_total 2578
telemt_upstream_connect_attempt_total 94094
telemt_upstream_connect_success_total 93626
telemt_upstream_connect_fail_total 468
telemt_upstream_connect_attempts_per_request{bucket="1"} 94094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13713
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 398
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 468
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 93622
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 1024569427 (977.11 MB)
telemt_user_octets_to_client{user="hello"} 27582555665 (25.69 GB)
telemt_user_msgs_from_client{user="hello"} 1426818
telemt_user_msgs_to_client{user="hello"} 3157620
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 34870.5 (9h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42160
telemt_connections_bad_total 212
telemt_handshake_timeouts_total 559
telemt_upstream_connect_attempt_total 39948
telemt_upstream_connect_success_total 39771
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 39946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5374
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 39767
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 337026776 (321.41 MB)
telemt_user_octets_to_client{user="hello"} 16919424997 (15.76 GB)
telemt_user_msgs_from_client{user="hello"} 670215
telemt_user_msgs_to_client{user="hello"} 5458015
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 34844.0 (9h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61658
telemt_connections_bad_total 767
telemt_handshake_timeouts_total 1194
telemt_upstream_connect_attempt_total 55870
telemt_upstream_connect_success_total 55726
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 55870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46148
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9417
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 55722
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 5508704188 (5.13 GB)
telemt_user_octets_to_client{user="hello"} 31745223554 (29.57 GB)
telemt_user_msgs_from_client{user="hello"} 2812673
telemt_user_msgs_to_client{user="hello"} 5686183
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 34869.5 (9h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68296
telemt_connections_bad_total 14247
telemt_handshake_timeouts_total 935
telemt_upstream_connect_attempt_total 50240
telemt_upstream_connect_success_total 48372
telemt_upstream_connect_fail_total 1867
telemt_upstream_connect_attempts_per_request{bucket="1"} 50239
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8184
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 237
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1867
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 48368
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 1509597062 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 38218965667 (35.59 GB)
telemt_user_msgs_from_client{user="hello"} 1282693
telemt_user_msgs_to_client{user="hello"} 15228977
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 5061.8 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8697
telemt_connections_bad_total 951
telemt_handshake_timeouts_total 148
telemt_upstream_connect_attempt_total 7365
telemt_upstream_connect_success_total 7250
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 7365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 633
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7248
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 183939470 (175.42 MB)
telemt_user_octets_to_client{user="hello"} 5152311377 (4.80 GB)
telemt_user_msgs_from_client{user="hello"} 181745
telemt_user_msgs_to_client{user="hello"} 795548
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 34870.2 (9h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66362
telemt_connections_bad_total 1118
telemt_handshake_timeouts_total 350
telemt_upstream_connect_attempt_total 62080
telemt_upstream_connect_success_total 61838
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 62080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10170
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 199
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 61834
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 1050968000 (1002.28 MB)
telemt_user_octets_to_client{user="hello"} 52166340800 (48.58 GB)
telemt_user_msgs_from_client{user="hello"} 1515165
telemt_user_msgs_to_client{user="hello"} 6756324
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 24
```