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

# Server Metrics 2026-03-11 00:29:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 36189.7 (10h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103463
telemt_connections_bad_total 3341
telemt_handshake_timeouts_total 2491
telemt_upstream_connect_attempt_total 93058
telemt_upstream_connect_success_total 93024
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 93058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 84580
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8391
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 93020
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 2692050088 (2.51 GB)
telemt_user_octets_to_client{user="hello"} 75859850428 (70.65 GB)
telemt_user_msgs_from_client{user="hello"} 2704842
telemt_user_msgs_to_client{user="hello"} 5178211
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 36188.9 (10h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40913
telemt_connections_bad_total 342
telemt_handshake_timeouts_total 975
telemt_upstream_connect_attempt_total 37214
telemt_upstream_connect_success_total 37205
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 37214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5549
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 37201
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 2009824749 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 38481427288 (35.84 GB)
telemt_user_msgs_from_client{user="hello"} 1584970
telemt_user_msgs_to_client{user="hello"} 9512244
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 36188.8 (10h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63731
telemt_connections_bad_total 457
telemt_handshake_timeouts_total 4091
telemt_upstream_connect_attempt_total 55571
telemt_upstream_connect_success_total 55569
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 55571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5689
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 55565
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 8168802735 (7.61 GB)
telemt_user_octets_to_client{user="hello"} 57764919761 (53.80 GB)
telemt_user_msgs_from_client{user="hello"} 3757212
telemt_user_msgs_to_client{user="hello"} 8574867
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 36187.7 (10h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60794
telemt_connections_bad_total 111
telemt_handshake_timeouts_total 526
telemt_upstream_connect_attempt_total 58167
telemt_upstream_connect_success_total 58013
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 58167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7033
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 58009
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 849117423 (809.78 MB)
telemt_user_octets_to_client{user="hello"} 38348478782 (35.71 GB)
telemt_user_msgs_from_client{user="hello"} 1182155
telemt_user_msgs_to_client{user="hello"} 7463780
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 36189.1 (10h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88228
telemt_connections_bad_total 8606
telemt_handshake_timeouts_total 1472
telemt_upstream_connect_attempt_total 74853
telemt_upstream_connect_success_total 74605
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 74853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9873
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 74601
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 2107241841 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 60091102400 (55.96 GB)
telemt_user_msgs_from_client{user="hello"} 2038523
telemt_user_msgs_to_client{user="hello"} 8582197
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 15158.4 (4h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45
telemt_connections_bad_total 41
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```