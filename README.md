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

# Server Metrics 2026-03-11 12:33:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 79664.5 (22h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 251081
telemt_connections_bad_total 3635
telemt_handshake_timeouts_total 4620
telemt_upstream_connect_attempt_total 231614
telemt_upstream_connect_success_total 231541
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 231614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 211892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19592
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 231533
telemt_user_connections_current{user="hello"} 348
telemt_user_octets_from_client{user="hello"} 4656469198 (4.34 GB)
telemt_user_octets_to_client{user="hello"} 124890923388 (116.31 GB)
telemt_user_msgs_from_client{user="hello"} 5263561
telemt_user_msgs_to_client{user="hello"} 9707736
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 79663.8 (22h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97839
telemt_connections_bad_total 896
telemt_handshake_timeouts_total 3314
telemt_upstream_connect_attempt_total 89293
telemt_upstream_connect_success_total 89276
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 89293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 77378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11617
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 281
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 89268
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 5180137815 (4.82 GB)
telemt_user_octets_to_client{user="hello"} 59498153636 (55.41 GB)
telemt_user_msgs_from_client{user="hello"} 3435015
telemt_user_msgs_to_client{user="hello"} 16160095
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 79663.6 (22h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135901
telemt_connections_bad_total 1101
telemt_handshake_timeouts_total 6700
telemt_upstream_connect_attempt_total 120524
telemt_upstream_connect_success_total 120510
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 120524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106879
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13536
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 120502
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 12452312609 (11.60 GB)
telemt_user_octets_to_client{user="hello"} 89883808556 (83.71 GB)
telemt_user_msgs_from_client{user="hello"} 6181588
telemt_user_msgs_to_client{user="hello"} 18096759
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 79662.7 (22h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148514
telemt_connections_bad_total 353
telemt_handshake_timeouts_total 1883
telemt_upstream_connect_attempt_total 140163
telemt_upstream_connect_success_total 139834
telemt_upstream_connect_fail_total 328
telemt_upstream_connect_attempts_per_request{bucket="1"} 140162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18021
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 72
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 372
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 328
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 139826
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 7870971693 (7.33 GB)
telemt_user_octets_to_client{user="hello"} 105087003446 (97.87 GB)
telemt_user_msgs_from_client{user="hello"} 4834661
telemt_user_msgs_to_client{user="hello"} 30557338
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 79663.7 (22h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224505
telemt_connections_bad_total 17552
telemt_handshake_timeouts_total 3881
telemt_upstream_connect_attempt_total 181947
telemt_upstream_connect_success_total 181447
telemt_upstream_connect_fail_total 500
telemt_upstream_connect_attempts_per_request{bucket="1"} 181947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 156707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24407
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 333
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 500
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 181439
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 4684440812 (4.36 GB)
telemt_user_octets_to_client{user="hello"} 149785838920 (139.50 GB)
telemt_user_msgs_from_client{user="hello"} 4372456
telemt_user_msgs_to_client{user="hello"} 20615104
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 58633.2 (16h 17m)
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