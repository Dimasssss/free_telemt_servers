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

# Server Metrics 2026-03-11 23:19:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 5698.4 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9446
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 66
telemt_upstream_connect_attempt_total 9057
telemt_upstream_connect_success_total 9053
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 9057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1073
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9051
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 132622413 (126.48 MB)
telemt_user_octets_to_client{user="hello"} 4254758959 (3.96 GB)
telemt_user_msgs_from_client{user="hello"} 216838
telemt_user_msgs_to_client{user="hello"} 596032
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 5686.7 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4151
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 3987
telemt_upstream_connect_success_total 3987
telemt_upstream_connect_attempts_per_request{bucket="1"} 3987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 517
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3985
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 18060393 (17.22 MB)
telemt_user_octets_to_client{user="hello"} 498203583 (475.12 MB)
telemt_user_msgs_from_client{user="hello"} 44926
telemt_user_msgs_to_client{user="hello"} 216645
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 5660.4 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7000
telemt_connections_bad_total 251
telemt_handshake_timeouts_total 233
telemt_upstream_connect_attempt_total 5746
telemt_upstream_connect_success_total 5746
telemt_upstream_connect_attempts_per_request{bucket="1"} 5746
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5025
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 721
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5744
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 36479069 (34.79 MB)
telemt_user_octets_to_client{user="hello"} 3206095163 (2.99 GB)
telemt_user_msgs_from_client{user="hello"} 113717
telemt_user_msgs_to_client{user="hello"} 801672
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 5685.8 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5432
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 57
telemt_upstream_connect_attempt_total 5211
telemt_upstream_connect_success_total 5204
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 5211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 670
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5202
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 41659937 (39.73 MB)
telemt_user_octets_to_client{user="hello"} 1935348376 (1.80 GB)
telemt_user_msgs_from_client{user="hello"} 81037
telemt_user_msgs_to_client{user="hello"} 714162
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 5687.0 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5864
telemt_connections_bad_total 1408
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 4341
telemt_upstream_connect_success_total 4338
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 4341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 375
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4336
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 47361948 (45.17 MB)
telemt_user_octets_to_client{user="hello"} 1608514503 (1.50 GB)
telemt_user_msgs_from_client{user="hello"} 64481
telemt_user_msgs_to_client{user="hello"} 297097
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 5686.6 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5582
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 92
telemt_upstream_connect_attempt_total 4803
telemt_upstream_connect_success_total 4803
telemt_upstream_connect_attempts_per_request{bucket="1"} 4803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4015
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 788
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4801
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 85103401 (81.16 MB)
telemt_user_octets_to_client{user="hello"} 11577592500 (10.78 GB)
telemt_user_msgs_from_client{user="hello"} 157977
telemt_user_msgs_to_client{user="hello"} 867195
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 6
```