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

# Server Metrics 2026-03-12 02:50:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 18309.3 (5h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36717
telemt_connections_bad_total 1921
telemt_handshake_timeouts_total 300
telemt_upstream_connect_attempt_total 32853
telemt_upstream_connect_success_total 32846
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 32853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3696
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32844
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 304483357 (290.38 MB)
telemt_user_octets_to_client{user="hello"} 10247435776 (9.54 GB)
telemt_user_msgs_from_client{user="hello"} 526417
telemt_user_msgs_to_client{user="hello"} 1286592
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 18297.2 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15119
telemt_connections_bad_total 104
telemt_handshake_timeouts_total 69
telemt_upstream_connect_attempt_total 14467
telemt_upstream_connect_success_total 14467
telemt_upstream_connect_attempts_per_request{bucket="1"} 14467
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1649
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14465
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 120065337 (114.50 MB)
telemt_user_octets_to_client{user="hello"} 7512564948 (7.00 GB)
telemt_user_msgs_from_client{user="hello"} 260690
telemt_user_msgs_to_client{user="hello"} 2036734
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 18270.7 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25393
telemt_connections_bad_total 365
telemt_handshake_timeouts_total 904
telemt_upstream_connect_attempt_total 22000
telemt_upstream_connect_success_total 21999
telemt_upstream_connect_attempts_per_request{bucket="1"} 21999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3403
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21995
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 5210013624 (4.85 GB)
telemt_user_octets_to_client{user="hello"} 12727595261 (11.85 GB)
telemt_user_msgs_from_client{user="hello"} 2188804
telemt_user_msgs_to_client{user="hello"} 2634585
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 18296.4 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28334
telemt_connections_bad_total 8468
telemt_handshake_timeouts_total 703
telemt_upstream_connect_attempt_total 18366
telemt_upstream_connect_success_total 16668
telemt_upstream_connect_fail_total 1698
telemt_upstream_connect_attempts_per_request{bucket="1"} 18366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2443
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1698
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16664
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 144716887 (138.01 MB)
telemt_user_octets_to_client{user="hello"} 11970846011 (11.15 GB)
telemt_user_msgs_from_client{user="hello"} 305028
telemt_user_msgs_to_client{user="hello"} 4812457
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 18297.0 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20185
telemt_connections_bad_total 142
telemt_handshake_timeouts_total 134
telemt_upstream_connect_attempt_total 18583
telemt_upstream_connect_success_total 18583
telemt_upstream_connect_attempts_per_request{bucket="1"} 18583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2898
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18581
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 447515769 (426.78 MB)
telemt_user_octets_to_client{user="hello"} 25086298770 (23.36 GB)
telemt_user_msgs_from_client{user="hello"} 590848
telemt_user_msgs_to_client{user="hello"} 3043527
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 22
```