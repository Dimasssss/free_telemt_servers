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
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-10 20:24:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 21504.2 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80795
telemt_connections_bad_total 3010
telemt_handshake_timeouts_total 2100
telemt_upstream_connect_attempt_total 72035
telemt_upstream_connect_success_total 72022
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 72035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6314
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 72020
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 2395611797 (2.23 GB)
telemt_user_octets_to_client{user="hello"} 56995233412 (53.08 GB)
telemt_user_msgs_from_client{user="hello"} 2176302
telemt_user_msgs_to_client{user="hello"} 3915594
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 21503.8 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31115
telemt_connections_bad_total 240
telemt_handshake_timeouts_total 486
telemt_upstream_connect_attempt_total 28514
telemt_upstream_connect_success_total 28506
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 28514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4227
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28504
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 1367844545 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 24211645147 (22.55 GB)
telemt_user_msgs_from_client{user="hello"} 1105157
telemt_user_msgs_to_client{user="hello"} 7132839
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 21503.7 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49955
telemt_connections_bad_total 289
telemt_handshake_timeouts_total 3678
telemt_upstream_connect_attempt_total 43103
telemt_upstream_connect_success_total 43102
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 43103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4116
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 43098
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 667529238 (636.61 MB)
telemt_user_octets_to_client{user="hello"} 40955457334 (38.14 GB)
telemt_user_msgs_from_client{user="hello"} 926567
telemt_user_msgs_to_client{user="hello"} 6142946
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 21502.3 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44191
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 314
telemt_upstream_connect_attempt_total 42358
telemt_upstream_connect_success_total 42234
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 42358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4901
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 128
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42230
telemt_user_connections_current{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 727952147 (694.23 MB)
telemt_user_octets_to_client{user="hello"} 32266538832 (30.05 GB)
telemt_user_msgs_from_client{user="hello"} 925126
telemt_user_msgs_to_client{user="hello"} 6156995
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 21503.6 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63257
telemt_connections_bad_total 5652
telemt_handshake_timeouts_total 1330
telemt_upstream_connect_attempt_total 53655
telemt_upstream_connect_success_total 53411
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 53655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46708
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 185
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53409
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 1592502481 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 41947314827 (39.07 GB)
telemt_user_msgs_from_client{user="hello"} 1490498
telemt_user_msgs_to_client{user="hello"} 5781148
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 473.1 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13
telemt_connections_bad_total 13
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```