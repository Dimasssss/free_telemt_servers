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

# Server Metrics 2026-03-11 20:31:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 12641.1 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45649
telemt_connections_bad_total 2484
telemt_handshake_timeouts_total 213
telemt_upstream_connect_attempt_total 40994
telemt_upstream_connect_success_total 40984
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 40994
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3802
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 40982
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 1411788445 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 23599253066 (21.98 GB)
telemt_user_msgs_from_client{user="hello"} 1139461
telemt_user_msgs_to_client{user="hello"} 1995665
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 12629.3 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21026
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 255
telemt_upstream_connect_attempt_total 19401
telemt_upstream_connect_success_total 19362
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 19401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2357
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 325
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19360
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 228475632 (217.89 MB)
telemt_user_octets_to_client{user="hello"} 10081517668 (9.39 GB)
telemt_user_msgs_from_client{user="hello"} 396278
telemt_user_msgs_to_client{user="hello"} 4036761
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 12649.2 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25467
telemt_connections_bad_total 29
telemt_handshake_timeouts_total 238
telemt_upstream_connect_attempt_total 23833
telemt_upstream_connect_success_total 23831
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 23833
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2122
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23829
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 235883808 (224.96 MB)
telemt_user_octets_to_client{user="hello"} 9537986621 (8.88 GB)
telemt_user_msgs_from_client{user="hello"} 458184
telemt_user_msgs_to_client{user="hello"} 2376625
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 12644.5 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27926
telemt_connections_bad_total 1803
telemt_handshake_timeouts_total 393
telemt_upstream_connect_attempt_total 24437
telemt_upstream_connect_success_total 24363
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 24437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2296
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24361
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 668881055 (637.89 MB)
telemt_user_octets_to_client{user="hello"} 13235775527 (12.33 GB)
telemt_user_msgs_from_client{user="hello"} 573271
telemt_user_msgs_to_client{user="hello"} 3824858
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 12652.8 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30448
telemt_connections_bad_total 2411
telemt_handshake_timeouts_total 173
telemt_upstream_connect_attempt_total 26933
telemt_upstream_connect_success_total 26932
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 26933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3274
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26930
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 487494717 (464.91 MB)
telemt_user_octets_to_client{user="hello"} 10376752523 (9.66 GB)
telemt_user_msgs_from_client{user="hello"} 612100
telemt_user_msgs_to_client{user="hello"} 3842035
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 87259.1 (24h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 825
telemt_connections_bad_total 493
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 303
telemt_upstream_connect_success_total 303
telemt_upstream_connect_attempts_per_request{bucket="1"} 303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 295
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 2343077 (2.23 MB)
telemt_user_octets_to_client{user="hello"} 110823605 (105.69 MB)
telemt_user_msgs_from_client{user="hello"} 4363
telemt_user_msgs_to_client{user="hello"} 12845
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```