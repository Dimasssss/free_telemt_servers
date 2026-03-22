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

# Server Metrics 2026-03-22 21:32:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 87939.0 (24h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3214014
telemt_connections_bad_total 235954
telemt_connections_current 937
telemt_connections_me_current 937
telemt_handshake_timeouts_total 103047
telemt_upstream_connect_attempt_total 32229
telemt_upstream_connect_success_total 32228
telemt_upstream_connect_attempts_per_request{bucket="1"} 32228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21017
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 87
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1307
telemt_me_reconnect_success_total 539
telemt_me_reader_eof_total 551
telemt_me_idle_close_by_peer_total 551
telemt_me_route_drop_no_conn_total 2839811
telemt_me_route_drop_channel_closed_total 1139
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2704777
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 592
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 681
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_me_writers_active_current 45
telemt_desync_total 11713
telemt_desync_full_logged_total 3675
telemt_desync_suppressed_total 8038
telemt_desync_frames_bucket_total{bucket="1_2"} 3170
telemt_desync_frames_bucket_total{bucket="3_10"} 4275
telemt_desync_frames_bucket_total{bucket="gt_10"} 4268
telemt_pool_swap_total 97
telemt_pool_force_close_total 3020
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 607
telemt_me_draining_writers_reap_progress_total 29477
telemt_me_writer_removed_unexpected_total 535
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2141
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27576
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2965
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26457
telemt_me_writer_teardown_success_total{mode="normal"} 29717
telemt_me_writer_teardown_noop_total 29488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59205
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 333.125587
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59205
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 607
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 479
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 2694789
telemt_user_connections_current{user="hello"} 937
telemt_user_octets_from_client{user="hello"} 39293364464 (36.59 GB)
telemt_user_octets_to_client{user="hello"} 728937447296 (678.88 GB)
telemt_user_unique_ips_current{user="hello"} 408
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 101305.9 (28h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3904924
telemt_connections_bad_total 345978
telemt_connections_current 358
telemt_connections_me_current 358
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 99308
telemt_upstream_connect_attempt_total 60657
telemt_upstream_connect_success_total 59922
telemt_upstream_connect_fail_total 649
telemt_upstream_connect_attempts_per_request{bucket="1"} 60571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26332
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 649
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 6978
telemt_me_reconnect_success_total 2716
telemt_me_reader_eof_total 2664
telemt_me_idle_close_by_peer_total 2664
telemt_me_route_drop_no_conn_total 3625809
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3113403
telemt_me_endpoint_quarantine_total 769
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 782
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 41
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_desync_total 12636
telemt_desync_full_logged_total 7081
telemt_desync_suppressed_total 5555
telemt_desync_frames_bucket_total{bucket="1_2"} 2855
telemt_desync_frames_bucket_total{bucket="3_10"} 4962
telemt_desync_frames_bucket_total{bucket="gt_10"} 4819
telemt_pool_swap_total 95
telemt_pool_force_close_total 2879
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 238
telemt_me_draining_writers_reap_progress_total 40364
telemt_me_writer_removed_unexpected_total 2605
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4915
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38076
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2452
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 427
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37485
telemt_me_writer_teardown_success_total{mode="normal"} 42991
telemt_me_writer_teardown_noop_total 40365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83356
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.383669
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83356
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 238
telemt_me_refill_failed_total 171
telemt_me_writer_restored_same_endpoint_total 2390
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 3124078
telemt_user_connections_current{user="hello"} 358
telemt_user_octets_from_client{user="hello"} 41159703739 (38.33 GB)
telemt_user_octets_to_client{user="hello"} 764204220590 (711.72 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 176165.8 (48h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16096554
telemt_connections_bad_total 1561679
telemt_connections_current 1262
telemt_connections_me_current 1262
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 394831
telemt_upstream_connect_attempt_total 78117
telemt_upstream_connect_success_total 78017
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 78034
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37579
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1693
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2842
telemt_me_reconnect_success_total 1477
telemt_me_reader_eof_total 1422
telemt_me_idle_close_by_peer_total 1420
telemt_me_route_drop_no_conn_total 14015145
telemt_me_route_drop_channel_closed_total 144
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12831129
telemt_me_endpoint_quarantine_total 1124
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1313
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 52971
telemt_desync_full_logged_total 16731
telemt_desync_suppressed_total 36240
telemt_desync_frames_bucket_total{bucket="1_2"} 11772
telemt_desync_frames_bucket_total{bucket="3_10"} 20635
telemt_desync_frames_bucket_total{bucket="gt_10"} 20564
telemt_pool_swap_total 190
telemt_pool_force_close_total 6380
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1031
telemt_me_draining_writers_reap_progress_total 58082
telemt_me_writer_removed_unexpected_total 1372
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5068
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53665
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5910
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51702
telemt_me_writer_teardown_success_total{mode="normal"} 58733
telemt_me_writer_teardown_noop_total 58133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 113547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 116256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 116827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 116857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 116858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 116862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 116864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 116866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 116866
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 315.364971
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 116866
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1031
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1276
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 12831429
telemt_user_connections_current{user="hello"} 1262
telemt_user_octets_from_client{user="hello"} 188528073405 (175.58 GB)
telemt_user_octets_to_client{user="hello"} 3439096985919 (3.13 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 532
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 176167.1 (48h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11677797
telemt_connections_bad_total 1183496
telemt_connections_current 967
telemt_connections_me_current 967
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343501
telemt_upstream_connect_attempt_total 92636
telemt_upstream_connect_success_total 91330
telemt_upstream_connect_fail_total 860
telemt_upstream_connect_attempts_per_request{bucket="1"} 92190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37604
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3790
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 860
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4278
telemt_me_reconnect_success_total 1786
telemt_me_reader_eof_total 1645
telemt_me_idle_close_by_peer_total 1645
telemt_me_route_drop_no_conn_total 4531343
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8695310
telemt_me_endpoint_quarantine_total 1124
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1336
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 38437
telemt_desync_full_logged_total 12933
telemt_desync_suppressed_total 25504
telemt_desync_frames_bucket_total{bucket="1_2"} 9492
telemt_desync_frames_bucket_total{bucket="3_10"} 14788
telemt_desync_frames_bucket_total{bucket="gt_10"} 14157
telemt_pool_swap_total 187
telemt_pool_force_close_total 5757
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 56479
telemt_me_writer_removed_unexpected_total 1682
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5223
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52787
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5245
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50722
telemt_me_writer_teardown_success_total{mode="normal"} 58010
telemt_me_writer_teardown_noop_total 56504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 113330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 114506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 114512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 114514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 114514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 114514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 114514
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.213230
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 114514
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 134
telemt_me_writer_restored_same_endpoint_total 1519
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 8633214
telemt_user_connections_current{user="hello"} 967
telemt_user_octets_from_client{user="hello"} 216737788028 (201.85 GB)
telemt_user_octets_to_client{user="hello"} 3910301121655 (3.56 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 407
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 176132.9 (48h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10919562
telemt_connections_bad_total 948265
telemt_connections_current 719
telemt_connections_me_current 719
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344657
telemt_upstream_connect_attempt_total 76291
telemt_upstream_connect_success_total 74889
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 75086
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35955
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1813
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2286
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1419
telemt_me_reconnect_attempts_total 5389
telemt_me_reconnect_success_total 2192
telemt_me_reader_eof_total 1926
telemt_me_idle_close_by_peer_total 1925
telemt_me_route_drop_no_conn_total 5311392
telemt_me_route_drop_channel_closed_total 382
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8263303
telemt_me_endpoint_quarantine_total 1211
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1290
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 66
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
telemt_desync_total 37836
telemt_desync_full_logged_total 12535
telemt_desync_suppressed_total 25301
telemt_desync_frames_bucket_total{bucket="1_2"} 9560
telemt_desync_frames_bucket_total{bucket="3_10"} 14472
telemt_desync_frames_bucket_total{bucket="gt_10"} 13804
telemt_pool_swap_total 184
telemt_pool_force_close_total 5698
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 723
telemt_me_draining_writers_reap_progress_total 56616
telemt_me_writer_removed_unexpected_total 2078
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5817
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52801
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5133
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 565
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50918
telemt_me_writer_teardown_success_total{mode="normal"} 58618
telemt_me_writer_teardown_noop_total 56687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 113161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115305
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.214901
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115305
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 723
telemt_me_refill_failed_total 169
telemt_me_writer_restored_same_endpoint_total 1892
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 8255329
telemt_user_connections_current{user="hello"} 719
telemt_user_octets_from_client{user="hello"} 191809973373 (178.64 GB)
telemt_user_octets_to_client{user="hello"} 3434200082501 (3.12 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 330
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 46410.2 (12h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10998962
telemt_connections_bad_total 666673
telemt_connections_current 1398
telemt_connections_me_current 1398
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 245474
telemt_upstream_connect_attempt_total 50328
telemt_upstream_connect_success_total 47791
telemt_upstream_connect_fail_total 1735
telemt_upstream_connect_attempts_per_request{bucket="1"} 49526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15719
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5984
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1735
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7003
telemt_me_reconnect_success_total 1025
telemt_me_reader_eof_total 633
telemt_me_idle_close_by_peer_total 632
telemt_me_route_drop_no_conn_total 25245087
telemt_me_route_drop_channel_closed_total 56
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9133956
telemt_me_endpoint_quarantine_total 322
telemt_me_single_endpoint_outage_enter_total 76
telemt_me_single_endpoint_outage_exit_total 76
telemt_me_single_endpoint_outage_reconnect_attempt_total 135
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 135
telemt_me_single_endpoint_shadow_rotate_total 368
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 15445
telemt_desync_full_logged_total 4102
telemt_desync_suppressed_total 11343
telemt_desync_frames_bucket_total{bucket="1_2"} 2928
telemt_desync_frames_bucket_total{bucket="3_10"} 6266
telemt_desync_frames_bucket_total{bucket="gt_10"} 6251
telemt_pool_swap_total 47
telemt_pool_force_close_total 1665
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 448
telemt_me_draining_writers_reap_progress_total 13541
telemt_me_writer_removed_unexpected_total 912
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1992
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12417
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1359
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 306
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11876
telemt_me_writer_teardown_success_total{mode="normal"} 14409
telemt_me_writer_teardown_noop_total 13560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27969
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.121278
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27969
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 448
telemt_me_refill_failed_total 325
telemt_me_writer_restored_same_endpoint_total 665
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 9158678
telemt_user_connections_current{user="hello"} 1398
telemt_user_octets_from_client{user="hello"} 85014667496 (79.18 GB)
telemt_user_octets_to_client{user="hello"} 545281427774 (507.83 GB)
telemt_user_msgs_from_client{user="hello"} 65206
telemt_user_msgs_to_client{user="hello"} 53386
telemt_user_unique_ips_current{user="hello"} 549
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 176136.8 (48h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10827056
telemt_connections_bad_total 912212
telemt_connections_current 1132
telemt_connections_me_current 1132
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 237861
telemt_upstream_connect_attempt_total 105162
telemt_upstream_connect_success_total 104062
telemt_upstream_connect_fail_total 936
telemt_upstream_connect_attempts_per_request{bucket="1"} 104998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39440
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1352
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 936
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72535
telemt_me_reconnect_success_total 2868
telemt_me_reader_eof_total 2564
telemt_me_idle_close_by_peer_total 2562
telemt_me_route_drop_no_conn_total 5230572
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8557951
telemt_me_endpoint_quarantine_total 1161
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1319
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 45647
telemt_desync_full_logged_total 15590
telemt_desync_suppressed_total 30057
telemt_desync_frames_bucket_total{bucket="1_2"} 9259
telemt_desync_frames_bucket_total{bucket="3_10"} 17476
telemt_desync_frames_bucket_total{bucket="gt_10"} 18912
telemt_pool_swap_total 180
telemt_pool_force_close_total 5371
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 646
telemt_me_draining_writers_reap_progress_total 60466
telemt_me_writer_removed_unexpected_total 2599
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6371
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56723
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4641
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 730
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55095
telemt_me_writer_teardown_success_total{mode="normal"} 63094
telemt_me_writer_teardown_noop_total 60467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 121434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 122825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 123244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 123517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 123551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 123554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 123554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 123557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 123561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 123561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 123561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 123561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 123561
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.139246
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 123561
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 646
telemt_me_refill_failed_total 4291
telemt_me_writer_restored_same_endpoint_total 2414
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 8561062
telemt_user_connections_current{user="hello"} 1132
telemt_user_octets_from_client{user="hello"} 193345442393 (180.07 GB)
telemt_user_octets_to_client{user="hello"} 3263709173712 (2.97 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 510
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 112973.1 (31h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11450137
telemt_connections_bad_total 458200
telemt_connections_current 895
telemt_connections_me_current 895
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4691806
telemt_upstream_connect_attempt_total 53357
telemt_upstream_connect_success_total 52962
telemt_upstream_connect_fail_total 385
telemt_upstream_connect_attempts_per_request{bucket="1"} 53347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23884
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 385
telemt_me_reconnect_attempts_total 48658
telemt_me_reconnect_success_total 1699
telemt_me_reader_eof_total 1360
telemt_me_idle_close_by_peer_total 1359
telemt_me_route_drop_no_conn_total 4063516
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5523155
telemt_me_endpoint_quarantine_total 735
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 855
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31016
telemt_desync_full_logged_total 10546
telemt_desync_suppressed_total 20470
telemt_desync_frames_bucket_total{bucket="1_2"} 6160
telemt_desync_frames_bucket_total{bucket="3_10"} 12265
telemt_desync_frames_bucket_total{bucket="gt_10"} 12591
telemt_pool_swap_total 119
telemt_pool_force_close_total 3619
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 361
telemt_me_draining_writers_reap_progress_total 39560
telemt_me_writer_removed_unexpected_total 1418
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3430
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37584
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3178
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35941
telemt_me_writer_teardown_success_total{mode="normal"} 41014
telemt_me_writer_teardown_noop_total 39567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80581
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.618468
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80581
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 361
telemt_me_refill_failed_total 2729
telemt_me_writer_restored_same_endpoint_total 1509
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5515832
telemt_user_connections_current{user="hello"} 895
telemt_user_octets_from_client{user="hello"} 118187615152 (110.07 GB)
telemt_user_octets_to_client{user="hello"} 2116875250234 (1.93 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 388
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 93943.8 (26h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1422159
telemt_connections_bad_total 35243
telemt_connections_current 753
telemt_connections_me_current 753
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 26836
telemt_upstream_connect_attempt_total 44028
telemt_upstream_connect_success_total 43890
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 44000
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23342
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 754
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2050
telemt_me_reconnect_success_total 835
telemt_me_reader_eof_total 817
telemt_me_idle_close_by_peer_total 817
telemt_me_route_drop_no_conn_total 494255
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1262159
telemt_me_endpoint_quarantine_total 763
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 774
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 7842
telemt_desync_full_logged_total 2391
telemt_desync_suppressed_total 5451
telemt_desync_frames_bucket_total{bucket="1_2"} 1880
telemt_desync_frames_bucket_total{bucket="3_10"} 3024
telemt_desync_frames_bucket_total{bucket="gt_10"} 2938
telemt_pool_swap_total 101
telemt_pool_force_close_total 2630
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 148
telemt_me_draining_writers_reap_progress_total 36792
telemt_me_writer_removed_unexpected_total 787
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2912
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34700
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2542
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34162
telemt_me_writer_teardown_success_total{mode="normal"} 37612
telemt_me_writer_teardown_noop_total 36796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74408
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.886400
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74408
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 148
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 708
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 1258122
telemt_user_connections_current{user="hello"} 753
telemt_user_octets_from_client{user="hello"} 24472861409 (22.79 GB)
telemt_user_octets_to_client{user="hello"} 532919103607 (496.32 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 176141.9 (48h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13161578
telemt_connections_bad_total 1558781
telemt_connections_current 1031
telemt_connections_me_current 1031
telemt_handshake_timeouts_total 377793
telemt_upstream_connect_attempt_total 67016
telemt_upstream_connect_success_total 66680
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 66880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33541
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2625
telemt_me_reconnect_success_total 1366
telemt_me_reader_eof_total 1334
telemt_me_idle_close_by_peer_total 1334
telemt_me_route_drop_no_conn_total 4461133
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9947540
telemt_me_endpoint_quarantine_total 1197
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1321
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 41494
telemt_desync_full_logged_total 13531
telemt_desync_suppressed_total 27963
telemt_desync_frames_bucket_total{bucket="1_2"} 9977
telemt_desync_frames_bucket_total{bucket="3_10"} 15279
telemt_desync_frames_bucket_total{bucket="gt_10"} 16238
telemt_pool_swap_total 195
telemt_pool_force_close_total 5337
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 657
telemt_me_draining_writers_reap_progress_total 60449
telemt_me_writer_removed_unexpected_total 1283
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4899
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56874
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5163
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55112
telemt_me_writer_teardown_success_total{mode="normal"} 61773
telemt_me_writer_teardown_noop_total 60451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 119666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 121332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 121715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 122091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 122211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 122224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 122224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 122224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 122224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 122224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 122224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 122224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 122224
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.546026
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 122224
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 657
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 1194
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 9914415
telemt_user_connections_current{user="hello"} 1031
telemt_user_octets_from_client{user="hello"} 193663923400 (180.36 GB)
telemt_user_octets_to_client{user="hello"} 4386922341684 (3.99 TB)
telemt_user_unique_ips_current{user="hello"} 398
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 176138.3 (48h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11443593
telemt_connections_bad_total 1299403
telemt_connections_current 969
telemt_connections_me_current 969
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 301715
telemt_upstream_connect_attempt_total 93460
telemt_upstream_connect_success_total 92623
telemt_upstream_connect_fail_total 630
telemt_upstream_connect_attempts_per_request{bucket="1"} 93253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39070
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 630
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9985
telemt_me_reconnect_success_total 2412
telemt_me_reader_eof_total 2253
telemt_me_idle_close_by_peer_total 2252
telemt_me_seq_mismatch_total 82
telemt_me_route_drop_no_conn_total 5620509
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8849007
telemt_me_endpoint_quarantine_total 1350
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 1321
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
telemt_me_writers_active_current 47
telemt_desync_total 41043
telemt_desync_full_logged_total 13151
telemt_desync_suppressed_total 27892
telemt_desync_frames_bucket_total{bucket="1_2"} 10524
telemt_desync_frames_bucket_total{bucket="3_10"} 15116
telemt_desync_frames_bucket_total{bucket="gt_10"} 15403
telemt_pool_swap_total 185
telemt_pool_force_close_total 5133
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 644
telemt_me_draining_writers_reap_progress_total 60178
telemt_me_writer_removed_unexpected_total 2286
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6235
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56307
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4662
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55045
telemt_me_writer_teardown_success_total{mode="normal"} 62542
telemt_me_writer_teardown_noop_total 60183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 120067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 121820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 122356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 122675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 122725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 122725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 122725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 122725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 122725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 122725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 122725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 122725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 122725
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.266219
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 122725
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 644
telemt_me_refill_failed_total 391
telemt_me_writer_restored_same_endpoint_total 1961
telemt_me_writer_restored_fallback_total 114
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 211
telemt_user_connections_total{user="hello"} 8854471
telemt_user_connections_current{user="hello"} 969
telemt_user_octets_from_client{user="hello"} 156459797293 (145.71 GB)
telemt_user_octets_to_client{user="hello"} 3443751431543 (3.13 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 392
telemt_user_unique_ips_recent_window{user="hello"} 105
```