# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

-----

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

# Server Metrics 2026-03-10 12:57:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 135438.0 (37h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 304051
telemt_connections_bad_total 3469
telemt_handshake_timeouts_total 3109
telemt_upstream_connect_attempt_total 284793
telemt_upstream_connect_success_total 284639
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 284793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 263243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21306
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 284625
telemt_user_connections_current{user="hello"} 367
telemt_user_octets_from_client{user="hello"} 6644911698 (6.19 GB)
telemt_user_octets_to_client{user="hello"} 189333754296 (176.33 GB)
telemt_user_msgs_from_client{user="hello"} 6870823
telemt_user_msgs_to_client{user="hello"} 11146372
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 135436.9 (37h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93543
telemt_connections_bad_total 3271
telemt_handshake_timeouts_total 1276
telemt_upstream_connect_attempt_total 84173
telemt_upstream_connect_success_total 84129
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 84173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 75667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8038
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 423
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 84115
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 2791336638 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 35581794264 (33.14 GB)
telemt_user_msgs_from_client{user="hello"} 2239173
telemt_user_msgs_to_client{user="hello"} 10307532
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 135437.2 (37h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132761
telemt_connections_bad_total 1223
telemt_handshake_timeouts_total 6336
telemt_upstream_connect_attempt_total 98415
telemt_upstream_connect_success_total 98412
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 98415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 87197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11177
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 98400
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 6634288653 (6.18 GB)
telemt_user_octets_to_client{user="hello"} 67399752251 (62.77 GB)
telemt_user_msgs_from_client{user="hello"} 4431396
telemt_user_msgs_to_client{user="hello"} 11282794
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 135432.1 (37h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137556
telemt_connections_bad_total 1053
telemt_handshake_timeouts_total 2916
telemt_upstream_connect_attempt_total 126882
telemt_upstream_connect_success_total 126603
telemt_upstream_connect_fail_total 279
telemt_upstream_connect_attempts_per_request{bucket="1"} 126882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13741
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 80
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 321
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 279
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 126589
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 4398644351 (4.10 GB)
telemt_user_octets_to_client{user="hello"} 87839178073 (81.81 GB)
telemt_user_msgs_from_client{user="hello"} 3530663
telemt_user_msgs_to_client{user="hello"} 20000281
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 135437.4 (37h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203769
telemt_connections_bad_total 30297
telemt_handshake_timeouts_total 5540
telemt_upstream_connect_attempt_total 159388
telemt_upstream_connect_success_total 158426
telemt_upstream_connect_fail_total 962
telemt_upstream_connect_attempts_per_request{bucket="1"} 159388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 137247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20959
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 962
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 158412
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 3461478191 (3.22 GB)
telemt_user_octets_to_client{user="hello"} 116648590981 (108.64 GB)
telemt_user_msgs_from_client{user="hello"} 3659462
telemt_user_msgs_to_client{user="hello"} 15883550
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 13
```