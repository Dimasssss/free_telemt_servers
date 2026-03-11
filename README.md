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

# Server Metrics 2026-03-11 23:41:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 6961.0 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11347
telemt_connections_bad_total 174
telemt_handshake_timeouts_total 73
telemt_upstream_connect_attempt_total 10819
telemt_upstream_connect_success_total 10815
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 10819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1263
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10813
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 154361604 (147.21 MB)
telemt_user_octets_to_client{user="hello"} 5407758280 (5.04 GB)
telemt_user_msgs_from_client{user="hello"} 266284
telemt_user_msgs_to_client{user="hello"} 699925
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 6949.1 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4862
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 4658
telemt_upstream_connect_success_total 4658
telemt_upstream_connect_attempts_per_request{bucket="1"} 4658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 614
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4656
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 22868247 (21.81 MB)
telemt_user_octets_to_client{user="hello"} 631639575 (602.38 MB)
telemt_user_msgs_from_client{user="hello"} 54617
telemt_user_msgs_to_client{user="hello"} 276887
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 6922.8 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9211
telemt_connections_bad_total 267
telemt_handshake_timeouts_total 751
telemt_upstream_connect_attempt_total 6885
telemt_upstream_connect_success_total 6885
telemt_upstream_connect_attempts_per_request{bucket="1"} 6885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 896
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6883
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 47645470 (45.44 MB)
telemt_user_octets_to_client{user="hello"} 5125389967 (4.77 GB)
telemt_user_msgs_from_client{user="hello"} 148055
telemt_user_msgs_to_client{user="hello"} 1221986
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 6948.0 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6538
telemt_connections_bad_total 60
telemt_handshake_timeouts_total 58
telemt_upstream_connect_attempt_total 6229
telemt_upstream_connect_success_total 6222
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 6229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 770
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6220
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 47545160 (45.34 MB)
telemt_user_octets_to_client{user="hello"} 2411702098 (2.25 GB)
telemt_user_msgs_from_client{user="hello"} 95634
telemt_user_msgs_to_client{user="hello"} 915707
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 6948.9 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6668
telemt_connections_bad_total 58
telemt_handshake_timeouts_total 99
telemt_upstream_connect_attempt_total 5778
telemt_upstream_connect_success_total 5778
telemt_upstream_connect_attempts_per_request{bucket="1"} 5778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 978
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5776
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 91101513 (86.88 MB)
telemt_user_octets_to_client{user="hello"} 11801620505 (10.99 GB)
telemt_user_msgs_from_client{user="hello"} 170981
telemt_user_msgs_to_client{user="hello"} 900041
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 6
```