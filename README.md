# Server Metrics 2026-03-20 10:51:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.27

telemt_uptime_seconds 2026.6 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164108
telemt_connections_bad_total 4773
telemt_connections_current 1505
telemt_connections_me_current 1505
telemt_handshake_timeouts_total 1485
telemt_upstream_connect_attempt_total 722
telemt_upstream_connect_success_total 710
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 412
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 108
telemt_me_reconnect_success_total 17
telemt_me_reader_eof_total 16
telemt_me_idle_close_by_peer_total 16
telemt_me_route_drop_no_conn_total 252470
telemt_me_route_drop_channel_closed_total 57
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 138093
telemt_me_writer_pick_total{mode="p2c",result="full"} 1
telemt_me_endpoint_quarantine_total 16
telemt_me_single_endpoint_shadow_rotate_total 21
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
telemt_me_writers_active_current 46
telemt_desync_total 271
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 174
telemt_desync_frames_bucket_total{bucket="1_2"} 70
telemt_desync_frames_bucket_total{bucket="3_10"} 103
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 2
telemt_pool_force_close_total 59
telemt_me_writer_close_signal_drop_total 28
telemt_me_draining_writers_reap_progress_total 562
telemt_me_writer_removed_unexpected_total 16
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 49
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 525
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 58
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 503
telemt_me_writer_teardown_success_total{mode="normal"} 574
telemt_me_writer_teardown_noop_total 562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1136
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.386292
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1136
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 28
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 11
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 137745
telemt_user_connections_current{user="hello"} 1505
telemt_user_octets_from_client{user="hello"} 897177000 (855.61 MB)
telemt_user_octets_to_client{user="hello"} 13762852420 (12.82 GB)
telemt_user_unique_ips_current{user="hello"} 509
telemt_user_unique_ips_recent_window{user="hello"} 501
```

## psb.hosting №1

```
telemt 3.3.27

telemt_uptime_seconds 2008.5 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 242191
telemt_connections_bad_total 29068
telemt_connections_current 4205
telemt_connections_me_current 4205
telemt_handshake_timeouts_total 6305
telemt_upstream_connect_attempt_total 893
telemt_upstream_connect_success_total 887
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 87
telemt_me_reconnect_success_total 82
telemt_me_reader_eof_total 82
telemt_me_idle_close_by_peer_total 82
telemt_me_route_drop_no_conn_total 180085
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183826
telemt_me_endpoint_quarantine_total 5
telemt_me_single_endpoint_shadow_rotate_total 18
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
telemt_me_writers_active_current 119
telemt_me_writers_warm_current 11
telemt_desync_total 579
telemt_desync_full_logged_total 212
telemt_desync_suppressed_total 367
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 204
telemt_me_writer_close_signal_drop_total 3
telemt_me_draining_writers_reap_progress_total 584
telemt_me_writer_removed_unexpected_total 83
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 108
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 559
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 584
telemt_me_writer_teardown_success_total{mode="normal"} 667
telemt_me_writer_teardown_noop_total 584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1251
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.034415
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1251
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 3
telemt_me_writer_restored_same_endpoint_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 183869
telemt_user_connections_current{user="hello"} 4205
telemt_user_octets_from_client{user="hello"} 2587243696 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 50866855404 (47.37 GB)
telemt_user_unique_ips_current{user="hello"} 1465
telemt_user_unique_ips_recent_window{user="hello"} 592
```

## psb.hosting №2

```
telemt 3.3.27

