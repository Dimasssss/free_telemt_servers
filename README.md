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

# Server Metrics 2026-03-11 00:44:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 37106.1 (10h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104627
telemt_connections_bad_total 3344
telemt_handshake_timeouts_total 2494
telemt_upstream_connect_attempt_total 94172
telemt_upstream_connect_success_total 94138
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 94172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 85573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8511
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 94134
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 2706584495 (2.52 GB)
telemt_user_octets_to_client{user="hello"} 77012866047 (71.72 GB)
telemt_user_msgs_from_client{user="hello"} 2733528
telemt_user_msgs_to_client{user="hello"} 5231721
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 37105.5 (10h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41585
telemt_connections_bad_total 342
telemt_handshake_timeouts_total 980
telemt_upstream_connect_attempt_total 37849
telemt_upstream_connect_success_total 37840
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 37849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5642
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 37836
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 2013220428 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 38528008956 (35.88 GB)
telemt_user_msgs_from_client{user="hello"} 1593951
telemt_user_msgs_to_client{user="hello"} 9538124
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 37105.3 (10h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64379
telemt_connections_bad_total 525
telemt_handshake_timeouts_total 4111
telemt_upstream_connect_attempt_total 56116
telemt_upstream_connect_success_total 56114
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 56116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5799
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 56110
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 8175836592 (7.61 GB)
telemt_user_octets_to_client{user="hello"} 59309834246 (55.24 GB)
telemt_user_msgs_from_client{user="hello"} 3776761
telemt_user_msgs_to_client{user="hello"} 9080622
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 37104.1 (10h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61593
telemt_connections_bad_total 111
telemt_handshake_timeouts_total 526
telemt_upstream_connect_attempt_total 58937
telemt_upstream_connect_success_total 58783
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 58937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7129
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 58779
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 851598569 (812.15 MB)
telemt_user_octets_to_client{user="hello"} 38375964332 (35.74 GB)
telemt_user_msgs_from_client{user="hello"} 1188499
telemt_user_msgs_to_client{user="hello"} 7475729
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 37105.5 (10h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89365
telemt_connections_bad_total 8774
telemt_handshake_timeouts_total 1486
telemt_upstream_connect_attempt_total 75785
telemt_upstream_connect_success_total 75537
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 75785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9953
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 75533
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 2115362670 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 61307927902 (57.10 GB)
telemt_user_msgs_from_client{user="hello"} 2058452
telemt_user_msgs_to_client{user="hello"} 8881754
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 16075.1 (4h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46
telemt_connections_bad_total 42
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```