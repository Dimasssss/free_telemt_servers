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

# Server Metrics 2026-03-10 20:55:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 23343.5 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85932
telemt_connections_bad_total 3265
telemt_handshake_timeouts_total 2145
telemt_upstream_connect_attempt_total 76641
telemt_upstream_connect_success_total 76611
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 76641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6675
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 76607
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 2451660879 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 59266364796 (55.20 GB)
telemt_user_msgs_from_client{user="hello"} 2263029
telemt_user_msgs_to_client{user="hello"} 4057683
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 23343.0 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32910
telemt_connections_bad_total 312
telemt_handshake_timeouts_total 574
telemt_upstream_connect_attempt_total 30039
telemt_upstream_connect_success_total 30031
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 30039
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4476
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30027
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 1524061026 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 25463569559 (23.71 GB)
telemt_user_msgs_from_client{user="hello"} 1188791
telemt_user_msgs_to_client{user="hello"} 7393555
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 23342.8 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52667
telemt_connections_bad_total 296
telemt_handshake_timeouts_total 3706
telemt_upstream_connect_attempt_total 45663
telemt_upstream_connect_success_total 45662
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 45663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4333
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 45658
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 704356380 (671.73 MB)
telemt_user_octets_to_client{user="hello"} 42139508621 (39.25 GB)
telemt_user_msgs_from_client{user="hello"} 974863
telemt_user_msgs_to_client{user="hello"} 6320768
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 23341.7 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46958
telemt_connections_bad_total 70
telemt_handshake_timeouts_total 315
telemt_upstream_connect_attempt_total 45075
telemt_upstream_connect_success_total 44943
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 45075
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5215
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44939
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 761216953 (725.95 MB)
telemt_user_octets_to_client{user="hello"} 34290521172 (31.94 GB)
telemt_user_msgs_from_client{user="hello"} 995798
telemt_user_msgs_to_client{user="hello"} 6536753
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 23343.0 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66475
telemt_connections_bad_total 6057
telemt_handshake_timeouts_total 1377
telemt_upstream_connect_attempt_total 56276
telemt_upstream_connect_success_total 56032
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 56276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6885
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 56028
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 1822246415 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 44350425075 (41.30 GB)
telemt_user_msgs_from_client{user="hello"} 1629581
telemt_user_msgs_to_client{user="hello"} 6111611
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 2312.4 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16
telemt_connections_bad_total 16
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```