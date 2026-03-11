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

# Server Metrics 2026-03-11 05:50:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 55442.3 (15h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144804
telemt_connections_bad_total 3480
telemt_handshake_timeouts_total 3735
telemt_upstream_connect_attempt_total 130446
telemt_upstream_connect_success_total 130402
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 130446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 118959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11388
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 130396
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 3160682796 (2.94 GB)
telemt_user_octets_to_client{user="hello"} 89973274777 (83.79 GB)
telemt_user_msgs_from_client{user="hello"} 3347201
telemt_user_msgs_to_client{user="hello"} 6334958
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 55441.9 (15h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58026
telemt_connections_bad_total 447
telemt_handshake_timeouts_total 2978
telemt_upstream_connect_attempt_total 51651
telemt_upstream_connect_success_total 51639
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 51651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7608
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51633
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 4535183726 (4.22 GB)
telemt_user_octets_to_client{user="hello"} 47516498937 (44.25 GB)
telemt_user_msgs_from_client{user="hello"} 2734660
telemt_user_msgs_to_client{user="hello"} 11236984
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 55441.4 (15h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79076
telemt_connections_bad_total 726
telemt_handshake_timeouts_total 4344
telemt_upstream_connect_attempt_total 69563
telemt_upstream_connect_success_total 69560
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 69563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7824
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 69554
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 11798578074 (10.99 GB)
telemt_user_octets_to_client{user="hello"} 71538565272 (66.63 GB)
telemt_user_msgs_from_client{user="hello"} 5219745
telemt_user_msgs_to_client{user="hello"} 13489504
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 55440.4 (15h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83682
telemt_connections_bad_total 171
telemt_handshake_timeouts_total 622
telemt_upstream_connect_attempt_total 80104
telemt_upstream_connect_success_total 79928
telemt_upstream_connect_fail_total 176
telemt_upstream_connect_attempts_per_request{bucket="1"} 80104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10525
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 176
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 79922
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 1871810546 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 53475509618 (49.80 GB)
telemt_user_msgs_from_client{user="hello"} 1822118
telemt_user_msgs_to_client{user="hello"} 12434161
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 55441.7 (15h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139433
telemt_connections_bad_total 12392
telemt_handshake_timeouts_total 1745
telemt_upstream_connect_attempt_total 113247
telemt_upstream_connect_success_total 112998
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 113247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 96965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15800
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 112992
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 2445109429 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 108549969456 (101.10 GB)
telemt_user_msgs_from_client{user="hello"} 2713899
telemt_user_msgs_to_client{user="hello"} 14305822
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 34411.1 (9h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153
telemt_connections_bad_total 144
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```