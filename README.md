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

# Server Metrics 2026-03-11 16:09:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 92572.5 (25h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 317949
telemt_connections_bad_total 5915
telemt_handshake_timeouts_total 5801
telemt_upstream_connect_attempt_total 292169
telemt_upstream_connect_success_total 292088
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 292169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 266945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25082
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 292078
telemt_user_connections_current{user="hello"} 368
telemt_user_octets_from_client{user="hello"} 5474824823 (5.10 GB)
telemt_user_octets_to_client{user="hello"} 141382430079 (131.67 GB)
telemt_user_msgs_from_client{user="hello"} 6293815
telemt_user_msgs_to_client{user="hello"} 11453625
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 92571.7 (25h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125858
telemt_connections_bad_total 974
telemt_handshake_timeouts_total 3421
telemt_upstream_connect_attempt_total 116126
telemt_upstream_connect_success_total 116103
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 116126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 101087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14449
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 567
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 116093
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 6095615839 (5.68 GB)
telemt_user_octets_to_client{user="hello"} 71943958556 (67.00 GB)
telemt_user_msgs_from_client{user="hello"} 4137238
telemt_user_msgs_to_client{user="hello"} 21110076
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 92571.3 (25h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171598
telemt_connections_bad_total 1446
telemt_handshake_timeouts_total 7647
telemt_upstream_connect_attempt_total 153112
telemt_upstream_connect_success_total 153098
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 153112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 135873
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17119
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 153088
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 12766284185 (11.89 GB)
telemt_user_octets_to_client{user="hello"} 132686077192 (123.57 GB)
telemt_user_msgs_from_client{user="hello"} 6934053
telemt_user_msgs_to_client{user="hello"} 29987090
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 92570.3 (25h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 193618
telemt_connections_bad_total 9407
telemt_handshake_timeouts_total 2929
telemt_upstream_connect_attempt_total 173533
telemt_upstream_connect_success_total 173113
telemt_upstream_connect_fail_total 420
telemt_upstream_connect_attempts_per_request{bucket="1"} 173533
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 150985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21560
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 96
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 472
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 420
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 173103
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 10026705046 (9.34 GB)
telemt_user_octets_to_client{user="hello"} 120186363365 (111.93 GB)
telemt_user_msgs_from_client{user="hello"} 6041698
telemt_user_msgs_to_client{user="hello"} 35939309
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 92571.4 (25h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 270212
telemt_connections_bad_total 20266
telemt_handshake_timeouts_total 6375
telemt_upstream_connect_attempt_total 221090
telemt_upstream_connect_success_total 220585
telemt_upstream_connect_fail_total 505
telemt_upstream_connect_attempts_per_request{bucket="1"} 221090
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 191139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29076
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 370
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 505
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 220577
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 5164628948 (4.81 GB)
telemt_user_octets_to_client{user="hello"} 175739164280 (163.67 GB)
telemt_user_msgs_from_client{user="hello"} 5157992
telemt_user_msgs_to_client{user="hello"} 24684626
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 71540.9 (19h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 473
telemt_connections_bad_total 450
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 19
telemt_upstream_connect_success_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```