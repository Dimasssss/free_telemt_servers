# Server Metrics 2026-03-20 15:02:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 2799.1 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155324
telemt_connections_bad_total 5954
telemt_connections_current 1721
telemt_connections_me_current 1721
telemt_handshake_timeouts_total 3802
telemt_upstream_connect_attempt_total 1164
telemt_upstream_connect_success_total 1159
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1164
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 712
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 131
telemt_me_reconnect_success_total 61
telemt_me_reader_eof_total 61
telemt_me_idle_close_by_peer_total 61
telemt_me_route_drop_no_conn_total 245487
telemt_me_route_drop_channel_closed_total 73
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139759
telemt_me_endpoint_quarantine_total 16
telemt_me_single_endpoint_shadow_rotate_total 24
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
telemt_me_writers_active_current 90
telemt_me_writers_warm_current 26
telemt_desync_total 394
telemt_desync_full_logged_total 126
telemt_desync_suppressed_total 268
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 147
telemt_pool_swap_total 1
telemt_pool_force_close_total 31
telemt_me_writer_close_signal_drop_total 23
telemt_me_draining_writers_reap_progress_total 881
telemt_me_writer_removed_unexpected_total 61
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 95
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 843
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 31
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 850
telemt_me_writer_teardown_success_total{mode="normal"} 938
telemt_me_writer_teardown_noop_total 881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1819
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.819363
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1819
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 23
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 57
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 139705
telemt_user_connections_current{user="hello"} 1721
telemt_user_octets_from_client{user="hello"} 1439939248 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 21016672032 (19.57 GB)
telemt_user_unique_ips_current{user="hello"} 633
telemt_user_unique_ips_recent_window{user="hello"} 346
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 2807.9 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 368951
telemt_connections_bad_total 20446
telemt_connections_current 4612
telemt_connections_me_current 4612
telemt_handshake_timeouts_total 4010
telemt_upstream_connect_attempt_total 871
telemt_upstream_connect_success_total 869
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 495
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 66
telemt_me_reconnect_success_total 18
telemt_me_reader_eof_total 19
telemt_me_idle_close_by_peer_total 19
telemt_me_route_drop_no_conn_total 153737
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 289487
telemt_me_endpoint_quarantine_total 10
telemt_me_single_endpoint_shadow_rotate_total 25
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 4
telemt_desync_total 832
telemt_desync_full_logged_total 308
telemt_desync_suppressed_total 524
telemt_desync_frames_bucket_total{bucket="1_2"} 197
telemt_desync_frames_bucket_total{bucket="3_10"} 322
telemt_desync_frames_bucket_total{bucket="gt_10"} 313
telemt_pool_swap_total 2
telemt_pool_force_close_total 91
telemt_me_writer_close_signal_drop_total 10
telemt_me_draining_writers_reap_progress_total 720
telemt_me_writer_removed_unexpected_total 19
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 62
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 650
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 629
telemt_me_writer_teardown_success_total{mode="normal"} 712
telemt_me_writer_teardown_noop_total 724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1436
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.974679
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1436
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 10
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 15
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 289378
telemt_user_connections_current{user="hello"} 4612
telemt_user_octets_from_client{user="hello"} 3507504776 (3.27 GB)
telemt_user_octets_to_client{user="hello"} 75235959968 (70.07 GB)
telemt_user_unique_ips_current{user="hello"} 1604
telemt_user_unique_ips_recent_window{user="hello"} 661
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 2801.9 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 267088
telemt_connections_bad_total 26920
telemt_connections_current 4105
telemt_connections_me_current 4105
telemt_handshake_timeouts_total 3216
telemt_upstream_connect_attempt_total 946
telemt_upstream_connect_success_total 925
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 481
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 124
telemt_me_reconnect_success_total 48
telemt_me_reader_eof_total 25
telemt_me_idle_close_by_peer_total 25
telemt_me_route_drop_no_conn_total 100411
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 223493
telemt_me_endpoint_quarantine_total 19
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 24
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_me_writers_active_current 58
telemt_me_writers_warm_current 24
telemt_desync_total 638
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 403
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 249
telemt_desync_frames_bucket_total{bucket="gt_10"} 267
telemt_pool_swap_total 2
telemt_pool_force_close_total 92
telemt_me_writer_close_signal_drop_total 13
telemt_me_draining_writers_reap_progress_total 752
telemt_me_writer_removed_unexpected_total 23
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 69
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 685
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 76
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 16
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 660
telemt_me_writer_teardown_success_total{mode="normal"} 754
telemt_me_writer_teardown_noop_total 752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1506
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.250561
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1506
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 13
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 41
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 223395
telemt_user_connections_current{user="hello"} 4105
telemt_user_octets_from_client{user="hello"} 4602648372 (4.29 GB)
telemt_user_octets_to_client{user="hello"} 73802539672 (68.73 GB)
telemt_user_unique_ips_current{user="hello"} 1444
telemt_user_unique_ips_recent_window{user="hello"} 591
```

## koara.io

```
telemt 3.3.27

