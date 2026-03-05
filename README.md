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

# Server Metrics 2026-03-05 12:07:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 88853.7 (24h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130256
telemt_connections_bad_total 530
telemt_handshake_timeouts_total 4210
telemt_upstream_connect_attempt_total 115030
telemt_upstream_connect_success_total 115002
telemt_upstream_connect_attempts_per_request{bucket="1"} 114974
telemt_upstream_connect_attempts_per_request{bucket="2"} 28
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 107613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7324
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 114992
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 3333140399 (3.10 GB)
telemt_user_octets_to_client{user="hello"} 79483723357 (74.02 GB)
telemt_user_msgs_from_client{user="hello"} 3296371
telemt_user_msgs_to_client{user="hello"} 12971498
telemt_user_unique_ips_current{user="hello"} 20
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 88856.1 (24h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23738
telemt_connections_bad_total 480
telemt_handshake_timeouts_total 74
telemt_upstream_connect_attempt_total 18850
telemt_upstream_connect_success_total 18846
telemt_upstream_connect_attempts_per_request{bucket="1"} 18842
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17496
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1250
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18836
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 1184675623 (1.10 GB)
telemt_user_octets_to_client{user="hello"} 15269673987 (14.22 GB)
telemt_user_msgs_from_client{user="hello"} 846381
telemt_user_msgs_to_client{user="hello"} 4885522
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 88854.4 (24h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20112
telemt_connections_bad_total 398
telemt_handshake_timeouts_total 32
telemt_upstream_connect_attempt_total 15809
telemt_upstream_connect_success_total 15809
telemt_upstream_connect_attempts_per_request{bucket="1"} 15809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15799
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 450990187 (430.10 MB)
telemt_user_octets_to_client{user="hello"} 9858485896 (9.18 GB)
telemt_user_msgs_from_client{user="hello"} 463020
telemt_user_msgs_to_client{user="hello"} 2107136
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 88852.2 (24h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34331
telemt_connections_bad_total 1008
telemt_handshake_timeouts_total 639
telemt_upstream_connect_attempt_total 30252
telemt_upstream_connect_success_total 30240
telemt_upstream_connect_attempts_per_request{bucket="1"} 30228
telemt_upstream_connect_attempts_per_request{bucket="2"} 12
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28096
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1946
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 182
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30230
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 523131400 (498.90 MB)
telemt_user_octets_to_client{user="hello"} 18403081626 (17.14 GB)
telemt_user_msgs_from_client{user="hello"} 574210
telemt_user_msgs_to_client{user="hello"} 4111320
telemt_user_unique_ips_current{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 88853.8 (24h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34552
telemt_connections_bad_total 16053
telemt_handshake_timeouts_total 73
telemt_upstream_connect_attempt_total 17927
telemt_upstream_connect_success_total 17922
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 17919
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2480
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17912
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 662466901 (631.78 MB)
telemt_user_octets_to_client{user="hello"} 28751032885 (26.78 GB)
telemt_user_msgs_from_client{user="hello"} 770178
telemt_user_msgs_to_client{user="hello"} 5512089
telemt_user_unique_ips_current{user="hello"} 4
```