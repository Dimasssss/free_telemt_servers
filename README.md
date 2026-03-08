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

# Server Metrics 2026-03-08 15:21:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 29538.5 (8h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72265
telemt_connections_bad_total 5024
telemt_handshake_timeouts_total 1043
telemt_upstream_connect_attempt_total 63609
telemt_upstream_connect_success_total 63586
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 63609
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3680
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 63582
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 1685547412 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 33146237849 (30.87 GB)
telemt_user_msgs_from_client{user="hello"} 1504145
telemt_user_msgs_to_client{user="hello"} 1997167
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 29537.8 (8h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15495
telemt_connections_bad_total 125
telemt_handshake_timeouts_total 119
telemt_upstream_connect_attempt_total 14963
telemt_upstream_connect_success_total 14962
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 14963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13807
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1071
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14958
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 566173263 (539.94 MB)
telemt_user_octets_to_client{user="hello"} 12898910508 (12.01 GB)
telemt_user_msgs_from_client{user="hello"} 573686
telemt_user_msgs_to_client{user="hello"} 3388143
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 29537.6 (8h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9880
telemt_connections_bad_total 146
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 9253
telemt_upstream_connect_success_total 9177
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 9253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 627
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9173
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 215890885 (205.89 MB)
telemt_user_octets_to_client{user="hello"} 3141474766 (2.93 GB)
telemt_user_msgs_from_client{user="hello"} 157772
telemt_user_msgs_to_client{user="hello"} 540384
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 29537.3 (8h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12708
telemt_connections_bad_total 155
telemt_handshake_timeouts_total 46
telemt_upstream_connect_attempt_total 12127
telemt_upstream_connect_success_total 12099
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 12127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 889
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12095
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 946038131 (902.21 MB)
telemt_user_octets_to_client{user="hello"} 4579617959 (4.27 GB)
telemt_user_msgs_from_client{user="hello"} 465501
telemt_user_msgs_to_client{user="hello"} 1030224
telemt_user_unique_ips_current{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 29537.6 (8h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16763
telemt_connections_bad_total 5438
telemt_handshake_timeouts_total 116
telemt_upstream_connect_attempt_total 10964
telemt_upstream_connect_success_total 10960
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 10964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1849
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10956
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 232673296 (221.89 MB)
telemt_user_octets_to_client{user="hello"} 8403112274 (7.83 GB)
telemt_user_msgs_from_client{user="hello"} 281036
telemt_user_msgs_to_client{user="hello"} 1177377
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```