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

# Server Metrics 2026-03-12 18:31:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 39473.0 (10h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201528
telemt_connections_bad_total 2416
telemt_handshake_timeouts_total 4958
telemt_upstream_connect_attempt_total 10037
telemt_upstream_connect_success_total 9994
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 10037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5539
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 11429
telemt_me_reconnect_success_total 7972
telemt_me_reader_eof_total 8435
telemt_me_idle_close_by_peer_total 8434
telemt_me_route_drop_no_conn_total 60172
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169841
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 636
telemt_desync_full_logged_total 240
telemt_desync_suppressed_total 396
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 242
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 8174
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 7956
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 169800
telemt_user_connections_current{user="hello"} 293
telemt_user_octets_from_client{user="hello"} 3006060812 (2.80 GB)
telemt_user_octets_to_client{user="hello"} 72372606412 (67.40 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 39365.9 (10h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87583
telemt_connections_bad_total 472
telemt_handshake_timeouts_total 695
telemt_upstream_connect_attempt_total 18614
telemt_upstream_connect_success_total 18361
telemt_upstream_connect_fail_total 253
telemt_upstream_connect_attempts_per_request{bucket="1"} 18614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 296
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 253
telemt_me_keepalive_timeout_total 328
telemt_me_reconnect_attempts_total 41639
telemt_me_reconnect_success_total 9088
telemt_me_reader_eof_total 10277
telemt_me_idle_close_by_peer_total 10277
telemt_me_route_drop_no_conn_total 35311
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76036
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 10177
telemt_me_refill_failed_total 1016
telemt_me_writer_restored_same_endpoint_total 9073
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1089
telemt_user_connections_total{user="hello"} 83299
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 891806789 (850.49 MB)
telemt_user_octets_to_client{user="hello"} 23260453076 (21.66 GB)
telemt_user_msgs_from_client{user="hello"} 112634
telemt_user_msgs_to_client{user="hello"} 789299
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 39329.3 (10h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114319
telemt_connections_bad_total 1513
telemt_handshake_timeouts_total 2121
telemt_upstream_connect_attempt_total 11037
telemt_upstream_connect_success_total 11037
telemt_upstream_connect_attempts_per_request{bucket="1"} 11037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5701
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 10125
telemt_me_reconnect_success_total 8994
telemt_me_reader_eof_total 9527
telemt_me_idle_close_by_peer_total 9527
telemt_me_route_drop_no_conn_total 42838
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106031
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 9115
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 8974
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 106003
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 2423837212 (2.26 GB)
telemt_user_octets_to_client{user="hello"} 54234322932 (50.51 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 39305.2 (10h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165360
telemt_connections_bad_total 13101
telemt_handshake_timeouts_total 1188
telemt_upstream_connect_attempt_total 20050
telemt_upstream_connect_success_total 10458
telemt_upstream_connect_fail_total 9591
telemt_upstream_connect_attempts_per_request{bucket="1"} 20049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4906
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9591
telemt_me_keepalive_timeout_total 2407
telemt_me_reconnect_attempts_total 37652
telemt_me_reconnect_success_total 6854
telemt_me_reader_eof_total 8008
telemt_me_idle_close_by_peer_total 8001
telemt_me_route_drop_no_conn_total 56700
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132496
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 320
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 168
telemt_desync_frames_bucket_total{bucket="gt_10"} 158
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 7943
telemt_me_refill_failed_total 959
telemt_me_writer_restored_same_endpoint_total 6844
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1089
telemt_user_connections_total{user="hello"} 133985
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 2357965414 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 54344686717 (50.61 GB)
telemt_user_msgs_from_client{user="hello"} 11468
telemt_user_msgs_to_client{user="hello"} 57574
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 39262.5 (10h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 250694
telemt_connections_bad_total 2016
telemt_handshake_timeouts_total 2109
telemt_upstream_connect_attempt_total 8353
telemt_upstream_connect_success_total 8310
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 8353
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4439
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 467
telemt_me_reconnect_attempts_total 9919
telemt_me_reconnect_success_total 6315
telemt_me_reader_eof_total 6729
telemt_me_idle_close_by_peer_total 6728
telemt_me_route_drop_no_conn_total 115072
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 248590
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 255
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 6509
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 6308
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 238515
telemt_user_connections_current{user="hello"} 409
telemt_user_octets_from_client{user="hello"} 4187346256 (3.90 GB)
telemt_user_octets_to_client{user="hello"} 109440722868 (101.92 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 59
```