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

# Server Metrics 2026-03-11 07:57:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 63088.7 (17h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175197
telemt_connections_bad_total 3538
telemt_handshake_timeouts_total 4058
telemt_upstream_connect_attempt_total 159104
telemt_upstream_connect_success_total 159053
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 159104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 145231
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13765
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 159045
telemt_user_connections_current{user="hello"} 306
telemt_user_octets_from_client{user="hello"} 3659983981 (3.41 GB)
telemt_user_octets_to_client{user="hello"} 101816619071 (94.82 GB)
telemt_user_msgs_from_client{user="hello"} 3912156
telemt_user_msgs_to_client{user="hello"} 7353467
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 63088.1 (17h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68329
telemt_connections_bad_total 581
telemt_handshake_timeouts_total 3083
telemt_upstream_connect_attempt_total 61368
telemt_upstream_connect_success_total 61354
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 61368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8478
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 234
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 61348
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 4809201972 (4.48 GB)
telemt_user_octets_to_client{user="hello"} 51658595681 (48.11 GB)
telemt_user_msgs_from_client{user="hello"} 2972887
telemt_user_msgs_to_client{user="hello"} 12745482
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 63087.9 (17h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94873
telemt_connections_bad_total 885
telemt_handshake_timeouts_total 5153
telemt_upstream_connect_attempt_total 83231
telemt_upstream_connect_success_total 83228
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 83231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9240
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 83222
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 11909054643 (11.09 GB)
telemt_user_octets_to_client{user="hello"} 75049995722 (69.90 GB)
telemt_user_msgs_from_client{user="hello"} 5412379
telemt_user_msgs_to_client{user="hello"} 14545260
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 63086.8 (17h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102453
telemt_connections_bad_total 220
telemt_handshake_timeouts_total 697
telemt_upstream_connect_attempt_total 98001
telemt_upstream_connect_success_total 97783
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 97999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 84587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12875
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 269
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 97775
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 3905554177 (3.64 GB)
telemt_user_octets_to_client{user="hello"} 66032490910 (61.50 GB)
telemt_user_msgs_from_client{user="hello"} 2790203
telemt_user_msgs_to_client{user="hello"} 16371149
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 63088.1 (17h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169681
telemt_connections_bad_total 13982
telemt_handshake_timeouts_total 2111
telemt_upstream_connect_attempt_total 135279
telemt_upstream_connect_success_total 135029
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 135279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 115976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18809
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 135023
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 2613594592 (2.43 GB)
telemt_user_octets_to_client{user="hello"} 128210166869 (119.41 GB)
telemt_user_msgs_from_client{user="hello"} 3058349
telemt_user_msgs_to_client{user="hello"} 16361988
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 42057.5 (11h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233
telemt_connections_bad_total 212
telemt_handshake_timeouts_total 9
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