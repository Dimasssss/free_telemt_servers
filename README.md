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

# Server Metrics 2026-03-11 01:15:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 38938.4 (10h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107026
telemt_connections_bad_total 3351
telemt_handshake_timeouts_total 2510
telemt_upstream_connect_attempt_total 96450
telemt_upstream_connect_success_total 96416
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 96450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 87696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8666
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 96412
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 2721397377 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 77705007398 (72.37 GB)
telemt_user_msgs_from_client{user="hello"} 2762588
telemt_user_msgs_to_client{user="hello"} 5330529
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 38938.0 (10h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43017
telemt_connections_bad_total 354
telemt_handshake_timeouts_total 1205
telemt_upstream_connect_attempt_total 38960
telemt_upstream_connect_success_total 38951
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 38960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5738
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 38947
telemt_user_connections_current{user="hello"} 38
telemt_user_octets_from_client{user="hello"} 2018423127 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 38595760042 (35.95 GB)
telemt_user_msgs_from_client{user="hello"} 1606340
telemt_user_msgs_to_client{user="hello"} 9569354
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 38937.6 (10h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65673
telemt_connections_bad_total 583
telemt_handshake_timeouts_total 4115
telemt_upstream_connect_attempt_total 57276
telemt_upstream_connect_success_total 57274
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 57276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6017
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 57270
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 8414400221 (7.84 GB)
telemt_user_octets_to_client{user="hello"} 63453253541 (59.10 GB)
telemt_user_msgs_from_client{user="hello"} 3898924
telemt_user_msgs_to_client{user="hello"} 10717641
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 38936.6 (10h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63279
telemt_connections_bad_total 121
telemt_handshake_timeouts_total 530
telemt_upstream_connect_attempt_total 60542
telemt_upstream_connect_success_total 60387
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 60542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7394
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 60383
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 867099722 (826.93 MB)
telemt_user_octets_to_client{user="hello"} 40580207263 (37.79 GB)
telemt_user_msgs_from_client{user="hello"} 1229169
telemt_user_msgs_to_client{user="hello"} 7845895
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 38937.8 (10h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91679
telemt_connections_bad_total 9148
telemt_handshake_timeouts_total 1488
telemt_upstream_connect_attempt_total 77680
telemt_upstream_connect_success_total 77432
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 77680
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10083
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 77428
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 2126631602 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 62130655272 (57.86 GB)
telemt_user_msgs_from_client{user="hello"} 2085844
telemt_user_msgs_to_client{user="hello"} 9038486
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 17907.2 (4h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52
telemt_connections_bad_total 48
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```