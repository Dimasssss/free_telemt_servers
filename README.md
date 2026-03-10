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

# Server Metrics 2026-03-10 22:37:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 29464.9 (8h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95321
telemt_connections_bad_total 3305
telemt_handshake_timeouts_total 2203
telemt_upstream_connect_attempt_total 85582
telemt_upstream_connect_success_total 85550
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 85582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 77991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7506
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 85546
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 2560193228 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 68980784587 (64.24 GB)
telemt_user_msgs_from_client{user="hello"} 2485518
telemt_user_msgs_to_client{user="hello"} 4554103
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 29464.4 (8h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36425
telemt_connections_bad_total 323
telemt_handshake_timeouts_total 741
telemt_upstream_connect_attempt_total 33188
telemt_upstream_connect_success_total 33179
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 33188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4876
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33175
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 1680152208 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 34806864091 (32.42 GB)
telemt_user_msgs_from_client{user="hello"} 1363933
telemt_user_msgs_to_client{user="hello"} 8722043
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 29464.0 (8h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58966
telemt_connections_bad_total 446
telemt_handshake_timeouts_total 4035
telemt_upstream_connect_attempt_total 51095
telemt_upstream_connect_success_total 51093
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 51095
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46079
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4966
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51089
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 772227847 (736.45 MB)
telemt_user_octets_to_client{user="hello"} 48086221994 (44.78 GB)
telemt_user_msgs_from_client{user="hello"} 1080272
telemt_user_msgs_to_client{user="hello"} 7196569
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 29463.0 (8h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54213
telemt_connections_bad_total 87
telemt_handshake_timeouts_total 329
telemt_upstream_connect_attempt_total 52047
telemt_upstream_connect_success_total 51902
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 52047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6160
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51898
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 823868302 (785.70 MB)
telemt_user_octets_to_client{user="hello"} 37293418080 (34.73 GB)
telemt_user_msgs_from_client{user="hello"} 1119033
telemt_user_msgs_to_client{user="hello"} 7123242
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 29464.3 (8h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79250
telemt_connections_bad_total 7287
telemt_handshake_timeouts_total 1456
telemt_upstream_connect_attempt_total 67417
telemt_upstream_connect_success_total 67169
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 67417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 67165
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 2055072396 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 54602939104 (50.85 GB)
telemt_user_msgs_from_client{user="hello"} 1909978
telemt_user_msgs_to_client{user="hello"} 7919414
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 8433.7 (2h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33
telemt_connections_bad_total 31
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```