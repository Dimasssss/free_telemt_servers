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

# Server Metrics 2026-03-11 11:01:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 74132.9 (20h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223313
telemt_connections_bad_total 3619
telemt_handshake_timeouts_total 4437
telemt_upstream_connect_attempt_total 205176
telemt_upstream_connect_success_total 205112
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 205176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 187618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17437
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 205104
telemt_user_connections_current{user="hello"} 359
telemt_user_octets_from_client{user="hello"} 4376822818 (4.08 GB)
telemt_user_octets_to_client{user="hello"} 117842638759 (109.75 GB)
telemt_user_msgs_from_client{user="hello"} 4831056
telemt_user_msgs_to_client{user="hello"} 8945024
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 74131.8 (20h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87488
telemt_connections_bad_total 815
telemt_handshake_timeouts_total 3201
telemt_upstream_connect_attempt_total 79452
telemt_upstream_connect_success_total 79436
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 79452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10620
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 261
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 79428
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 5052173032 (4.71 GB)
telemt_user_octets_to_client{user="hello"} 56828603020 (52.93 GB)
telemt_user_msgs_from_client{user="hello"} 3274605
telemt_user_msgs_to_client{user="hello"} 14913289
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 74131.8 (20h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121160
telemt_connections_bad_total 1083
telemt_handshake_timeouts_total 5340
telemt_upstream_connect_attempt_total 107754
telemt_upstream_connect_success_total 107750
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 107754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 95574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12109
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 107742
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 12321140466 (11.47 GB)
telemt_user_octets_to_client{user="hello"} 87198667743 (81.21 GB)
telemt_user_msgs_from_client{user="hello"} 5947578
telemt_user_msgs_to_client{user="hello"} 17200066
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 74130.8 (20h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132520
telemt_connections_bad_total 325
telemt_handshake_timeouts_total 1235
telemt_upstream_connect_attempt_total 125681
telemt_upstream_connect_success_total 125385
telemt_upstream_connect_fail_total 296
telemt_upstream_connect_attempts_per_request{bucket="1"} 125681
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16417
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 66
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 342
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 296
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 125377
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 5675294045 (5.29 GB)
telemt_user_octets_to_client{user="hello"} 92433736574 (86.09 GB)
telemt_user_msgs_from_client{user="hello"} 3840501
telemt_user_msgs_to_client{user="hello"} 25234329
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 74131.9 (20h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205693
telemt_connections_bad_total 16081
telemt_handshake_timeouts_total 3434
telemt_upstream_connect_attempt_total 165590
telemt_upstream_connect_success_total 165188
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 165590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 142058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22823
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 307
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 165180
telemt_user_connections_current{user="hello"} 266
telemt_user_octets_from_client{user="hello"} 3692376488 (3.44 GB)
telemt_user_octets_to_client{user="hello"} 143242487079 (133.40 GB)
telemt_user_msgs_from_client{user="hello"} 3818285
telemt_user_msgs_to_client{user="hello"} 19135180
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 53101.2 (14h 45m)
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