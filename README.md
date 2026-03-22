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

# Server Metrics 2026-03-22 20:40:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 84872.4 (23h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3139321
telemt_connections_bad_total 219381
telemt_connections_current 939
telemt_connections_me_current 939
telemt_handshake_timeouts_total 100171
telemt_upstream_connect_attempt_total 31082
telemt_upstream_connect_success_total 31081
telemt_upstream_connect_attempts_per_request{bucket="1"} 31081
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20264
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 84
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1270
telemt_me_reconnect_success_total 519
telemt_me_reader_eof_total 529
telemt_me_idle_close_by_peer_total 529
telemt_me_route_drop_no_conn_total 2805657
telemt_me_route_drop_channel_closed_total 1116
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2651891
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 576
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 657
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 11460
telemt_desync_full_logged_total 3593
telemt_desync_suppressed_total 7867
telemt_desync_frames_bucket_total{bucket="1_2"} 3088
telemt_desync_frames_bucket_total{bucket="3_10"} 4207
telemt_desync_frames_bucket_total{bucket="gt_10"} 4165
telemt_pool_swap_total 94
telemt_pool_force_close_total 2936
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 601
telemt_me_draining_writers_reap_progress_total 28426
telemt_me_writer_removed_unexpected_total 513
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2076
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26567
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2882
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 54
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25490
telemt_me_writer_teardown_success_total{mode="normal"} 28643
telemt_me_writer_teardown_noop_total 28437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57080
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 328.727231
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57080
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 601
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 460
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 2643005
telemt_user_connections_current{user="hello"} 939
telemt_user_octets_from_client{user="hello"} 38681640884 (36.03 GB)
telemt_user_octets_to_client{user="hello"} 703179184628 (654.89 GB)
telemt_user_unique_ips_current{user="hello"} 406
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 98238.6 (27h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3868163
telemt_connections_bad_total 341680
telemt_connections_current 640
telemt_connections_me_current 640
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 98461
telemt_upstream_connect_attempt_total 59300
telemt_upstream_connect_success_total 58573
telemt_upstream_connect_fail_total 642
telemt_upstream_connect_attempts_per_request{bucket="1"} 59215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25627
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 642
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 6848
telemt_me_reconnect_success_total 2674
telemt_me_reader_eof_total 2623
telemt_me_idle_close_by_peer_total 2623
telemt_me_route_drop_no_conn_total 3616072
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3083381
telemt_me_endpoint_quarantine_total 752
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 756
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
telemt_me_writers_active_current 43
telemt_desync_total 12424
telemt_desync_full_logged_total 6954
telemt_desync_suppressed_total 5470
telemt_desync_frames_bucket_total{bucket="1_2"} 2828
telemt_desync_frames_bucket_total{bucket="3_10"} 4867
telemt_desync_frames_bucket_total{bucket="gt_10"} 4729
telemt_pool_swap_total 92
telemt_pool_force_close_total 2774
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 233
telemt_me_draining_writers_reap_progress_total 39143
telemt_me_writer_removed_unexpected_total 2566
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4797
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36932
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2347
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 427
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36369
telemt_me_writer_teardown_success_total{mode="normal"} 41729
telemt_me_writer_teardown_noop_total 39144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80873
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.265202
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80873
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 233
telemt_me_refill_failed_total 166
telemt_me_writer_restored_same_endpoint_total 2357
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 3094112
telemt_user_connections_current{user="hello"} 640
telemt_user_octets_from_client{user="hello"} 40610926651 (37.82 GB)
telemt_user_octets_to_client{user="hello"} 746941513170 (695.64 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 375
telemt_user_unique_ips_recent_window{user="hello"} 284
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 173098.6 (48h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16023870
telemt_connections_bad_total 1553767
telemt_connections_current 1362
telemt_connections_me_current 1362
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 393783
telemt_upstream_connect_attempt_total 76806
telemt_upstream_connect_success_total 76706
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 76723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36849
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1689
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2817
telemt_me_reconnect_success_total 1454
telemt_me_reader_eof_total 1398
telemt_me_idle_close_by_peer_total 1396
telemt_me_route_drop_no_conn_total 13996565
telemt_me_route_drop_channel_closed_total 144
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12769353
telemt_me_endpoint_quarantine_total 1097
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1292
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
telemt_desync_total 52713
telemt_desync_full_logged_total 16608
telemt_desync_suppressed_total 36105
telemt_desync_frames_bucket_total{bucket="1_2"} 11739
telemt_desync_frames_bucket_total{bucket="3_10"} 20526
telemt_desync_frames_bucket_total{bucket="gt_10"} 20448
telemt_pool_swap_total 187
telemt_pool_force_close_total 6303
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1020
telemt_me_draining_writers_reap_progress_total 56904
telemt_me_writer_removed_unexpected_total 1349
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4984
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52547
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5833
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50601
telemt_me_writer_teardown_success_total{mode="normal"} 57531
telemt_me_writer_teardown_noop_total 56955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 114477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 114478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 114482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 114484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 114486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 114486
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 313.761948
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 114486
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1020
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1254
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 12769755
telemt_user_connections_current{user="hello"} 1362
telemt_user_octets_from_client{user="hello"} 187073432777 (174.23 GB)
telemt_user_octets_to_client{user="hello"} 3408465800255 (3.10 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 598
telemt_user_unique_ips_recent_window{user="hello"} 255
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 173099.9 (48h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11603516
telemt_connections_bad_total 1166161
telemt_connections_current 841
telemt_connections_me_current 841
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343311
telemt_upstream_connect_attempt_total 91265
telemt_upstream_connect_success_total 89983
telemt_upstream_connect_fail_total 857
telemt_upstream_connect_attempts_per_request{bucket="1"} 90840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36886
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3770
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 857
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4261
telemt_me_reconnect_success_total 1771
telemt_me_reader_eof_total 1628
telemt_me_idle_close_by_peer_total 1628
telemt_me_route_drop_no_conn_total 4513702
telemt_me_route_drop_channel_closed_total 496
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8642040
telemt_me_endpoint_quarantine_total 1101
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1313
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
telemt_desync_total 38295
telemt_desync_full_logged_total 12881
telemt_desync_suppressed_total 25414
telemt_desync_frames_bucket_total{bucket="1_2"} 9447
telemt_desync_frames_bucket_total{bucket="3_10"} 14732
telemt_desync_frames_bucket_total{bucket="gt_10"} 14116
telemt_pool_swap_total 184
telemt_pool_force_close_total 5673
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 704
telemt_me_draining_writers_reap_progress_total 55269
telemt_me_writer_removed_unexpected_total 1667
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5140
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51643
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5161
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49596
telemt_me_writer_teardown_success_total{mode="normal"} 56783
telemt_me_writer_teardown_noop_total 55294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112077
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.765022
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112077
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 704
telemt_me_refill_failed_total 134
telemt_me_writer_restored_same_endpoint_total 1504
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 8582015
telemt_user_connections_current{user="hello"} 841
telemt_user_octets_from_client{user="hello"} 215664412508 (200.85 GB)
telemt_user_octets_to_client{user="hello"} 3878714782771 (3.53 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 320
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 173064.2 (48h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10871932
telemt_connections_bad_total 941732
telemt_connections_current 1272
telemt_connections_me_current 1272
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344321
telemt_upstream_connect_attempt_total 74606
telemt_upstream_connect_success_total 73373
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 73564
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35145
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1680
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2231
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1391
telemt_me_reconnect_attempts_total 5163
telemt_me_reconnect_success_total 2105
telemt_me_reader_eof_total 1842
telemt_me_idle_close_by_peer_total 1841
telemt_me_route_drop_no_conn_total 5289658
telemt_me_route_drop_channel_closed_total 379
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8225505
telemt_me_endpoint_quarantine_total 1176
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1267
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 65
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
telemt_me_writers_active_current 82
telemt_me_writers_warm_current 4
telemt_desync_total 37665
telemt_desync_full_logged_total 12463
telemt_desync_suppressed_total 25202
telemt_desync_frames_bucket_total{bucket="1_2"} 9527
telemt_desync_frames_bucket_total{bucket="3_10"} 14391
telemt_desync_frames_bucket_total{bucket="gt_10"} 13747
telemt_pool_swap_total 181
telemt_pool_force_close_total 5609
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 716
telemt_me_draining_writers_reap_progress_total 55339
telemt_me_writer_removed_unexpected_total 1987
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5636
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51612
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5058
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 551
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49730
telemt_me_writer_teardown_success_total{mode="normal"} 57248
telemt_me_writer_teardown_noop_total 55410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112658
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.037151
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112658
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 716
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 1813
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 8217620
telemt_user_connections_current{user="hello"} 1272
telemt_user_octets_from_client{user="hello"} 191420959889 (178.27 GB)
telemt_user_octets_to_client{user="hello"} 3418949799609 (3.11 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 527
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 43344.0 (12h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10898718
telemt_connections_bad_total 660907
telemt_connections_current 1601
telemt_connections_me_current 1601
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 238516
telemt_upstream_connect_attempt_total 46182
telemt_upstream_connect_success_total 43877
telemt_upstream_connect_fail_total 1565
telemt_upstream_connect_attempts_per_request{bucket="1"} 45442
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14114
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5967
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1565
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6745
telemt_me_reconnect_success_total 944
telemt_me_reader_eof_total 601
telemt_me_idle_close_by_peer_total 601
telemt_me_route_drop_no_conn_total 25223804
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9053452
telemt_me_endpoint_quarantine_total 292
telemt_me_single_endpoint_outage_enter_total 67
telemt_me_single_endpoint_outage_exit_total 67
telemt_me_single_endpoint_outage_reconnect_attempt_total 119
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 119
telemt_me_single_endpoint_shadow_rotate_total 337
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
telemt_me_writers_active_current 40
telemt_desync_total 14920
telemt_desync_full_logged_total 3954
telemt_desync_suppressed_total 10966
telemt_desync_frames_bucket_total{bucket="1_2"} 2807
telemt_desync_frames_bucket_total{bucket="3_10"} 6055
telemt_desync_frames_bucket_total{bucket="gt_10"} 6058
telemt_pool_swap_total 44
telemt_pool_force_close_total 1563
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 438
telemt_me_draining_writers_reap_progress_total 12465
telemt_me_writer_removed_unexpected_total 842
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1848
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11411
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1261
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 302
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10902
telemt_me_writer_teardown_success_total{mode="normal"} 13259
telemt_me_writer_teardown_noop_total 12484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 22139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 23727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25743
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 51.903943
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25743
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 438
telemt_me_refill_failed_total 320
telemt_me_writer_restored_same_endpoint_total 632
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 9075515
telemt_user_connections_current{user="hello"} 1601
telemt_user_octets_from_client{user="hello"} 83922276775 (78.16 GB)
telemt_user_octets_to_client{user="hello"} 518169908543 (482.58 GB)
telemt_user_msgs_from_client{user="hello"} 58278
telemt_user_msgs_to_client{user="hello"} 46361
telemt_user_unique_ips_current{user="hello"} 634
telemt_user_unique_ips_recent_window{user="hello"} 202
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 173070.7 (48h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10762844
telemt_connections_bad_total 908790
telemt_connections_current 1026
telemt_connections_me_current 1026
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 236800
telemt_upstream_connect_attempt_total 103908
telemt_upstream_connect_success_total 102817
telemt_upstream_connect_fail_total 930
telemt_upstream_connect_attempts_per_request{bucket="1"} 103747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38798
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1344
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 930
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72436
telemt_me_reconnect_success_total 2842
telemt_me_reader_eof_total 2534
telemt_me_idle_close_by_peer_total 2532
telemt_me_route_drop_no_conn_total 5213885
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8503749
telemt_me_endpoint_quarantine_total 1144
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1294
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
telemt_me_writers_active_current 45
telemt_desync_total 45335
telemt_desync_full_logged_total 15462
telemt_desync_suppressed_total 29873
telemt_desync_frames_bucket_total{bucket="1_2"} 9193
telemt_desync_frames_bucket_total{bucket="3_10"} 17371
telemt_desync_frames_bucket_total{bucket="gt_10"} 18771
telemt_pool_swap_total 177
telemt_pool_force_close_total 5287
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 643
telemt_me_draining_writers_reap_progress_total 59366
telemt_me_writer_removed_unexpected_total 2572
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6288
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55676
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4557
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 730
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54079
telemt_me_writer_teardown_success_total{mode="normal"} 61964
telemt_me_writer_teardown_noop_total 59367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 119221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 120596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 121014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 121287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 121321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 121324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 121324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 121327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 121331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 121331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 121331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 121331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 121331
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.065591
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 121331
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 643
telemt_me_refill_failed_total 4287
telemt_me_writer_restored_same_endpoint_total 2391
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 8506958
telemt_user_connections_current{user="hello"} 1026
telemt_user_octets_from_client{user="hello"} 192268769441 (179.06 GB)
telemt_user_octets_to_client{user="hello"} 3237303914996 (2.94 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 109906.9 (30h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11364699
telemt_connections_bad_total 455440
telemt_connections_current 1476
telemt_connections_me_current 1476
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4664189
telemt_upstream_connect_attempt_total 52026
telemt_upstream_connect_success_total 51635
telemt_upstream_connect_fail_total 381
telemt_upstream_connect_attempts_per_request{bucket="1"} 52016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 200
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 381
telemt_me_reconnect_attempts_total 48596
telemt_me_reconnect_success_total 1686
telemt_me_reader_eof_total 1344
telemt_me_idle_close_by_peer_total 1343
telemt_me_route_drop_no_conn_total 4049425
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5478703
telemt_me_endpoint_quarantine_total 713
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 828
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30804
telemt_desync_full_logged_total 10456
telemt_desync_suppressed_total 20348
telemt_desync_frames_bucket_total{bucket="1_2"} 6126
telemt_desync_frames_bucket_total{bucket="3_10"} 12189
telemt_desync_frames_bucket_total{bucket="gt_10"} 12489
telemt_pool_swap_total 116
telemt_pool_force_close_total 3510
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 355
telemt_me_draining_writers_reap_progress_total 38302
telemt_me_writer_removed_unexpected_total 1404
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3369
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36371
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3069
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34792
telemt_me_writer_teardown_success_total{mode="normal"} 39740
telemt_me_writer_teardown_noop_total 38309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78049
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.530171
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78049
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 355
telemt_me_refill_failed_total 2726
telemt_me_writer_restored_same_endpoint_total 1498
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5471475
telemt_user_connections_current{user="hello"} 1476
telemt_user_octets_from_client{user="hello"} 117572929032 (109.50 GB)
telemt_user_octets_to_client{user="hello"} 2098802888806 (1.91 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 590
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 90877.3 (25h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1377226
telemt_connections_bad_total 33746
telemt_connections_current 874
telemt_connections_me_current 874
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 25605
telemt_upstream_connect_attempt_total 42811
telemt_upstream_connect_success_total 42680
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 42784
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22691
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 737
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2020
telemt_me_reconnect_success_total 824
telemt_me_reader_eof_total 804
telemt_me_idle_close_by_peer_total 804
telemt_me_route_drop_no_conn_total 481198
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1221354
telemt_me_endpoint_quarantine_total 746
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 746
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
telemt_me_writers_active_current 43
telemt_desync_total 7400
telemt_desync_full_logged_total 2298
telemt_desync_suppressed_total 5102
telemt_desync_frames_bucket_total{bucket="1_2"} 1639
telemt_desync_frames_bucket_total{bucket="3_10"} 2887
telemt_desync_frames_bucket_total{bucket="gt_10"} 2874
telemt_pool_swap_total 97
telemt_pool_force_close_total 2522
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 146
telemt_me_draining_writers_reap_progress_total 35693
telemt_me_writer_removed_unexpected_total 775
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2817
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33683
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2435
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 87
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33171
telemt_me_writer_teardown_success_total{mode="normal"} 36500
telemt_me_writer_teardown_noop_total 35697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72197
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.541538
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72197
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 146
telemt_me_refill_failed_total 66
telemt_me_writer_restored_same_endpoint_total 698
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 1217407
telemt_user_connections_current{user="hello"} 874
telemt_user_octets_from_client{user="hello"} 23526920605 (21.91 GB)
telemt_user_octets_to_client{user="hello"} 516425653959 (480.96 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 320
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 173075.1 (48h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13082183
telemt_connections_bad_total 1532757
telemt_connections_current 1398
telemt_connections_me_current 1398
telemt_handshake_timeouts_total 375065
telemt_upstream_connect_attempt_total 65563
telemt_upstream_connect_success_total 65231
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 65428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32830
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2572
telemt_me_reconnect_success_total 1349
telemt_me_reader_eof_total 1316
telemt_me_idle_close_by_peer_total 1316
telemt_me_route_drop_no_conn_total 4431146
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9898776
telemt_me_endpoint_quarantine_total 1168
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1295
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
telemt_desync_total 41034
telemt_desync_full_logged_total 13381
telemt_desync_suppressed_total 27653
telemt_desync_frames_bucket_total{bucket="1_2"} 9800
telemt_desync_frames_bucket_total{bucket="3_10"} 15144
telemt_desync_frames_bucket_total{bucket="gt_10"} 16090
telemt_pool_swap_total 192
telemt_pool_force_close_total 5272
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 654
telemt_me_draining_writers_reap_progress_total 59085
telemt_me_writer_removed_unexpected_total 1266
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4814
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55577
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5098
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53813
telemt_me_writer_teardown_success_total{mode="normal"} 60391
telemt_me_writer_teardown_noop_total 59087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 116921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 118586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 118969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 119345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 119465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 119478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 119478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 119478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 119478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 119478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 119478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 119478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 119478
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.522983
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 119478
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 654
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1180
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 9866395
telemt_user_connections_current{user="hello"} 1398
telemt_user_octets_from_client{user="hello"} 192650996984 (179.42 GB)
telemt_user_octets_to_client{user="hello"} 4362027620580 (3.97 TB)
telemt_user_unique_ips_current{user="hello"} 476
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 173072.4 (48h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11381668
telemt_connections_bad_total 1288568
telemt_connections_current 1175
telemt_connections_me_current 1175
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 299694
telemt_upstream_connect_attempt_total 92030
telemt_upstream_connect_success_total 91199
telemt_upstream_connect_fail_total 624
telemt_upstream_connect_attempts_per_request{bucket="1"} 91823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38370
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 624
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9917
telemt_me_reconnect_success_total 2381
telemt_me_reader_eof_total 2225
telemt_me_idle_close_by_peer_total 2224
telemt_me_seq_mismatch_total 79
telemt_me_route_drop_no_conn_total 5608062
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8802423
telemt_me_endpoint_quarantine_total 1328
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 48
telemt_me_single_endpoint_outage_exit_total 48
telemt_me_single_endpoint_outage_reconnect_attempt_total 48
telemt_me_single_endpoint_outage_reconnect_success_total 46
telemt_me_single_endpoint_quarantine_bypass_total 48
telemt_me_single_endpoint_shadow_rotate_total 1298
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
telemt_me_writers_active_current 41
telemt_desync_total 40308
telemt_desync_full_logged_total 13020
telemt_desync_suppressed_total 27288
telemt_desync_frames_bucket_total{bucket="1_2"} 10068
telemt_desync_frames_bucket_total{bucket="3_10"} 14964
telemt_desync_frames_bucket_total{bucket="gt_10"} 15276
telemt_pool_swap_total 182
telemt_pool_force_close_total 5069
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 640
telemt_me_draining_writers_reap_progress_total 58869
telemt_me_writer_removed_unexpected_total 2257
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6162
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55040
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4598
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53800
telemt_me_writer_teardown_success_total{mode="normal"} 61202
telemt_me_writer_teardown_noop_total 58874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 117421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 119171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 119707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 120026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 120076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 120076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 120076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 120076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 120076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 120076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 120076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 120076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 120076
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.230103
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 120076
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 640
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 1939
telemt_me_writer_restored_fallback_total 109
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 8807928
telemt_user_connections_current{user="hello"} 1175
telemt_user_octets_from_client{user="hello"} 155895533453 (145.19 GB)
telemt_user_octets_to_client{user="hello"} 3413741744139 (3.10 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 427
telemt_user_unique_ips_recent_window{user="hello"} 147
```