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
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-10 20:29:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 21810.6 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81606
telemt_connections_bad_total 3067
telemt_handshake_timeouts_total 2108
telemt_upstream_connect_attempt_total 72645
telemt_upstream_connect_success_total 72632
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 72645
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6355
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 72630
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 2400011658 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 57206688770 (53.28 GB)
telemt_user_msgs_from_client{user="hello"} 2186823
telemt_user_msgs_to_client{user="hello"} 3931880
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 21810.1 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31320
telemt_connections_bad_total 241
telemt_handshake_timeouts_total 515
telemt_upstream_connect_attempt_total 28674
telemt_upstream_connect_success_total 28666
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 28674
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28662
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 1369633025 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 24246281701 (22.58 GB)
telemt_user_msgs_from_client{user="hello"} 1108442
telemt_user_msgs_to_client{user="hello"} 7143912
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 21810.1 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50339
telemt_connections_bad_total 290
telemt_handshake_timeouts_total 3682
telemt_upstream_connect_attempt_total 43465
telemt_upstream_connect_success_total 43464
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 43465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4142
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 43460
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 669611145 (638.59 MB)
telemt_user_octets_to_client{user="hello"} 41157723474 (38.33 GB)
telemt_user_msgs_from_client{user="hello"} 932026
telemt_user_msgs_to_client{user="hello"} 6176477
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 21808.8 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44615
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 314
telemt_upstream_connect_attempt_total 42775
telemt_upstream_connect_success_total 42651
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 42775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4941
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42647
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 731758856 (697.86 MB)
telemt_user_octets_to_client{user="hello"} 32654549824 (30.41 GB)
telemt_user_msgs_from_client{user="hello"} 935126
telemt_user_msgs_to_client{user="hello"} 6256273
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 21810.1 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63781
telemt_connections_bad_total 5715
telemt_handshake_timeouts_total 1348
telemt_upstream_connect_attempt_total 54064
telemt_upstream_connect_success_total 53820
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 54064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6591
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53816
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 1732098506 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 42617513211 (39.69 GB)
telemt_user_msgs_from_client{user="hello"} 1552588
telemt_user_msgs_to_client{user="hello"} 5849594
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 779.5 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13
telemt_connections_bad_total 13
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```