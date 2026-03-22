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

# Server Metrics 2026-03-22 19:29:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 80566.8 (22h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2999589
telemt_connections_bad_total 198379
telemt_connections_current 1237
telemt_connections_me_current 1237
telemt_handshake_timeouts_total 97825
telemt_upstream_connect_attempt_total 29496
telemt_upstream_connect_success_total 29495
telemt_upstream_connect_attempts_per_request{bucket="1"} 29495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19163
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 71
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1185
telemt_me_reconnect_success_total 499
telemt_me_reader_eof_total 504
telemt_me_idle_close_by_peer_total 504
telemt_me_route_drop_no_conn_total 2677033
telemt_me_route_drop_channel_closed_total 1063
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2542185
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 542
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 625
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 10965
telemt_desync_full_logged_total 3489
telemt_desync_suppressed_total 7476
telemt_desync_frames_bucket_total{bucket="1_2"} 2945
telemt_desync_frames_bucket_total{bucket="3_10"} 4072
telemt_desync_frames_bucket_total{bucket="gt_10"} 3948
telemt_pool_swap_total 89
telemt_pool_force_close_total 2762
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 576
telemt_me_draining_writers_reap_progress_total 26957
telemt_me_writer_removed_unexpected_total 488
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1966
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25216
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2709
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24195
telemt_me_writer_teardown_success_total{mode="normal"} 27182
telemt_me_writer_teardown_noop_total 26967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54149
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 299.806175
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54149
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 576
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 441
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 2534719
telemt_user_connections_current{user="hello"} 1237
telemt_user_octets_from_client{user="hello"} 37081654592 (34.53 GB)
telemt_user_octets_to_client{user="hello"} 663588501660 (618.01 GB)
telemt_user_unique_ips_current{user="hello"} 495
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 93932.7 (26h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3808589
telemt_connections_bad_total 339842
telemt_connections_current 1115
telemt_connections_me_current 1115
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 97239
telemt_upstream_connect_attempt_total 56968
telemt_upstream_connect_success_total 56266
telemt_upstream_connect_fail_total 620
telemt_upstream_connect_attempts_per_request{bucket="1"} 56886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 182
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 620
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6483
telemt_me_reconnect_success_total 2391
telemt_me_reader_eof_total 2328
telemt_me_idle_close_by_peer_total 2328
telemt_me_route_drop_no_conn_total 3597515
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3029678
telemt_me_endpoint_quarantine_total 729
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 723
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_me_writers_active_current 84
telemt_desync_total 12105
telemt_desync_full_logged_total 6769
telemt_desync_suppressed_total 5336
telemt_desync_frames_bucket_total{bucket="1_2"} 2778
telemt_desync_frames_bucket_total{bucket="3_10"} 4741
telemt_desync_frames_bucket_total{bucket="gt_10"} 4586
telemt_pool_swap_total 88
telemt_pool_force_close_total 2657
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 225
telemt_me_draining_writers_reap_progress_total 37253
telemt_me_writer_removed_unexpected_total 2278
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4414
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35129
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2268
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 389
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34596
telemt_me_writer_teardown_success_total{mode="normal"} 39543
telemt_me_writer_teardown_noop_total 37253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76796
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.962643
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76796
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 225
telemt_me_refill_failed_total 164
telemt_me_writer_restored_same_endpoint_total 2078
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 3040477
telemt_user_connections_current{user="hello"} 1115
telemt_user_octets_from_client{user="hello"} 39377405567 (36.67 GB)
telemt_user_octets_to_client{user="hello"} 716006384822 (666.83 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 659
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 168792.7 (46h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15869686
telemt_connections_bad_total 1530009
telemt_connections_current 1923
telemt_connections_me_current 1923
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 391340
telemt_upstream_connect_attempt_total 75186
telemt_upstream_connect_success_total 75089
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 75106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35943
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1685
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2774
telemt_me_reconnect_success_total 1430
telemt_me_reader_eof_total 1371
telemt_me_idle_close_by_peer_total 1369
telemt_me_route_drop_no_conn_total 13952865
telemt_me_route_drop_channel_closed_total 143
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12647493
telemt_me_endpoint_quarantine_total 1064
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1257
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 52146
telemt_desync_full_logged_total 16398
telemt_desync_suppressed_total 35748
telemt_desync_frames_bucket_total{bucket="1_2"} 11627
telemt_desync_frames_bucket_total{bucket="3_10"} 20312
telemt_desync_frames_bucket_total{bucket="gt_10"} 20207
telemt_pool_swap_total 182
telemt_pool_force_close_total 6145
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 999
telemt_me_draining_writers_reap_progress_total 55427
telemt_me_writer_removed_unexpected_total 1323
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4860
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51183
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5677
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 468
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49282
telemt_me_writer_teardown_success_total{mode="normal"} 56043
telemt_me_writer_teardown_noop_total 55478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111521
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 310.803983
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111521
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 999
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1232
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 12648048
telemt_user_connections_current{user="hello"} 1923
telemt_user_octets_from_client{user="hello"} 184662895185 (171.98 GB)
telemt_user_octets_to_client{user="hello"} 3345481110955 (3.04 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 765
telemt_user_unique_ips_recent_window{user="hello"} 252
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 168793.9 (46h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11464481
telemt_connections_bad_total 1137345
telemt_connections_current 1805
telemt_connections_me_current 1805
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 341175
telemt_upstream_connect_attempt_total 87654
telemt_upstream_connect_success_total 86426
telemt_upstream_connect_fail_total 843
telemt_upstream_connect_attempts_per_request{bucket="1"} 87269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35816
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3708
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 843
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4128
telemt_me_reconnect_success_total 1709
telemt_me_reader_eof_total 1578
telemt_me_idle_close_by_peer_total 1578
telemt_me_route_drop_no_conn_total 4475645
telemt_me_route_drop_channel_closed_total 491
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8544701
telemt_me_endpoint_quarantine_total 1064
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1278
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 37854
telemt_desync_full_logged_total 12758
telemt_desync_suppressed_total 25096
telemt_desync_frames_bucket_total{bucket="1_2"} 9337
telemt_desync_frames_bucket_total{bucket="3_10"} 14578
telemt_desync_frames_bucket_total{bucket="gt_10"} 13939
telemt_pool_swap_total 179
telemt_pool_force_close_total 5554
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 701
telemt_me_draining_writers_reap_progress_total 53853
telemt_me_writer_removed_unexpected_total 1616
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4980
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50335
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5051
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 503
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48299
telemt_me_writer_teardown_success_total{mode="normal"} 55315
telemt_me_writer_teardown_noop_total 53878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109193
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.641526
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109193
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 701
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1462
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 8482935
telemt_user_connections_current{user="hello"} 1805
telemt_user_octets_from_client{user="hello"} 212980291885 (198.35 GB)
telemt_user_octets_to_client{user="hello"} 3826810842806 (3.48 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 631
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 168759.5 (46h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10773990
telemt_connections_bad_total 928989
telemt_connections_current 966
telemt_connections_me_current 966
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 343328
telemt_upstream_connect_attempt_total 72752
telemt_upstream_connect_success_total 71661
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 71846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34252
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1568
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_keepalive_timeout_total 1385
telemt_me_reconnect_attempts_total 4939
telemt_me_reconnect_success_total 1997
telemt_me_reader_eof_total 1742
telemt_me_idle_close_by_peer_total 1741
telemt_me_route_drop_no_conn_total 5247446
telemt_me_route_drop_channel_closed_total 374
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8145750
telemt_me_endpoint_quarantine_total 1152
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1240
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 60
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
telemt_desync_total 37365
telemt_desync_full_logged_total 12365
telemt_desync_suppressed_total 25000
telemt_desync_frames_bucket_total{bucket="1_2"} 9450
telemt_desync_frames_bucket_total{bucket="3_10"} 14298
telemt_desync_frames_bucket_total{bucket="gt_10"} 13617
telemt_pool_swap_total 177
telemt_pool_force_close_total 5501
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 708
telemt_me_draining_writers_reap_progress_total 53980
telemt_me_writer_removed_unexpected_total 1884
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5409
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50372
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4950
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 551
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48479
telemt_me_writer_teardown_success_total{mode="normal"} 55781
telemt_me_writer_teardown_noop_total 54051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109832
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3173.765095
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109832
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 708
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 1718
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 8138084
telemt_user_connections_current{user="hello"} 966
telemt_user_octets_from_client{user="hello"} 189076643585 (176.09 GB)
telemt_user_octets_to_client{user="hello"} 3386817662245 (3.08 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 399
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 39037.9 (10h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10733111
telemt_connections_bad_total 655101
telemt_connections_current 2074
telemt_connections_me_current 2074
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 228407
telemt_upstream_connect_attempt_total 44498
telemt_upstream_connect_success_total 42262
telemt_upstream_connect_fail_total 1541
telemt_upstream_connect_attempts_per_request{bucket="1"} 43803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13251
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5955
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1541
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6469
telemt_me_reconnect_success_total 872
telemt_me_reader_eof_total 544
telemt_me_idle_close_by_peer_total 544
telemt_me_route_drop_no_conn_total 25166990
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8912663
telemt_me_endpoint_quarantine_total 241
telemt_me_single_endpoint_outage_enter_total 63
telemt_me_single_endpoint_outage_exit_total 63
telemt_me_single_endpoint_outage_reconnect_attempt_total 114
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 114
telemt_me_single_endpoint_shadow_rotate_total 304
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_desync_total 14384
telemt_desync_full_logged_total 3763
telemt_desync_suppressed_total 10621
telemt_desync_frames_bucket_total{bucket="1_2"} 2662
telemt_desync_frames_bucket_total{bucket="3_10"} 5840
telemt_desync_frames_bucket_total{bucket="gt_10"} 5882
telemt_pool_swap_total 39
telemt_pool_force_close_total 1442
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 425
telemt_me_draining_writers_reap_progress_total 11034
telemt_me_writer_removed_unexpected_total 788
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1678
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10097
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1150
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 292
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9592
telemt_me_writer_teardown_success_total{mode="normal"} 11775
telemt_me_writer_teardown_noop_total 11053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 19447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 20964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 21550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 22311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 22654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 22772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 22828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 22828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 22828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 22828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 22828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 22828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 22828
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.036900
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 22828
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 425
telemt_me_refill_failed_total 310
telemt_me_writer_restored_same_endpoint_total 582
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 8934852
telemt_user_connections_current{user="hello"} 2074
telemt_user_octets_from_client{user="hello"} 81621544811 (76.02 GB)
telemt_user_octets_to_client{user="hello"} 461890907123 (430.17 GB)
telemt_user_msgs_from_client{user="hello"} 58278
telemt_user_msgs_to_client{user="hello"} 46361
telemt_user_unique_ips_current{user="hello"} 760
telemt_user_unique_ips_recent_window{user="hello"} 271
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 168764.5 (46h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10640947
telemt_connections_bad_total 896529
telemt_connections_current 1664
telemt_connections_me_current 1664
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 233764
telemt_upstream_connect_attempt_total 102108
telemt_upstream_connect_success_total 101029
telemt_upstream_connect_fail_total 920
telemt_upstream_connect_attempts_per_request{bucket="1"} 101949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37817
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 920
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72288
telemt_me_reconnect_success_total 2799
telemt_me_reader_eof_total 2488
telemt_me_idle_close_by_peer_total 2486
telemt_me_route_drop_no_conn_total 5178914
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8405087
telemt_me_endpoint_quarantine_total 1118
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1260
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 44699
telemt_desync_full_logged_total 15222
telemt_desync_suppressed_total 29477
telemt_desync_frames_bucket_total{bucket="1_2"} 9059
telemt_desync_frames_bucket_total{bucket="3_10"} 17137
telemt_desync_frames_bucket_total{bucket="gt_10"} 18503
telemt_pool_swap_total 172
telemt_pool_force_close_total 5137
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 631
telemt_me_draining_writers_reap_progress_total 57766
telemt_me_writer_removed_unexpected_total 2526
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6161
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54157
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4412
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 725
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52629
telemt_me_writer_teardown_success_total{mode="normal"} 60318
telemt_me_writer_teardown_noop_total 57767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 115999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 117355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 117768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 118041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 118081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 118085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 118085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 118085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 118085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 118085
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.966688
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 118085
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 631
telemt_me_refill_failed_total 4281
telemt_me_writer_restored_same_endpoint_total 2351
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 8408475
telemt_user_connections_current{user="hello"} 1664
telemt_user_octets_from_client{user="hello"} 191011143605 (177.89 GB)
telemt_user_octets_to_client{user="hello"} 3193414482616 (2.90 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 688
telemt_user_unique_ips_recent_window{user="hello"} 183
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 105600.6 (29h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11203087
telemt_connections_bad_total 441105
telemt_connections_current 1256
telemt_connections_me_current 1256
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4625468
telemt_upstream_connect_attempt_total 50209
telemt_upstream_connect_success_total 49832
telemt_upstream_connect_fail_total 368
telemt_upstream_connect_attempts_per_request{bucket="1"} 50200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 191
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 368
telemt_me_reconnect_attempts_total 48461
telemt_me_reconnect_success_total 1660
telemt_me_reader_eof_total 1316
telemt_me_idle_close_by_peer_total 1315
telemt_me_route_drop_no_conn_total 4021423
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5391813
telemt_me_endpoint_quarantine_total 687
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 797
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 30250
telemt_desync_full_logged_total 10227
telemt_desync_suppressed_total 20023
telemt_desync_frames_bucket_total{bucket="1_2"} 6054
telemt_desync_frames_bucket_total{bucket="3_10"} 11956
telemt_desync_frames_bucket_total{bucket="gt_10"} 12240
telemt_pool_swap_total 111
telemt_pool_force_close_total 3403
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 345
telemt_me_draining_writers_reap_progress_total 36696
telemt_me_writer_removed_unexpected_total 1376
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3274
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34832
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2963
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 440
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33293
telemt_me_writer_teardown_success_total{mode="normal"} 38106
telemt_me_writer_teardown_noop_total 36703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74809
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.449621
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74809
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 345
telemt_me_refill_failed_total 2720
telemt_me_writer_restored_same_endpoint_total 1476
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5384738
telemt_user_connections_current{user="hello"} 1256
telemt_user_octets_from_client{user="hello"} 116311859364 (108.32 GB)
telemt_user_octets_to_client{user="hello"} 2060574086434 (1.87 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 447
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 86571.7 (24h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1291621
telemt_connections_bad_total 29127
telemt_connections_current 1057
telemt_connections_me_current 1057
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 24541
telemt_upstream_connect_attempt_total 41209
telemt_upstream_connect_success_total 41085
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 41182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21850
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 696
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1891
telemt_me_reconnect_success_total 798
telemt_me_reader_eof_total 774
telemt_me_idle_close_by_peer_total 774
telemt_me_route_drop_no_conn_total 450783
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1144722
telemt_me_endpoint_quarantine_total 725
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 711
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 6754
telemt_desync_full_logged_total 2080
telemt_desync_suppressed_total 4674
telemt_desync_frames_bucket_total{bucket="1_2"} 1512
telemt_desync_frames_bucket_total{bucket="3_10"} 2668
telemt_desync_frames_bucket_total{bucket="gt_10"} 2574
telemt_pool_swap_total 93
telemt_pool_force_close_total 2380
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 141
telemt_me_draining_writers_reap_progress_total 34250
telemt_me_writer_removed_unexpected_total 747
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2699
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32328
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2295
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31870
telemt_me_writer_teardown_success_total{mode="normal"} 35027
telemt_me_writer_teardown_noop_total 34254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69281
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.275391
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69281
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 141
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 676
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 1140906
telemt_user_connections_current{user="hello"} 1057
telemt_user_octets_from_client{user="hello"} 21784312737 (20.29 GB)
telemt_user_octets_to_client{user="hello"} 483836550303 (450.61 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 397
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 168769.1 (46h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12958084
telemt_connections_bad_total 1514113
telemt_connections_current 1707
telemt_connections_me_current 1707
telemt_handshake_timeouts_total 370366
telemt_upstream_connect_attempt_total 63626
telemt_upstream_connect_success_total 63295
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 63491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31912
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2518
telemt_me_reconnect_success_total 1311
telemt_me_reader_eof_total 1276
telemt_me_idle_close_by_peer_total 1276
telemt_me_route_drop_no_conn_total 4401812
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9803082
telemt_me_endpoint_quarantine_total 1129
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1263
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_me_writers_active_current 42
telemt_desync_total 40431
telemt_desync_full_logged_total 13184
telemt_desync_suppressed_total 27247
telemt_desync_frames_bucket_total{bucket="1_2"} 9667
telemt_desync_frames_bucket_total{bucket="3_10"} 14911
telemt_desync_frames_bucket_total{bucket="gt_10"} 15853
telemt_pool_swap_total 187
telemt_pool_force_close_total 5148
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 645
telemt_me_draining_writers_reap_progress_total 57313
telemt_me_writer_removed_unexpected_total 1228
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4697
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53882
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4974
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52165
telemt_me_writer_teardown_success_total{mode="normal"} 58579
telemt_me_writer_teardown_noop_total 57315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 113384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 115400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115894
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.201852
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115894
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 645
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 1146
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 9770899
telemt_user_connections_current{user="hello"} 1707
telemt_user_octets_from_client{user="hello"} 191380791000 (178.24 GB)
telemt_user_octets_to_client{user="hello"} 4316952503880 (3.93 TB)
telemt_user_unique_ips_current{user="hello"} 612
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 168765.5 (46h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11264882
telemt_connections_bad_total 1275401
telemt_connections_current 1377
telemt_connections_me_current 1377
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 296225
telemt_upstream_connect_attempt_total 90058
telemt_upstream_connect_success_total 89242
telemt_upstream_connect_fail_total 610
telemt_upstream_connect_attempts_per_request{bucket="1"} 89852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37415
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 610
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9726
telemt_me_reconnect_success_total 2327
telemt_me_reader_eof_total 2172
telemt_me_idle_close_by_peer_total 2171
telemt_me_seq_mismatch_total 78
telemt_me_route_drop_no_conn_total 5579504
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8706592
telemt_me_endpoint_quarantine_total 1293
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 46
telemt_me_single_endpoint_outage_exit_total 46
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1263
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_desync_total 39734
telemt_desync_full_logged_total 12835
telemt_desync_suppressed_total 26899
telemt_desync_frames_bucket_total{bucket="1_2"} 9911
telemt_desync_frames_bucket_total{bucket="3_10"} 14779
telemt_desync_frames_bucket_total{bucket="gt_10"} 15044
telemt_pool_swap_total 177
telemt_pool_force_close_total 4948
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 634
telemt_me_draining_writers_reap_progress_total 57099
telemt_me_writer_removed_unexpected_total 2206
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6030
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53348
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4477
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52151
telemt_me_writer_teardown_success_total{mode="normal"} 59378
telemt_me_writer_teardown_noop_total 57104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 113861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 116113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 116432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 116482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 116482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 116482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 116482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 116482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 116482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 116482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 116482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 116482
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.113949
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 116482
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 634
telemt_me_refill_failed_total 382
telemt_me_writer_restored_same_endpoint_total 1899
telemt_me_writer_restored_fallback_total 106
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 8712216
telemt_user_connections_current{user="hello"} 1377
telemt_user_octets_from_client{user="hello"} 154172638489 (143.58 GB)
telemt_user_octets_to_client{user="hello"} 3357876207087 (3.05 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 530
telemt_user_unique_ips_recent_window{user="hello"} 165
```