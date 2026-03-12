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

# Server Metrics 2026-03-12 03:28:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 20578.2 (5h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41973
telemt_connections_bad_total 1933
telemt_handshake_timeouts_total 331
telemt_upstream_connect_attempt_total 37792
telemt_upstream_connect_success_total 37784
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 37792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 37780
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 349010600 (332.84 MB)
telemt_user_octets_to_client{user="hello"} 11288919614 (10.51 GB)
telemt_user_msgs_from_client{user="hello"} 593550
telemt_user_msgs_to_client{user="hello"} 1417780
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 20566.5 (5h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16799
telemt_connections_bad_total 106
telemt_handshake_timeouts_total 72
telemt_upstream_connect_attempt_total 16050
telemt_upstream_connect_success_total 16050
telemt_upstream_connect_attempts_per_request{bucket="1"} 16050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1868
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16048
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 141173275 (134.63 MB)
telemt_user_octets_to_client{user="hello"} 9125932645 (8.50 GB)
telemt_user_msgs_from_client{user="hello"} 304698
telemt_user_msgs_to_client{user="hello"} 2474546
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 20540.0 (5h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29227
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 915
telemt_upstream_connect_attempt_total 25676
telemt_upstream_connect_success_total 25676
telemt_upstream_connect_attempts_per_request{bucket="1"} 25676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21488
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4182
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25672
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 5240717955 (4.88 GB)
telemt_user_octets_to_client{user="hello"} 16278298705 (15.16 GB)
telemt_user_msgs_from_client{user="hello"} 2282865
telemt_user_msgs_to_client{user="hello"} 3262591
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 20565.5 (5h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30812
telemt_connections_bad_total 8515
telemt_handshake_timeouts_total 712
telemt_upstream_connect_attempt_total 20676
telemt_upstream_connect_success_total 18978
telemt_upstream_connect_fail_total 1698
telemt_upstream_connect_attempts_per_request{bucket="1"} 20676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2823
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1698
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18974
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 175361711 (167.24 MB)
telemt_user_octets_to_client{user="hello"} 14787379934 (13.77 GB)
telemt_user_msgs_from_client{user="hello"} 353772
telemt_user_msgs_to_client{user="hello"} 6104975
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 20566.2 (5h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23532
telemt_connections_bad_total 144
telemt_handshake_timeouts_total 147
telemt_upstream_connect_attempt_total 21789
telemt_upstream_connect_success_total 21788
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 21789
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3479
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21786
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 537048966 (512.17 MB)
telemt_user_octets_to_client{user="hello"} 29981827409 (27.92 GB)
telemt_user_msgs_from_client{user="hello"} 720059
telemt_user_msgs_to_client{user="hello"} 3757252
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 16
```