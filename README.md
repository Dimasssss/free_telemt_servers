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

# Server Metrics 2026-03-11 05:09:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 52996.7 (14h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134708
telemt_connections_bad_total 3399
telemt_handshake_timeouts_total 2835
telemt_upstream_connect_attempt_total 122363
telemt_upstream_connect_success_total 122319
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 122363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10707
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 122313
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 3075667022 (2.86 GB)
telemt_user_octets_to_client{user="hello"} 87081283687 (81.10 GB)
telemt_user_msgs_from_client{user="hello"} 3204806
telemt_user_msgs_to_client{user="hello"} 6066854
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 52996.0 (14h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55337
telemt_connections_bad_total 435
telemt_handshake_timeouts_total 2972
telemt_upstream_connect_attempt_total 49069
telemt_upstream_connect_success_total 49058
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 49069
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7365
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49052
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 4481969095 (4.17 GB)
telemt_user_octets_to_client{user="hello"} 45263135821 (42.15 GB)
telemt_user_msgs_from_client{user="hello"} 2639104
telemt_user_msgs_to_client{user="hello"} 10831507
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 52995.9 (14h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76137
telemt_connections_bad_total 714
telemt_handshake_timeouts_total 4320
telemt_upstream_connect_attempt_total 66770
telemt_upstream_connect_success_total 66767
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 66770
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7530
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 66761
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 11781015425 (10.97 GB)
telemt_user_octets_to_client{user="hello"} 71237945459 (66.35 GB)
telemt_user_msgs_from_client{user="hello"} 5191718
telemt_user_msgs_to_client{user="hello"} 13402536
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 52994.7 (14h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79291
telemt_connections_bad_total 157
telemt_handshake_timeouts_total 584
telemt_upstream_connect_attempt_total 75909
telemt_upstream_connect_success_total 75743
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 75909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65635
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9870
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 75737
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 1828764799 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 49081474704 (45.71 GB)
telemt_user_msgs_from_client{user="hello"} 1736338
telemt_user_msgs_to_client{user="hello"} 10790219
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 52995.9 (14h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125628
telemt_connections_bad_total 11954
telemt_handshake_timeouts_total 1702
telemt_upstream_connect_attempt_total 106622
telemt_upstream_connect_success_total 106373
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 106622
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 92939
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13204
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 106367
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 2397547314 (2.23 GB)
telemt_user_octets_to_client{user="hello"} 101551043753 (94.58 GB)
telemt_user_msgs_from_client{user="hello"} 2605464
telemt_user_msgs_to_client{user="hello"} 13027883
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 31965.4 (8h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129
telemt_connections_bad_total 120
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```