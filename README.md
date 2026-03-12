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

# Server Metrics 2026-03-12 01:45:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 14416.3 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27501
telemt_connections_bad_total 1861
telemt_handshake_timeouts_total 164
telemt_upstream_connect_attempt_total 24529
telemt_upstream_connect_success_total 24522
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 24529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2419
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24520
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 258370006 (246.40 MB)
telemt_user_octets_to_client{user="hello"} 8704301135 (8.11 GB)
telemt_user_msgs_from_client{user="hello"} 443272
telemt_user_msgs_to_client{user="hello"} 1085563
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 14404.6 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11692
telemt_connections_bad_total 47
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 11228
telemt_upstream_connect_success_total 11228
telemt_upstream_connect_attempts_per_request{bucket="1"} 11228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1306
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11226
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 73244485 (69.85 MB)
telemt_user_octets_to_client{user="hello"} 3794782916 (3.53 GB)
telemt_user_msgs_from_client{user="hello"} 181488
telemt_user_msgs_to_client{user="hello"} 1272921
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 14378.4 (3h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19559
telemt_connections_bad_total 291
telemt_handshake_timeouts_total 874
telemt_upstream_connect_attempt_total 16498
telemt_upstream_connect_success_total 16498
telemt_upstream_connect_attempts_per_request{bucket="1"} 16498
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2287
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16496
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 3260815788 (3.04 GB)
telemt_user_octets_to_client{user="hello"} 8658353555 (8.06 GB)
telemt_user_msgs_from_client{user="hello"} 1416343
telemt_user_msgs_to_client{user="hello"} 1803057
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 14403.6 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21346
telemt_connections_bad_total 6741
telemt_handshake_timeouts_total 691
telemt_upstream_connect_attempt_total 13281
telemt_upstream_connect_success_total 13269
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 13281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1737
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13267
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 109855850 (104.77 MB)
telemt_user_octets_to_client{user="hello"} 6409713155 (5.97 GB)
telemt_user_msgs_from_client{user="hello"} 212799
telemt_user_msgs_to_client{user="hello"} 2438877
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 14404.5 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15635
telemt_connections_bad_total 128
telemt_handshake_timeouts_total 127
telemt_upstream_connect_attempt_total 14205
telemt_upstream_connect_success_total 14205
telemt_upstream_connect_attempts_per_request{bucket="1"} 14205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2203
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14203
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 213186701 (203.31 MB)
telemt_user_octets_to_client{user="hello"} 20540592226 (19.13 GB)
telemt_user_msgs_from_client{user="hello"} 407045
telemt_user_msgs_to_client{user="hello"} 2005424
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 11
```