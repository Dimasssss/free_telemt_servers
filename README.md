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

# Server Metrics 2026-03-04 10:00:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 5858.0 (1h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10289
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 176
telemt_upstream_connect_attempt_total 9143
telemt_upstream_connect_success_total 9143
telemt_upstream_connect_attempts_per_request{bucket="1"} 9143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 568
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9141
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 122755764 (117.07 MB)
telemt_user_octets_to_client{user="hello"} 4240244867 (3.95 GB)
telemt_user_msgs_from_client{user="hello"} 195838
telemt_user_msgs_to_client{user="hello"} 730223
telemt_user_unique_ips_current{user="hello"} 12
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 5869.2 (1h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1237
telemt_connections_bad_total 37
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 1135
telemt_upstream_connect_success_total 1135
telemt_upstream_connect_attempts_per_request{bucket="1"} 1135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1133
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 40178942 (38.32 MB)
telemt_user_octets_to_client{user="hello"} 488932557 (466.28 MB)
telemt_user_msgs_from_client{user="hello"} 38673
telemt_user_msgs_to_client{user="hello"} 151722
telemt_user_unique_ips_current{user="hello"} 3
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 5853.7 (1h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1140
telemt_connections_bad_total 66
telemt_upstream_connect_attempt_total 1052
telemt_upstream_connect_success_total 1052
telemt_upstream_connect_attempts_per_request{bucket="1"} 1052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 136
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1050
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 19530673 (18.63 MB)
telemt_user_octets_to_client{user="hello"} 2221183907 (2.07 GB)
telemt_user_msgs_from_client{user="hello"} 55659
telemt_user_msgs_to_client{user="hello"} 424682
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 5844.4 (1h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2408
telemt_connections_bad_total 44
telemt_handshake_timeouts_total 11
telemt_upstream_connect_attempt_total 2162
telemt_upstream_connect_success_total 2161
telemt_upstream_connect_attempts_per_request{bucket="1"} 2160
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 57
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2159
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 8349219 (7.96 MB)
telemt_user_octets_to_client{user="hello"} 269833137 (257.33 MB)
telemt_user_msgs_from_client{user="hello"} 19275
telemt_user_msgs_to_client{user="hello"} 90343
telemt_user_unique_ips_current{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 5855.7 (1h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2080
telemt_connections_bad_total 1023
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 999
telemt_upstream_connect_success_total 999
telemt_upstream_connect_attempts_per_request{bucket="1"} 999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 146
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 997
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 13883899 (13.24 MB)
telemt_user_octets_to_client{user="hello"} 513840338 (490.04 MB)
telemt_user_msgs_from_client{user="hello"} 31043
telemt_user_msgs_to_client{user="hello"} 132459
telemt_user_unique_ips_current{user="hello"} 4
```