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

# Server Metrics 2026-03-10 09:12:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 121929.8 (33h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 249359
telemt_connections_bad_total 3427
telemt_handshake_timeouts_total 2140
telemt_upstream_connect_attempt_total 233946
telemt_upstream_connect_success_total 233873
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 233946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 215778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18029
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 233861
telemt_user_connections_current{user="hello"} 279
telemt_user_octets_from_client{user="hello"} 5831128298 (5.43 GB)
telemt_user_octets_to_client{user="hello"} 139409467603 (129.84 GB)
telemt_user_msgs_from_client{user="hello"} 5664388
telemt_user_msgs_to_client{user="hello"} 8799358
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 121928.5 (33h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75167
telemt_connections_bad_total 3227
telemt_handshake_timeouts_total 1019
telemt_upstream_connect_attempt_total 67043
telemt_upstream_connect_success_total 67001
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 67043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6329
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 396
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 66989
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 2309647152 (2.15 GB)
telemt_user_octets_to_client{user="hello"} 31746320538 (29.57 GB)
telemt_user_msgs_from_client{user="hello"} 1875290
telemt_user_msgs_to_client{user="hello"} 9043824
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 121928.9 (33h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108458
telemt_connections_bad_total 1141
telemt_handshake_timeouts_total 5096
telemt_upstream_connect_attempt_total 76589
telemt_upstream_connect_success_total 76587
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 76589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8744
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 76575
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 6337825086 (5.90 GB)
telemt_user_octets_to_client{user="hello"} 60750388568 (56.58 GB)
telemt_user_msgs_from_client{user="hello"} 4005177
telemt_user_msgs_to_client{user="hello"} 9700401
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 121923.7 (33h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109443
telemt_connections_bad_total 949
telemt_handshake_timeouts_total 1300
telemt_upstream_connect_attempt_total 101708
telemt_upstream_connect_success_total 101483
telemt_upstream_connect_fail_total 225
telemt_upstream_connect_attempts_per_request{bucket="1"} 101708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 89784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11402
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 60
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 237
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 225
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 101471
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 2914755150 (2.71 GB)
telemt_user_octets_to_client{user="hello"} 75354737723 (70.18 GB)
telemt_user_msgs_from_client{user="hello"} 2644705
telemt_user_msgs_to_client{user="hello"} 17089761
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 121929.2 (33h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167572
telemt_connections_bad_total 26812
telemt_handshake_timeouts_total 4196
telemt_upstream_connect_attempt_total 129486
telemt_upstream_connect_success_total 128684
telemt_upstream_connect_fail_total 802
telemt_upstream_connect_attempts_per_request{bucket="1"} 129486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17409
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 802
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 128672
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 1996231262 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 104529811628 (97.35 GB)
telemt_user_msgs_from_client{user="hello"} 2741089
telemt_user_msgs_to_client{user="hello"} 14142631
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 19
```