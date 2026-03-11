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

# Server Metrics 2026-03-11 04:23:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 50244.7 (13h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128502
telemt_connections_bad_total 3384
telemt_handshake_timeouts_total 2738
telemt_upstream_connect_attempt_total 116431
telemt_upstream_connect_success_total 116389
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 116431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 116383
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 3016097998 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 84454934024 (78.65 GB)
telemt_user_msgs_from_client{user="hello"} 3092242
telemt_user_msgs_to_client{user="hello"} 5877352
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 50244.3 (13h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52560
telemt_connections_bad_total 412
telemt_handshake_timeouts_total 2942
telemt_upstream_connect_attempt_total 46440
telemt_upstream_connect_success_total 46430
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 46440
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39207
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6997
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 46424
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 2818574864 (2.63 GB)
telemt_user_octets_to_client{user="hello"} 44391273527 (41.34 GB)
telemt_user_msgs_from_client{user="hello"} 2008293
telemt_user_msgs_to_client{user="hello"} 10576690
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 50243.7 (13h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73440
telemt_connections_bad_total 673
telemt_handshake_timeouts_total 4292
telemt_upstream_connect_attempt_total 64407
telemt_upstream_connect_success_total 64404
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 64407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7287
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 64398
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 11767397557 (10.96 GB)
telemt_user_octets_to_client{user="hello"} 70866567500 (66.00 GB)
telemt_user_msgs_from_client{user="hello"} 5166753
telemt_user_msgs_to_client{user="hello"} 13301043
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 50243.0 (13h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75306
telemt_connections_bad_total 155
telemt_handshake_timeouts_total 566
telemt_upstream_connect_attempt_total 72105
telemt_upstream_connect_success_total 71942
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 72105
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9281
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 71936
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 1797285202 (1.67 GB)
telemt_user_octets_to_client{user="hello"} 45697193285 (42.56 GB)
telemt_user_msgs_from_client{user="hello"} 1669909
telemt_user_msgs_to_client{user="hello"} 9610613
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 50244.1 (13h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119296
telemt_connections_bad_total 11380
telemt_handshake_timeouts_total 1658
telemt_upstream_connect_attempt_total 101701
telemt_upstream_connect_success_total 101451
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 101700
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 88842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12380
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 101445
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 2332436526 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 94752834735 (88.25 GB)
telemt_user_msgs_from_client{user="hello"} 2493706
telemt_user_msgs_to_client{user="hello"} 12187983
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 29213.4 (8h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```