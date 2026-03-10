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

# Server Metrics 2026-03-10 22:42:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 29771.8 (8h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95650
telemt_connections_bad_total 3305
telemt_handshake_timeouts_total 2207
telemt_upstream_connect_attempt_total 85899
telemt_upstream_connect_success_total 85867
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 85899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 78266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7548
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 85863
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 2563911721 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 69169583183 (64.42 GB)
telemt_user_msgs_from_client{user="hello"} 2495528
telemt_user_msgs_to_client{user="hello"} 4589995
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 29770.8 (8h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36619
telemt_connections_bad_total 331
telemt_handshake_timeouts_total 756
telemt_upstream_connect_attempt_total 33334
telemt_upstream_connect_success_total 33325
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 33334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4917
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33321
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 1681507927 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 34934602243 (32.54 GB)
telemt_user_msgs_from_client{user="hello"} 1367366
telemt_user_msgs_to_client{user="hello"} 8763130
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 29770.5 (8h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59205
telemt_connections_bad_total 446
telemt_handshake_timeouts_total 4056
telemt_upstream_connect_attempt_total 51270
telemt_upstream_connect_success_total 51268
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 51270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4995
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51264
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 774179198 (738.31 MB)
telemt_user_octets_to_client{user="hello"} 48264568046 (44.95 GB)
telemt_user_msgs_from_client{user="hello"} 1085301
telemt_user_msgs_to_client{user="hello"} 7224416
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 29769.4 (8h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54444
telemt_connections_bad_total 87
telemt_handshake_timeouts_total 329
telemt_upstream_connect_attempt_total 52262
telemt_upstream_connect_success_total 52113
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 52262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6180
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 52109
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 824828514 (786.62 MB)
telemt_user_octets_to_client{user="hello"} 37328777759 (34.77 GB)
telemt_user_msgs_from_client{user="hello"} 1121762
telemt_user_msgs_to_client{user="hello"} 7132487
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 29770.7 (8h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79783
telemt_connections_bad_total 7342
telemt_handshake_timeouts_total 1457
telemt_upstream_connect_attempt_total 67886
telemt_upstream_connect_success_total 67638
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 67886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8944
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 67634
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 2058260350 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 54969788726 (51.19 GB)
telemt_user_msgs_from_client{user="hello"} 1917920
telemt_user_msgs_to_client{user="hello"} 8034566
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 8740.2 (2h 25m)
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