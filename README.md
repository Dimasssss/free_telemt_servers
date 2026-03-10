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

# Server Metrics 2026-03-10 12:46:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 134824.0 (37h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 301310
telemt_connections_bad_total 3468
telemt_handshake_timeouts_total 3105
telemt_upstream_connect_attempt_total 282143
telemt_upstream_connect_success_total 281990
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 282143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 260778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21123
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 281978
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 6621957846 (6.17 GB)
telemt_user_octets_to_client{user="hello"} 187953076622 (175.04 GB)
telemt_user_msgs_from_client{user="hello"} 6827945
telemt_user_msgs_to_client{user="hello"} 11049433
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 134822.8 (37h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92653
telemt_connections_bad_total 3271
telemt_handshake_timeouts_total 1276
telemt_upstream_connect_attempt_total 83298
telemt_upstream_connect_success_total 83254
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 83298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7916
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 422
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 83240
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 2786736861 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 35430184191 (33.00 GB)
telemt_user_msgs_from_client{user="hello"} 2225967
telemt_user_msgs_to_client{user="hello"} 10255609
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 134823.2 (37h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131410
telemt_connections_bad_total 1219
telemt_handshake_timeouts_total 6302
telemt_upstream_connect_attempt_total 97167
telemt_upstream_connect_success_total 97164
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 97167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 86080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11050
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 97152
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 6617111710 (6.16 GB)
telemt_user_octets_to_client{user="hello"} 67242617852 (62.62 GB)
telemt_user_msgs_from_client{user="hello"} 4410462
telemt_user_msgs_to_client{user="hello"} 11231851
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 134818.0 (37h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136387
telemt_connections_bad_total 1053
telemt_handshake_timeouts_total 2915
telemt_upstream_connect_attempt_total 125750
telemt_upstream_connect_success_total 125475
telemt_upstream_connect_fail_total 275
telemt_upstream_connect_attempts_per_request{bucket="1"} 125750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13601
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 80
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 320
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 275
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 125461
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 4027370520 (3.75 GB)
telemt_user_octets_to_client{user="hello"} 87118374847 (81.14 GB)
telemt_user_msgs_from_client{user="hello"} 3382567
telemt_user_msgs_to_client{user="hello"} 19839042
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 134823.4 (37h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202519
telemt_connections_bad_total 30174
telemt_handshake_timeouts_total 5525
telemt_upstream_connect_attempt_total 158321
telemt_upstream_connect_success_total 157359
telemt_upstream_connect_fail_total 962
telemt_upstream_connect_attempts_per_request{bucket="1"} 158321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 136365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20774
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 962
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 157345
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 3444696568 (3.21 GB)
telemt_user_octets_to_client{user="hello"} 116071496060 (108.10 GB)
telemt_user_msgs_from_client{user="hello"} 3635346
telemt_user_msgs_to_client{user="hello"} 15804769
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 19
```