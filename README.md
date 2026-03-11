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

# Server Metrics 2026-03-11 08:53:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 66456.6 (18h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 189813
telemt_connections_bad_total 3551
telemt_handshake_timeouts_total 4160
telemt_upstream_connect_attempt_total 173212
telemt_upstream_connect_success_total 173158
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 173212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 158077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 173150
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 3856837680 (3.59 GB)
telemt_user_octets_to_client{user="hello"} 106702767334 (99.37 GB)
telemt_user_msgs_from_client{user="hello"} 4163090
telemt_user_msgs_to_client{user="hello"} 7776576
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 66455.7 (18h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73647
telemt_connections_bad_total 592
telemt_handshake_timeouts_total 3134
telemt_upstream_connect_attempt_total 66453
telemt_upstream_connect_success_total 66438
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 66453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9054
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 66432
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 4916586012 (4.58 GB)
telemt_user_octets_to_client{user="hello"} 53469019445 (49.80 GB)
telemt_user_msgs_from_client{user="hello"} 3078419
telemt_user_msgs_to_client{user="hello"} 13646193
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 66455.4 (18h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101957
telemt_connections_bad_total 926
telemt_handshake_timeouts_total 5194
telemt_upstream_connect_attempt_total 89928
telemt_upstream_connect_success_total 89925
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 89928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9942
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 89917
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 11944343848 (11.12 GB)
telemt_user_octets_to_client{user="hello"} 76343596361 (71.10 GB)
telemt_user_msgs_from_client{user="hello"} 5509817
telemt_user_msgs_to_client{user="hello"} 14941173
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 66454.5 (18h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113273
telemt_connections_bad_total 226
telemt_handshake_timeouts_total 1039
telemt_upstream_connect_attempt_total 107599
telemt_upstream_connect_success_total 107355
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 107599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 92609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14401
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 107347
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 4590007418 (4.27 GB)
telemt_user_octets_to_client{user="hello"} 73726518009 (68.66 GB)
telemt_user_msgs_from_client{user="hello"} 3174241
telemt_user_msgs_to_client{user="hello"} 18673576
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 66455.6 (18h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181735
telemt_connections_bad_total 14601
telemt_handshake_timeouts_total 3083
telemt_upstream_connect_attempt_total 144783
telemt_upstream_connect_success_total 144382
telemt_upstream_connect_fail_total 401
telemt_upstream_connect_attempts_per_request{bucket="1"} 144783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 123746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20362
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 274
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 401
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 144376
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 2868820999 (2.67 GB)
telemt_user_octets_to_client{user="hello"} 132100296402 (123.03 GB)
telemt_user_msgs_from_client{user="hello"} 3249283
telemt_user_msgs_to_client{user="hello"} 17075560
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 45425.1 (12h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 419
telemt_connections_bad_total 397
telemt_handshake_timeouts_total 9
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