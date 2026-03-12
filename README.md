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

# Server Metrics 2026-03-12 04:27:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 24145.1 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52632
telemt_connections_bad_total 1984
telemt_handshake_timeouts_total 561
telemt_upstream_connect_attempt_total 47751
telemt_upstream_connect_success_total 47737
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 47751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6204
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 47733
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 521855737 (497.68 MB)
telemt_user_octets_to_client{user="hello"} 15097408648 (14.06 GB)
telemt_user_msgs_from_client{user="hello"} 761279
telemt_user_msgs_to_client{user="hello"} 1821531
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 24133.4 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20494
telemt_connections_bad_total 138
telemt_handshake_timeouts_total 105
telemt_upstream_connect_attempt_total 19495
telemt_upstream_connect_success_total 19492
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 19495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2380
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19488
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 175833273 (167.69 MB)
telemt_user_octets_to_client{user="hello"} 11394188743 (10.61 GB)
telemt_user_msgs_from_client{user="hello"} 370225
telemt_user_msgs_to_client{user="hello"} 3120756
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 24106.8 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35070
telemt_connections_bad_total 446
telemt_handshake_timeouts_total 933
telemt_upstream_connect_attempt_total 31163
telemt_upstream_connect_success_total 31163
telemt_upstream_connect_attempts_per_request{bucket="1"} 31163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31159
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 5283211193 (4.92 GB)
telemt_user_octets_to_client{user="hello"} 20634328658 (19.22 GB)
telemt_user_msgs_from_client{user="hello"} 2399391
telemt_user_msgs_to_client{user="hello"} 3744039
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 24132.2 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35827
telemt_connections_bad_total 8656
telemt_handshake_timeouts_total 748
telemt_upstream_connect_attempt_total 25312
telemt_upstream_connect_success_total 23612
telemt_upstream_connect_fail_total 1700
telemt_upstream_connect_attempts_per_request{bucket="1"} 25312
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3710
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1700
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23608
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 226946448 (216.43 MB)
telemt_user_octets_to_client{user="hello"} 19426811495 (18.09 GB)
telemt_user_msgs_from_client{user="hello"} 451262
telemt_user_msgs_to_client{user="hello"} 8125619
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 24133.0 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31093
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 171
telemt_upstream_connect_attempt_total 28957
telemt_upstream_connect_success_total 28956
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 28957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4760
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28954
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 629835152 (600.66 MB)
telemt_user_octets_to_client{user="hello"} 32538709258 (30.30 GB)
telemt_user_msgs_from_client{user="hello"} 852602
telemt_user_msgs_to_client{user="hello"} 4240538
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 19
```