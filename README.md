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

# Server Metrics 2026-03-11 10:36:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 72596.5 (20h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216854
telemt_connections_bad_total 3616
telemt_handshake_timeouts_total 4417
telemt_upstream_connect_attempt_total 198969
telemt_upstream_connect_success_total 198907
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 198969
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 181927
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16923
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 198899
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 4299630236 (4.00 GB)
telemt_user_octets_to_client{user="hello"} 115364514618 (107.44 GB)
telemt_user_msgs_from_client{user="hello"} 4705200
telemt_user_msgs_to_client{user="hello"} 8704262
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 72596.0 (20h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84957
telemt_connections_bad_total 793
telemt_handshake_timeouts_total 3171
telemt_upstream_connect_attempt_total 77055
telemt_upstream_connect_success_total 77039
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 77055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10358
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 258
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 77031
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 5027810984 (4.68 GB)
telemt_user_octets_to_client{user="hello"} 56425134119 (52.55 GB)
telemt_user_msgs_from_client{user="hello"} 3239450
telemt_user_msgs_to_client{user="hello"} 14700748
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 72595.8 (20h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117536
telemt_connections_bad_total 1077
telemt_handshake_timeouts_total 5310
telemt_upstream_connect_attempt_total 104480
telemt_upstream_connect_success_total 104476
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 104480
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 92663
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11747
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 104468
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 12300084413 (11.46 GB)
telemt_user_octets_to_client{user="hello"} 86185362363 (80.27 GB)
telemt_user_msgs_from_client{user="hello"} 5890270
telemt_user_msgs_to_client{user="hello"} 16898665
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 72594.8 (20h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129061
telemt_connections_bad_total 324
telemt_handshake_timeouts_total 1231
telemt_upstream_connect_attempt_total 122323
telemt_upstream_connect_success_total 122043
telemt_upstream_connect_fail_total 280
telemt_upstream_connect_attempts_per_request{bucket="1"} 122323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16089
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 63
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 280
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 122035
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 5614712385 (5.23 GB)
telemt_user_octets_to_client{user="hello"} 85809141748 (79.92 GB)
telemt_user_msgs_from_client{user="hello"} 3739073
telemt_user_msgs_to_client{user="hello"} 22576181
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 72596.0 (20h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201553
telemt_connections_bad_total 15750
telemt_handshake_timeouts_total 3415
telemt_upstream_connect_attempt_total 161925
telemt_upstream_connect_success_total 161523
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 161925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 138750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22473
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 300
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 161515
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 3607232474 (3.36 GB)
telemt_user_octets_to_client{user="hello"} 142426856189 (132.65 GB)
telemt_user_msgs_from_client{user="hello"} 3752423
telemt_user_msgs_to_client{user="hello"} 18957842
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 51565.3 (14h 19m)
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