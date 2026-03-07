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

# Server Metrics 2026-03-07 01:41:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 27208.1 (7h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33931
telemt_connections_bad_total 200
telemt_handshake_timeouts_total 494
telemt_upstream_connect_attempt_total 31683
telemt_upstream_connect_success_total 31675
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 31683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29751
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1896
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31671
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 2084801021 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 33134822485 (30.86 GB)
telemt_user_msgs_from_client{user="hello"} 1388084
telemt_user_msgs_to_client{user="hello"} 5228090
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 27207.0 (7h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6726
telemt_connections_bad_total 174
telemt_handshake_timeouts_total 104
telemt_upstream_connect_attempt_total 6294
telemt_upstream_connect_success_total 6291
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6287
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 215511952 (205.53 MB)
telemt_user_octets_to_client{user="hello"} 3897788475 (3.63 GB)
telemt_user_msgs_from_client{user="hello"} 202400
telemt_user_msgs_to_client{user="hello"} 1090579
telemt_user_unique_ips_current{user="hello"} 4
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 27207.0 (7h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3242
telemt_connections_bad_total 170
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 2950
telemt_upstream_connect_success_total 2950
telemt_upstream_connect_attempts_per_request{bucket="1"} 2950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 265
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2946
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 65396766 (62.37 MB)
telemt_user_octets_to_client{user="hello"} 1871874407 (1.74 GB)
telemt_user_msgs_from_client{user="hello"} 64857
telemt_user_msgs_to_client{user="hello"} 397592
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 27207.0 (7h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4511
telemt_connections_bad_total 130
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 4309
telemt_upstream_connect_success_total 4302
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 408
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4298
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 101009286 (96.33 MB)
telemt_user_octets_to_client{user="hello"} 1374656429 (1.28 GB)
telemt_user_msgs_from_client{user="hello"} 86635
telemt_user_msgs_to_client{user="hello"} 355527
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 27207.3 (7h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12860
telemt_connections_bad_total 5844
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 6855
telemt_upstream_connect_success_total 6854
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6855
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1066
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6850
telemt_user_connections_current{user="hello"} 1
telemt_user_octets_from_client{user="hello"} 229415284 (218.79 MB)
telemt_user_octets_to_client{user="hello"} 7685584281 (7.16 GB)
telemt_user_msgs_from_client{user="hello"} 219107
telemt_user_msgs_to_client{user="hello"} 1576715
telemt_user_unique_ips_current{user="hello"} 1
telemt_user_unique_ips_recent_window{user="hello"} 1
```