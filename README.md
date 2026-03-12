# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

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

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-12 07:46:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 798.1 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6055
telemt_handshake_timeouts_total 853
telemt_upstream_connect_attempt_total 171
telemt_upstream_connect_success_total 169
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 96
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 106
telemt_me_reconnect_success_total 105
telemt_me_reader_eof_total 71
telemt_me_idle_close_by_peer_total 71
telemt_me_route_drop_no_conn_total 849
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4886
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 35
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_me_writer_removed_unexpected_total 94
telemt_me_writer_restored_same_endpoint_total 89
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_user_connections_total{user="hello"} 4885
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 38103932 (36.34 MB)
telemt_user_octets_to_client{user="hello"} 1242763416 (1.16 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 691.2 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1434
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 198
telemt_upstream_connect_success_total 193
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 131
telemt_me_reconnect_success_total 130
telemt_me_reader_eof_total 85
telemt_me_idle_close_by_peer_total 85
telemt_me_route_drop_no_conn_total 417
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1385
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 107
telemt_me_writer_restored_same_endpoint_total 115
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_user_connections_total{user="hello"} 1385
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 5355568 (5.11 MB)
telemt_user_octets_to_client{user="hello"} 137902356 (131.51 MB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 654.8 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2186
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 174
telemt_upstream_connect_success_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 174
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 68
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 110
telemt_me_reconnect_success_total 109
telemt_me_reader_eof_total 68
telemt_me_idle_close_by_peer_total 68
telemt_me_route_drop_no_conn_total 466
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2098
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 5
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_me_writer_removed_unexpected_total 86
telemt_me_writer_restored_same_endpoint_total 89
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 2096
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 12350776 (11.78 MB)
telemt_user_octets_to_client{user="hello"} 1161477076 (1.08 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 630.7 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2470
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 98
telemt_upstream_connect_success_total 79
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 98
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 29
telemt_me_reconnect_success_total 11
telemt_me_route_drop_no_conn_total 594
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2170
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 13
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_me_writer_removed_unexpected_total 19
telemt_me_writer_restored_same_endpoint_total 3
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 90
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 2171
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 18453572 (17.60 MB)
telemt_user_octets_to_client{user="hello"} 485384928 (462.90 MB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 599.9 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 929
telemt_connections_bad_total 152
telemt_handshake_timeouts_total 32
telemt_upstream_connect_attempt_total 145
telemt_upstream_connect_success_total 139
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 77
telemt_me_reconnect_success_total 77
telemt_me_reader_eof_total 47
telemt_me_idle_close_by_peer_total 47
telemt_me_route_drop_no_conn_total 252
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 715
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 4
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_me_writer_removed_unexpected_total 65
telemt_me_writer_restored_same_endpoint_total 66
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 18
telemt_user_connections_total{user="hello"} 715
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 3159348 (3.01 MB)
telemt_user_octets_to_client{user="hello"} 147217776 (140.40 MB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 586.8 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2399
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 27
telemt_upstream_connect_attempt_total 85
telemt_upstream_connect_success_total 84
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 85
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 21
telemt_me_reconnect_success_total 21
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 751
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2265
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 4
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_me_writer_removed_unexpected_total 23
telemt_me_writer_restored_same_endpoint_total 14
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 2266
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 123064660 (117.36 MB)
telemt_user_octets_to_client{user="hello"} 462857560 (441.42 MB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 30
```