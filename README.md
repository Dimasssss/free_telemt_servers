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

# Server Metrics 2026-03-11 13:35:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 83351.5 (23h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 271218
telemt_connections_bad_total 3659
telemt_handshake_timeouts_total 4725
telemt_upstream_connect_attempt_total 250732
telemt_upstream_connect_success_total 250656
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 250732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 229483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21114
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 250646
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 4893551243 (4.56 GB)
telemt_user_octets_to_client{user="hello"} 129426507230 (120.54 GB)
telemt_user_msgs_from_client{user="hello"} 5589769
telemt_user_msgs_to_client{user="hello"} 10226965
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 83351.1 (23h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105417
telemt_connections_bad_total 907
telemt_handshake_timeouts_total 3332
telemt_upstream_connect_attempt_total 96588
telemt_upstream_connect_success_total 96569
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 96588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 83707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12505
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 96561
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 5249646064 (4.89 GB)
telemt_user_octets_to_client{user="hello"} 64824135906 (60.37 GB)
telemt_user_msgs_from_client{user="hello"} 3570976
telemt_user_msgs_to_client{user="hello"} 18336262
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 83350.5 (23h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147079
telemt_connections_bad_total 1217
telemt_handshake_timeouts_total 6798
telemt_upstream_connect_attempt_total 130866
telemt_upstream_connect_success_total 130852
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 130866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 116180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14574
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 130844
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 12571906423 (11.71 GB)
telemt_user_octets_to_client{user="hello"} 113794601827 (105.98 GB)
telemt_user_msgs_from_client{user="hello"} 6482631
telemt_user_msgs_to_client{user="hello"} 24492766
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 83349.5 (23h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 162371
telemt_connections_bad_total 3948
telemt_handshake_timeouts_total 1908
telemt_upstream_connect_attempt_total 149870
telemt_upstream_connect_success_total 149513
telemt_upstream_connect_fail_total 357
telemt_upstream_connect_attempts_per_request{bucket="1"} 149870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 129897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19130
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 86
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 400
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 357
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 149505
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 8883905673 (8.27 GB)
telemt_user_octets_to_client{user="hello"} 109063984660 (101.57 GB)
telemt_user_msgs_from_client{user="hello"} 5327734
telemt_user_msgs_to_client{user="hello"} 32160986
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 83350.7 (23h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239031
telemt_connections_bad_total 18523
telemt_handshake_timeouts_total 6130
telemt_upstream_connect_attempt_total 192911
telemt_upstream_connect_success_total 192409
telemt_upstream_connect_fail_total 502
telemt_upstream_connect_attempts_per_request{bucket="1"} 192911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 166409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25659
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 502
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 192401
telemt_user_connections_current{user="hello"} 261
telemt_user_octets_from_client{user="hello"} 4784578974 (4.46 GB)
telemt_user_octets_to_client{user="hello"} 155220173481 (144.56 GB)
telemt_user_msgs_from_client{user="hello"} 4552521
telemt_user_msgs_to_client{user="hello"} 21470124
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 62320.1 (17h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 440
telemt_connections_bad_total 418
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