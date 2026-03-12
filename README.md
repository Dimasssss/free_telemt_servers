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

# Server Metrics 2026-03-12 07:31:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 35189.4 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105228
telemt_connections_bad_total 2195
telemt_handshake_timeouts_total 2580
telemt_upstream_connect_attempt_total 95686
telemt_upstream_connect_success_total 95160
telemt_upstream_connect_fail_total 524
telemt_upstream_connect_attempts_per_request{bucket="1"} 95684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13904
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 429
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 524
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 95156
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 1032970828 (985.12 MB)
telemt_user_octets_to_client{user="hello"} 27825987302 (25.91 GB)
telemt_user_msgs_from_client{user="hello"} 1445605
telemt_user_msgs_to_client{user="hello"} 3195486
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 35177.4 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43009
telemt_connections_bad_total 219
telemt_handshake_timeouts_total 562
telemt_upstream_connect_attempt_total 40745
telemt_upstream_connect_success_total 40545
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 40744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5469
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 40541
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 340626009 (324.85 MB)
telemt_user_octets_to_client{user="hello"} 17031401927 (15.86 GB)
telemt_user_msgs_from_client{user="hello"} 678972
telemt_user_msgs_to_client{user="hello"} 5504727
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 35151.0 (9h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62876
telemt_connections_bad_total 767
telemt_handshake_timeouts_total 1197
telemt_upstream_connect_attempt_total 56810
telemt_upstream_connect_success_total 56641
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 56810
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9551
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 56637
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 5514603874 (5.14 GB)
telemt_user_octets_to_client{user="hello"} 31821744808 (29.64 GB)
telemt_user_msgs_from_client{user="hello"} 2822642
telemt_user_msgs_to_client{user="hello"} 5714741
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 35176.3 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69493
telemt_connections_bad_total 14308
telemt_handshake_timeouts_total 939
telemt_upstream_connect_attempt_total 51288
telemt_upstream_connect_success_total 49393
telemt_upstream_connect_fail_total 1894
telemt_upstream_connect_attempts_per_request{bucket="1"} 51287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8324
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 248
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1894
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49389
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 1520383379 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 38342962471 (35.71 GB)
telemt_user_msgs_from_client{user="hello"} 1294715
telemt_user_msgs_to_client{user="hello"} 15281791
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 5368.8 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9206
telemt_connections_bad_total 1009
telemt_handshake_timeouts_total 148
telemt_upstream_connect_attempt_total 7802
telemt_upstream_connect_success_total 7667
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 7802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6895
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 663
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7665
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 185092501 (176.52 MB)
telemt_user_octets_to_client{user="hello"} 5162407405 (4.81 GB)
telemt_user_msgs_from_client{user="hello"} 184245
telemt_user_msgs_to_client{user="hello"} 800675
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 35177.2 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67308
telemt_connections_bad_total 1119
telemt_handshake_timeouts_total 352
telemt_upstream_connect_attempt_total 62969
telemt_upstream_connect_success_total 62702
telemt_upstream_connect_fail_total 267
telemt_upstream_connect_attempts_per_request{bucket="1"} 62969
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10303
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 267
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 62698
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 1078504466 (1.00 GB)
telemt_user_octets_to_client{user="hello"} 52419497977 (48.82 GB)
telemt_user_msgs_from_client{user="hello"} 1539937
telemt_user_msgs_to_client{user="hello"} 6803157
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 33
```