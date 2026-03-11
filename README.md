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

# Server Metrics 2026-03-11 03:47:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 48106.5 (13h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122786
telemt_connections_bad_total 3374
telemt_handshake_timeouts_total 2602
telemt_upstream_connect_attempt_total 111228
telemt_upstream_connect_success_total 111189
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 111228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 101300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9835
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 111183
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 2969410203 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 83119683191 (77.41 GB)
telemt_user_msgs_from_client{user="hello"} 3021159
telemt_user_msgs_to_client{user="hello"} 5771628
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 48105.9 (13h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51015
telemt_connections_bad_total 399
telemt_handshake_timeouts_total 2926
telemt_upstream_connect_attempt_total 44981
telemt_upstream_connect_success_total 44968
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 44978
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6860
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44962
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 2319087293 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 44089868910 (41.06 GB)
telemt_user_msgs_from_client{user="hello"} 1809143
telemt_user_msgs_to_client{user="hello"} 10482808
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 48105.5 (13h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71572
telemt_connections_bad_total 667
telemt_handshake_timeouts_total 4231
telemt_upstream_connect_attempt_total 62687
telemt_upstream_connect_success_total 62685
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 62687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7071
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 62679
telemt_user_connections_current{user="hello"} 46
telemt_user_octets_from_client{user="hello"} 11749081152 (10.94 GB)
telemt_user_octets_to_client{user="hello"} 70623098339 (65.77 GB)
telemt_user_msgs_from_client{user="hello"} 5143527
telemt_user_msgs_to_client{user="hello"} 13229484
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 48104.5 (13h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72380
telemt_connections_bad_total 152
telemt_handshake_timeouts_total 560
telemt_upstream_connect_attempt_total 69260
telemt_upstream_connect_success_total 69101
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 69260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8813
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 182
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 69095
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 1780505177 (1.66 GB)
telemt_user_octets_to_client{user="hello"} 43024644335 (40.07 GB)
telemt_user_msgs_from_client{user="hello"} 1628349
telemt_user_msgs_to_client{user="hello"} 8470424
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 48105.8 (13h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114371
telemt_connections_bad_total 10944
telemt_handshake_timeouts_total 1648
telemt_upstream_connect_attempt_total 97373
telemt_upstream_connect_success_total 97125
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 97373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 84965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11931
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 97119
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 2274452813 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 90267234542 (84.07 GB)
telemt_user_msgs_from_client{user="hello"} 2404068
telemt_user_msgs_to_client{user="hello"} 11722069
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 27075.2 (7h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113
telemt_connections_bad_total 107
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```