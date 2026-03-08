# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

-----

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

# Server Metrics 2026-03-08 20:34:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 48334.9 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108565
telemt_connections_bad_total 5128
telemt_handshake_timeouts_total 1275
telemt_upstream_connect_attempt_total 98743
telemt_upstream_connect_success_total 98708
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 98743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 92903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5742
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 98702
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 2317286997 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 61756162620 (57.51 GB)
telemt_user_msgs_from_client{user="hello"} 2385779
telemt_user_msgs_to_client{user="hello"} 3345482
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 48333.6 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25250
telemt_connections_bad_total 274
telemt_handshake_timeouts_total 129
telemt_upstream_connect_attempt_total 24411
telemt_upstream_connect_success_total 24404
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 24411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1531
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24398
telemt_user_connections_current{user="hello"} 50
telemt_user_octets_from_client{user="hello"} 810635551 (773.08 MB)
telemt_user_octets_to_client{user="hello"} 21835742724 (20.34 GB)
telemt_user_msgs_from_client{user="hello"} 936213
telemt_user_msgs_to_client{user="hello"} 5927234
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 48333.4 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14819
telemt_connections_bad_total 227
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 13420
telemt_upstream_connect_success_total 13344
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 993
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13338
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 1413597179 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 5571780064 (5.19 GB)
telemt_user_msgs_from_client{user="hello"} 642343
telemt_user_msgs_to_client{user="hello"} 942004
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 48333.4 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19372
telemt_connections_bad_total 189
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 18543
telemt_upstream_connect_success_total 18505
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 18543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1382
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18501
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 1059730673 (1010.64 MB)
telemt_user_octets_to_client{user="hello"} 6384367267 (5.95 GB)
telemt_user_msgs_from_client{user="hello"} 562664
telemt_user_msgs_to_client{user="hello"} 1439783
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 48333.5 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28444
telemt_connections_bad_total 9226
telemt_handshake_timeouts_total 237
telemt_upstream_connect_attempt_total 18525
telemt_upstream_connect_success_total 18518
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 18525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3237
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18512
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 343845418 (327.92 MB)
telemt_user_octets_to_client{user="hello"} 15541789121 (14.47 GB)
telemt_user_msgs_from_client{user="hello"} 477497
telemt_user_msgs_to_client{user="hello"} 2039984
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```