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

# Server Metrics 2026-03-12 01:29:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 13443.6 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25638
telemt_connections_bad_total 1844
telemt_handshake_timeouts_total 159
telemt_upstream_connect_attempt_total 22787
telemt_upstream_connect_success_total 22781
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 22787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2220
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22779
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 246751614 (235.32 MB)
telemt_user_octets_to_client{user="hello"} 7847502343 (7.31 GB)
telemt_user_msgs_from_client{user="hello"} 418010
telemt_user_msgs_to_client{user="hello"} 1030805
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 13431.9 (3h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10854
telemt_connections_bad_total 44
telemt_handshake_timeouts_total 31
telemt_upstream_connect_attempt_total 10420
telemt_upstream_connect_success_total 10420
telemt_upstream_connect_attempts_per_request{bucket="1"} 10420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1265
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10418
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 69748536 (66.52 MB)
telemt_user_octets_to_client{user="hello"} 3618932712 (3.37 GB)
telemt_user_msgs_from_client{user="hello"} 172560
telemt_user_msgs_to_client{user="hello"} 1173125
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 13405.7 (3h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17820
telemt_connections_bad_total 282
telemt_handshake_timeouts_total 867
telemt_upstream_connect_attempt_total 14859
telemt_upstream_connect_success_total 14859
telemt_upstream_connect_attempts_per_request{bucket="1"} 14859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14857
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 1887496333 (1.76 GB)
telemt_user_octets_to_client{user="hello"} 7620472955 (7.10 GB)
telemt_user_msgs_from_client{user="hello"} 914136
telemt_user_msgs_to_client{user="hello"} 1706554
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 13431.0 (3h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18871
telemt_connections_bad_total 5080
telemt_handshake_timeouts_total 690
telemt_upstream_connect_attempt_total 12499
telemt_upstream_connect_success_total 12488
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 12499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1610
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12486
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 98860186 (94.28 MB)
telemt_user_octets_to_client{user="hello"} 5773262576 (5.38 GB)
telemt_user_msgs_from_client{user="hello"} 197103
telemt_user_msgs_to_client{user="hello"} 2194726
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 13431.7 (3h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14628
telemt_connections_bad_total 122
telemt_handshake_timeouts_total 124
telemt_upstream_connect_attempt_total 13227
telemt_upstream_connect_success_total 13227
telemt_upstream_connect_attempts_per_request{bucket="1"} 13227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2051
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13225
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 202091883 (192.73 MB)
telemt_user_octets_to_client{user="hello"} 19974451760 (18.60 GB)
telemt_user_msgs_from_client{user="hello"} 373122
telemt_user_msgs_to_client{user="hello"} 1865576
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 7
```