# Server Metrics 2026-03-20 10:46:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.27

telemt_uptime_seconds 1766.7 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151119
telemt_connections_bad_total 4370
telemt_connections_current 1653
telemt_connections_me_current 1653
telemt_handshake_timeouts_total 1302
telemt_upstream_connect_attempt_total 584
telemt_upstream_connect_success_total 574
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 339
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 65
telemt_me_reconnect_success_total 12
telemt_me_reader_eof_total 12
telemt_me_idle_close_by_peer_total 12
telemt_me_route_drop_no_conn_total 249428
telemt_me_route_drop_channel_closed_total 54
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128198
telemt_me_writer_pick_total{mode="p2c",result="full"} 1
telemt_me_endpoint_quarantine_total 13
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 245
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 159
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 86
telemt_pool_swap_total 1
telemt_pool_force_close_total 27
telemt_me_writer_close_signal_drop_total 26
telemt_me_draining_writers_reap_progress_total 438
telemt_me_writer_removed_unexpected_total 12
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 410
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 411
telemt_me_writer_teardown_success_total{mode="normal"} 446
telemt_me_writer_teardown_noop_total 438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 884
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.633479
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 884
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 26
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 9
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 127886
telemt_user_connections_current{user="hello"} 1653
telemt_user_octets_from_client{user="hello"} 786486608 (750.05 MB)
telemt_user_octets_to_client{user="hello"} 10892268700 (10.14 GB)
telemt_user_unique_ips_current{user="hello"} 562
telemt_user_unique_ips_recent_window{user="hello"} 274
```

## psb.hosting №1

```
telemt 3.3.27

telemt_uptime_seconds 1748.5 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213237
telemt_connections_bad_total 24242
telemt_connections_current 4337
telemt_connections_me_current 4337
telemt_handshake_timeouts_total 5793
telemt_upstream_connect_attempt_total 696
telemt_upstream_connect_success_total 693
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 299
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 392
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 54
telemt_me_reconnect_success_total 50
telemt_me_reader_eof_total 50
telemt_me_idle_close_by_peer_total 50
telemt_me_route_drop_no_conn_total 167522
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163059
telemt_me_endpoint_quarantine_total 5
telemt_me_single_endpoint_shadow_rotate_total 13
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 86
telemt_desync_total 503
telemt_desync_full_logged_total 188
telemt_desync_suppressed_total 315
telemt_desync_frames_bucket_total{bucket="1_2"} 94
telemt_desync_frames_bucket_total{bucket="3_10"} 230
telemt_desync_frames_bucket_total{bucket="gt_10"} 179
telemt_me_writer_close_signal_drop_total 3
telemt_me_draining_writers_reap_progress_total 472
telemt_me_writer_removed_unexpected_total 51
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 69
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 454
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 472
telemt_me_writer_teardown_success_total{mode="normal"} 523
telemt_me_writer_teardown_noop_total 472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 995
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.027555
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 995
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 3
telemt_me_writer_restored_same_endpoint_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 163094
telemt_user_connections_current{user="hello"} 4337
telemt_user_octets_from_client{user="hello"} 2288130920 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 43081628416 (40.12 GB)
telemt_user_unique_ips_current{user="hello"} 1463
telemt_user_unique_ips_recent_window{user="hello"} 575
```

## psb.hosting №2

```
telemt 3.3.27

telemt_uptime_seconds 1737.0 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 162387
telemt_connections_bad_total 26497
telemt_connections_current 3552
telemt_connections_me_current 3552
telemt_handshake_timeouts_total 1876
telemt_upstream_connect_attempt_total 550
telemt_upstream_connect_success_total 550
telemt_upstream_connect_attempts_per_request{bucket="1"} 550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 243
telemt_me_reconnect_attempts_total 59
telemt_me_reconnect_success_total 9
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 54677
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 120423
telemt_me_endpoint_quarantine_total 3
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 41
telemt_desync_total 323
telemt_desync_full_logged_total 106
telemt_desync_suppressed_total 217
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 113
telemt_desync_frames_bucket_total{bucket="gt_10"} 144
telemt_pool_swap_total 1
telemt_pool_force_close_total 27
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 415
telemt_me_writer_removed_unexpected_total 10
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 390
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 388
telemt_me_writer_teardown_success_total{mode="normal"} 426
telemt_me_writer_teardown_noop_total 415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 841
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.055880
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 841
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 7
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 120447
telemt_user_connections_current{user="hello"} 3552
telemt_user_octets_from_client{user="hello"} 1748010624 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 43400077268 (40.42 GB)
telemt_user_unique_ips_current{user="hello"} 1432
telemt_user_unique_ips_recent_window{user="hello"} 489
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.27

telemt_uptime_seconds 1528.3 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 594712
telemt_connections_bad_total 8203
telemt_connections_current 5900
telemt_connections_me_current 5900
telemt_handshake_timeouts_total 4629
telemt_upstream_connect_attempt_total 635
telemt_upstream_connect_success_total 570
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 309
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 58
telemt_me_reconnect_success_total 55
telemt_me_reader_eof_total 52
telemt_me_idle_close_by_peer_total 52
telemt_me_route_drop_no_conn_total 1191692
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 548155
telemt_me_endpoint_quarantine_total 4
telemt_me_single_endpoint_shadow_rotate_total 13
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 91
telemt_desync_total 329
telemt_desync_full_logged_total 99
telemt_desync_suppressed_total 230
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 146
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_me_writer_close_signal_drop_total 5
telemt_me_draining_writers_reap_progress_total 343
telemt_me_writer_removed_unexpected_total 54
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 66
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 331
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 343
telemt_me_writer_teardown_success_total{mode="normal"} 397
telemt_me_writer_teardown_noop_total 343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 740
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.251706
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 740
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 5
telemt_me_writer_restored_same_endpoint_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 548116
telemt_user_connections_current{user="hello"} 5900
telemt_user_octets_from_client{user="hello"} 2065446796 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 17539327380 (16.33 GB)
telemt_user_unique_ips_current{user="hello"} 1730
telemt_user_unique_ips_recent_window{user="hello"} 1059
```

## rdp-onedash.ru

```
telemt 3.3.27

