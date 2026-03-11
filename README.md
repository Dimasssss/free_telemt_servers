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

# Server Metrics 2026-03-11 22:49:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 3858.2 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6445
telemt_connections_bad_total 25
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 6199
telemt_upstream_connect_success_total 6196
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 732
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6194
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 73256865 (69.86 MB)
telemt_user_octets_to_client{user="hello"} 2761246606 (2.57 GB)
telemt_user_msgs_from_client{user="hello"} 138450
telemt_user_msgs_to_client{user="hello"} 422934
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 3846.5 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2447
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 2329
telemt_upstream_connect_success_total 2329
telemt_upstream_connect_attempts_per_request{bucket="1"} 2329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 205
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2327
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 12783878 (12.19 MB)
telemt_user_octets_to_client{user="hello"} 330951936 (315.62 MB)
telemt_user_msgs_from_client{user="hello"} 31386
telemt_user_msgs_to_client{user="hello"} 146451
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 3820.0 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5277
telemt_connections_bad_total 244
telemt_handshake_timeouts_total 99
telemt_upstream_connect_attempt_total 4256
telemt_upstream_connect_success_total 4256
telemt_upstream_connect_attempts_per_request{bucket="1"} 4256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 560
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4254
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 24736472 (23.59 MB)
telemt_user_octets_to_client{user="hello"} 2259228913 (2.10 GB)
telemt_user_msgs_from_client{user="hello"} 80247
telemt_user_msgs_to_client{user="hello"} 615702
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 3845.4 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3863
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 52
telemt_upstream_connect_attempt_total 3687
telemt_upstream_connect_success_total 3684
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 530
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3682
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 32949565 (31.42 MB)
telemt_user_octets_to_client{user="hello"} 1202251335 (1.12 GB)
telemt_user_msgs_from_client{user="hello"} 59129
telemt_user_msgs_to_client{user="hello"} 461366
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 3846.7 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3943
telemt_connections_bad_total 777
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 3107
telemt_upstream_connect_success_total 3107
telemt_upstream_connect_attempts_per_request{bucket="1"} 3107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 263
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3105
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 39648122 (37.81 MB)
telemt_user_octets_to_client{user="hello"} 1259323588 (1.17 GB)
telemt_user_msgs_from_client{user="hello"} 45106
telemt_user_msgs_to_client{user="hello"} 231737
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 3846.2 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4092
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 86
telemt_upstream_connect_attempt_total 3420
telemt_upstream_connect_success_total 3420
telemt_upstream_connect_attempts_per_request{bucket="1"} 3420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 574
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3418
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 67982245 (64.83 MB)
telemt_user_octets_to_client{user="hello"} 10467995448 (9.75 GB)
telemt_user_msgs_from_client{user="hello"} 120080
telemt_user_msgs_to_client{user="hello"} 673050
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 5
```