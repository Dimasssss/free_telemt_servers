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

# Server Metrics 2026-03-11 09:29:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 68604.6 (19h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 200182
telemt_connections_bad_total 3591
telemt_handshake_timeouts_total 4257
telemt_upstream_connect_attempt_total 183040
telemt_upstream_connect_success_total 182982
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 183040
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 167101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 182974
telemt_user_connections_current{user="hello"} 430
telemt_user_octets_from_client{user="hello"} 4033679100 (3.76 GB)
telemt_user_octets_to_client{user="hello"} 109661852404 (102.13 GB)
telemt_user_msgs_from_client{user="hello"} 4356443
telemt_user_msgs_to_client{user="hello"} 8133699
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 68604.1 (19h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77696
telemt_connections_bad_total 761
telemt_handshake_timeouts_total 3140
telemt_upstream_connect_attempt_total 70157
telemt_upstream_connect_success_total 70142
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 70157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9542
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 249
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 70134
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 4941719000 (4.60 GB)
telemt_user_octets_to_client{user="hello"} 55116889189 (51.33 GB)
telemt_user_msgs_from_client{user="hello"} 3129881
telemt_user_msgs_to_client{user="hello"} 14099304
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 68604.5 (19h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107520
telemt_connections_bad_total 940
telemt_handshake_timeouts_total 5217
telemt_upstream_connect_attempt_total 95230
telemt_upstream_connect_success_total 95226
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 95230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 84444
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10719
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 95218
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 11982974032 (11.16 GB)
telemt_user_octets_to_client{user="hello"} 79864908096 (74.38 GB)
telemt_user_msgs_from_client{user="hello"} 5612147
telemt_user_msgs_to_client{user="hello"} 15506796
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 68602.9 (19h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118920
telemt_connections_bad_total 250
telemt_handshake_timeouts_total 1106
telemt_upstream_connect_attempt_total 112932
telemt_upstream_connect_success_total 112674
telemt_upstream_connect_fail_total 258
telemt_upstream_connect_attempts_per_request{bucket="1"} 112932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 97192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15115
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 58
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 309
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 258
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 112666
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 5005741863 (4.66 GB)
telemt_user_octets_to_client{user="hello"} 81171265140 (75.60 GB)
telemt_user_msgs_from_client{user="hello"} 3404373
telemt_user_msgs_to_client{user="hello"} 20832277
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 68604.0 (19h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188314
telemt_connections_bad_total 14985
telemt_handshake_timeouts_total 3310
telemt_upstream_connect_attempt_total 150474
telemt_upstream_connect_success_total 150072
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 150474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 128648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21145
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 279
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 150066
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 2917464440 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 134384836797 (125.16 GB)
telemt_user_msgs_from_client{user="hello"} 3347582
telemt_user_msgs_to_client{user="hello"} 17556599
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 47573.5 (13h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 420
telemt_connections_bad_total 398
telemt_handshake_timeouts_total 9
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