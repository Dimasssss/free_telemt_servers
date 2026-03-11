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

# Server Metrics 2026-03-11 12:03:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 77821.0 (21h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 241052
telemt_connections_bad_total 3634
telemt_handshake_timeouts_total 4544
telemt_upstream_connect_attempt_total 222058
telemt_upstream_connect_success_total 221988
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 222058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 203186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18745
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 221980
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 4570772250 (4.26 GB)
telemt_user_octets_to_client{user="hello"} 122968181870 (114.52 GB)
telemt_user_msgs_from_client{user="hello"} 5126985
telemt_user_msgs_to_client{user="hello"} 9475345
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 77819.9 (21h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94291
telemt_connections_bad_total 895
telemt_handshake_timeouts_total 3299
telemt_upstream_connect_attempt_total 85859
telemt_upstream_connect_success_total 85843
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 85859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11299
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 269
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 85835
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 5147063407 (4.79 GB)
telemt_user_octets_to_client{user="hello"} 58380240021 (54.37 GB)
telemt_user_msgs_from_client{user="hello"} 3386787
telemt_user_msgs_to_client{user="hello"} 15687342
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 77819.6 (21h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131833
telemt_connections_bad_total 1096
telemt_handshake_timeouts_total 6688
telemt_upstream_connect_attempt_total 116619
telemt_upstream_connect_success_total 116605
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 116619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 103470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13040
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 116597
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 12397402217 (11.55 GB)
telemt_user_octets_to_client{user="hello"} 88459191097 (82.38 GB)
telemt_user_msgs_from_client{user="hello"} 6094088
telemt_user_msgs_to_client{user="hello"} 17677470
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 77818.7 (21h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143245
telemt_connections_bad_total 337
telemt_handshake_timeouts_total 1850
telemt_upstream_connect_attempt_total 135220
telemt_upstream_connect_success_total 134904
telemt_upstream_connect_fail_total 316
telemt_upstream_connect_attempts_per_request{bucket="1"} 135220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17434
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 71
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 316
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 134896
telemt_user_connections_current{user="hello"} 232
telemt_user_octets_from_client{user="hello"} 5966472596 (5.56 GB)
telemt_user_octets_to_client{user="hello"} 100941241249 (94.01 GB)
telemt_user_msgs_from_client{user="hello"} 4089544
telemt_user_msgs_to_client{user="hello"} 28996820
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 77819.9 (21h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217879
telemt_connections_bad_total 17018
telemt_handshake_timeouts_total 3832
telemt_upstream_connect_attempt_total 176113
telemt_upstream_connect_success_total 175709
telemt_upstream_connect_fail_total 404
telemt_upstream_connect_attempts_per_request{bucket="1"} 176113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 151551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23840
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 318
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 404
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 175701
telemt_user_connections_current{user="hello"} 325
telemt_user_octets_from_client{user="hello"} 4641890796 (4.32 GB)
telemt_user_octets_to_client{user="hello"} 147030211385 (136.93 GB)
telemt_user_msgs_from_client{user="hello"} 4284916
telemt_user_msgs_to_client{user="hello"} 20103473
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 56789.3 (15h 46m)
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