# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

Можете писать свой ник в коментарии к переводу

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
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

## rdp-onedash.ru (2 сервера)
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

## 4vps.su (2 сервера)
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-21 06:38:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 36134.6 (10h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 766797
telemt_connections_bad_total 42234
telemt_connections_current 1328
telemt_connections_me_current 1328
telemt_handshake_timeouts_total 38376
telemt_upstream_connect_attempt_total 14669
telemt_upstream_connect_success_total 14602
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 14646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9488
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 456
telemt_me_reconnect_success_total 235
telemt_me_reader_eof_total 247
telemt_me_idle_close_by_peer_total 247
telemt_me_route_drop_no_conn_total 255184
telemt_me_route_drop_channel_closed_total 60
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 573631
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 258
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 299
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 12
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
telemt_desync_total 2516
telemt_desync_full_logged_total 904
telemt_desync_suppressed_total 1612
telemt_desync_frames_bucket_total{bucket="1_2"} 527
telemt_desync_frames_bucket_total{bucket="3_10"} 1000
telemt_desync_frames_bucket_total{bucket="gt_10"} 989
telemt_pool_swap_total 40
telemt_pool_force_close_total 1065
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 99
telemt_me_draining_writers_reap_progress_total 13192
telemt_me_writer_removed_unexpected_total 232
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 974
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12409
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1061
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12127
telemt_me_writer_teardown_success_total{mode="normal"} 13383
telemt_me_writer_teardown_noop_total 13193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26576
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 38.424877
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26576
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 99
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 212
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 572929
telemt_user_connections_current{user="hello"} 1328
telemt_user_octets_from_client{user="hello"} 6826419760 (6.36 GB)
telemt_user_octets_to_client{user="hello"} 180733260628 (168.32 GB)
telemt_user_unique_ips_current{user="hello"} 510
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 36135.8 (10h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1946237
telemt_connections_bad_total 223792
telemt_connections_current 3565
telemt_connections_me_current 3565
telemt_handshake_timeouts_total 59956
telemt_upstream_connect_attempt_total 13676
telemt_upstream_connect_success_total 13613
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 13657
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7993
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_reconnect_attempts_total 760
telemt_me_reconnect_success_total 272
telemt_me_reader_eof_total 285
telemt_me_idle_close_by_peer_total 285
telemt_me_route_drop_no_conn_total 376146
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1152378
telemt_me_endpoint_quarantine_total 237
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 290
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
telemt_me_writers_active_current 33
telemt_desync_total 4913
telemt_desync_full_logged_total 1718
telemt_desync_suppressed_total 3195
telemt_desync_frames_bucket_total{bucket="1_2"} 1003
telemt_desync_frames_bucket_total{bucket="3_10"} 1951
telemt_desync_frames_bucket_total{bucket="gt_10"} 1959
telemt_pool_swap_total 39
telemt_pool_force_close_total 1131
telemt_me_writer_close_signal_drop_total 114
telemt_me_draining_writers_reap_progress_total 12244
telemt_me_writer_removed_unexpected_total 266
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1075
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11427
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1078
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11113
telemt_me_writer_teardown_success_total{mode="normal"} 12502
telemt_me_writer_teardown_noop_total 12244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24746
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.378363
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24746
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 114
telemt_me_refill_failed_total 27
telemt_me_writer_restored_same_endpoint_total 233
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 1149464
telemt_user_connections_current{user="hello"} 3565
telemt_user_octets_from_client{user="hello"} 15776665632 (14.69 GB)
telemt_user_octets_to_client{user="hello"} 474206528756 (441.64 GB)
telemt_user_unique_ips_current{user="hello"} 1419
telemt_user_unique_ips_recent_window{user="hello"} 527
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 36132.3 (10h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1280426
telemt_connections_bad_total 158451
telemt_connections_current 3272
telemt_connections_me_current 3272
telemt_handshake_timeouts_total 59126
telemt_upstream_connect_attempt_total 14776
telemt_upstream_connect_success_total 14766
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 14767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6720
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8003
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 411
telemt_me_reconnect_success_total 240
telemt_me_reader_eof_total 250
telemt_me_idle_close_by_peer_total 250
telemt_me_route_drop_no_conn_total 307956
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 989396
telemt_me_endpoint_quarantine_total 259
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 292
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 11
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
telemt_desync_total 3982
telemt_desync_full_logged_total 1447
telemt_desync_suppressed_total 2535
telemt_desync_frames_bucket_total{bucket="1_2"} 892
telemt_desync_frames_bucket_total{bucket="3_10"} 1544
telemt_desync_frames_bucket_total{bucket="gt_10"} 1546
telemt_pool_swap_total 40
telemt_pool_force_close_total 1052
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 119
telemt_me_draining_writers_reap_progress_total 13415
telemt_me_writer_removed_unexpected_total 231
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1040
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12557
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1046
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12363
telemt_me_writer_teardown_success_total{mode="normal"} 13597
telemt_me_writer_teardown_noop_total 13418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27015
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.747534
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27015
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 119
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 206
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 987311
telemt_user_connections_current{user="hello"} 3272
telemt_user_octets_from_client{user="hello"} 13666415212 (12.73 GB)
telemt_user_octets_to_client{user="hello"} 437070269556 (407.05 GB)
telemt_user_unique_ips_current{user="hello"} 1242
telemt_user_unique_ips_recent_window{user="hello"} 450
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 36133.8 (10h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1110868
telemt_connections_bad_total 149995
telemt_connections_current 2813
telemt_connections_me_current 2813
telemt_handshake_timeouts_total 55141
telemt_upstream_connect_attempt_total 14918
telemt_upstream_connect_success_total 14829
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 14870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8269
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_reconnect_attempts_total 651
telemt_me_reconnect_success_total 266
telemt_me_reader_eof_total 266
telemt_me_idle_close_by_peer_total 266
telemt_me_route_drop_no_conn_total 240051
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 749808
telemt_me_endpoint_quarantine_total 260
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 292
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_desync_total 3344
telemt_desync_full_logged_total 1243
telemt_desync_suppressed_total 2101
telemt_desync_frames_bucket_total{bucket="1_2"} 725
telemt_desync_frames_bucket_total{bucket="3_10"} 1447
telemt_desync_frames_bucket_total{bucket="gt_10"} 1172
telemt_pool_swap_total 40
telemt_pool_force_close_total 1010
telemt_me_writer_close_signal_drop_total 50
telemt_me_draining_writers_reap_progress_total 13352
telemt_me_writer_removed_unexpected_total 254
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 964
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12656
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 992
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12342
telemt_me_writer_teardown_success_total{mode="normal"} 13620
telemt_me_writer_teardown_noop_total 13353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26973
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.151813
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26973
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 50
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 227
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 748524
telemt_user_connections_current{user="hello"} 2813
telemt_user_octets_from_client{user="hello"} 13705316852 (12.76 GB)
telemt_user_octets_to_client{user="hello"} 364118133808 (339.11 GB)
telemt_user_unique_ips_current{user="hello"} 1102
telemt_user_unique_ips_recent_window{user="hello"} 483
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 36097.4 (10h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1057440
telemt_connections_bad_total 134062
telemt_connections_current 2027
telemt_connections_me_current 2027
telemt_handshake_timeouts_total 39080
telemt_upstream_connect_attempt_total 15405
telemt_upstream_connect_success_total 15396
telemt_upstream_connect_attempts_per_request{bucket="1"} 15396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8551
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 275
telemt_me_reconnect_success_total 231
telemt_me_reader_eof_total 228
telemt_me_idle_close_by_peer_total 228
telemt_me_route_drop_no_conn_total 212270
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 744682
telemt_me_endpoint_quarantine_total 304
telemt_me_single_endpoint_shadow_rotate_total 288
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_desync_total 3381
telemt_desync_full_logged_total 1301
telemt_desync_suppressed_total 2080
telemt_desync_frames_bucket_total{bucket="1_2"} 804
telemt_desync_frames_bucket_total{bucket="3_10"} 1345
telemt_desync_frames_bucket_total{bucket="gt_10"} 1232
telemt_pool_swap_total 40
telemt_pool_force_close_total 968
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 60
telemt_me_draining_writers_reap_progress_total 13929
telemt_me_writer_removed_unexpected_total 209
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 917
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13241
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 958
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12961
telemt_me_writer_teardown_success_total{mode="normal"} 14158
telemt_me_writer_teardown_noop_total 13930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28088
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.448369
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28088
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 60
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 205
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 743210
telemt_user_connections_current{user="hello"} 2027
telemt_user_octets_from_client{user="hello"} 17498775412 (16.30 GB)
telemt_user_octets_to_client{user="hello"} 385970720964 (359.46 GB)
telemt_user_unique_ips_current{user="hello"} 736
telemt_user_unique_ips_recent_window{user="hello"} 505
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 36136.8 (10h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2196007
telemt_connections_bad_total 164891
telemt_connections_current 3821
telemt_connections_me_current 3821
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 146783
telemt_upstream_connect_attempt_total 28571
telemt_upstream_connect_success_total 27185
telemt_upstream_connect_fail_total 875
telemt_upstream_connect_attempts_per_request{bucket="1"} 28060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9234
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 432
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 875
telemt_me_reconnect_attempts_total 1761
telemt_me_reconnect_success_total 570
telemt_me_reader_eof_total 383
telemt_me_idle_close_by_peer_total 382
telemt_me_route_drop_no_conn_total 1765593
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1735631
telemt_me_endpoint_quarantine_total 294
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 78
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 78
telemt_me_single_endpoint_shadow_rotate_total 292
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_me_writers_active_current 35
telemt_desync_total 4315
telemt_desync_full_logged_total 1612
telemt_desync_suppressed_total 2703
telemt_desync_frames_bucket_total{bucket="1_2"} 964
telemt_desync_frames_bucket_total{bucket="3_10"} 1827
telemt_desync_frames_bucket_total{bucket="gt_10"} 1524
telemt_pool_swap_total 39
telemt_pool_force_close_total 1083
telemt_me_writer_close_signal_drop_total 146
telemt_me_draining_writers_reap_progress_total 12385
telemt_me_writer_removed_unexpected_total 554
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1372
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11538
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1017
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 66
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11302
telemt_me_writer_teardown_success_total{mode="normal"} 12910
telemt_me_writer_teardown_noop_total 12389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25299
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.300668
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25299
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 146
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 368
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 1746985
telemt_user_connections_current{user="hello"} 3821
telemt_user_octets_from_client{user="hello"} 32049008440 (29.85 GB)
telemt_user_octets_to_client{user="hello"} 445769696707 (415.16 GB)
telemt_user_msgs_from_client{user="hello"} 40291
telemt_user_msgs_to_client{user="hello"} 96775
telemt_user_unique_ips_current{user="hello"} 1496
telemt_user_unique_ips_recent_window{user="hello"} 606
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 36104.2 (10h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1133192
telemt_connections_bad_total 158512
telemt_connections_current 2492
telemt_connections_me_current 2492
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 24386
telemt_upstream_connect_attempt_total 16877
telemt_upstream_connect_success_total 16726
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 16862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_reconnect_attempts_total 1319
telemt_me_reconnect_success_total 326
telemt_me_reader_eof_total 338
telemt_me_idle_close_by_peer_total 338
telemt_me_route_drop_no_conn_total 270826
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 815115
telemt_me_endpoint_quarantine_total 242
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 291
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 17
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
telemt_me_writers_warm_current 34
telemt_desync_total 3285
telemt_desync_full_logged_total 1252
telemt_desync_suppressed_total 2033
telemt_desync_frames_bucket_total{bucket="1_2"} 621
telemt_desync_frames_bucket_total{bucket="3_10"} 1352
telemt_desync_frames_bucket_total{bucket="gt_10"} 1312
telemt_pool_swap_total 39
telemt_pool_force_close_total 924
telemt_me_writer_close_signal_drop_total 51
telemt_me_draining_writers_reap_progress_total 13866
telemt_me_writer_removed_unexpected_total 318
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1036
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13168
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 918
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12942
telemt_me_writer_teardown_success_total{mode="normal"} 14204
telemt_me_writer_teardown_noop_total 13866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28070
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.012114
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28070
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 51
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 253
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 812774
telemt_user_connections_current{user="hello"} 2492
telemt_user_octets_from_client{user="hello"} 13081664524 (12.18 GB)
telemt_user_octets_to_client{user="hello"} 408203078246 (380.17 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1002
telemt_user_unique_ips_recent_window{user="hello"} 360
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 36098.6 (10h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1433086
telemt_connections_bad_total 91055
telemt_connections_current 2338
telemt_connections_me_current 2338
telemt_handshake_timeouts_total 509498
telemt_upstream_connect_attempt_total 16047
telemt_upstream_connect_success_total 16020
telemt_upstream_connect_attempts_per_request{bucket="1"} 16020
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8590
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 258
telemt_me_reconnect_attempts_total 316
telemt_me_reconnect_success_total 234
telemt_me_reader_eof_total 242
telemt_me_idle_close_by_peer_total 242
telemt_me_route_drop_no_conn_total 237112
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 725304
telemt_me_endpoint_quarantine_total 306
telemt_me_single_endpoint_shadow_rotate_total 294
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 36
telemt_desync_total 3211
telemt_desync_full_logged_total 1141
telemt_desync_suppressed_total 2070
telemt_desync_frames_bucket_total{bucket="1_2"} 592
telemt_desync_frames_bucket_total{bucket="3_10"} 1311
telemt_desync_frames_bucket_total{bucket="gt_10"} 1308
telemt_pool_swap_total 39
telemt_pool_force_close_total 892
telemt_me_writer_close_signal_drop_total 52
telemt_me_draining_writers_reap_progress_total 14343
telemt_me_writer_removed_unexpected_total 227
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 838
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13748
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 884
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13451
telemt_me_writer_teardown_success_total{mode="normal"} 14586
telemt_me_writer_teardown_noop_total 14343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28929
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.513359
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28929
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 52
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 211
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 722426
telemt_user_connections_current{user="hello"} 2338
telemt_user_octets_from_client{user="hello"} 11672928284 (10.87 GB)
telemt_user_octets_to_client{user="hello"} 375708871024 (349.91 GB)
telemt_user_unique_ips_current{user="hello"} 1011
telemt_user_unique_ips_recent_window{user="hello"} 346
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 34090.2 (9h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 273435
telemt_connections_bad_total 11147
telemt_connections_current 528
telemt_connections_me_current 528
telemt_handshake_timeouts_total 72821
telemt_upstream_connect_attempt_total 17414
telemt_upstream_connect_success_total 17413
telemt_upstream_connect_attempts_per_request{bucket="1"} 17413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7346
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10031
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 521
telemt_me_reconnect_success_total 249
telemt_me_reader_eof_total 261
telemt_me_idle_close_by_peer_total 261
telemt_me_route_drop_no_conn_total 65731
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177320
telemt_me_endpoint_quarantine_total 329
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 294
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
telemt_desync_total 1093
telemt_desync_full_logged_total 525
telemt_desync_suppressed_total 568
telemt_desync_frames_bucket_total{bucket="1_2"} 206
telemt_desync_frames_bucket_total{bucket="3_10"} 456
telemt_desync_frames_bucket_total{bucket="gt_10"} 431
telemt_pool_swap_total 37
telemt_pool_force_close_total 756
telemt_me_writer_close_signal_drop_total 46
telemt_me_draining_writers_reap_progress_total 15530
telemt_me_writer_removed_unexpected_total 245
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1065
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14711
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 756
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14774
telemt_me_writer_teardown_success_total{mode="normal"} 15776
telemt_me_writer_teardown_noop_total 15530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31306
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.977261
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31306
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 46
telemt_me_refill_failed_total 15
telemt_me_writer_restored_same_endpoint_total 218
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 177560
telemt_user_connections_current{user="hello"} 528
telemt_user_octets_from_client{user="hello"} 1943335999 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 73235059805 (68.21 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 36108.7 (10h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1158334
telemt_connections_bad_total 87436
telemt_connections_current 2776
telemt_connections_me_current 2776
telemt_handshake_timeouts_total 30785
telemt_upstream_connect_attempt_total 16532
telemt_upstream_connect_success_total 16457
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 16503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8187
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_reconnect_attempts_total 576
telemt_me_reconnect_success_total 331
telemt_me_reader_eof_total 316
telemt_me_idle_close_by_peer_total 316
telemt_me_route_drop_no_conn_total 248039
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 896983
telemt_me_endpoint_quarantine_total 304
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 290
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_desync_total 3552
telemt_desync_full_logged_total 1186
telemt_desync_suppressed_total 2366
telemt_desync_frames_bucket_total{bucket="1_2"} 950
telemt_desync_frames_bucket_total{bucket="3_10"} 1339
telemt_desync_frames_bucket_total{bucket="gt_10"} 1263
telemt_pool_swap_total 40
telemt_pool_force_close_total 906
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 69
telemt_me_draining_writers_reap_progress_total 14891
telemt_me_writer_removed_unexpected_total 317
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1034
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14181
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 905
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13985
telemt_me_writer_teardown_success_total{mode="normal"} 15215
telemt_me_writer_teardown_noop_total 14891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30106
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.613307
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30106
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 69
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 303
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 892703
telemt_user_connections_current{user="hello"} 2776
telemt_user_octets_from_client{user="hello"} 13666286812 (12.73 GB)
telemt_user_octets_to_client{user="hello"} 405066366128 (377.25 GB)
telemt_user_unique_ips_current{user="hello"} 1127
telemt_user_unique_ips_recent_window{user="hello"} 382
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 36105.4 (10h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1104226
telemt_connections_bad_total 72487
telemt_connections_current 2832
telemt_connections_me_current 2832
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 29134
telemt_upstream_connect_attempt_total 25053
telemt_upstream_connect_success_total 24877
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 25015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8617
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_reconnect_attempts_total 2456
telemt_me_reconnect_success_total 438
telemt_me_reader_eof_total 381
telemt_me_idle_close_by_peer_total 381
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 254778
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 875935
telemt_me_endpoint_quarantine_total 363
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 289
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_me_writers_warm_current 31
telemt_desync_total 3334
telemt_desync_full_logged_total 1060
telemt_desync_suppressed_total 2274
telemt_desync_frames_bucket_total{bucket="1_2"} 1001
telemt_desync_frames_bucket_total{bucket="3_10"} 1213
telemt_desync_frames_bucket_total{bucket="gt_10"} 1120
telemt_pool_swap_total 39
telemt_pool_force_close_total 874
telemt_me_writer_close_signal_drop_total 75
telemt_me_draining_writers_reap_progress_total 14087
telemt_me_writer_removed_unexpected_total 393
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1218
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13284
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 856
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13213
telemt_me_writer_teardown_success_total{mode="normal"} 14502
telemt_me_writer_teardown_noop_total 14087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28589
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.344734
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28589
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 75
telemt_me_refill_failed_total 115
telemt_me_writer_restored_same_endpoint_total 324
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 39
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 880587
telemt_user_connections_current{user="hello"} 2832
telemt_user_octets_from_client{user="hello"} 11220785383 (10.45 GB)
telemt_user_octets_to_client{user="hello"} 385997069299 (359.49 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1083
telemt_user_unique_ips_recent_window{user="hello"} 403
```