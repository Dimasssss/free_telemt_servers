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

# Server Metrics 2026-03-11 13:25:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 82736.2 (22h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268044
telemt_connections_bad_total 3646
telemt_handshake_timeouts_total 4719
telemt_upstream_connect_attempt_total 247730
telemt_upstream_connect_success_total 247655
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 247730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 226752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20844
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 247647
telemt_user_connections_current{user="hello"} 336
telemt_user_octets_from_client{user="hello"} 4870241307 (4.54 GB)
telemt_user_octets_to_client{user="hello"} 128851455061 (120.00 GB)
telemt_user_msgs_from_client{user="hello"} 5541302
telemt_user_msgs_to_client{user="hello"} 10150479
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 82735.5 (22h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104248
telemt_connections_bad_total 906
telemt_handshake_timeouts_total 3331
telemt_upstream_connect_attempt_total 95460
telemt_upstream_connect_success_total 95441
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 95460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 82749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 338
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 95433
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 5230853952 (4.87 GB)
telemt_user_octets_to_client{user="hello"} 64204393021 (59.80 GB)
telemt_user_msgs_from_client{user="hello"} 3548525
telemt_user_msgs_to_client{user="hello"} 18130688
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 82735.2 (22h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145130
telemt_connections_bad_total 1161
telemt_handshake_timeouts_total 6794
telemt_upstream_connect_attempt_total 129227
telemt_upstream_connect_success_total 129213
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 129227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 114672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14443
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 129205
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 12550814403 (11.69 GB)
telemt_user_octets_to_client{user="hello"} 110007754629 (102.45 GB)
telemt_user_msgs_from_client{user="hello"} 6433444
telemt_user_msgs_to_client{user="hello"} 23390814
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 82734.1 (22h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160005
telemt_connections_bad_total 3240
telemt_handshake_timeouts_total 1905
telemt_upstream_connect_attempt_total 148420
telemt_upstream_connect_success_total 148070
telemt_upstream_connect_fail_total 350
telemt_upstream_connect_attempts_per_request{bucket="1"} 148420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 128650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18938
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 85
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 397
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 350
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 148062
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 8720309680 (8.12 GB)
telemt_user_octets_to_client{user="hello"} 108872341920 (101.40 GB)
telemt_user_msgs_from_client{user="hello"} 5253188
telemt_user_msgs_to_client{user="hello"} 32092165
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 82735.4 (22h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236975
telemt_connections_bad_total 18396
telemt_handshake_timeouts_total 6129
telemt_upstream_connect_attempt_total 191046
telemt_upstream_connect_success_total 190544
telemt_upstream_connect_fail_total 502
telemt_upstream_connect_attempts_per_request{bucket="1"} 191046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 164783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25420
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 502
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 190536
telemt_user_connections_current{user="hello"} 293
telemt_user_octets_from_client{user="hello"} 4770843984 (4.44 GB)
telemt_user_octets_to_client{user="hello"} 155000052128 (144.36 GB)
telemt_user_msgs_from_client{user="hello"} 4529462
telemt_user_msgs_to_client{user="hello"} 21419753
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 61704.8 (17h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 440
telemt_connections_bad_total 418
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