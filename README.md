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

# Server Metrics 2026-03-11 07:16:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 60640.1 (16h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165079
telemt_connections_bad_total 3522
telemt_handshake_timeouts_total 3992
telemt_upstream_connect_attempt_total 149356
telemt_upstream_connect_success_total 149309
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 149356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 136180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13073
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 149301
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 3537606924 (3.29 GB)
telemt_user_octets_to_client{user="hello"} 98688357401 (91.91 GB)
telemt_user_msgs_from_client{user="hello"} 3758019
telemt_user_msgs_to_client{user="hello"} 7065792
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 60639.5 (16h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65027
telemt_connections_bad_total 459
telemt_handshake_timeouts_total 3067
telemt_upstream_connect_attempt_total 58314
telemt_upstream_connect_success_total 58300
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 58314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8211
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 232
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 58294
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 4662757503 (4.34 GB)
telemt_user_octets_to_client{user="hello"} 50439803788 (46.98 GB)
telemt_user_msgs_from_client{user="hello"} 2880745
telemt_user_msgs_to_client{user="hello"} 12255713
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 60639.3 (16h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88224
telemt_connections_bad_total 743
telemt_handshake_timeouts_total 4637
telemt_upstream_connect_attempt_total 77619
telemt_upstream_connect_success_total 77616
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 77619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8643
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 77610
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 11858889558 (11.04 GB)
telemt_user_octets_to_client{user="hello"} 74452984051 (69.34 GB)
telemt_user_msgs_from_client{user="hello"} 5336918
telemt_user_msgs_to_client{user="hello"} 14288134
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 60638.1 (16h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95573
telemt_connections_bad_total 217
telemt_handshake_timeouts_total 656
telemt_upstream_connect_attempt_total 91602
telemt_upstream_connect_success_total 91399
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 91602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12005
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 49
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 257
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 91393
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 2108360918 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 61139890015 (56.94 GB)
telemt_user_msgs_from_client{user="hello"} 2081224
telemt_user_msgs_to_client{user="hello"} 15076061
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 60639.3 (16h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161346
telemt_connections_bad_total 13383
telemt_handshake_timeouts_total 1843
telemt_upstream_connect_attempt_total 128203
telemt_upstream_connect_success_total 127953
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 128203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17836
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 127947
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 2562105910 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 123822095231 (115.32 GB)
telemt_user_msgs_from_client{user="hello"} 2953804
telemt_user_msgs_to_client{user="hello"} 15774815
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 39608.8 (11h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219
telemt_connections_bad_total 199
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 15
telemt_upstream_connect_success_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```