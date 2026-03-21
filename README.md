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

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
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
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
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

# Server Metrics 2026-03-21 23:27:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 8464.6 (2h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138609
telemt_connections_bad_total 10859
telemt_connections_current 630
telemt_connections_me_current 630
telemt_handshake_timeouts_total 6761
telemt_upstream_connect_attempt_total 3394
telemt_upstream_connect_success_total 3393
telemt_upstream_connect_attempts_per_request{bucket="1"} 3393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2129
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 86
telemt_me_reconnect_success_total 52
telemt_me_reader_eof_total 52
telemt_me_idle_close_by_peer_total 52
telemt_me_route_drop_no_conn_total 28975
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112683
telemt_me_endpoint_quarantine_total 57
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 663
telemt_desync_full_logged_total 210
telemt_desync_suppressed_total 453
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 323
telemt_pool_swap_total 9
telemt_pool_force_close_total 251
telemt_me_writer_close_signal_drop_total 18
telemt_me_draining_writers_reap_progress_total 3009
telemt_me_writer_removed_unexpected_total 49
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 220
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2825
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 247
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2758
telemt_me_writer_teardown_success_total{mode="normal"} 3045
telemt_me_writer_teardown_noop_total 3009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 6009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 6042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 6052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 6054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 6054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 6054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 6054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 6054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 6054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 6054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 6054
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.695097
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 6054
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 18
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 112557
telemt_user_connections_current{user="hello"} 630
telemt_user_octets_from_client{user="hello"} 1333738856 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 42496761828 (39.58 GB)
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 21830.9 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 650087
telemt_connections_bad_total 31853
telemt_connections_current 349
telemt_connections_me_current 349
telemt_handshake_timeouts_total 24862
telemt_upstream_connect_attempt_total 9132
telemt_upstream_connect_success_total 8970
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 9115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4903
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_reconnect_attempts_total 814
telemt_me_reconnect_success_total 273
telemt_me_reader_eof_total 235
telemt_me_idle_close_by_peer_total 235
telemt_me_route_drop_no_conn_total 322239
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 529271
telemt_me_endpoint_quarantine_total 192
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 176
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 2341
telemt_desync_full_logged_total 1337
telemt_desync_suppressed_total 1004
telemt_desync_frames_bucket_total{bucket="1_2"} 494
telemt_desync_frames_bucket_total{bucket="3_10"} 884
telemt_desync_frames_bucket_total{bucket="gt_10"} 963
telemt_pool_swap_total 24
telemt_pool_force_close_total 680
telemt_me_writer_close_signal_drop_total 54
telemt_me_draining_writers_reap_progress_total 8042
telemt_me_writer_removed_unexpected_total 220
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 703
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7561
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 673
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7362
telemt_me_writer_teardown_success_total{mode="normal"} 8264
telemt_me_writer_teardown_noop_total 8042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 15846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 16114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 16200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 16292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 16304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 16306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 16306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 16306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 16306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 16306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 16306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 16306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 16306
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.360326
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 16306
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 54
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 188
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 528546
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 8920153104 (8.31 GB)
telemt_user_octets_to_client{user="hello"} 183412289768 (170.82 GB)
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 239
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 96690.7 (26h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7382036
telemt_connections_bad_total 574856
telemt_connections_current 1729
telemt_connections_me_current 1729
telemt_handshake_timeouts_total 238495
telemt_upstream_connect_attempt_total 34999
telemt_upstream_connect_success_total 34930
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 34937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18976
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1477
telemt_me_reconnect_success_total 731
telemt_me_reader_eof_total 739
telemt_me_idle_close_by_peer_total 739
telemt_me_route_drop_no_conn_total 4489356
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6031111
telemt_me_endpoint_quarantine_total 611
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 719
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 25545
telemt_desync_full_logged_total 8436
telemt_desync_suppressed_total 17109
telemt_desync_frames_bucket_total{bucket="1_2"} 5477
telemt_desync_frames_bucket_total{bucket="3_10"} 9977
telemt_desync_frames_bucket_total{bucket="gt_10"} 10091
telemt_pool_swap_total 104
telemt_pool_force_close_total 3504
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 566
telemt_me_draining_writers_reap_progress_total 31902
telemt_me_writer_removed_unexpected_total 711
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2706
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29484
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3265
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28398
telemt_me_writer_teardown_success_total{mode="normal"} 32190
telemt_me_writer_teardown_noop_total 31946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64136
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 152.400131
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64136
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 566
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 651
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 6023596
telemt_user_connections_current{user="hello"} 1729
telemt_user_octets_from_client{user="hello"} 103471244496 (96.37 GB)
telemt_user_octets_to_client{user="hello"} 1969156591144 (1.79 TB)
telemt_user_unique_ips_current{user="hello"} 823
telemt_user_unique_ips_recent_window{user="hello"} 282
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 96692.0 (26h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6068741
telemt_connections_bad_total 576899
telemt_connections_current 1552
telemt_connections_me_current 1552
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 200246
telemt_upstream_connect_attempt_total 38916
telemt_upstream_connect_success_total 38578
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 38756
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18652
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 543
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1797
telemt_me_reconnect_success_total 761
telemt_me_reader_eof_total 738
telemt_me_idle_close_by_peer_total 738
telemt_me_route_drop_no_conn_total 2152797
telemt_me_route_drop_channel_closed_total 250
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4546612
telemt_me_endpoint_quarantine_total 593
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 739
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 21866
telemt_desync_full_logged_total 7365
telemt_desync_suppressed_total 14501
telemt_desync_frames_bucket_total{bucket="1_2"} 5268
telemt_desync_frames_bucket_total{bucket="3_10"} 8488
telemt_desync_frames_bucket_total{bucket="gt_10"} 8110
telemt_pool_swap_total 106
telemt_pool_force_close_total 3195
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 343
telemt_me_draining_writers_reap_progress_total 30433
telemt_me_writer_removed_unexpected_total 713
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2602
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28478
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2996
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27238
telemt_me_writer_teardown_success_total{mode="normal"} 31080
telemt_me_writer_teardown_noop_total 30439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61519
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.840435
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61519
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 343
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 657
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 4492597
telemt_user_connections_current{user="hello"} 1552
telemt_user_octets_from_client{user="hello"} 137568793873 (128.12 GB)
telemt_user_octets_to_client{user="hello"} 2099595107071 (1.91 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 774
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 96656.1 (26h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5987412
telemt_connections_bad_total 538739
telemt_connections_current 1543
telemt_connections_me_current 1543
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 190716
telemt_upstream_connect_attempt_total 45339
telemt_upstream_connect_success_total 45032
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 45167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20072
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 357
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1046
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1800
telemt_me_reconnect_success_total 814
telemt_me_reader_eof_total 762
telemt_me_idle_close_by_peer_total 762
telemt_me_route_drop_no_conn_total 2093595
telemt_me_route_drop_channel_closed_total 109
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4473404
telemt_me_endpoint_quarantine_total 654
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 723
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
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
telemt_desync_total 21755
telemt_desync_full_logged_total 7227
telemt_desync_suppressed_total 14528
telemt_desync_frames_bucket_total{bucket="1_2"} 5334
telemt_desync_frames_bucket_total{bucket="3_10"} 8316
telemt_desync_frames_bucket_total{bucket="gt_10"} 8105
telemt_pool_swap_total 104
telemt_pool_force_close_total 3069
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 366
telemt_me_draining_writers_reap_progress_total 31883
telemt_me_writer_removed_unexpected_total 729
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2684
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29935
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2854
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28814
telemt_me_writer_teardown_success_total{mode="normal"} 32619
telemt_me_writer_teardown_noop_total 31894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64513
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.308508
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64513
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 366
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 705
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 4474851
telemt_user_connections_current{user="hello"} 1543
telemt_user_octets_from_client{user="hello"} 131008612423 (122.01 GB)
telemt_user_octets_to_client{user="hello"} 2049702855275 (1.86 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 727
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 96695.5 (26h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19878443
telemt_connections_bad_total 1442469
telemt_connections_current 2162
telemt_connections_me_current 2162
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 572323
telemt_upstream_connect_attempt_total 188530
telemt_upstream_connect_success_total 170943
telemt_upstream_connect_fail_total 16024
telemt_upstream_connect_attempts_per_request{bucket="1"} 186967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39664
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8880
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16024
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64273
telemt_me_reconnect_success_total 2133
telemt_me_reader_eof_total 1328
telemt_me_idle_close_by_peer_total 1327
telemt_me_route_drop_no_conn_total 39435586
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16208980
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 743
telemt_me_single_endpoint_outage_enter_total 122
telemt_me_single_endpoint_outage_exit_total 122
telemt_me_single_endpoint_outage_reconnect_attempt_total 258
telemt_me_single_endpoint_outage_reconnect_success_total 61
telemt_me_single_endpoint_quarantine_bypass_total 258
telemt_me_single_endpoint_shadow_rotate_total 754
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 31158
telemt_desync_full_logged_total 9253
telemt_desync_suppressed_total 21905
telemt_desync_frames_bucket_total{bucket="1_2"} 6808
telemt_desync_frames_bucket_total{bucket="3_10"} 13801
telemt_desync_frames_bucket_total{bucket="gt_10"} 10549
telemt_pool_swap_total 99
telemt_pool_force_close_total 3287
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 749
telemt_me_draining_writers_reap_progress_total 30014
telemt_me_writer_removed_unexpected_total 1989
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4151
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27586
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2771
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 516
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26727
telemt_me_writer_teardown_success_total{mode="normal"} 31737
telemt_me_writer_teardown_noop_total 30040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61777
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 210.123349
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61777
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 749
telemt_me_refill_failed_total 3787
telemt_me_writer_restored_same_endpoint_total 1475
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14672
telemt_me_writer_removed_unexpected_minus_restored_total 493
telemt_user_connections_total{user="hello"} 16336965
telemt_user_connections_current{user="hello"} 2162
telemt_user_octets_from_client{user="hello"} 180814741368 (168.40 GB)
telemt_user_octets_to_client{user="hello"} 1095706602910 (1020.46 GB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 1022
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 96663.0 (26h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5784661
telemt_connections_bad_total 537695
telemt_connections_current 1615
telemt_connections_me_current 1615
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 119169
telemt_upstream_connect_attempt_total 53395
telemt_upstream_connect_success_total 52782
telemt_upstream_connect_fail_total 523
telemt_upstream_connect_attempts_per_request{bucket="1"} 53305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20932
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 338
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 523
telemt_me_reconnect_attempts_total 68079
telemt_me_reconnect_success_total 1675
telemt_me_reader_eof_total 1453
telemt_me_idle_close_by_peer_total 1452
telemt_me_route_drop_no_conn_total 2349446
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4514338
telemt_me_endpoint_quarantine_total 637
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 726
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 22820
telemt_desync_full_logged_total 7969
telemt_desync_suppressed_total 14851
telemt_desync_frames_bucket_total{bucket="1_2"} 4333
telemt_desync_frames_bucket_total{bucket="3_10"} 8837
telemt_desync_frames_bucket_total{bucket="gt_10"} 9650
telemt_pool_swap_total 99
telemt_pool_force_close_total 2921
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 372
telemt_me_draining_writers_reap_progress_total 33172
telemt_me_writer_removed_unexpected_total 1500
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3562
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31132
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2520
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30251
telemt_me_writer_teardown_success_total{mode="normal"} 34694
telemt_me_writer_teardown_noop_total 33173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67867
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.872652
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67867
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 372
telemt_me_refill_failed_total 4118
telemt_me_writer_restored_same_endpoint_total 1419
telemt_me_writer_restored_fallback_total 26
telemt_me_no_writer_failfast_total 223
telemt_me_async_recovery_trigger_total 7257
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 4507454
telemt_user_connections_current{user="hello"} 1615
telemt_user_octets_from_client{user="hello"} 121168311432 (112.85 GB)
telemt_user_octets_to_client{user="hello"} 1837522156674 (1.67 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 740
telemt_user_unique_ips_recent_window{user="hello"} 349
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 33498.9 (9h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3658567
telemt_connections_bad_total 129464
telemt_connections_current 1127
telemt_connections_me_current 1127
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1530314
telemt_upstream_connect_attempt_total 21572
telemt_upstream_connect_success_total 21436
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 21565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6821
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_reconnect_attempts_total 45578
telemt_me_reconnect_success_total 878
telemt_me_reader_eof_total 549
telemt_me_idle_close_by_peer_total 549
telemt_me_route_drop_no_conn_total 988694
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1761623
telemt_me_endpoint_quarantine_total 233
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 252
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 9797
telemt_desync_full_logged_total 3338
telemt_desync_suppressed_total 6459
telemt_desync_frames_bucket_total{bucket="1_2"} 1729
telemt_desync_frames_bucket_total{bucket="3_10"} 3743
telemt_desync_frames_bucket_total{bucket="gt_10"} 4325
telemt_pool_swap_total 36
telemt_pool_force_close_total 1202
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 117
telemt_me_draining_writers_reap_progress_total 11132
telemt_me_writer_removed_unexpected_total 631
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1262
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10519
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 996
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9930
telemt_me_writer_teardown_success_total{mode="normal"} 11781
telemt_me_writer_teardown_noop_total 11134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 22473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 22728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 22809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 22915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 22915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 22915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 22915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 22915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 22915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 22915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 22915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 22915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 22915
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.996694
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 22915
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 117
telemt_me_refill_failed_total 2597
telemt_me_writer_restored_same_endpoint_total 789
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1765366
telemt_user_connections_current{user="hello"} 1127
telemt_user_octets_from_client{user="hello"} 51702112464 (48.15 GB)
telemt_user_octets_to_client{user="hello"} 758150117326 (706.08 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 535
telemt_user_unique_ips_recent_window{user="hello"} 510
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 14469.9 (4h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151126
telemt_connections_bad_total 1368
telemt_connections_current 329
telemt_connections_me_current 329
telemt_handshake_timeouts_total 3560
telemt_upstream_connect_attempt_total 6505
telemt_upstream_connect_success_total 6488
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 6504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2755
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 130
telemt_me_reconnect_success_total 84
telemt_me_reader_eof_total 85
telemt_me_idle_close_by_peer_total 85
telemt_me_route_drop_no_conn_total 43045
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132158
telemt_me_endpoint_quarantine_total 119
telemt_me_single_endpoint_shadow_rotate_total 127
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 27
telemt_desync_total 947
telemt_desync_full_logged_total 236
telemt_desync_suppressed_total 711
telemt_desync_frames_bucket_total{bucket="1_2"} 383
telemt_desync_frames_bucket_total{bucket="3_10"} 344
telemt_desync_frames_bucket_total{bucket="gt_10"} 220
telemt_pool_swap_total 15
telemt_pool_force_close_total 361
telemt_me_writer_close_signal_drop_total 18
telemt_me_draining_writers_reap_progress_total 5775
telemt_me_writer_removed_unexpected_total 83
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 383
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5477
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 359
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5414
telemt_me_writer_teardown_success_total{mode="normal"} 5860
telemt_me_writer_teardown_noop_total 5775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 11503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 11607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 11635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 11635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 11635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 11635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 11635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 11635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 11635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 11635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 11635
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.730037
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 11635
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 18
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 78
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 131970
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 2462228600 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 78427243288 (73.04 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 96667.4 (26h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6943086
telemt_connections_bad_total 706985
telemt_connections_current 1762
telemt_connections_me_current 1762
telemt_handshake_timeouts_total 197531
telemt_upstream_connect_attempt_total 36847
telemt_upstream_connect_success_total 36702
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 36810
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18422
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_reconnect_attempts_total 1483
telemt_me_reconnect_success_total 771
telemt_me_reader_eof_total 749
telemt_me_idle_close_by_peer_total 749
telemt_me_route_drop_no_conn_total 2088265
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5270380
telemt_me_endpoint_quarantine_total 654
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 741
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 20279
telemt_desync_full_logged_total 6779
telemt_desync_suppressed_total 13500
telemt_desync_frames_bucket_total{bucket="1_2"} 4938
telemt_desync_frames_bucket_total{bucket="3_10"} 7362
telemt_desync_frames_bucket_total{bucket="gt_10"} 7979
telemt_pool_swap_total 107
telemt_pool_force_close_total 2924
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 363
telemt_me_draining_writers_reap_progress_total 33144
telemt_me_writer_removed_unexpected_total 725
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2688
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31195
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2836
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30220
telemt_me_writer_teardown_success_total{mode="normal"} 33883
telemt_me_writer_teardown_noop_total 33146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67029
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.510904
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67029
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 363
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 687
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 5245650
telemt_user_connections_current{user="hello"} 1762
telemt_user_octets_from_client{user="hello"} 105281016012 (98.05 GB)
telemt_user_octets_to_client{user="hello"} 2463893400204 (2.24 TB)
telemt_user_unique_ips_current{user="hello"} 779
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 96664.0 (26h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5960216
telemt_connections_bad_total 581481
telemt_connections_current 1894
telemt_connections_me_current 1894
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 166150
telemt_upstream_connect_attempt_total 52909
telemt_upstream_connect_success_total 52510
telemt_upstream_connect_fail_total 340
telemt_upstream_connect_attempts_per_request{bucket="1"} 52850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20218
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 340
telemt_me_reconnect_attempts_total 5283
telemt_me_reconnect_success_total 1074
telemt_me_reader_eof_total 950
telemt_me_idle_close_by_peer_total 950
telemt_me_seq_mismatch_total 41
telemt_me_route_drop_no_conn_total 2141472
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4640588
telemt_me_endpoint_quarantine_total 759
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 735
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 18994
telemt_desync_full_logged_total 6409
telemt_desync_suppressed_total 12585
telemt_desync_frames_bucket_total{bucket="1_2"} 4721
telemt_desync_frames_bucket_total{bucket="3_10"} 6918
telemt_desync_frames_bucket_total{bucket="gt_10"} 7355
telemt_pool_swap_total 105
telemt_pool_force_close_total 2883
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 364
telemt_me_draining_writers_reap_progress_total 31994
telemt_me_writer_removed_unexpected_total 963
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3170
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29830
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2660
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29111
telemt_me_writer_teardown_success_total{mode="normal"} 33000
telemt_me_writer_teardown_noop_total 31998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64998
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.725689
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64998
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 364
telemt_me_refill_failed_total 243
telemt_me_writer_restored_same_endpoint_total 832
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 4643932
telemt_user_connections_current{user="hello"} 1894
telemt_user_octets_from_client{user="hello"} 88333795401 (82.27 GB)
telemt_user_octets_to_client{user="hello"} 1997230677172 (1.82 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 783
telemt_user_unique_ips_recent_window{user="hello"} 174
```