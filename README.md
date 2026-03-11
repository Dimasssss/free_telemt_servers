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

# Server Metrics 2026-03-11 11:22:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 75361.3 (20h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229192
telemt_connections_bad_total 3623
telemt_handshake_timeouts_total 4466
telemt_upstream_connect_attempt_total 210812
telemt_upstream_connect_success_total 210745
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 210812
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 192767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17921
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 210737
telemt_user_connections_current{user="hello"} 409
telemt_user_octets_from_client{user="hello"} 4460764708 (4.15 GB)
telemt_user_octets_to_client{user="hello"} 120167231785 (111.91 GB)
telemt_user_msgs_from_client{user="hello"} 4961121
telemt_user_msgs_to_client{user="hello"} 9167363
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 75360.5 (20h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89732
telemt_connections_bad_total 845
telemt_handshake_timeouts_total 3255
telemt_upstream_connect_attempt_total 81540
telemt_upstream_connect_success_total 81524
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 81540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10848
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 264
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 81516
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 5085844851 (4.74 GB)
telemt_user_octets_to_client{user="hello"} 57452630457 (53.51 GB)
telemt_user_msgs_from_client{user="hello"} 3313918
telemt_user_msgs_to_client{user="hello"} 15239390
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 75360.4 (20h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124442
telemt_connections_bad_total 1090
telemt_handshake_timeouts_total 5363
telemt_upstream_connect_attempt_total 110820
telemt_upstream_connect_success_total 110807
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 110820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 98315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12402
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 110799
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 12341966918 (11.49 GB)
telemt_user_octets_to_client{user="hello"} 87779835839 (81.75 GB)
telemt_user_msgs_from_client{user="hello"} 5998365
telemt_user_msgs_to_client{user="hello"} 17411723
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 75359.3 (20h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135555
telemt_connections_bad_total 332
telemt_handshake_timeouts_total 1250
telemt_upstream_connect_attempt_total 128594
telemt_upstream_connect_success_total 128292
telemt_upstream_connect_fail_total 302
telemt_upstream_connect_attempts_per_request{bucket="1"} 128594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16746
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 69
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 349
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 302
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 128284
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 5705487915 (5.31 GB)
telemt_user_octets_to_client{user="hello"} 96038160723 (89.44 GB)
telemt_user_msgs_from_client{user="hello"} 3900921
telemt_user_msgs_to_client{user="hello"} 26816231
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 75360.6 (20h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209524
telemt_connections_bad_total 16318
telemt_handshake_timeouts_total 3550
telemt_upstream_connect_attempt_total 168951
telemt_upstream_connect_success_total 168549
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 168951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 145165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23071
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 313
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 168541
telemt_user_connections_current{user="hello"} 282
telemt_user_octets_from_client{user="hello"} 3726365700 (3.47 GB)
telemt_user_octets_to_client{user="hello"} 144034382829 (134.14 GB)
telemt_user_msgs_from_client{user="hello"} 3870263
telemt_user_msgs_to_client{user="hello"} 19300979
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 54329.9 (15h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 424
telemt_connections_bad_total 402
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 17
telemt_upstream_connect_success_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```