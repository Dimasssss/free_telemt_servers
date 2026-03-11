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

# Server Metrics 2026-03-11 04:43:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 51467.6 (14h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130987
telemt_connections_bad_total 3386
telemt_handshake_timeouts_total 2788
telemt_upstream_connect_attempt_total 118821
telemt_upstream_connect_success_total 118777
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 118820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 118771
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 3034781986 (2.83 GB)
telemt_user_octets_to_client{user="hello"} 85727039471 (79.84 GB)
telemt_user_msgs_from_client{user="hello"} 3135672
telemt_user_msgs_to_client{user="hello"} 5950022
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 51466.8 (14h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53815
telemt_connections_bad_total 412
telemt_handshake_timeouts_total 2951
telemt_upstream_connect_attempt_total 47632
telemt_upstream_connect_success_total 47622
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 47632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 47616
telemt_user_connections_current{user="hello"} 50
telemt_user_octets_from_client{user="hello"} 4440904592 (4.14 GB)
telemt_user_octets_to_client{user="hello"} 44506623272 (41.45 GB)
telemt_user_msgs_from_client{user="hello"} 2591283
telemt_user_msgs_to_client{user="hello"} 10632186
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 51466.6 (14h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74670
telemt_connections_bad_total 675
telemt_handshake_timeouts_total 4304
telemt_upstream_connect_attempt_total 65452
telemt_upstream_connect_success_total 65449
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 65452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58004
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7393
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 65443
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 11773501571 (10.96 GB)
telemt_user_octets_to_client{user="hello"} 71122465234 (66.24 GB)
telemt_user_msgs_from_client{user="hello"} 5179572
telemt_user_msgs_to_client{user="hello"} 13353255
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 51465.5 (14h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77034
telemt_connections_bad_total 155
telemt_handshake_timeouts_total 571
telemt_upstream_connect_attempt_total 73771
telemt_upstream_connect_success_total 73607
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 73771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9549
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 73601
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 1811324583 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 48189460028 (44.88 GB)
telemt_user_msgs_from_client{user="hello"} 1707355
telemt_user_msgs_to_client{user="hello"} 10612412
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 51466.9 (14h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122433
telemt_connections_bad_total 11640
telemt_handshake_timeouts_total 1678
telemt_upstream_connect_attempt_total 104143
telemt_upstream_connect_success_total 103894
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 104143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 90861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12803
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 103888
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 2365451299 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 97886082603 (91.16 GB)
telemt_user_msgs_from_client{user="hello"} 2544093
telemt_user_msgs_to_client{user="hello"} 12672652
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 30436.3 (8h 27m)
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