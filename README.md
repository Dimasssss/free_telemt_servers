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

# Server Metrics 2026-03-10 10:08:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 125307.0 (34h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 262894
telemt_connections_bad_total 3451
telemt_handshake_timeouts_total 2713
telemt_upstream_connect_attempt_total 246122
telemt_upstream_connect_success_total 246035
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 246122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 227233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 246023
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 6121551851 (5.70 GB)
telemt_user_octets_to_client{user="hello"} 147494133076 (137.36 GB)
telemt_user_msgs_from_client{user="hello"} 5950204
telemt_user_msgs_to_client{user="hello"} 9382960
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 125305.8 (34h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79235
telemt_connections_bad_total 3258
telemt_handshake_timeouts_total 1042
telemt_upstream_connect_attempt_total 70888
telemt_upstream_connect_success_total 70845
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 70888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6688
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 400
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 70833
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 2336182057 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 32863970731 (30.61 GB)
telemt_user_msgs_from_client{user="hello"} 1933938
telemt_user_msgs_to_client{user="hello"} 9401820
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 125306.3 (34h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113896
telemt_connections_bad_total 1155
telemt_handshake_timeouts_total 5619
telemt_upstream_connect_attempt_total 81318
telemt_upstream_connect_success_total 81316
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 81318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9256
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 81304
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 6389260282 (5.95 GB)
telemt_user_octets_to_client{user="hello"} 63190445839 (58.85 GB)
telemt_user_msgs_from_client{user="hello"} 4109135
telemt_user_msgs_to_client{user="hello"} 10169077
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 125301.1 (34h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116020
telemt_connections_bad_total 1024
telemt_handshake_timeouts_total 1343
telemt_upstream_connect_attempt_total 107964
telemt_upstream_connect_success_total 107723
telemt_upstream_connect_fail_total 241
telemt_upstream_connect_attempts_per_request{bucket="1"} 107964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 95402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12005
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 61
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 255
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 241
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 107711
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 2965412670 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 79637188574 (74.17 GB)
telemt_user_msgs_from_client{user="hello"} 2759912
telemt_user_msgs_to_client{user="hello"} 18252302
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 125306.4 (34h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175939
telemt_connections_bad_total 27443
telemt_handshake_timeouts_total 4441
telemt_upstream_connect_attempt_total 136641
telemt_upstream_connect_success_total 135835
telemt_upstream_connect_fail_total 806
telemt_upstream_connect_attempts_per_request{bucket="1"} 136641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18264
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 806
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 135821
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 2044539139 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 106861776321 (99.52 GB)
telemt_user_msgs_from_client{user="hello"} 2844059
telemt_user_msgs_to_client{user="hello"} 14552644
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 29
```