telemt_uptime_seconds 1520.6 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 478249
telemt_connections_bad_total 10691
telemt_connections_current 7071
telemt_connections_me_current 7071
telemt_handshake_timeouts_total 5949
telemt_upstream_connect_attempt_total 413
telemt_upstream_connect_success_total 408
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 202
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 6
telemt_me_reconnect_success_total 8
telemt_me_reader_eof_total 6
telemt_me_idle_close_by_peer_total 6
telemt_me_route_drop_no_conn_total 732300
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 425111
telemt_me_endpoint_quarantine_total 8
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 942
telemt_desync_full_logged_total 265
telemt_desync_suppressed_total 677
telemt_desync_frames_bucket_total{bucket="1_2"} 212
telemt_desync_frames_bucket_total{bucket="3_10"} 401
telemt_desync_frames_bucket_total{bucket="gt_10"} 329
telemt_pool_swap_total 1
telemt_pool_force_close_total 33
telemt_me_writer_close_signal_drop_total 6
telemt_me_draining_writers_reap_progress_total 297
telemt_me_writer_removed_unexpected_total 6
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 28
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 275
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 264
telemt_me_writer_teardown_success_total{mode="normal"} 303
telemt_me_writer_teardown_noop_total 297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 600
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.607576
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 600
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 6
telemt_me_writer_restored_same_endpoint_total 6
telemt_user_connections_total{user="hello"} 425059
telemt_user_connections_current{user="hello"} 7071
telemt_user_octets_from_client{user="hello"} 2551650284 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 31773307864 (29.59 GB)
telemt_user_unique_ips_current{user="hello"} 2121
telemt_user_unique_ips_recent_window{user="hello"} 1028
```

## hostvds.com

```
telemt 3.3.27

telemt_uptime_seconds 1518.7 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36828
telemt_connections_bad_total 6406
telemt_connections_current 804
telemt_connections_me_current 804
telemt_handshake_timeouts_total 537
telemt_upstream_connect_attempt_total 733
telemt_upstream_connect_success_total 733
telemt_upstream_connect_attempts_per_request{bucket="1"} 733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 492
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_me_reconnect_attempts_total 95
telemt_me_reconnect_success_total 46
telemt_me_reader_eof_total 48
telemt_me_idle_close_by_peer_total 48
telemt_me_route_drop_no_conn_total 18168
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26790
telemt_me_endpoint_quarantine_total 7
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 86
telemt_desync_total 50
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_force_close_total 1
telemt_me_writer_close_signal_drop_total 5
telemt_me_draining_writers_reap_progress_total 509
telemt_me_writer_removed_unexpected_total 48
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 68
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 490
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 508
telemt_me_writer_teardown_success_total{mode="normal"} 558
telemt_me_writer_teardown_noop_total 509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1067
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.340257
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1067
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 5
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 26792
telemt_user_connections_current{user="hello"} 804
telemt_user_octets_from_client{user="hello"} 340166812 (324.41 MB)
telemt_user_octets_to_client{user="hello"} 4617474744 (4.30 GB)
telemt_user_unique_ips_current{user="hello"} 284
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## 4vps.su

```
telemt 3.3.27

telemt_uptime_seconds 1511.1 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 278833
telemt_connections_bad_total 60315
telemt_connections_current 6854
telemt_connections_me_current 6854
telemt_handshake_timeouts_total 4282
telemt_upstream_connect_attempt_total 556
telemt_upstream_connect_success_total 540
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 263
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 51
telemt_me_reconnect_success_total 51
telemt_me_reader_eof_total 48
telemt_me_idle_close_by_peer_total 48
telemt_me_route_drop_no_conn_total 119361
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 204748
telemt_me_endpoint_quarantine_total 6
telemt_me_single_endpoint_shadow_rotate_total 13
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 90
telemt_desync_total 695
telemt_desync_full_logged_total 218
telemt_desync_suppressed_total 477
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 282
telemt_me_writer_close_signal_drop_total 2
telemt_me_draining_writers_reap_progress_total 341
telemt_me_writer_removed_unexpected_total 48
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 333
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 341
telemt_me_writer_teardown_success_total{mode="normal"} 389
telemt_me_writer_teardown_noop_total 341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 730
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.017930
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 730
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 2
telemt_me_writer_restored_same_endpoint_total 48
telemt_user_connections_total{user="hello"} 204747
telemt_user_connections_current{user="hello"} 6854
telemt_user_octets_from_client{user="hello"} 5333464748 (4.97 GB)
telemt_user_octets_to_client{user="hello"} 69482298104 (64.71 GB)
telemt_user_unique_ips_current{user="hello"} 2199
telemt_user_unique_ips_recent_window{user="hello"} 893
```