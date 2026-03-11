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

# Server Metrics 2026-03-11 03:17:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 46272.3 (12h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119817
telemt_connections_bad_total 3363
telemt_handshake_timeouts_total 2583
telemt_upstream_connect_attempt_total 108400
telemt_upstream_connect_success_total 108361
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 108400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 98696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9611
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 108355
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 2932381276 (2.73 GB)
telemt_user_octets_to_client{user="hello"} 82223227811 (76.58 GB)
telemt_user_msgs_from_client{user="hello"} 2979183
telemt_user_msgs_to_client{user="hello"} 5690752
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 46271.8 (12h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50022
telemt_connections_bad_total 388
telemt_handshake_timeouts_total 2922
telemt_upstream_connect_attempt_total 44048
telemt_upstream_connect_success_total 44039
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 44048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44035
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 2292742806 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 42982554354 (40.03 GB)
telemt_user_msgs_from_client{user="hello"} 1780484
telemt_user_msgs_to_client{user="hello"} 10324889
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 46271.4 (12h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70326
telemt_connections_bad_total 660
telemt_handshake_timeouts_total 4215
telemt_upstream_connect_attempt_total 61532
telemt_upstream_connect_success_total 61530
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 61532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6891
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 61524
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 11745271399 (10.94 GB)
telemt_user_octets_to_client{user="hello"} 70567989614 (65.72 GB)
telemt_user_msgs_from_client{user="hello"} 5135364
telemt_user_msgs_to_client{user="hello"} 13203423
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 46270.2 (12h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70223
telemt_connections_bad_total 149
telemt_handshake_timeouts_total 551
telemt_upstream_connect_attempt_total 67189
telemt_upstream_connect_success_total 67032
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 67189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8484
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 67026
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 1767562151 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 42727812590 (39.79 GB)
telemt_user_msgs_from_client{user="hello"} 1605471
telemt_user_msgs_to_client{user="hello"} 8398860
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 46271.7 (12h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108296
telemt_connections_bad_total 10579
telemt_handshake_timeouts_total 1536
telemt_upstream_connect_attempt_total 92190
telemt_upstream_connect_success_total 91942
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 92190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11576
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 91938
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 2227109719 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 83136207903 (77.43 GB)
telemt_user_msgs_from_client{user="hello"} 2321509
telemt_user_msgs_to_client{user="hello"} 11162846
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 25241.1 (7h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86
telemt_connections_bad_total 82
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```