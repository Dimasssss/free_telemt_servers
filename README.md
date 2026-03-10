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

# Server Metrics 2026-03-10 23:33:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 32829.3 (9h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98955
telemt_connections_bad_total 3322
telemt_handshake_timeouts_total 2219
telemt_upstream_connect_attempt_total 89054
telemt_upstream_connect_success_total 89022
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 89054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7941
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 89018
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 2616195891 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 73070073373 (68.05 GB)
telemt_user_msgs_from_client{user="hello"} 2594373
telemt_user_msgs_to_client{user="hello"} 4976217
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 32829.1 (9h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38616
telemt_connections_bad_total 334
telemt_handshake_timeouts_total 891
telemt_upstream_connect_attempt_total 35105
telemt_upstream_connect_success_total 35096
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 35105
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 35092
telemt_user_connections_current{user="hello"} 64
telemt_user_octets_from_client{user="hello"} 1860690726 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 36905263710 (34.37 GB)
telemt_user_msgs_from_client{user="hello"} 1492280
telemt_user_msgs_to_client{user="hello"} 9183006
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 32828.4 (9h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61401
telemt_connections_bad_total 453
telemt_handshake_timeouts_total 4083
telemt_upstream_connect_attempt_total 53337
telemt_upstream_connect_success_total 53335
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 53337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5278
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53331
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 1076715756 (1.00 GB)
telemt_user_octets_to_client{user="hello"} 53442761762 (49.77 GB)
telemt_user_msgs_from_client{user="hello"} 1242900
telemt_user_msgs_to_client{user="hello"} 7910031
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 32827.4 (9h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57228
telemt_connections_bad_total 88
telemt_handshake_timeouts_total 337
telemt_upstream_connect_attempt_total 54953
telemt_upstream_connect_success_total 54801
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 54953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6487
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 54797
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 833956013 (795.32 MB)
telemt_user_octets_to_client{user="hello"} 37601298287 (35.02 GB)
telemt_user_msgs_from_client{user="hello"} 1144603
telemt_user_msgs_to_client{user="hello"} 7220155
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 32828.7 (9h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83749
telemt_connections_bad_total 7938
telemt_handshake_timeouts_total 1468
telemt_upstream_connect_attempt_total 71148
telemt_upstream_connect_success_total 70900
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 71148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9377
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 70896
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 2083657072 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 57329506858 (53.39 GB)
telemt_user_msgs_from_client{user="hello"} 1982078
telemt_user_msgs_to_client{user="hello"} 8323425
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 11798.2 (3h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```