telemt_uptime_seconds 16860.4 (4h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3019975
telemt_connections_bad_total 290360
telemt_connections_current 6007
telemt_connections_me_current 6007
telemt_handshake_timeouts_total 54735
telemt_upstream_connect_attempt_total 5686
telemt_upstream_connect_success_total 5650
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 5675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3063
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 545
telemt_me_reconnect_success_total 394
telemt_me_reader_eof_total 398
telemt_me_idle_close_by_peer_total 398
telemt_me_route_drop_no_conn_total 2001033
telemt_me_route_drop_channel_closed_total 116
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2411576
telemt_me_writer_pick_total{mode="p2c",result="full"} 1
telemt_me_endpoint_quarantine_total 70
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 104
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_me_writers_active_current 85
telemt_desync_total 6149
telemt_desync_full_logged_total 1751
telemt_desync_suppressed_total 4398
telemt_desync_frames_bucket_total{bucket="1_2"} 1536
telemt_desync_frames_bucket_total{bucket="3_10"} 2388
telemt_desync_frames_bucket_total{bucket="gt_10"} 2225
telemt_pool_swap_total 11
telemt_pool_force_close_total 613
telemt_me_writer_close_signal_drop_total 160
telemt_me_draining_writers_reap_progress_total 4781
telemt_me_writer_removed_unexpected_total 396
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 690
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4429
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 327
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 286
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4168
telemt_me_writer_teardown_success_total{mode="normal"} 5119
telemt_me_writer_teardown_noop_total 4791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 8115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 8904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 9122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 9374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 9652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 9833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 9910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 9910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 9910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 9910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 9910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 9910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 9910
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 39.866285
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 9910
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 160
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 382
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 2409065
telemt_user_connections_current{user="hello"} 6007
telemt_user_octets_from_client{user="hello"} 25371273724 (23.63 GB)
telemt_user_octets_to_client{user="hello"} 640736456584 (596.73 GB)
telemt_user_unique_ips_current{user="hello"} 1949
telemt_user_unique_ips_recent_window{user="hello"} 879
```

## landvps.ru

Не удалось получить метрики для этого сервера.

## rdp-onedash.ru

```
telemt 3.3.28

telemt_uptime_seconds 2805.6 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1035377
telemt_connections_bad_total 61069
telemt_connections_current 6587
telemt_connections_me_current 6587
telemt_handshake_timeouts_total 10381
telemt_upstream_connect_attempt_total 801
telemt_upstream_connect_success_total 801
telemt_upstream_connect_attempts_per_request{bucket="1"} 801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 35
telemt_me_reconnect_success_total 14
telemt_me_reader_eof_total 14
telemt_me_idle_close_by_peer_total 14
telemt_me_route_drop_no_conn_total 1977373
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 895054
telemt_me_endpoint_quarantine_total 12
telemt_me_single_endpoint_shadow_rotate_total 20
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_desync_total 1149
telemt_desync_full_logged_total 323
telemt_desync_suppressed_total 826
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 483
telemt_desync_frames_bucket_total{bucket="gt_10"} 388
telemt_pool_swap_total 3
telemt_pool_force_close_total 69
telemt_me_writer_close_signal_drop_total 13
telemt_me_draining_writers_reap_progress_total 609
telemt_me_writer_removed_unexpected_total 14
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 573
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 58
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 540
telemt_me_writer_teardown_success_total{mode="normal"} 624
telemt_me_writer_teardown_noop_total 610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1234
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.999186
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1234
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 13
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 895066
telemt_user_connections_current{user="hello"} 6587
telemt_user_octets_from_client{user="hello"} 5776449464 (5.38 GB)
telemt_user_octets_to_client{user="hello"} 53831254700 (50.13 GB)
telemt_user_unique_ips_current{user="hello"} 2075
telemt_user_unique_ips_recent_window{user="hello"} 1026
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 2230.9 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47498
telemt_connections_bad_total 640
telemt_connections_current 816
telemt_connections_me_current 816
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 567
telemt_upstream_connect_attempt_total 2529
telemt_upstream_connect_success_total 2526
telemt_upstream_connect_attempts_per_request{bucket="1"} 2526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1774
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 93
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 75
telemt_me_reconnect_success_total 18
telemt_me_reader_eof_total 16
telemt_me_idle_close_by_peer_total 16
telemt_me_route_drop_no_conn_total 46269
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42781
telemt_me_endpoint_quarantine_total 13
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
telemt_me_writers_active_current 44
telemt_desync_total 65
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 41
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 2
telemt_pool_force_close_total 31
telemt_me_writer_close_signal_drop_total 29
telemt_me_draining_writers_reap_progress_total 695
telemt_me_writer_removed_unexpected_total 16
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 86
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 625
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 31
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 664
telemt_me_writer_teardown_success_total{mode="normal"} 711
telemt_me_writer_teardown_noop_total 695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1406
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.305389
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1406
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 29
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 11
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 43911
telemt_user_connections_current{user="hello"} 816
telemt_user_octets_from_client{user="hello"} 573283350 (546.73 MB)
telemt_user_octets_to_client{user="hello"} 6988850049 (6.51 GB)
telemt_user_msgs_from_client{user="hello"} 5317
telemt_user_msgs_to_client{user="hello"} 6420
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## 4vps.su

```
telemt 3.3.28

telemt_uptime_seconds 2803.4 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 487127
telemt_connections_bad_total 27193
telemt_connections_current 7256
telemt_connections_me_current 7256
telemt_handshake_timeouts_total 18175
telemt_upstream_connect_attempt_total 821
telemt_upstream_connect_success_total 820
telemt_upstream_connect_attempts_per_request{bucket="1"} 820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 448
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 12
telemt_me_reconnect_success_total 14
telemt_me_reader_eof_total 10
telemt_me_idle_close_by_peer_total 10
telemt_me_route_drop_no_conn_total 185381
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 413025
telemt_me_endpoint_quarantine_total 14
telemt_me_single_endpoint_shadow_rotate_total 20
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_desync_total 1213
telemt_desync_full_logged_total 356
telemt_desync_suppressed_total 857
telemt_desync_frames_bucket_total{bucket="1_2"} 239
telemt_desync_frames_bucket_total{bucket="3_10"} 484
telemt_desync_frames_bucket_total{bucket="gt_10"} 490
telemt_pool_swap_total 3
telemt_pool_force_close_total 76
telemt_me_writer_close_signal_drop_total 10
telemt_me_draining_writers_reap_progress_total 629
telemt_me_writer_removed_unexpected_total 10
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 49
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 590
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 62
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 14
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 553
telemt_me_writer_teardown_success_total{mode="normal"} 639
telemt_me_writer_teardown_noop_total 630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1269
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.470840
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1269
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 10
telemt_me_writer_restored_same_endpoint_total 10
telemt_user_connections_total{user="hello"} 412831
telemt_user_connections_current{user="hello"} 7256
telemt_user_octets_from_client{user="hello"} 5201296732 (4.84 GB)
telemt_user_octets_to_client{user="hello"} 134083131024 (124.87 GB)
telemt_user_unique_ips_current{user="hello"} 2269
telemt_user_unique_ips_recent_window{user="hello"} 1025
```