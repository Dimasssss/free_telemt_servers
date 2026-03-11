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

# Server Metrics 2026-03-11 10:05:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 70754.2 (19h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208684
telemt_connections_bad_total 3613
telemt_handshake_timeouts_total 4370
telemt_upstream_connect_attempt_total 191192
telemt_upstream_connect_success_total 191132
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 191192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 174716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16359
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 191124
telemt_user_connections_current{user="hello"} 353
telemt_user_octets_from_client{user="hello"} 4109815549 (3.83 GB)
telemt_user_octets_to_client{user="hello"} 112484416911 (104.76 GB)
telemt_user_msgs_from_client{user="hello"} 4508640
telemt_user_msgs_to_client{user="hello"} 8424014
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 70752.8 (19h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81588
telemt_connections_bad_total 782
telemt_handshake_timeouts_total 3148
telemt_upstream_connect_attempt_total 73873
telemt_upstream_connect_success_total 73857
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 73873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9961
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 253
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 73849
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 5007335692 (4.66 GB)
telemt_user_octets_to_client{user="hello"} 55877325168 (52.04 GB)
telemt_user_msgs_from_client{user="hello"} 3194662
telemt_user_msgs_to_client{user="hello"} 14436099
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 70753.9 (19h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113017
telemt_connections_bad_total 1076
telemt_handshake_timeouts_total 5246
telemt_upstream_connect_attempt_total 100279
telemt_upstream_connect_success_total 100275
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 100279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 88927
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11284
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 100267
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 12021325721 (11.20 GB)
telemt_user_octets_to_client{user="hello"} 82529455536 (76.86 GB)
telemt_user_msgs_from_client{user="hello"} 5711495
telemt_user_msgs_to_client{user="hello"} 16026567
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 70751.7 (19h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124174
telemt_connections_bad_total 251
telemt_handshake_timeouts_total 1170
telemt_upstream_connect_attempt_total 117776
telemt_upstream_connect_success_total 117508
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 117776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 101512
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15616
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 60
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 320
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 117500
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 5524046436 (5.14 GB)
telemt_user_octets_to_client{user="hello"} 82818800130 (77.13 GB)
telemt_user_msgs_from_client{user="hello"} 3644395
telemt_user_msgs_to_client{user="hello"} 21494429
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 70752.9 (19h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195660
telemt_connections_bad_total 15418
telemt_handshake_timeouts_total 3370
telemt_upstream_connect_attempt_total 156573
telemt_upstream_connect_success_total 156171
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 156573
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 133994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21887
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 290
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 156163
telemt_user_connections_current{user="hello"} 232
telemt_user_octets_from_client{user="hello"} 3043213634 (2.83 GB)
telemt_user_octets_to_client{user="hello"} 137134855062 (127.72 GB)
telemt_user_msgs_from_client{user="hello"} 3466102
telemt_user_msgs_to_client{user="hello"} 18012765
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 49722.2 (13h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 422
telemt_connections_bad_total 400
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