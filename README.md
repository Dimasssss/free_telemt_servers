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

# Server Metrics 2026-03-12 03:17:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 19929.9 (5h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40421
telemt_connections_bad_total 1933
telemt_handshake_timeouts_total 322
telemt_upstream_connect_attempt_total 36372
telemt_upstream_connect_success_total 36365
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 36372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4294
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 36363
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 336117344 (320.55 MB)
telemt_user_octets_to_client{user="hello"} 11028292896 (10.27 GB)
telemt_user_msgs_from_client{user="hello"} 574018
telemt_user_msgs_to_client{user="hello"} 1388132
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 19918.0 (5h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16303
telemt_connections_bad_total 105
telemt_handshake_timeouts_total 71
telemt_upstream_connect_attempt_total 15577
telemt_upstream_connect_success_total 15577
telemt_upstream_connect_attempts_per_request{bucket="1"} 15577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1783
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15575
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 135596868 (129.32 MB)
telemt_user_octets_to_client{user="hello"} 8946039106 (8.33 GB)
telemt_user_msgs_from_client{user="hello"} 292683
telemt_user_msgs_to_client{user="hello"} 2387601
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 19891.5 (5h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27991
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 911
telemt_upstream_connect_attempt_total 24496
telemt_upstream_connect_success_total 24496
telemt_upstream_connect_attempts_per_request{bucket="1"} 24496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3877
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24492
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 5234106949 (4.87 GB)
telemt_user_octets_to_client{user="hello"} 15855750095 (14.77 GB)
telemt_user_msgs_from_client{user="hello"} 2261840
telemt_user_msgs_to_client{user="hello"} 3163074
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 19917.0 (5h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29979
telemt_connections_bad_total 8512
telemt_handshake_timeouts_total 711
telemt_upstream_connect_attempt_total 19888
telemt_upstream_connect_success_total 18190
telemt_upstream_connect_fail_total 1698
telemt_upstream_connect_attempts_per_request{bucket="1"} 19888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2689
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1698
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18186
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 166296304 (158.59 MB)
telemt_user_octets_to_client{user="hello"} 12203822282 (11.37 GB)
telemt_user_msgs_from_client{user="hello"} 329199
telemt_user_msgs_to_client{user="hello"} 4920363
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 19917.6 (5h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22628
telemt_connections_bad_total 144
telemt_handshake_timeouts_total 142
telemt_upstream_connect_attempt_total 20924
telemt_upstream_connect_success_total 20923
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 20924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3322
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20921
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 487544748 (464.96 MB)
telemt_user_octets_to_client{user="hello"} 29473757603 (27.45 GB)
telemt_user_msgs_from_client{user="hello"} 683064
telemt_user_msgs_to_client{user="hello"} 3684775
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 11
```