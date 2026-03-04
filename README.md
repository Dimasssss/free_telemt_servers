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

# Server Metrics 2026-03-04 19:10:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 27791.2 (7h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45010
telemt_connections_bad_total 80
telemt_handshake_timeouts_total 1307
telemt_upstream_connect_attempt_total 42620
telemt_upstream_connect_success_total 42610
telemt_upstream_connect_attempts_per_request{bucket="1"} 42600
telemt_upstream_connect_attempts_per_request{bucket="2"} 10
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2454
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42606
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 1433446058 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 34379522371 (32.02 GB)
telemt_user_msgs_from_client{user="hello"} 1334375
telemt_user_msgs_to_client{user="hello"} 5417117
telemt_user_unique_ips_current{user="hello"} 12
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 27794.3 (7h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10009
telemt_connections_bad_total 120
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 9404
telemt_upstream_connect_success_total 9402
telemt_upstream_connect_attempts_per_request{bucket="1"} 9400
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 582
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9398
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 846098699 (806.90 MB)
telemt_user_octets_to_client{user="hello"} 10528693711 (9.81 GB)
telemt_user_msgs_from_client{user="hello"} 539931
telemt_user_msgs_to_client{user="hello"} 3556674
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 27792.0 (7h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5769
telemt_connections_bad_total 55
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 5590
telemt_upstream_connect_success_total 5590
telemt_upstream_connect_attempts_per_request{bucket="1"} 5590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 373
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5586
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 234003490 (223.16 MB)
telemt_user_octets_to_client{user="hello"} 4185115749 (3.90 GB)
telemt_user_msgs_from_client{user="hello"} 209582
telemt_user_msgs_to_client{user="hello"} 902317
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 27790.0 (7h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9436
telemt_connections_bad_total 431
telemt_handshake_timeouts_total 54
telemt_upstream_connect_attempt_total 8461
telemt_upstream_connect_success_total 8457
telemt_upstream_connect_attempts_per_request{bucket="1"} 8453
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 662
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8453
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 134598312 (128.36 MB)
telemt_user_octets_to_client{user="hello"} 4393660981 (4.09 GB)
telemt_user_msgs_from_client{user="hello"} 160281
telemt_user_msgs_to_client{user="hello"} 1065066
telemt_user_unique_ips_current{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 27791.7 (7h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11351
telemt_connections_bad_total 4936
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 6188
telemt_upstream_connect_success_total 6185
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6184
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 847
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6181
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 182437302 (173.99 MB)
telemt_user_octets_to_client{user="hello"} 11893054909 (11.08 GB)
telemt_user_msgs_from_client{user="hello"} 282487
telemt_user_msgs_to_client{user="hello"} 2269025
telemt_user_unique_ips_current{user="hello"} 3
```