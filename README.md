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

# Server Metrics 2026-03-15 10:27:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 44006.4 (12h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182320
telemt_connections_bad_total 1296
telemt_handshake_timeouts_total 4181
telemt_upstream_connect_attempt_total 10996
telemt_upstream_connect_success_total 10938
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 10996
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6059
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 11125
telemt_me_reconnect_success_total 8756
telemt_me_reader_eof_total 9370
telemt_me_idle_close_by_peer_total 9370
telemt_me_route_drop_no_conn_total 411417
telemt_me_route_drop_channel_closed_total 60
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230962
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1360
telemt_desync_full_logged_total 544
telemt_desync_suppressed_total 816
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 544
telemt_desync_frames_bucket_total{bucket="gt_10"} 594
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 8911
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 8725
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 170244
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 2659949012 (2.48 GB)
telemt_user_octets_to_client{user="hello"} 177251200640 (165.08 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 44013.2 (12h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58659
telemt_connections_bad_total 2308
telemt_handshake_timeouts_total 3053
telemt_upstream_connect_attempt_total 11795
telemt_upstream_connect_success_total 11795
telemt_upstream_connect_attempts_per_request{bucket="1"} 11795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6663
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 11910
telemt_me_reconnect_success_total 9588
telemt_me_reader_eof_total 10305
telemt_me_idle_close_by_peer_total 10305
telemt_me_route_drop_no_conn_total 27689
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51428
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 9766
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 9572
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 51426
telemt_user_connections_current{user="hello"} 245
telemt_user_octets_from_client{user="hello"} 1017210876 (970.09 MB)
telemt_user_octets_to_client{user="hello"} 22252955752 (20.72 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 44005.9 (12h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66176
telemt_connections_bad_total 645
telemt_handshake_timeouts_total 2434
telemt_upstream_connect_attempt_total 12162
telemt_upstream_connect_success_total 12161
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6959
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 10006
telemt_me_reconnect_success_total 9959
telemt_me_reader_eof_total 10687
telemt_me_idle_close_by_peer_total 10687
telemt_me_route_drop_no_conn_total 24821
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60465
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 30
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 10051
telemt_me_writer_restored_same_endpoint_total 9955
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 60389
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 9291484064 (8.65 GB)
telemt_user_octets_to_client{user="hello"} 37447834636 (34.88 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 44005.4 (12h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85817
telemt_connections_bad_total 207
telemt_handshake_timeouts_total 590
telemt_upstream_connect_attempt_total 10366
telemt_upstream_connect_success_total 10365
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5397
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 8226
telemt_me_reconnect_success_total 8187
telemt_me_reader_eof_total 8743
telemt_me_idle_close_by_peer_total 8743
telemt_me_route_drop_no_conn_total 35880
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 78125
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 163
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 113
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 8272
telemt_me_writer_restored_same_endpoint_total 8176
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 78055
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 1567693928 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 49127479000 (45.75 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 19076.9 (5h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32269
telemt_connections_bad_total 3568
telemt_handshake_timeouts_total 495
telemt_upstream_connect_attempt_total 6379
telemt_upstream_connect_success_total 6328
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 6379
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3465
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 99581
telemt_me_reconnect_success_total 5173
telemt_me_reader_eof_total 5356
telemt_me_idle_close_by_peer_total 5356
telemt_me_route_drop_no_conn_total 10788
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27414
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 40
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 5142
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 5069
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 27554
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 427501021 (407.70 MB)
telemt_user_octets_to_client{user="hello"} 12696872699 (11.82 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 44004.7 (12h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233645
telemt_connections_bad_total 44134
telemt_handshake_timeouts_total 1460
telemt_upstream_connect_attempt_total 9366
telemt_upstream_connect_success_total 9311
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 9366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4605
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 7163
telemt_me_reconnect_success_total 7122
telemt_me_reader_eof_total 7592
telemt_me_idle_close_by_peer_total 7592
telemt_me_route_drop_no_conn_total 102296
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 181921
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 73
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 38
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 7175
telemt_me_writer_restored_same_endpoint_total 7095
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 180292
telemt_user_connections_current{user="hello"} 492
telemt_user_octets_from_client{user="hello"} 4420751004 (4.12 GB)
telemt_user_octets_to_client{user="hello"} 92571181656 (86.21 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 98
```