telemt_uptime_seconds 1996.9 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185284
telemt_connections_bad_total 29900
telemt_connections_current 3518
telemt_connections_me_current 3518
telemt_handshake_timeouts_total 2289
telemt_upstream_connect_attempt_total 678
telemt_upstream_connect_success_total 678
telemt_upstream_connect_attempts_per_request{bucket="1"} 678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 301
telemt_me_reconnect_attempts_total 97
telemt_me_reconnect_success_total 44
telemt_me_reader_eof_total 50
telemt_me_idle_close_by_peer_total 50
telemt_me_route_drop_no_conn_total 61726
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 138205
telemt_me_endpoint_quarantine_total 3
telemt_me_single_endpoint_shadow_rotate_total 17
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
telemt_me_writers_active_current 74
telemt_me_writers_warm_current 6
telemt_desync_total 358
telemt_desync_full_logged_total 121
telemt_desync_suppressed_total 237
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 126
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 1
telemt_pool_force_close_total 27
telemt_me_writer_close_signal_drop_total 3
telemt_me_draining_writers_reap_progress_total 462
telemt_me_writer_removed_unexpected_total 49
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 434
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 435
telemt_me_writer_teardown_success_total{mode="normal"} 512
telemt_me_writer_teardown_noop_total 462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 974
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.067274
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 974
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 3
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 138234
telemt_user_connections_current{user="hello"} 3518
telemt_user_octets_from_client{user="hello"} 1916951436 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 49843020308 (46.42 GB)
telemt_user_unique_ips_current{user="hello"} 1413
telemt_user_unique_ips_recent_window{user="hello"} 486
```

## koara.io

```
telemt 3.3.27

