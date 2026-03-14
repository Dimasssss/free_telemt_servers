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

# Server Metrics 2026-03-14 18:35:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 19172.9 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108252
telemt_connections_bad_total 15557
telemt_handshake_timeouts_total 948
telemt_upstream_connect_attempt_total 4528
telemt_upstream_connect_success_total 4526
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4528
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2285
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 123
telemt_me_reconnect_attempts_total 3540
telemt_me_reconnect_success_total 3508
telemt_me_reader_eof_total 3715
telemt_me_idle_close_by_peer_total 3715
telemt_me_route_drop_no_conn_total 37970
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87194
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 338
telemt_desync_full_logged_total 124
telemt_desync_suppressed_total 214
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 128
telemt_desync_frames_bucket_total{bucket="gt_10"} 131
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3564
telemt_me_writer_restored_same_endpoint_total 3490
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 87122
telemt_user_connections_current{user="hello"} 327
telemt_user_octets_from_client{user="hello"} 1797792556 (1.67 GB)
telemt_user_octets_to_client{user="hello"} 43401033456 (40.42 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 19171.4 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43500
telemt_connections_bad_total 503
telemt_handshake_timeouts_total 860
telemt_upstream_connect_attempt_total 5162
telemt_upstream_connect_success_total 5124
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 5162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2952
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 6680
telemt_me_reconnect_success_total 4106
telemt_me_reader_eof_total 4362
telemt_me_idle_close_by_peer_total 4362
telemt_me_route_drop_no_conn_total 23284
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40567
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 4245
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 4101
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 40551
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 583330664 (556.31 MB)
telemt_user_octets_to_client{user="hello"} 17531439932 (16.33 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 19175.7 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46667
telemt_connections_bad_total 374
telemt_handshake_timeouts_total 1769
telemt_upstream_connect_attempt_total 6932
telemt_upstream_connect_success_total 6858
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 6932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3539
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 103381
telemt_me_reconnect_success_total 5521
telemt_me_reader_eof_total 5895
telemt_me_idle_close_by_peer_total 5895
telemt_me_route_drop_no_conn_total 18430
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41971
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 5786
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 5483
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 265
telemt_user_connections_total{user="hello"} 42036
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 2918415137 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 24207609550 (22.55 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 19180.4 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59222
telemt_connections_bad_total 141
telemt_handshake_timeouts_total 514
telemt_upstream_connect_attempt_total 4773
telemt_upstream_connect_success_total 4743
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 4773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2567
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 3754
telemt_me_reconnect_success_total 3733
telemt_me_reader_eof_total 3908
telemt_me_idle_close_by_peer_total 3908
telemt_me_route_drop_no_conn_total 26645
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56016
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 472
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 350
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 192
telemt_desync_frames_bucket_total{bucket="gt_10"} 205
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3773
telemt_me_writer_restored_same_endpoint_total 3731
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 55894
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 786254244 (749.83 MB)
telemt_user_octets_to_client{user="hello"} 17680912212 (16.47 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 19173.6 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44541
telemt_connections_bad_total 3711
telemt_handshake_timeouts_total 2619
telemt_upstream_connect_attempt_total 4420
telemt_upstream_connect_success_total 4368
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 4419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1929
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2415
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 9876
telemt_me_reconnect_success_total 3350
telemt_me_reader_eof_total 3677
telemt_me_idle_close_by_peer_total 3677
telemt_me_route_drop_no_conn_total 15180
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35991
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 202
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 176
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 113
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3585
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 3346
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 35983
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 575820624 (549.15 MB)
telemt_user_octets_to_client{user="hello"} 9748749476 (9.08 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 19173.0 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 154297
telemt_connections_bad_total 7182
telemt_handshake_timeouts_total 2260
telemt_upstream_connect_attempt_total 3879
telemt_upstream_connect_success_total 3810
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 3879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1930
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 7790
telemt_me_reconnect_success_total 2791
telemt_me_reader_eof_total 3042
telemt_me_idle_close_by_peer_total 3042
telemt_me_route_drop_no_conn_total 82499
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139414
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2976
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 2787
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 185
telemt_user_connections_total{user="hello"} 136963
telemt_user_connections_current{user="hello"} 508
telemt_user_octets_from_client{user="hello"} 3163416416 (2.95 GB)
telemt_user_octets_to_client{user="hello"} 71456106784 (66.55 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 77
```