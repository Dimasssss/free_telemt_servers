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

# Server Metrics 2026-03-08 06:16:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 48662.0 (13h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70675
telemt_connections_bad_total 6040
telemt_handshake_timeouts_total 490
telemt_upstream_connect_attempt_total 60713
telemt_upstream_connect_success_total 60594
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 60713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3163
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 60588
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 2556977247 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 39361034722 (36.66 GB)
telemt_user_msgs_from_client{user="hello"} 1790825
telemt_user_msgs_to_client{user="hello"} 6179869
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 48661.4 (13h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10578
telemt_connections_bad_total 371
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 10019
telemt_upstream_connect_success_total 10010
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 10019
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9171
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 789
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10004
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 280491064 (267.50 MB)
telemt_user_octets_to_client{user="hello"} 15437406196 (14.38 GB)
telemt_user_msgs_from_client{user="hello"} 503202
telemt_user_msgs_to_client{user="hello"} 3576698
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 48661.0 (13h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6667
telemt_connections_bad_total 306
telemt_handshake_timeouts_total 260
telemt_upstream_connect_attempt_total 5972
telemt_upstream_connect_success_total 5972
telemt_upstream_connect_attempts_per_request{bucket="1"} 5972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 790
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5966
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 135357991 (129.09 MB)
telemt_user_octets_to_client{user="hello"} 14735914390 (13.72 GB)
telemt_user_msgs_from_client{user="hello"} 244745
telemt_user_msgs_to_client{user="hello"} 3151809
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 48489.4 (13h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15432
telemt_connections_bad_total 243
telemt_handshake_timeouts_total 62
telemt_upstream_connect_attempt_total 14799
telemt_upstream_connect_success_total 14773
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 14799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12446
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2251
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14767
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 478440994 (456.28 MB)
telemt_user_octets_to_client{user="hello"} 13465709875 (12.54 GB)
telemt_user_msgs_from_client{user="hello"} 459620
telemt_user_msgs_to_client{user="hello"} 3766837
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 48661.2 (13h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19946
telemt_connections_bad_total 9007
telemt_handshake_timeouts_total 43
telemt_upstream_connect_attempt_total 10657
telemt_upstream_connect_success_total 10649
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 10657
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2373
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10645
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 1653343522 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 10626917105 (9.90 GB)
telemt_user_msgs_from_client{user="hello"} 879944
telemt_user_msgs_to_client{user="hello"} 2304525
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```