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

# Server Metrics 2026-03-11 23:04:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 4778.1 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7825
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 65
telemt_upstream_connect_attempt_total 7484
telemt_upstream_connect_success_total 7480
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 7484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 893
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7478
telemt_user_connections_current{user="hello"} 240
telemt_user_octets_from_client{user="hello"} 97328097 (92.82 MB)
telemt_user_octets_to_client{user="hello"} 3322770490 (3.09 GB)
telemt_user_msgs_from_client{user="hello"} 168341
telemt_user_msgs_to_client{user="hello"} 485268
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 4766.6 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3739
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 3597
telemt_upstream_connect_success_total 3597
telemt_upstream_connect_attempts_per_request{bucket="1"} 3597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 473
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3595
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 16551293 (15.78 MB)
telemt_user_octets_to_client{user="hello"} 448518576 (427.74 MB)
telemt_user_msgs_from_client{user="hello"} 41067
telemt_user_msgs_to_client{user="hello"} 197462
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 4739.8 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6017
telemt_connections_bad_total 249
telemt_handshake_timeouts_total 126
telemt_upstream_connect_attempt_total 4933
telemt_upstream_connect_success_total 4930
telemt_upstream_connect_attempts_per_request{bucket="1"} 4930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 637
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4928
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 28691847 (27.36 MB)
telemt_user_octets_to_client{user="hello"} 2423273642 (2.26 GB)
telemt_user_msgs_from_client{user="hello"} 93049
telemt_user_msgs_to_client{user="hello"} 654066
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 4765.4 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4625
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 55
telemt_upstream_connect_attempt_total 4427
telemt_upstream_connect_success_total 4423
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 621
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4421
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 37190344 (35.47 MB)
telemt_user_octets_to_client{user="hello"} 1576343469 (1.47 GB)
telemt_user_msgs_from_client{user="hello"} 69836
telemt_user_msgs_to_client{user="hello"} 571982
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 4766.6 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4765
telemt_connections_bad_total 947
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 3740
telemt_upstream_connect_success_total 3737
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3740
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3735
telemt_user_connections_current{user="hello"} 64
telemt_user_octets_from_client{user="hello"} 43274220 (41.27 MB)
telemt_user_octets_to_client{user="hello"} 1517501865 (1.41 GB)
telemt_user_msgs_from_client{user="hello"} 54590
telemt_user_msgs_to_client{user="hello"} 276121
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 4766.1 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4878
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 90
telemt_upstream_connect_attempt_total 4156
telemt_upstream_connect_success_total 4156
telemt_upstream_connect_attempts_per_request{bucket="1"} 4156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 667
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4154
telemt_user_connections_current{user="hello"} 38
telemt_user_octets_from_client{user="hello"} 79401757 (75.72 MB)
telemt_user_octets_to_client{user="hello"} 11167710781 (10.40 GB)
telemt_user_msgs_from_client{user="hello"} 142845
telemt_user_msgs_to_client{user="hello"} 810048
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```