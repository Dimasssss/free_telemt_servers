# Server Metrics 2026-03-20 14:16:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 35.8 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4273
telemt_connections_bad_total 44
telemt_connections_current 2176
telemt_connections_me_current 2176
telemt_upstream_connect_attempt_total 93
telemt_upstream_connect_success_total 91
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 93
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 465
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3902
telemt_me_endpoint_quarantine_total 7
telemt_me_single_endpoint_shadow_rotate_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 43
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_me_draining_writers_reap_progress_total 7
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7
telemt_me_writer_teardown_success_total{mode="normal"} 7
telemt_me_writer_teardown_noop_total 7
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 14
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 14
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 14
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 14
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 14
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 14
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 14
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 14
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 14
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 14
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 14
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 14
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 14
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.000999
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 14
telemt_user_connections_total{user="hello"} 3933
telemt_user_connections_current{user="hello"} 2176
telemt_user_octets_from_client{user="hello"} 12938204 (12.34 MB)
telemt_user_octets_to_client{user="hello"} 5338332 (5.09 MB)
telemt_user_unique_ips_current{user="hello"} 493
telemt_user_unique_ips_recent_window{user="hello"} 509
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 44.4 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16350
telemt_connections_bad_total 862
telemt_connections_current 4841
telemt_connections_me_current 4841
telemt_upstream_connect_attempt_total 91
telemt_upstream_connect_success_total 90
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 91
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_route_drop_no_conn_total 9353
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14861
telemt_me_endpoint_quarantine_total 5
telemt_me_single_endpoint_shadow_rotate_total 6
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 43
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_me_draining_writers_reap_progress_total 5
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5
telemt_me_writer_teardown_success_total{mode="normal"} 5
telemt_me_writer_teardown_noop_total 5
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 6
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 10
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.037212
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 10
telemt_user_connections_total{user="hello"} 14861
telemt_user_connections_current{user="hello"} 4841
telemt_user_octets_from_client{user="hello"} 25966524 (24.76 MB)
telemt_user_octets_to_client{user="hello"} 414433568 (395.23 MB)
telemt_user_unique_ips_current{user="hello"} 1369
telemt_user_unique_ips_recent_window{user="hello"} 1796
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 38.3 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7838
telemt_connections_bad_total 54
telemt_connections_current 3041
telemt_connections_me_current 3041
telemt_upstream_connect_attempt_total 93
telemt_upstream_connect_success_total 82
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 91
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 3
telemt_me_route_drop_no_conn_total 2835
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7603
telemt_me_endpoint_quarantine_total 5
telemt_me_single_endpoint_shadow_rotate_total 5
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 43
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_me_draining_writers_reap_progress_total 5
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5
telemt_me_writer_teardown_success_total{mode="normal"} 5
telemt_me_writer_teardown_noop_total 5
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 10
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.000964
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 10
telemt_user_connections_total{user="hello"} 7603
telemt_user_connections_current{user="hello"} 3041
telemt_user_octets_from_client{user="hello"} 10257660 (9.78 MB)
telemt_user_octets_to_client{user="hello"} 214368892 (204.44 MB)
telemt_user_unique_ips_current{user="hello"} 1143
telemt_user_unique_ips_recent_window{user="hello"} 1278
```

## koara.io

```
telemt 3.3.27

