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

# Server Metrics 2026-03-11 11:27:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 75668.6 (21h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 230467
telemt_connections_bad_total 3623
telemt_handshake_timeouts_total 4487
telemt_upstream_connect_attempt_total 212013
telemt_upstream_connect_success_total 211946
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 212013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 193824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18065
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 211938
telemt_user_connections_current{user="hello"} 324
telemt_user_octets_from_client{user="hello"} 4474137514 (4.17 GB)
telemt_user_octets_to_client{user="hello"} 120445149860 (112.17 GB)
telemt_user_msgs_from_client{user="hello"} 4981769
telemt_user_msgs_to_client{user="hello"} 9201671
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 75668.0 (21h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90227
telemt_connections_bad_total 845
telemt_handshake_timeouts_total 3258
telemt_upstream_connect_attempt_total 82026
telemt_upstream_connect_success_total 82010
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 82026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10904
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 264
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 82002
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 5105944939 (4.76 GB)
telemt_user_octets_to_client{user="hello"} 57605896081 (53.65 GB)
telemt_user_msgs_from_client{user="hello"} 3327836
telemt_user_msgs_to_client{user="hello"} 15299737
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 75667.5 (21h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125883
telemt_connections_bad_total 1091
telemt_handshake_timeouts_total 5935
telemt_upstream_connect_attempt_total 111515
telemt_upstream_connect_success_total 111502
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 111515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 98947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12465
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 111494
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 12346680762 (11.50 GB)
telemt_user_octets_to_client{user="hello"} 87840754865 (81.81 GB)
telemt_user_msgs_from_client{user="hello"} 6008528
telemt_user_msgs_to_client{user="hello"} 17442050
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 75668.5 (21h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136476
telemt_connections_bad_total 333
telemt_handshake_timeouts_total 1256
telemt_upstream_connect_attempt_total 129484
telemt_upstream_connect_success_total 129181
telemt_upstream_connect_fail_total 303
telemt_upstream_connect_attempts_per_request{bucket="1"} 129484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16828
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 69
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 352
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 303
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 129173
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 5716070688 (5.32 GB)
telemt_user_octets_to_client{user="hello"} 98352914106 (91.60 GB)
telemt_user_msgs_from_client{user="hello"} 3926702
telemt_user_msgs_to_client{user="hello"} 27871209
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 75667.9 (21h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210451
telemt_connections_bad_total 16374
telemt_handshake_timeouts_total 3741
telemt_upstream_connect_attempt_total 169626
telemt_upstream_connect_success_total 169224
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 169626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 145748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23162
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 314
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 169216
telemt_user_connections_current{user="hello"} 284
telemt_user_octets_from_client{user="hello"} 3731103969 (3.47 GB)
telemt_user_octets_to_client{user="hello"} 144387587254 (134.47 GB)
telemt_user_msgs_from_client{user="hello"} 3881979
telemt_user_msgs_to_client{user="hello"} 19428400
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 54637.3 (15h 10m)
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