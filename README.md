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

# Server Metrics 2026-03-12 05:37:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 28358.8 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71243
telemt_connections_bad_total 2108
telemt_handshake_timeouts_total 2161
telemt_upstream_connect_attempt_total 63748
telemt_upstream_connect_success_total 63730
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 63748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9952
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 63726
telemt_user_connections_current{user="hello"} 309
telemt_user_octets_from_client{user="hello"} 651693993 (621.50 MB)
telemt_user_octets_to_client{user="hello"} 20560282713 (19.15 GB)
telemt_user_msgs_from_client{user="hello"} 966918
telemt_user_msgs_to_client{user="hello"} 2332238
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 28347.2 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28142
telemt_connections_bad_total 208
telemt_handshake_timeouts_total 149
telemt_upstream_connect_attempt_total 26799
telemt_upstream_connect_success_total 26793
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 26799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3525
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26789
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 240544750 (229.40 MB)
telemt_user_octets_to_client{user="hello"} 14466502917 (13.47 GB)
telemt_user_msgs_from_client{user="hello"} 499823
telemt_user_msgs_to_client{user="hello"} 4342741
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 28320.9 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43637
telemt_connections_bad_total 618
telemt_handshake_timeouts_total 1032
telemt_upstream_connect_attempt_total 39117
telemt_upstream_connect_success_total 39116
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 39117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 39112
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 5345548305 (4.98 GB)
telemt_user_octets_to_client{user="hello"} 23852737461 (22.21 GB)
telemt_user_msgs_from_client{user="hello"} 2540520
telemt_user_msgs_to_client{user="hello"} 4292886
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 28346.3 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48085
telemt_connections_bad_total 11617
telemt_handshake_timeouts_total 831
telemt_upstream_connect_attempt_total 33829
telemt_upstream_connect_success_total 32129
telemt_upstream_connect_fail_total 1700
telemt_upstream_connect_attempts_per_request{bucket="1"} 33829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5250
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1700
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32125
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 376602201 (359.16 MB)
telemt_user_octets_to_client{user="hello"} 22253615834 (20.73 GB)
telemt_user_msgs_from_client{user="hello"} 605853
telemt_user_msgs_to_client{user="hello"} 9212444
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 28346.8 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42163
telemt_connections_bad_total 761
telemt_handshake_timeouts_total 214
telemt_upstream_connect_attempt_total 39040
telemt_upstream_connect_success_total 39039
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 39040
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32418
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6611
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 39035
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 745458131 (710.92 MB)
telemt_user_octets_to_client{user="hello"} 36099935249 (33.62 GB)
telemt_user_msgs_from_client{user="hello"} 1036093
telemt_user_msgs_to_client{user="hello"} 4908524
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 23
```