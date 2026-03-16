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

# Server Metrics 2026-03-16 13:36:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 59.6 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2106
telemt_upstream_connect_attempt_total 1411
telemt_upstream_connect_success_total 1404
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 66312
telemt_me_reconnect_success_total 124
telemt_me_route_drop_no_conn_total 69
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 487
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 22
telemt_me_refill_failed_total 2780
telemt_me_writer_restored_same_endpoint_total 60
telemt_me_writer_restored_fallback_total 64
telemt_me_async_recovery_trigger_total 5819
telemt_user_connections_total{user="hello"} 1765
telemt_user_connections_current{user="hello"} 674
telemt_user_octets_from_client{user="hello"} 12048541 (11.49 MB)
telemt_user_octets_to_client{user="hello"} 126559027 (120.70 MB)
telemt_user_msgs_from_client{user="hello"} 8724
telemt_user_msgs_to_client{user="hello"} 8587
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 102.7 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2204
telemt_connections_bad_total 24
telemt_upstream_connect_attempt_total 1159
telemt_upstream_connect_success_total 1151
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 120
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 319551
telemt_me_reconnect_success_total 116
telemt_me_route_drop_no_conn_total 169
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 798
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 13
telemt_me_refill_failed_total 9980
telemt_me_writer_restored_same_endpoint_total 116
telemt_me_async_recovery_trigger_total 19766
telemt_user_connections_total{user="hello"} 1839
telemt_user_connections_current{user="hello"} 511
telemt_user_octets_from_client{user="hello"} 2240722 (2.14 MB)
telemt_user_octets_to_client{user="hello"} 69329889 (66.12 MB)
telemt_user_msgs_from_client{user="hello"} 4689
telemt_user_msgs_to_client{user="hello"} 18849
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 38.9 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165
telemt_upstream_connect_attempt_total 91
telemt_upstream_connect_success_total 88
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 90
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 18
telemt_me_reconnect_success_total 11
telemt_me_route_drop_no_conn_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 15
telemt_me_writer_restored_same_endpoint_total 10
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 132
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 238628 (233.04 KB)
telemt_user_octets_to_client{user="hello"} 547048 (534.23 KB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 171.7 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2617
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 118
telemt_upstream_connect_success_total 117
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 75
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 47
telemt_me_reconnect_success_total 46
telemt_me_reader_eof_total 12
telemt_me_idle_close_by_peer_total 12
telemt_me_route_drop_no_conn_total 595
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2508
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 6
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 11
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_me_writer_removed_unexpected_total 24
telemt_me_writer_restored_same_endpoint_total 42
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 16
telemt_user_connections_total{user="hello"} 2494
telemt_user_connections_current{user="hello"} 448
telemt_user_octets_from_client{user="hello"} 9854580 (9.40 MB)
telemt_user_octets_to_client{user="hello"} 234911088 (224.03 MB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 161.1 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1324
telemt_connections_bad_total 274
telemt_upstream_connect_attempt_total 103
telemt_upstream_connect_success_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46
telemt_me_reconnect_attempts_total 30
telemt_me_reconnect_success_total 29
telemt_me_reader_eof_total 8
telemt_me_idle_close_by_peer_total 8
telemt_me_route_drop_no_conn_total 175
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 946
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_restored_same_endpoint_total 28
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 12
telemt_user_connections_total{user="hello"} 936
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 10788200 (10.29 MB)
telemt_user_octets_to_client{user="hello"} 46872400 (44.70 MB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 141724.5 (39h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1040764
telemt_connections_bad_total 78884
telemt_handshake_timeouts_total 13148
telemt_upstream_connect_attempt_total 30106
telemt_upstream_connect_success_total 29949
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 30106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15826
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_keepalive_timeout_total 214
telemt_me_reconnect_attempts_total 26506
telemt_me_reconnect_success_total 22852
telemt_me_reader_eof_total 24389
telemt_me_idle_close_by_peer_total 24388
telemt_me_route_drop_no_conn_total 733662
telemt_me_route_drop_channel_closed_total 149
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1008643
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 769
telemt_desync_full_logged_total 239
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 189
telemt_desync_frames_bucket_total{bucket="3_10"} 281
telemt_desync_frames_bucket_total{bucket="gt_10"} 299
telemt_pool_swap_total 125
telemt_me_writer_removed_unexpected_total 23242
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 22825
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 390
telemt_user_connections_total{user="hello"} 867212
telemt_user_connections_current{user="hello"} 779
telemt_user_octets_from_client{user="hello"} 18245413192 (16.99 GB)
telemt_user_octets_to_client{user="hello"} 490460760360 (456.78 GB)
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 104
```