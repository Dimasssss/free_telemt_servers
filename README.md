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

# Server Metrics 2026-03-10 20:39:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 22423.8 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83492
telemt_connections_bad_total 3197
telemt_handshake_timeouts_total 2120
telemt_upstream_connect_attempt_total 74330
telemt_upstream_connect_success_total 74300
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 74330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67775
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6476
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 74298
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 2420831428 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 57690862127 (53.73 GB)
telemt_user_msgs_from_client{user="hello"} 2213411
telemt_user_msgs_to_client{user="hello"} 3974459
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 22423.0 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31965
telemt_connections_bad_total 299
telemt_handshake_timeouts_total 547
telemt_upstream_connect_attempt_total 29194
telemt_upstream_connect_success_total 29186
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 29194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4323
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29182
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 1464147284 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 24446774863 (22.77 GB)
telemt_user_msgs_from_client{user="hello"} 1149222
telemt_user_msgs_to_client{user="hello"} 7196719
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 22422.9 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51308
telemt_connections_bad_total 290
telemt_handshake_timeouts_total 3702
telemt_upstream_connect_attempt_total 44380
telemt_upstream_connect_success_total 44379
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 44380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4200
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44375
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 676019760 (644.70 MB)
telemt_user_octets_to_client{user="hello"} 41827855825 (38.96 GB)
telemt_user_msgs_from_client{user="hello"} 949373
telemt_user_msgs_to_client{user="hello"} 6261732
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 22421.9 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45715
telemt_connections_bad_total 69
telemt_handshake_timeouts_total 314
telemt_upstream_connect_attempt_total 43852
telemt_upstream_connect_success_total 43722
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 43852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5048
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 43718
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 743486188 (709.04 MB)
telemt_user_octets_to_client{user="hello"} 33377423505 (31.09 GB)
telemt_user_msgs_from_client{user="hello"} 959188
telemt_user_msgs_to_client{user="hello"} 6387699
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 22422.9 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64862
telemt_connections_bad_total 5873
telemt_handshake_timeouts_total 1353
telemt_upstream_connect_attempt_total 54921
telemt_upstream_connect_success_total 54677
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 54921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6699
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 54673
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 1741442603 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 43466573865 (40.48 GB)
telemt_user_msgs_from_client{user="hello"} 1574577
telemt_user_msgs_to_client{user="hello"} 5970296
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 1392.4 (0h 23m)
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