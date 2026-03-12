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

# Server Metrics 2026-03-12 00:02:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 8257.7 (2h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13930
telemt_connections_bad_total 177
telemt_handshake_timeouts_total 84
telemt_upstream_connect_attempt_total 13283
telemt_upstream_connect_success_total 13278
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 13283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11826
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1448
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13276
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 170229641 (162.34 MB)
telemt_user_octets_to_client{user="hello"} 5819971219 (5.42 GB)
telemt_user_msgs_from_client{user="hello"} 294914
telemt_user_msgs_to_client{user="hello"} 759773
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 8245.9 (2h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5965
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 5718
telemt_upstream_connect_success_total 5718
telemt_upstream_connect_attempts_per_request{bucket="1"} 5718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 726
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5716
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 28818332 (27.48 MB)
telemt_user_octets_to_client{user="hello"} 913426612 (871.11 MB)
telemt_user_msgs_from_client{user="hello"} 69565
telemt_user_msgs_to_client{user="hello"} 386864
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 8224.9 (2h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10543
telemt_connections_bad_total 270
telemt_handshake_timeouts_total 767
telemt_upstream_connect_attempt_total 8137
telemt_upstream_connect_success_total 8137
telemt_upstream_connect_attempts_per_request{bucket="1"} 8137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1071
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8135
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 55563893 (52.99 MB)
telemt_user_octets_to_client{user="hello"} 5875696985 (5.47 GB)
telemt_user_msgs_from_client{user="hello"} 174294
telemt_user_msgs_to_client{user="hello"} 1342150
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 8245.0 (2h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9272
telemt_connections_bad_total 1460
telemt_handshake_timeouts_total 236
telemt_upstream_connect_attempt_total 7304
telemt_upstream_connect_success_total 7294
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 7304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 868
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7292
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 54871454 (52.33 MB)
telemt_user_octets_to_client{user="hello"} 3189288614 (2.97 GB)
telemt_user_msgs_from_client{user="hello"} 111897
telemt_user_msgs_to_client{user="hello"} 1120218
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 8245.8 (2h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7854
telemt_connections_bad_total 61
telemt_handshake_timeouts_total 101
telemt_upstream_connect_attempt_total 6899
telemt_upstream_connect_success_total 6899
telemt_upstream_connect_attempts_per_request{bucket="1"} 6899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1197
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6897
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 104445099 (99.61 MB)
telemt_user_octets_to_client{user="hello"} 14214682701 (13.24 GB)
telemt_user_msgs_from_client{user="hello"} 207971
telemt_user_msgs_to_client{user="hello"} 1246611
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 8
```