telemt_uptime_seconds 14097.3 (3h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2422443
telemt_connections_bad_total 263851
telemt_connections_current 6271
telemt_connections_me_current 6271
telemt_handshake_timeouts_total 43899
telemt_upstream_connect_attempt_total 4799
telemt_upstream_connect_success_total 4768
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 4788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2597
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 449
telemt_me_reconnect_success_total 334
telemt_me_reader_eof_total 334
telemt_me_idle_close_by_peer_total 334
telemt_me_route_drop_no_conn_total 1410390
telemt_me_route_drop_channel_closed_total 89
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1912899
telemt_me_endpoint_quarantine_total 60
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 89
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
telemt_me_writers_active_current 89
telemt_desync_total 4570
telemt_desync_full_logged_total 1340
telemt_desync_suppressed_total 3230
telemt_desync_frames_bucket_total{bucket="1_2"} 1119
telemt_desync_frames_bucket_total{bucket="3_10"} 1748
telemt_desync_frames_bucket_total{bucket="gt_10"} 1703
telemt_pool_swap_total 9
telemt_pool_force_close_total 501
telemt_me_writer_close_signal_drop_total 127
telemt_me_draining_writers_reap_progress_total 4005
telemt_me_writer_removed_unexpected_total 333
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 578
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3715
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 259
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 242
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3504
telemt_me_writer_teardown_success_total{mode="normal"} 4293
telemt_me_writer_teardown_noop_total 4015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 6880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 7532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 7708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 7890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 8111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 8244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 8308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 8308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 8308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 8308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 8308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 8308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 8308
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 30.822876
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 8308
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 127
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 323
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 1910822
telemt_user_connections_current{user="hello"} 6271
telemt_user_octets_from_client{user="hello"} 20696989316 (19.28 GB)
telemt_user_octets_to_client{user="hello"} 543427644252 (506.11 GB)
telemt_user_unique_ips_current{user="hello"} 1942
telemt_user_unique_ips_recent_window{user="hello"} 843
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 37.1 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12582
telemt_connections_bad_total 92
telemt_connections_current 5015
telemt_connections_me_current 5015
telemt_upstream_connect_attempt_total 89
telemt_upstream_connect_success_total 87
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 89
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_route_drop_no_conn_total 4233
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11886
telemt_me_endpoint_quarantine_total 8
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 43
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 3
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_draining_writers_reap_progress_total 8
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8
telemt_me_writer_teardown_success_total{mode="normal"} 8
telemt_me_writer_teardown_noop_total 8
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 16
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 16
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 16
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 16
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 16
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 16
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 16
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 16
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 16
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 16
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 16
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 16
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 16
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.000300
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 16
telemt_user_connections_total{user="hello"} 11886
telemt_user_connections_current{user="hello"} 5015
telemt_user_octets_from_client{user="hello"} 31520880 (30.06 MB)
telemt_user_octets_to_client{user="hello"} 187229676 (178.56 MB)
telemt_user_unique_ips_current{user="hello"} 1415
telemt_user_unique_ips_recent_window{user="hello"} 1582
```

## rdp-onedash.ru

```
telemt 3.3.28

telemt_uptime_seconds 42.0 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16929
telemt_connections_bad_total 287
telemt_connections_current 5945
telemt_connections_me_current 5945
telemt_upstream_connect_attempt_total 85
telemt_upstream_connect_success_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 85
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34
telemt_me_route_drop_no_conn_total 5322
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12503
telemt_me_endpoint_quarantine_total 3
telemt_me_single_endpoint_shadow_rotate_total 3
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 43
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_draining_writers_reap_progress_total 3
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3
telemt_me_writer_teardown_success_total{mode="normal"} 3
telemt_me_writer_teardown_noop_total 3
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 6
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 6
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 6
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 6
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 6
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 6
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 6
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 6
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 6
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 6
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 6
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 6
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 6
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.000074
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 6
telemt_user_connections_total{user="hello"} 12504
telemt_user_connections_current{user="hello"} 5945
telemt_user_octets_from_client{user="hello"} 50434376 (48.10 MB)
telemt_user_octets_to_client{user="hello"} 575997136 (549.31 MB)
telemt_user_unique_ips_current{user="hello"} 1746
telemt_user_unique_ips_recent_window{user="hello"} 2008
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 35.4 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1946
telemt_connections_bad_total 62
telemt_connections_current 766
telemt_connections_me_current 766
telemt_upstream_connect_attempt_total 94
telemt_upstream_connect_success_total 92
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 94
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_success_total 3
telemt_me_route_drop_no_conn_total 447
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1864
telemt_me_endpoint_quarantine_total 3
telemt_me_single_endpoint_shadow_rotate_total 5
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 43
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_me_draining_writers_reap_progress_total 4
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4
telemt_me_writer_teardown_success_total{mode="normal"} 4
telemt_me_writer_teardown_noop_total 4
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 7
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 7
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 7
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 8
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 8
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 8
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 8
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 8
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 8
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 8
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 8
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 8
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 8
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.014666
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 8
telemt_user_connections_total{user="hello"} 1817
telemt_user_connections_current{user="hello"} 766
telemt_user_octets_from_client{user="hello"} 4280440 (4.08 MB)
telemt_user_octets_to_client{user="hello"} 11045188 (10.53 MB)
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 257
```

## 4vps.su

```
telemt 3.3.28

telemt_uptime_seconds 39.9 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16937
telemt_connections_bad_total 184
telemt_connections_current 6612
telemt_connections_me_current 6612
telemt_upstream_connect_attempt_total 93
telemt_upstream_connect_success_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 92
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 4
telemt_me_route_drop_no_conn_total 5627
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15547
telemt_me_endpoint_quarantine_total 3
telemt_me_single_endpoint_shadow_rotate_total 5
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 43
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_desync_total 7
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_draining_writers_reap_progress_total 3
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3
telemt_me_writer_teardown_success_total{mode="normal"} 3
telemt_me_writer_teardown_noop_total 3
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 6
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 6
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 6
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 6
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 6
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 6
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 6
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 6
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 6
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 6
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 6
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 6
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 6
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.001049
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 6
telemt_user_connections_total{user="hello"} 15547
telemt_user_connections_current{user="hello"} 6612
telemt_user_octets_from_client{user="hello"} 27646356 (26.37 MB)
telemt_user_octets_to_client{user="hello"} 637053784 (607.54 MB)
telemt_user_unique_ips_current{user="hello"} 1842
telemt_user_unique_ips_recent_window{user="hello"} 2066
```