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

# Server Metrics 2026-03-11 04:38:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 51161.6 (14h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130341
telemt_connections_bad_total 3386
telemt_handshake_timeouts_total 2787
telemt_upstream_connect_attempt_total 118203
telemt_upstream_connect_success_total 118160
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 118203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 107810
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10295
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 118154
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 3029953426 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 85360734419 (79.50 GB)
telemt_user_msgs_from_client{user="hello"} 3125089
telemt_user_msgs_to_client{user="hello"} 5932070
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 51160.8 (14h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53494
telemt_connections_bad_total 412
telemt_handshake_timeouts_total 2948
telemt_upstream_connect_attempt_total 47324
telemt_upstream_connect_success_total 47314
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 47324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7121
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 47308
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 4438447793 (4.13 GB)
telemt_user_octets_to_client{user="hello"} 44473139911 (41.42 GB)
telemt_user_msgs_from_client{user="hello"} 2586314
telemt_user_msgs_to_client{user="hello"} 10619394
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 51160.6 (14h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74340
telemt_connections_bad_total 673
telemt_handshake_timeouts_total 4304
telemt_upstream_connect_attempt_total 65182
telemt_upstream_connect_success_total 65179
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 65182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57755
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7372
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 65173
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 11772260013 (10.96 GB)
telemt_user_octets_to_client{user="hello"} 71055207873 (66.18 GB)
telemt_user_msgs_from_client{user="hello"} 5177268
telemt_user_msgs_to_client{user="hello"} 13342667
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 51159.5 (14h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76589
telemt_connections_bad_total 155
telemt_handshake_timeouts_total 570
telemt_upstream_connect_attempt_total 73346
telemt_upstream_connect_success_total 73183
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 73346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9475
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 192
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 73177
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 1808586742 (1.68 GB)
telemt_user_octets_to_client{user="hello"} 47884532241 (44.60 GB)
telemt_user_msgs_from_client{user="hello"} 1700208
telemt_user_msgs_to_client{user="hello"} 10552879
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 51160.9 (14h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121758
telemt_connections_bad_total 11563
telemt_handshake_timeouts_total 1667
telemt_upstream_connect_attempt_total 103610
telemt_upstream_connect_success_total 103361
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 103610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 90448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12683
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 103355
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 2360523043 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 97288076227 (90.61 GB)
telemt_user_msgs_from_client{user="hello"} 2534207
telemt_user_msgs_to_client{user="hello"} 12583103
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 30130.3 (8h 22m)
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