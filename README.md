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

# Server Metrics 2026-03-10 10:54:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 128067.6 (35h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 273980
telemt_connections_bad_total 3454
telemt_handshake_timeouts_total 2968
telemt_upstream_connect_attempt_total 256146
telemt_upstream_connect_success_total 256001
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 256146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 236401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 255989
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 6253260470 (5.82 GB)
telemt_user_octets_to_client{user="hello"} 155808006267 (145.11 GB)
telemt_user_msgs_from_client{user="hello"} 6170102
telemt_user_msgs_to_client{user="hello"} 9781826
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 128066.2 (35h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83162
telemt_connections_bad_total 3260
telemt_handshake_timeouts_total 1142
telemt_upstream_connect_attempt_total 74423
telemt_upstream_connect_success_total 74380
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 74423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7068
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 406
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 74366
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 2412719379 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 33636979936 (31.33 GB)
telemt_user_msgs_from_client{user="hello"} 1996352
telemt_user_msgs_to_client{user="hello"} 9652766
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 128066.8 (35h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118645
telemt_connections_bad_total 1163
telemt_handshake_timeouts_total 6033
telemt_upstream_connect_attempt_total 85398
telemt_upstream_connect_success_total 85396
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 85398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 75423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9949
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 85384
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 6426232564 (5.98 GB)
telemt_user_octets_to_client{user="hello"} 64474577968 (60.05 GB)
telemt_user_msgs_from_client{user="hello"} 4189003
telemt_user_msgs_to_client{user="hello"} 10531538
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 128061.6 (35h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121011
telemt_connections_bad_total 1030
telemt_handshake_timeouts_total 1358
telemt_upstream_connect_attempt_total 112735
telemt_upstream_connect_success_total 112489
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 112735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 99622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12537
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 63
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 267
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 112477
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 3068528549 (2.86 GB)
telemt_user_octets_to_client{user="hello"} 80968781748 (75.41 GB)
telemt_user_msgs_from_client{user="hello"} 2857201
telemt_user_msgs_to_client{user="hello"} 18563188
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 128067.0 (35h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183943
telemt_connections_bad_total 27978
telemt_handshake_timeouts_total 4663
telemt_upstream_connect_attempt_total 143515
telemt_upstream_connect_success_total 142555
telemt_upstream_connect_fail_total 960
telemt_upstream_connect_attempts_per_request{bucket="1"} 143515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 123118
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19236
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 201
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 960
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 142541
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 3111617875 (2.90 GB)
telemt_user_octets_to_client{user="hello"} 109912458678 (102.36 GB)
telemt_user_msgs_from_client{user="hello"} 3300488
telemt_user_msgs_to_client{user="hello"} 14916332
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 31
```