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

# Server Metrics 2026-03-11 18:23:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 4973.3 (1h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20369
telemt_connections_bad_total 1047
telemt_handshake_timeouts_total 102
telemt_upstream_connect_attempt_total 18331
telemt_upstream_connect_success_total 18327
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 18331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1775
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18325
telemt_user_connections_current{user="hello"} 351
telemt_user_octets_from_client{user="hello"} 556755347 (530.96 MB)
telemt_user_octets_to_client{user="hello"} 11475990641 (10.69 GB)
telemt_user_msgs_from_client{user="hello"} 474379
telemt_user_msgs_to_client{user="hello"} 857889
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 4961.0 (1h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10270
telemt_connections_bad_total 27
telemt_handshake_timeouts_total 194
telemt_upstream_connect_attempt_total 9244
telemt_upstream_connect_success_total 9243
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1140
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9241
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 156424050 (149.18 MB)
telemt_user_octets_to_client{user="hello"} 6054233543 (5.64 GB)
telemt_user_msgs_from_client{user="hello"} 220105
telemt_user_msgs_to_client{user="hello"} 2251804
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 4980.7 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11490
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 103
telemt_upstream_connect_attempt_total 10778
telemt_upstream_connect_success_total 10777
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 982
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10775
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 86243061 (82.25 MB)
telemt_user_octets_to_client{user="hello"} 4680426922 (4.36 GB)
telemt_user_msgs_from_client{user="hello"} 221965
telemt_user_msgs_to_client{user="hello"} 1342368
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 4976.2 (1h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11194
telemt_connections_bad_total 565
telemt_handshake_timeouts_total 191
telemt_upstream_connect_attempt_total 10050
telemt_upstream_connect_success_total 10027
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 10050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8993
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1006
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10025
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 455257946 (434.17 MB)
telemt_user_octets_to_client{user="hello"} 5000026949 (4.66 GB)
telemt_user_msgs_from_client{user="hello"} 286800
telemt_user_msgs_to_client{user="hello"} 1176860
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 4984.5 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12408
telemt_connections_bad_total 1016
telemt_handshake_timeouts_total 77
telemt_upstream_connect_attempt_total 10955
telemt_upstream_connect_success_total 10955
telemt_upstream_connect_attempts_per_request{bucket="1"} 10955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1528
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10953
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 92952496 (88.65 MB)
telemt_user_octets_to_client{user="hello"} 1884158177 (1.75 GB)
telemt_user_msgs_from_client{user="hello"} 168011
telemt_user_msgs_to_client{user="hello"} 619287
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 79590.9 (22h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 496
telemt_connections_bad_total 472
telemt_handshake_timeouts_total 14
telemt_upstream_connect_attempt_total 19
telemt_upstream_connect_success_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```