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

# Server Metrics 2026-03-11 03:22:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 46578.3 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120257
telemt_connections_bad_total 3364
telemt_handshake_timeouts_total 2583
telemt_upstream_connect_attempt_total 108825
telemt_upstream_connect_success_total 108786
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 108825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 99082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9650
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 108780
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 2936735789 (2.74 GB)
telemt_user_octets_to_client{user="hello"} 82295707179 (76.64 GB)
telemt_user_msgs_from_client{user="hello"} 2984138
telemt_user_msgs_to_client{user="hello"} 5697984
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 46577.6 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50141
telemt_connections_bad_total 388
telemt_handshake_timeouts_total 2922
telemt_upstream_connect_attempt_total 44162
telemt_upstream_connect_success_total 44153
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 44162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6739
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44147
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 2311131724 (2.15 GB)
telemt_user_octets_to_client{user="hello"} 43424738513 (40.44 GB)
telemt_user_msgs_from_client{user="hello"} 1791309
telemt_user_msgs_to_client{user="hello"} 10372009
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 46577.2 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70562
telemt_connections_bad_total 661
telemt_handshake_timeouts_total 4215
telemt_upstream_connect_attempt_total 61749
telemt_upstream_connect_success_total 61747
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 61749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6938
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 61741
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 11745942550 (10.94 GB)
telemt_user_octets_to_client{user="hello"} 70577655729 (65.73 GB)
telemt_user_msgs_from_client{user="hello"} 5136669
telemt_user_msgs_to_client{user="hello"} 13208439
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 46576.1 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70579
telemt_connections_bad_total 150
telemt_handshake_timeouts_total 552
telemt_upstream_connect_attempt_total 67531
telemt_upstream_connect_success_total 67374
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 67531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8526
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 180
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 67368
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 1769345535 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 42770876767 (39.83 GB)
telemt_user_msgs_from_client{user="hello"} 1608847
telemt_user_msgs_to_client{user="hello"} 8407813
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 46577.5 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109159
telemt_connections_bad_total 10641
telemt_handshake_timeouts_total 1542
telemt_upstream_connect_attempt_total 92967
telemt_upstream_connect_success_total 92719
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 92967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11625
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 92715
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 2242450562 (2.09 GB)
telemt_user_octets_to_client{user="hello"} 84113671356 (78.34 GB)
telemt_user_msgs_from_client{user="hello"} 2335457
telemt_user_msgs_to_client{user="hello"} 11230235
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 25546.9 (7h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86
telemt_connections_bad_total 82
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```