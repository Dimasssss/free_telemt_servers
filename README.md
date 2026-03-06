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

# Server Metrics 2026-03-06 05:50:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 27322.5 (7h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79356
telemt_connections_bad_total 51939
telemt_handshake_timeouts_total 2449
telemt_upstream_connect_attempt_total 23412
telemt_upstream_connect_success_total 23409
telemt_upstream_connect_attempts_per_request{bucket="1"} 23406
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1455
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23405
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 332449114 (317.05 MB)
telemt_user_octets_to_client{user="hello"} 20946137970 (19.51 GB)
telemt_user_msgs_from_client{user="hello"} 591491
telemt_user_msgs_to_client{user="hello"} 3150046
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 27320.5 (7h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3081
telemt_connections_bad_total 147
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 2874
telemt_upstream_connect_success_total 2873
telemt_upstream_connect_attempts_per_request{bucket="1"} 2872
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2869
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 59407137 (56.66 MB)
telemt_user_octets_to_client{user="hello"} 1257420417 (1.17 GB)
telemt_user_msgs_from_client{user="hello"} 84523
telemt_user_msgs_to_client{user="hello"} 401492
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 27320.8 (7h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2126
telemt_connections_bad_total 214
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 1887
telemt_upstream_connect_success_total 1887
telemt_upstream_connect_attempts_per_request{bucket="1"} 1887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 190
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1883
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 46659761 (44.50 MB)
telemt_user_octets_to_client{user="hello"} 2383027027 (2.22 GB)
telemt_user_msgs_from_client{user="hello"} 65201
telemt_user_msgs_to_client{user="hello"} 490984
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 27323.6 (7h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4161
telemt_connections_bad_total 138
telemt_handshake_timeouts_total 309
telemt_upstream_connect_attempt_total 3524
telemt_upstream_connect_success_total 3524
telemt_upstream_connect_attempts_per_request{bucket="1"} 3524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 426
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3520
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 98641468 (94.07 MB)
telemt_user_octets_to_client{user="hello"} 5784271295 (5.39 GB)
telemt_user_msgs_from_client{user="hello"} 142469
telemt_user_msgs_to_client{user="hello"} 1227511
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 27323.3 (7h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9174
telemt_connections_bad_total 4958
telemt_handshake_timeouts_total 163
telemt_upstream_connect_attempt_total 3946
telemt_upstream_connect_success_total 3946
telemt_upstream_connect_attempts_per_request{bucket="1"} 3946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 564
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3942
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 79032197 (75.37 MB)
telemt_user_octets_to_client{user="hello"} 15967971926 (14.87 GB)
telemt_user_msgs_from_client{user="hello"} 201636
telemt_user_msgs_to_client{user="hello"} 3044596
telemt_user_unique_ips_current{user="hello"} 3
```