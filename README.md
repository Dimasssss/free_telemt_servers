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

# Server Metrics 2026-03-11 11:42:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 76590.3 (21h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 235159
telemt_connections_bad_total 3631
telemt_handshake_timeouts_total 4502
telemt_upstream_connect_attempt_total 216481
telemt_upstream_connect_success_total 216413
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 216481
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 198006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 216405
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 4508123368 (4.20 GB)
telemt_user_octets_to_client{user="hello"} 121246435579 (112.92 GB)
telemt_user_msgs_from_client{user="hello"} 5043141
telemt_user_msgs_to_client{user="hello"} 9300092
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 76589.8 (21h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91891
telemt_connections_bad_total 848
telemt_handshake_timeouts_total 3263
telemt_upstream_connect_attempt_total 83634
telemt_upstream_connect_success_total 83618
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 83634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11089
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 266
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 83610
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 5131005751 (4.78 GB)
telemt_user_octets_to_client{user="hello"} 57886479164 (53.91 GB)
telemt_user_msgs_from_client{user="hello"} 3353534
telemt_user_msgs_to_client{user="hello"} 15426348
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 76589.8 (21h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128697
telemt_connections_bad_total 1093
telemt_handshake_timeouts_total 6644
telemt_upstream_connect_attempt_total 113689
telemt_upstream_connect_success_total 113675
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 113689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 100864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12716
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 113667
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 12358150949 (11.51 GB)
telemt_user_octets_to_client{user="hello"} 88174977654 (82.12 GB)
telemt_user_msgs_from_client{user="hello"} 6040213
telemt_user_msgs_to_client{user="hello"} 17557230
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 76588.3 (21h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138947
telemt_connections_bad_total 335
telemt_handshake_timeouts_total 1263
telemt_upstream_connect_attempt_total 131861
telemt_upstream_connect_success_total 131554
telemt_upstream_connect_fail_total 306
telemt_upstream_connect_attempts_per_request{bucket="1"} 131860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 114068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17060
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 69
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 306
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 131546
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 5734074035 (5.34 GB)
telemt_user_octets_to_client{user="hello"} 100405022131 (93.51 GB)
telemt_user_msgs_from_client{user="hello"} 3967530
telemt_user_msgs_to_client{user="hello"} 28767456
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 76589.8 (21h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213542
telemt_connections_bad_total 16738
telemt_handshake_timeouts_total 3758
telemt_upstream_connect_attempt_total 172269
telemt_upstream_connect_success_total 171866
telemt_upstream_connect_fail_total 403
telemt_upstream_connect_attempts_per_request{bucket="1"} 172269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 148128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23422
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 316
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 403
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 171858
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 4019436176 (3.74 GB)
telemt_user_octets_to_client{user="hello"} 145703648964 (135.70 GB)
telemt_user_msgs_from_client{user="hello"} 4017470
telemt_user_msgs_to_client{user="hello"} 19757661
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 55559.0 (15h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 426
telemt_connections_bad_total 404
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