telemt_uptime_seconds 1803.3 (0h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 263395
telemt_connections_bad_total 24523
telemt_connections_current 5673
telemt_connections_me_current 5673
telemt_handshake_timeouts_total 4659
telemt_upstream_connect_attempt_total 493
telemt_upstream_connect_success_total 492
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 277
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 4
telemt_me_reader_eof_total 3
telemt_me_idle_close_by_peer_total 3
telemt_me_route_drop_no_conn_total 128208
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 217154
telemt_me_endpoint_quarantine_total 8
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_me_writers_active_current 44
telemt_desync_total 319
telemt_desync_full_logged_total 127
telemt_desync_suppressed_total 192
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 114
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 376
telemt_me_writer_removed_unexpected_total 3
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 358
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 342
telemt_me_writer_teardown_success_total{mode="normal"} 379
telemt_me_writer_teardown_noop_total 376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 755
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.795307
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 755
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_writer_restored_same_endpoint_total 3
telemt_user_connections_total{user="hello"} 216504
telemt_user_connections_current{user="hello"} 5673
telemt_user_octets_from_client{user="hello"} 2349056620 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 72853785220 (67.85 GB)
telemt_user_unique_ips_current{user="hello"} 1809
telemt_user_unique_ips_recent_window{user="hello"} 771
```

## landvps.ru

```
telemt 3.3.27

telemt_uptime_seconds 1788.3 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 698262
telemt_connections_bad_total 9167
telemt_connections_current 5916
telemt_connections_me_current 5916
telemt_handshake_timeouts_total 5229
telemt_upstream_connect_attempt_total 755
telemt_upstream_connect_success_total 685
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 381
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 58
telemt_me_reconnect_success_total 55
telemt_me_reader_eof_total 52
telemt_me_idle_close_by_peer_total 52
telemt_me_route_drop_no_conn_total 1437734
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 644772
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
telemt_desync_total 400
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 281
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 175
telemt_desync_frames_bucket_total{bucket="gt_10"} 117
telemt_me_writer_close_signal_drop_total 5
telemt_me_draining_writers_reap_progress_total 458
telemt_me_writer_removed_unexpected_total 54
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 68
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 458
telemt_me_writer_teardown_success_total{mode="normal"} 512
telemt_me_writer_teardown_noop_total 458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 970
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.274273
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 970
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 5
telemt_me_writer_restored_same_endpoint_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 644731
telemt_user_connections_current{user="hello"} 5916
telemt_user_octets_from_client{user="hello"} 2445840060 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 20338142324 (18.94 GB)
telemt_user_unique_ips_current{user="hello"} 1764
telemt_user_unique_ips_recent_window{user="hello"} 1075
```

## rdp-onedash.ru

```
telemt 3.3.27

telemt_uptime_seconds 1780.2 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 530955
telemt_connections_bad_total 12769
telemt_connections_current 7007
telemt_connections_me_current 7007
telemt_handshake_timeouts_total 7025
telemt_upstream_connect_attempt_total 458
telemt_upstream_connect_success_total 453
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 229
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 6
telemt_me_reconnect_success_total 8
telemt_me_reader_eof_total 6
telemt_me_idle_close_by_peer_total 6
telemt_me_route_drop_no_conn_total 781171
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 470900
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
telemt_desync_total 1044
telemt_desync_full_logged_total 298
telemt_desync_suppressed_total 746
telemt_desync_frames_bucket_total{bucket="1_2"} 229
telemt_desync_frames_bucket_total{bucket="3_10"} 452
telemt_desync_frames_bucket_total{bucket="gt_10"} 363
telemt_pool_swap_total 1
telemt_pool_force_close_total 33
telemt_me_writer_close_signal_drop_total 6
telemt_me_draining_writers_reap_progress_total 342
telemt_me_writer_removed_unexpected_total 6
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 28
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 320
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 309
telemt_me_writer_teardown_success_total{mode="normal"} 348
telemt_me_writer_teardown_noop_total 342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 690
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.608846
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 690
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 6
telemt_me_writer_restored_same_endpoint_total 6
telemt_user_connections_total{user="hello"} 470848
telemt_user_connections_current{user="hello"} 7007
telemt_user_octets_from_client{user="hello"} 2979053484 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 38089544080 (35.47 GB)
telemt_user_unique_ips_current{user="hello"} 2168
telemt_user_unique_ips_recent_window{user="hello"} 969
```

## hostvds.com

```
telemt 3.3.27

telemt_uptime_seconds 1779.3 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42287
telemt_connections_bad_total 7429
telemt_connections_current 866
telemt_connections_me_current 866
telemt_handshake_timeouts_total 587
telemt_upstream_connect_attempt_total 896
telemt_upstream_connect_success_total 896
telemt_upstream_connect_attempts_per_request{bucket="1"} 896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 613
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_me_reconnect_attempts_total 95
telemt_me_reconnect_success_total 46
telemt_me_reader_eof_total 48
telemt_me_idle_close_by_peer_total 48
telemt_me_route_drop_no_conn_total 20755
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30855
telemt_me_endpoint_quarantine_total 7
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
telemt_me_writers_active_current 86
telemt_desync_total 59
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_force_close_total 1
telemt_me_writer_close_signal_drop_total 5
telemt_me_draining_writers_reap_progress_total 671
telemt_me_writer_removed_unexpected_total 48
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 69
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 651
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 670
telemt_me_writer_teardown_success_total{mode="normal"} 720
telemt_me_writer_teardown_noop_total 671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1391
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.373686
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1391
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 5
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 30856
telemt_user_connections_current{user="hello"} 866
telemt_user_octets_from_client{user="hello"} 415190788 (395.96 MB)
telemt_user_octets_to_client{user="hello"} 5199912220 (4.84 GB)
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## 4vps.su

```
telemt 3.3.27

telemt_uptime_seconds 1770.9 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 313790
telemt_connections_bad_total 62815
telemt_connections_current 6722
telemt_connections_me_current 6722
telemt_handshake_timeouts_total 5074
telemt_upstream_connect_attempt_total 661
telemt_upstream_connect_success_total 645
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 318
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 51
telemt_me_reconnect_success_total 51
telemt_me_reader_eof_total 48
telemt_me_idle_close_by_peer_total 48
telemt_me_route_drop_no_conn_total 131659
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 235409
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
telemt_desync_total 804
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 545
telemt_desync_frames_bucket_total{bucket="1_2"} 193
telemt_desync_frames_bucket_total{bucket="3_10"} 289
telemt_desync_frames_bucket_total{bucket="gt_10"} 322
telemt_me_writer_close_signal_drop_total 2
telemt_me_draining_writers_reap_progress_total 446
telemt_me_writer_removed_unexpected_total 48
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 58
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 436
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 446
telemt_me_writer_teardown_success_total{mode="normal"} 494
telemt_me_writer_teardown_noop_total 446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 940
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.028042
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 940
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 2
telemt_me_writer_restored_same_endpoint_total 48
telemt_user_connections_total{user="hello"} 235407
telemt_user_connections_current{user="hello"} 6722
telemt_user_octets_from_client{user="hello"} 6394119476 (5.95 GB)
telemt_user_octets_to_client{user="hello"} 84251488176 (78.47 GB)
telemt_user_unique_ips_current{user="hello"} 2205
telemt_user_unique_ips_recent_window{user="hello"} 855
```