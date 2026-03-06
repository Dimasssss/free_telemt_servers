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

# Server Metrics 2026-03-06 04:13:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 21475.4 (5h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71940
telemt_connections_bad_total 51934
telemt_handshake_timeouts_total 2428
telemt_upstream_connect_attempt_total 16178
telemt_upstream_connect_success_total 16176
telemt_upstream_connect_attempts_per_request{bucket="1"} 16174
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 963
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16174
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 208902952 (199.23 MB)
telemt_user_octets_to_client{user="hello"} 15075699363 (14.04 GB)
telemt_user_msgs_from_client{user="hello"} 379934
telemt_user_msgs_to_client{user="hello"} 2217580
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 21472.9 (5h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2041
telemt_connections_bad_total 142
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 1872
telemt_upstream_connect_success_total 1871
telemt_upstream_connect_attempts_per_request{bucket="1"} 1870
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 70
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1869
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 50946237 (48.59 MB)
telemt_user_octets_to_client{user="hello"} 916575328 (874.11 MB)
telemt_user_msgs_from_client{user="hello"} 66769
telemt_user_msgs_to_client{user="hello"} 286547
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 21473.2 (5h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1402
telemt_connections_bad_total 195
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1198
telemt_upstream_connect_success_total 1198
telemt_upstream_connect_attempts_per_request{bucket="1"} 1198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 161
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1194
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 36669703 (34.97 MB)
telemt_user_octets_to_client{user="hello"} 1732386048 (1.61 GB)
telemt_user_msgs_from_client{user="hello"} 46481
telemt_user_msgs_to_client{user="hello"} 347636
telemt_user_unique_ips_current{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 21476.0 (5h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2918
telemt_connections_bad_total 131
telemt_handshake_timeouts_total 298
telemt_upstream_connect_attempt_total 2417
telemt_upstream_connect_success_total 2417
telemt_upstream_connect_attempts_per_request{bucket="1"} 2417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 381
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2413
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 95234385 (90.82 MB)
telemt_user_octets_to_client{user="hello"} 5656357392 (5.27 GB)
telemt_user_msgs_from_client{user="hello"} 134070
telemt_user_msgs_to_client{user="hello"} 1186635
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 21475.8 (5h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7051
telemt_connections_bad_total 3914
telemt_handshake_timeouts_total 142
telemt_upstream_connect_attempt_total 2909
telemt_upstream_connect_success_total 2909
telemt_upstream_connect_attempts_per_request{bucket="1"} 2909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 377
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2907
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 50984047 (48.62 MB)
telemt_user_octets_to_client{user="hello"} 11310752826 (10.53 GB)
telemt_user_msgs_from_client{user="hello"} 134455
telemt_user_msgs_to_client{user="hello"} 2057963
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```