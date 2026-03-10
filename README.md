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

# Server Metrics 2026-03-10 14:08:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 139739.7 (38h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 321712
telemt_connections_bad_total 3679
telemt_handshake_timeouts_total 3372
telemt_upstream_connect_attempt_total 301166
telemt_upstream_connect_success_total 301006
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 301166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 278288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22617
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 300992
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 6883744680 (6.41 GB)
telemt_user_octets_to_client{user="hello"} 198319919620 (184.70 GB)
telemt_user_msgs_from_client{user="hello"} 7187607
telemt_user_msgs_to_client{user="hello"} 11816062
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 139738.5 (38h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99456
telemt_connections_bad_total 3275
telemt_handshake_timeouts_total 1308
telemt_upstream_connect_attempt_total 89794
telemt_upstream_connect_success_total 89748
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 89794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8633
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 89734
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 2888633130 (2.69 GB)
telemt_user_octets_to_client{user="hello"} 38273057342 (35.64 GB)
telemt_user_msgs_from_client{user="hello"} 2352489
telemt_user_msgs_to_client{user="hello"} 11064762
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 139739.0 (38h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142667
telemt_connections_bad_total 1241
telemt_handshake_timeouts_total 6894
telemt_upstream_connect_attempt_total 107185
telemt_upstream_connect_success_total 107182
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 107185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 94817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12324
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 107168
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 6699133448 (6.24 GB)
telemt_user_octets_to_client{user="hello"} 69469405853 (64.70 GB)
telemt_user_msgs_from_client{user="hello"} 4585843
telemt_user_msgs_to_client{user="hello"} 11812682
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 139733.9 (38h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146346
telemt_connections_bad_total 1064
telemt_handshake_timeouts_total 3064
telemt_upstream_connect_attempt_total 135283
telemt_upstream_connect_success_total 134978
telemt_upstream_connect_fail_total 305
telemt_upstream_connect_attempts_per_request{bucket="1"} 135283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 119955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14589
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 86
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 348
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 305
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 134964
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 5072760641 (4.72 GB)
telemt_user_octets_to_client{user="hello"} 94566479090 (88.07 GB)
telemt_user_msgs_from_client{user="hello"} 3909846
telemt_user_msgs_to_client{user="hello"} 21420431
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 139739.3 (38h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216794
telemt_connections_bad_total 31239
telemt_handshake_timeouts_total 6233
telemt_upstream_connect_attempt_total 170324
telemt_upstream_connect_success_total 169362
telemt_upstream_connect_fail_total 962
telemt_upstream_connect_attempts_per_request{bucket="1"} 170324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 146535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22601
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 962
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 169348
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 3651568878 (3.40 GB)
telemt_user_octets_to_client{user="hello"} 120275233505 (112.02 GB)
telemt_user_msgs_from_client{user="hello"} 3869865
telemt_user_msgs_to_client{user="hello"} 16542949
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 34
```