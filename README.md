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

# Server Metrics 2026-03-12 01:56:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 15065.3 (4h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29019
telemt_connections_bad_total 1904
telemt_handshake_timeouts_total 171
telemt_upstream_connect_attempt_total 25848
telemt_upstream_connect_success_total 25841
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 25848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2558
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25839
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 264669643 (252.41 MB)
telemt_user_octets_to_client{user="hello"} 9045509516 (8.42 GB)
telemt_user_msgs_from_client{user="hello"} 457694
telemt_user_msgs_to_client{user="hello"} 1114957
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 15053.5 (4h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12174
telemt_connections_bad_total 56
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 11686
telemt_upstream_connect_success_total 11686
telemt_upstream_connect_attempts_per_request{bucket="1"} 11686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10344
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1337
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11684
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 78700098 (75.05 MB)
telemt_user_octets_to_client{user="hello"} 4305211249 (4.01 GB)
telemt_user_msgs_from_client{user="hello"} 193690
telemt_user_msgs_to_client{user="hello"} 1370112
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 15027.1 (4h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20426
telemt_connections_bad_total 292
telemt_handshake_timeouts_total 875
telemt_upstream_connect_attempt_total 17326
telemt_upstream_connect_success_total 17326
telemt_upstream_connect_attempts_per_request{bucket="1"} 17326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2413
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17324
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 3962561012 (3.69 GB)
telemt_user_octets_to_client{user="hello"} 9323118292 (8.68 GB)
telemt_user_msgs_from_client{user="hello"} 1676761
telemt_user_msgs_to_client{user="hello"} 1942651
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 15052.4 (4h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22766
telemt_connections_bad_total 7539
telemt_handshake_timeouts_total 694
telemt_upstream_connect_attempt_total 13872
telemt_upstream_connect_success_total 13833
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 13872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1842
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13829
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 114157963 (108.87 MB)
telemt_user_octets_to_client{user="hello"} 6583364932 (6.13 GB)
telemt_user_msgs_from_client{user="hello"} 222197
telemt_user_msgs_to_client{user="hello"} 2506910
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 15053.3 (4h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16458
telemt_connections_bad_total 132
telemt_handshake_timeouts_total 128
telemt_upstream_connect_attempt_total 14992
telemt_upstream_connect_success_total 14992
telemt_upstream_connect_attempts_per_request{bucket="1"} 14992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12699
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2289
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14990
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 398660484 (380.19 MB)
telemt_user_octets_to_client{user="hello"} 20936072507 (19.50 GB)
telemt_user_msgs_from_client{user="hello"} 485956
telemt_user_msgs_to_client{user="hello"} 2140861
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 7
```