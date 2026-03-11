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

# Server Metrics 2026-03-11 15:17:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 89498.3 (24h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 302074
telemt_connections_bad_total 4546
telemt_handshake_timeouts_total 5144
telemt_upstream_connect_attempt_total 278891
telemt_upstream_connect_success_total 278809
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 278889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 254965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23783
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 278799
telemt_user_connections_current{user="hello"} 336
telemt_user_octets_from_client{user="hello"} 5138198603 (4.79 GB)
telemt_user_octets_to_client{user="hello"} 138035633651 (128.56 GB)
telemt_user_msgs_from_client{user="hello"} 6031453
telemt_user_msgs_to_client{user="hello"} 11075015
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 89497.8 (24h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119502
telemt_connections_bad_total 966
telemt_handshake_timeouts_total 3409
telemt_upstream_connect_attempt_total 109991
telemt_upstream_connect_success_total 109970
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 109991
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 95563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13897
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 510
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 109960
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 6008819929 (5.60 GB)
telemt_user_octets_to_client{user="hello"} 69439759444 (64.67 GB)
telemt_user_msgs_from_client{user="hello"} 4012641
telemt_user_msgs_to_client{user="hello"} 20129205
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 89497.6 (24h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164320
telemt_connections_bad_total 1251
telemt_handshake_timeouts_total 7158
telemt_upstream_connect_attempt_total 146793
telemt_upstream_connect_success_total 146779
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 146793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16323
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 146769
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 12723493944 (11.85 GB)
telemt_user_octets_to_client{user="hello"} 130221748284 (121.28 GB)
telemt_user_msgs_from_client{user="hello"} 6819142
telemt_user_msgs_to_client{user="hello"} 29132868
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 89496.6 (24h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183169
telemt_connections_bad_total 8146
telemt_handshake_timeouts_total 2124
telemt_upstream_connect_attempt_total 165620
telemt_upstream_connect_success_total 165215
telemt_upstream_connect_fail_total 405
telemt_upstream_connect_attempts_per_request{bucket="1"} 165620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 143892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20782
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 450
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 405
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 165205
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 9847388049 (9.17 GB)
telemt_user_octets_to_client{user="hello"} 114787839205 (106.90 GB)
telemt_user_msgs_from_client{user="hello"} 5863335
telemt_user_msgs_to_client{user="hello"} 34339663
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 89497.9 (24h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259944
telemt_connections_bad_total 19706
telemt_handshake_timeouts_total 6329
telemt_upstream_connect_attempt_total 211864
telemt_upstream_connect_success_total 211360
telemt_upstream_connect_fail_total 504
telemt_upstream_connect_attempts_per_request{bucket="1"} 211864
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 183077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27925
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 358
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 504
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 211352
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 5090271642 (4.74 GB)
telemt_user_octets_to_client{user="hello"} 173073414625 (161.19 GB)
telemt_user_msgs_from_client{user="hello"} 4996547
telemt_user_msgs_to_client{user="hello"} 24081990
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 68467.1 (19h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 465
telemt_connections_bad_total 442
telemt_handshake_timeouts_total 11
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