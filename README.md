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

# Server Metrics 2026-03-12 03:55:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 22199.4 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46529
telemt_connections_bad_total 1944
telemt_handshake_timeouts_total 365
telemt_upstream_connect_attempt_total 42140
telemt_upstream_connect_success_total 42130
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 42140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42126
telemt_user_connections_current{user="hello"} 250
telemt_user_octets_from_client{user="hello"} 433159227 (413.09 MB)
telemt_user_octets_to_client{user="hello"} 13238633101 (12.33 GB)
telemt_user_msgs_from_client{user="hello"} 669917
telemt_user_msgs_to_client{user="hello"} 1639864
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 22187.3 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18273
telemt_connections_bad_total 111
telemt_handshake_timeouts_total 77
telemt_upstream_connect_attempt_total 17441
telemt_upstream_connect_success_total 17441
telemt_upstream_connect_attempts_per_request{bucket="1"} 17441
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2037
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17437
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 151997706 (144.96 MB)
telemt_user_octets_to_client{user="hello"} 9498924516 (8.85 GB)
telemt_user_msgs_from_client{user="hello"} 329830
telemt_user_msgs_to_client{user="hello"} 2630037
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 22160.9 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31751
telemt_connections_bad_total 386
telemt_handshake_timeouts_total 919
telemt_upstream_connect_attempt_total 28092
telemt_upstream_connect_success_total 28092
telemt_upstream_connect_attempts_per_request{bucket="1"} 28092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4796
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28088
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 5255188580 (4.89 GB)
telemt_user_octets_to_client{user="hello"} 17546397517 (16.34 GB)
telemt_user_msgs_from_client{user="hello"} 2327087
telemt_user_msgs_to_client{user="hello"} 3470889
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 22186.4 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33054
telemt_connections_bad_total 8602
telemt_handshake_timeouts_total 728
telemt_upstream_connect_attempt_total 22705
telemt_upstream_connect_success_total 21007
telemt_upstream_connect_fail_total 1698
telemt_upstream_connect_attempts_per_request{bucket="1"} 22705
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3218
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1698
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21003
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 189787825 (181.00 MB)
telemt_user_octets_to_client{user="hello"} 15921622493 (14.83 GB)
telemt_user_msgs_from_client{user="hello"} 386758
telemt_user_msgs_to_client{user="hello"} 6616109
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 22187.2 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26718
telemt_connections_bad_total 155
telemt_handshake_timeouts_total 156
telemt_upstream_connect_attempt_total 24772
telemt_upstream_connect_success_total 24771
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 24772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4089
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24769
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 557110834 (531.30 MB)
telemt_user_octets_to_client{user="hello"} 30509801131 (28.41 GB)
telemt_user_msgs_from_client{user="hello"} 766479
telemt_user_msgs_to_client{user="hello"} 3866001
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 14
```