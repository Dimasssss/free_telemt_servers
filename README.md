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

# Server Metrics 2026-03-10 13:53:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 138817.8 (38h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 317812
telemt_connections_bad_total 3485
telemt_handshake_timeouts_total 3359
telemt_upstream_connect_attempt_total 297664
telemt_upstream_connect_success_total 297505
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 297664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 275124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22280
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 297491
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 6835366500 (6.37 GB)
telemt_user_octets_to_client{user="hello"} 195972310134 (182.51 GB)
telemt_user_msgs_from_client{user="hello"} 7114981
telemt_user_msgs_to_client{user="hello"} 11668753
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 138816.4 (38h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98168
telemt_connections_bad_total 3275
telemt_handshake_timeouts_total 1306
telemt_upstream_connect_attempt_total 88577
telemt_upstream_connect_success_total 88533
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 88577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8500
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 435
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 88519
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 2844798443 (2.65 GB)
telemt_user_octets_to_client{user="hello"} 37758006190 (35.16 GB)
telemt_user_msgs_from_client{user="hello"} 2314132
telemt_user_msgs_to_client{user="hello"} 10936197
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 138816.7 (38h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140160
telemt_connections_bad_total 1237
telemt_handshake_timeouts_total 6494
telemt_upstream_connect_attempt_total 105306
telemt_upstream_connect_success_total 105303
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 105306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 93180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12083
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 105289
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 6673989118 (6.22 GB)
telemt_user_octets_to_client{user="hello"} 69014769239 (64.28 GB)
telemt_user_msgs_from_client{user="hello"} 4548370
telemt_user_msgs_to_client{user="hello"} 11710275
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 138811.4 (38h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144154
telemt_connections_bad_total 1063
telemt_handshake_timeouts_total 3057
telemt_upstream_connect_attempt_total 133163
telemt_upstream_connect_success_total 132864
telemt_upstream_connect_fail_total 299
telemt_upstream_connect_attempts_per_request{bucket="1"} 133163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 118082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14363
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 82
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 337
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 299
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 132850
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 5051802309 (4.70 GB)
telemt_user_octets_to_client{user="hello"} 94011751850 (87.56 GB)
telemt_user_msgs_from_client{user="hello"} 3881877
telemt_user_msgs_to_client{user="hello"} 21283963
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 138816.9 (38h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213806
telemt_connections_bad_total 31065
telemt_handshake_timeouts_total 5978
telemt_upstream_connect_attempt_total 167867
telemt_upstream_connect_success_total 166905
telemt_upstream_connect_fail_total 962
telemt_upstream_connect_attempts_per_request{bucket="1"} 167867
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 144395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22287
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 962
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 166891
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 3587378307 (3.34 GB)
telemt_user_octets_to_client{user="hello"} 119381092031 (111.18 GB)
telemt_user_msgs_from_client{user="hello"} 3811386
telemt_user_msgs_to_client{user="hello"} 16382171
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 29
```