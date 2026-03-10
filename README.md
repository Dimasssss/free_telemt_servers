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

# Server Metrics 2026-03-10 10:44:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 127454.3 (35h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 271179
telemt_connections_bad_total 3452
telemt_handshake_timeouts_total 2911
telemt_upstream_connect_attempt_total 253778
telemt_upstream_connect_success_total 253634
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 253778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 234241
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19310
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 253622
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 6199411774 (5.77 GB)
telemt_user_octets_to_client{user="hello"} 154237645664 (143.65 GB)
telemt_user_msgs_from_client{user="hello"} 6109482
telemt_user_msgs_to_client{user="hello"} 9677683
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 127452.9 (35h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82052
telemt_connections_bad_total 3260
telemt_handshake_timeouts_total 1098
telemt_upstream_connect_attempt_total 73427
telemt_upstream_connect_success_total 73384
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 73427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6966
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 405
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 73370
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 2386093477 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 33377408739 (31.09 GB)
telemt_user_msgs_from_client{user="hello"} 1978371
telemt_user_msgs_to_client{user="hello"} 9578995
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 127453.4 (35h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117761
telemt_connections_bad_total 1163
telemt_handshake_timeouts_total 5987
telemt_upstream_connect_attempt_total 84588
telemt_upstream_connect_success_total 84586
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 84588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9823
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 84574
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 6421177834 (5.98 GB)
telemt_user_octets_to_client{user="hello"} 64273827433 (59.86 GB)
telemt_user_msgs_from_client{user="hello"} 4172914
telemt_user_msgs_to_client{user="hello"} 10480475
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 127448.2 (35h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120047
telemt_connections_bad_total 1029
telemt_handshake_timeouts_total 1354
telemt_upstream_connect_attempt_total 111812
telemt_upstream_connect_success_total 111567
telemt_upstream_connect_fail_total 245
telemt_upstream_connect_attempts_per_request{bucket="1"} 111812
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 98803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12436
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 63
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 265
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 245
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 111555
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 3063106006 (2.85 GB)
telemt_user_octets_to_client{user="hello"} 80836497228 (75.28 GB)
telemt_user_msgs_from_client{user="hello"} 2846114
telemt_user_msgs_to_client{user="hello"} 18526470
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 127453.6 (35h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182435
telemt_connections_bad_total 27869
telemt_handshake_timeouts_total 4557
telemt_upstream_connect_attempt_total 142275
telemt_upstream_connect_success_total 141314
telemt_upstream_connect_fail_total 960
telemt_upstream_connect_attempts_per_request{bucket="1"} 142274
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 122080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19033
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 201
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 960
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 141300
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 2114301626 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 109341477134 (101.83 GB)
telemt_user_msgs_from_client{user="hello"} 2934079
telemt_user_msgs_to_client{user="hello"} 14838623
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 16
```