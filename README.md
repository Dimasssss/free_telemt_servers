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

# Server Metrics 2026-03-11 22:43:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 3551.4 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5566
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 53
telemt_upstream_connect_attempt_total 5379
telemt_upstream_connect_success_total 5378
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5379
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 620
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5376
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 54486178 (51.96 MB)
telemt_user_octets_to_client{user="hello"} 2537395026 (2.36 GB)
telemt_user_msgs_from_client{user="hello"} 121574
telemt_user_msgs_to_client{user="hello"} 383980
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 3539.6 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2226
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 2126
telemt_upstream_connect_success_total 2126
telemt_upstream_connect_attempts_per_request{bucket="1"} 2126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 180
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2124
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 11675245 (11.13 MB)
telemt_user_octets_to_client{user="hello"} 301208216 (287.25 MB)
telemt_user_msgs_from_client{user="hello"} 28588
telemt_user_msgs_to_client{user="hello"} 132479
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 3513.2 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5085
telemt_connections_bad_total 244
telemt_handshake_timeouts_total 90
telemt_upstream_connect_attempt_total 4083
telemt_upstream_connect_success_total 4083
telemt_upstream_connect_attempts_per_request{bucket="1"} 4083
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 554
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4081
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 24063995 (22.95 MB)
telemt_user_octets_to_client{user="hello"} 2250332982 (2.10 GB)
telemt_user_msgs_from_client{user="hello"} 77122
telemt_user_msgs_to_client{user="hello"} 610773
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 3538.6 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3600
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 52
telemt_upstream_connect_attempt_total 3433
telemt_upstream_connect_success_total 3430
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2911
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 509
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3428
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 30830972 (29.40 MB)
telemt_user_octets_to_client{user="hello"} 1073490170 (1023.76 MB)
telemt_user_msgs_from_client{user="hello"} 53329
telemt_user_msgs_to_client{user="hello"} 404979
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 3539.9 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3728
telemt_connections_bad_total 698
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 2974
telemt_upstream_connect_success_total 2974
telemt_upstream_connect_attempts_per_request{bucket="1"} 2974
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2712
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 257
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2972
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 38726191 (36.93 MB)
telemt_user_octets_to_client{user="hello"} 1211318120 (1.13 GB)
telemt_user_msgs_from_client{user="hello"} 42705
telemt_user_msgs_to_client{user="hello"} 224896
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 3539.5 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3776
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 86
telemt_upstream_connect_attempt_total 3130
telemt_upstream_connect_success_total 3130
telemt_upstream_connect_attempts_per_request{bucket="1"} 3130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 520
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3128
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 66070162 (63.01 MB)
telemt_user_octets_to_client{user="hello"} 10355271243 (9.64 GB)
telemt_user_msgs_from_client{user="hello"} 115587
telemt_user_msgs_to_client{user="hello"} 647666
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 6
```