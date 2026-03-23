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

# Server Metrics 2026-03-23 00:40:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 99241.8 (27h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3477839
telemt_connections_bad_total 301312
telemt_connections_current 752
telemt_connections_me_current 752
telemt_handshake_timeouts_total 108622
telemt_upstream_connect_attempt_total 36814
telemt_upstream_connect_success_total 36813
telemt_upstream_connect_attempts_per_request{bucket="1"} 36813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23907
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1386
telemt_me_reconnect_success_total 592
telemt_me_reader_eof_total 608
telemt_me_idle_close_by_peer_total 608
telemt_me_route_drop_no_conn_total 2979250
telemt_me_route_drop_channel_closed_total 1231
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2878247
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 697
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 773
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 12374
telemt_desync_full_logged_total 3873
telemt_desync_suppressed_total 8501
telemt_desync_frames_bucket_total{bucket="1_2"} 3343
telemt_desync_frames_bucket_total{bucket="3_10"} 4499
telemt_desync_frames_bucket_total{bucket="gt_10"} 4532
telemt_pool_swap_total 110
telemt_pool_force_close_total 3403
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 651
telemt_me_draining_writers_reap_progress_total 33706
telemt_me_writer_removed_unexpected_total 587
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2446
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31494
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3347
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30303
telemt_me_writer_teardown_success_total{mode="normal"} 33940
telemt_me_writer_teardown_noop_total 33717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67657
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 376.138290
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67657
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 651
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 530
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2867410
telemt_user_connections_current{user="hello"} 752
telemt_user_octets_from_client{user="hello"} 40922766568 (38.11 GB)
telemt_user_octets_to_client{user="hello"} 784949285804 (731.04 GB)
telemt_user_unique_ips_current{user="hello"} 366
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 112607.9 (31h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3990273
telemt_connections_bad_total 365282
telemt_connections_current 438
telemt_connections_me_current 438
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100475
telemt_upstream_connect_attempt_total 69966
telemt_upstream_connect_success_total 69129
telemt_upstream_connect_fail_total 744
telemt_upstream_connect_attempts_per_request{bucket="1"} 69873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30387
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 744
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9916
telemt_me_reconnect_success_total 3582
telemt_me_reader_eof_total 3579
telemt_me_idle_close_by_peer_total 3579
telemt_me_route_drop_no_conn_total 3640168
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3172542
telemt_me_endpoint_quarantine_total 884
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 44
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 44
telemt_me_single_endpoint_shadow_rotate_total 875
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
telemt_me_writers_active_current 49
telemt_me_writers_warm_current 42
telemt_desync_total 12942
telemt_desync_full_logged_total 7253
telemt_desync_suppressed_total 5689
telemt_desync_frames_bucket_total{bucket="1_2"} 2939
telemt_desync_frames_bucket_total{bucket="3_10"} 5072
telemt_desync_frames_bucket_total{bucket="gt_10"} 4931
telemt_pool_swap_total 105
telemt_pool_force_close_total 3031
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 252
telemt_me_draining_writers_reap_progress_total 46098
telemt_me_writer_removed_unexpected_total 3511
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6108
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43532
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2573
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43067
telemt_me_writer_teardown_success_total{mode="normal"} 49640
telemt_me_writer_teardown_noop_total 46099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95739
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.583768
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95739
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 252
telemt_me_refill_failed_total 243
telemt_me_writer_restored_same_endpoint_total 3208
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 3185380
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 42949289727 (40.00 GB)
telemt_user_octets_to_client{user="hello"} 789993255475 (735.74 GB)
telemt_user_msgs_from_client{user="hello"} 48526
telemt_user_msgs_to_client{user="hello"} 183196
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 187467.8 (52h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16314167
telemt_connections_bad_total 1644161
telemt_connections_current 659
telemt_connections_me_current 659
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 397028
telemt_upstream_connect_attempt_total 83849
telemt_upstream_connect_success_total 83745
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 83762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40890
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1715
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2982
telemt_me_reconnect_success_total 1560
telemt_me_reader_eof_total 1507
telemt_me_idle_close_by_peer_total 1505
telemt_me_route_drop_no_conn_total 14043119
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12958919
telemt_me_endpoint_quarantine_total 1233
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1410
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 53725
telemt_desync_full_logged_total 17052
telemt_desync_suppressed_total 36673
telemt_desync_frames_bucket_total{bucket="1_2"} 11965
telemt_desync_frames_bucket_total{bucket="3_10"} 20957
telemt_desync_frames_bucket_total{bucket="gt_10"} 20803
telemt_pool_swap_total 203
telemt_pool_force_close_total 6681
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1058
telemt_me_draining_writers_reap_progress_total 63366
telemt_me_writer_removed_unexpected_total 1452
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5434
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58658
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6211
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56685
telemt_me_writer_teardown_success_total{mode="normal"} 64092
telemt_me_writer_teardown_noop_total 63419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 116406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 120019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 121791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 124183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 125850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 126901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 127472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 127502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 127503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 127507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 127509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 127511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 127511
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.595708
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 127511
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1058
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1349
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 12958963
telemt_user_connections_current{user="hello"} 659
telemt_user_octets_from_client{user="hello"} 190981120989 (177.87 GB)
telemt_user_octets_to_client{user="hello"} 3485223922039 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 187469.2 (52h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11858500
telemt_connections_bad_total 1229958
telemt_connections_current 511
telemt_connections_me_current 511
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344522
telemt_upstream_connect_attempt_total 98221
telemt_upstream_connect_success_total 96899
telemt_upstream_connect_fail_total 869
telemt_upstream_connect_attempts_per_request{bucket="1"} 97768
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40771
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3800
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 869
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4399
telemt_me_reconnect_success_total 1866
telemt_me_reader_eof_total 1731
telemt_me_idle_close_by_peer_total 1731
telemt_me_route_drop_no_conn_total 4553306
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8804915
telemt_me_endpoint_quarantine_total 1244
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1430
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
telemt_me_writers_active_current 43
telemt_desync_total 38730
telemt_desync_full_logged_total 13043
telemt_desync_suppressed_total 25687
telemt_desync_frames_bucket_total{bucket="1_2"} 9595
telemt_desync_frames_bucket_total{bucket="3_10"} 14876
telemt_desync_frames_bucket_total{bucket="gt_10"} 14259
telemt_pool_swap_total 200
telemt_pool_force_close_total 6042
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 708
telemt_me_draining_writers_reap_progress_total 61589
telemt_me_writer_removed_unexpected_total 1762
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5527
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57679
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5530
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55547
telemt_me_writer_teardown_success_total{mode="normal"} 63206
telemt_me_writer_teardown_noop_total 61614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 118077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 121297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 122445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 123636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 124395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 124735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 124810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 124812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 124818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 124820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 124820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 124820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 124820
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.398535
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 124820
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 708
telemt_me_refill_failed_total 136
telemt_me_writer_restored_same_endpoint_total 1594
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 8742679
telemt_user_connections_current{user="hello"} 511
telemt_user_octets_from_client{user="hello"} 217716873804 (202.76 GB)
telemt_user_octets_to_client{user="hello"} 3958891190279 (3.60 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 187433.3 (52h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11040258
telemt_connections_bad_total 972378
telemt_connections_current 487
telemt_connections_me_current 487
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345511
telemt_upstream_connect_attempt_total 82554
telemt_upstream_connect_success_total 80995
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 81200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39277
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2026
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5730
telemt_me_reconnect_success_total 2355
telemt_me_reader_eof_total 2100
telemt_me_idle_close_by_peer_total 2099
telemt_me_route_drop_no_conn_total 5335256
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8346368
telemt_me_endpoint_quarantine_total 1319
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1384
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_me_writers_active_current 42
telemt_desync_total 38069
telemt_desync_full_logged_total 12622
telemt_desync_suppressed_total 25447
telemt_desync_frames_bucket_total{bucket="1_2"} 9612
telemt_desync_frames_bucket_total{bucket="3_10"} 14561
telemt_desync_frames_bucket_total{bucket="gt_10"} 13896
telemt_pool_swap_total 196
telemt_pool_force_close_total 5939
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 739
telemt_me_draining_writers_reap_progress_total 62015
telemt_me_writer_removed_unexpected_total 2250
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6279
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57918
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5368
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56076
telemt_me_writer_teardown_success_total{mode="normal"} 64197
telemt_me_writer_teardown_noop_total 62086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 120451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 123165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 124128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 125201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 125802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 126016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 126144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 126175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 126183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 126196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 126229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 126232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 126283
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.774062
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 126283
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 739
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2045
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 8338329
telemt_user_connections_current{user="hello"} 487
telemt_user_octets_from_client{user="hello"} 192606601039 (179.38 GB)
telemt_user_octets_to_client{user="hello"} 3466052513921 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 57713.3 (16h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11216147
telemt_connections_bad_total 668604
telemt_connections_current 896
telemt_connections_me_current 896
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 268601
telemt_upstream_connect_attempt_total 56399
telemt_upstream_connect_success_total 53518
telemt_upstream_connect_fail_total 1911
telemt_upstream_connect_attempts_per_request{bucket="1"} 55429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18407
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6006
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1911
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7483
telemt_me_reconnect_success_total 1181
telemt_me_reader_eof_total 754
telemt_me_idle_close_by_peer_total 753
telemt_me_route_drop_no_conn_total 25287050
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9310735
telemt_me_endpoint_quarantine_total 435
telemt_me_single_endpoint_outage_enter_total 85
telemt_me_single_endpoint_outage_exit_total 85
telemt_me_single_endpoint_outage_reconnect_attempt_total 158
telemt_me_single_endpoint_outage_reconnect_success_total 42
telemt_me_single_endpoint_quarantine_bypass_total 158
telemt_me_single_endpoint_shadow_rotate_total 453
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
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 39
telemt_desync_total 16286
telemt_desync_full_logged_total 4430
telemt_desync_suppressed_total 11856
telemt_desync_frames_bucket_total{bucket="1_2"} 3088
telemt_desync_frames_bucket_total{bucket="3_10"} 6625
telemt_desync_frames_bucket_total{bucket="gt_10"} 6573
telemt_pool_swap_total 60
telemt_pool_force_close_total 1961
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 475
telemt_me_draining_writers_reap_progress_total 17923
telemt_me_writer_removed_unexpected_total 1069
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2410
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16524
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1654
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15962
telemt_me_writer_teardown_success_total{mode="normal"} 18934
telemt_me_writer_teardown_noop_total 17942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36876
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.618834
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36876
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 475
telemt_me_refill_failed_total 336
telemt_me_writer_restored_same_endpoint_total 772
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 9336069
telemt_user_connections_current{user="hello"} 896
telemt_user_octets_from_client{user="hello"} 87010245982 (81.03 GB)
telemt_user_octets_to_client{user="hello"} 602406915253 (561.04 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 393
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 187439.7 (52h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10975008
telemt_connections_bad_total 942819
telemt_connections_current 546
telemt_connections_me_current 546
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 241906
telemt_upstream_connect_attempt_total 111455
telemt_upstream_connect_success_total 110304
telemt_upstream_connect_fail_total 978
telemt_upstream_connect_attempts_per_request{bucket="1"} 111282
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65901
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42806
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1359
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 978
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72871
telemt_me_reconnect_success_total 3066
telemt_me_reader_eof_total 2753
telemt_me_idle_close_by_peer_total 2751
telemt_me_route_drop_no_conn_total 5259779
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8663543
telemt_me_endpoint_quarantine_total 1266
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 1415
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 46183
telemt_desync_full_logged_total 15809
telemt_desync_suppressed_total 30374
telemt_desync_frames_bucket_total{bucket="1_2"} 9385
telemt_desync_frames_bucket_total{bucket="3_10"} 17679
telemt_desync_frames_bucket_total{bucket="gt_10"} 19119
telemt_pool_swap_total 192
telemt_pool_force_close_total 5644
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 662
telemt_me_draining_writers_reap_progress_total 66166
telemt_me_writer_removed_unexpected_total 2782
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6797
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62186
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4895
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60522
telemt_me_writer_teardown_success_total{mode="normal"} 68983
telemt_me_writer_teardown_noop_total 66167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 133006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 134414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 134833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 135106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 135140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 135143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 135143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 135146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 135150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 135150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 135150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 135150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 135150
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.245115
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 135150
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 662
telemt_me_refill_failed_total 4297
telemt_me_writer_restored_same_endpoint_total 2587
telemt_me_writer_restored_fallback_total 51
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8666555
telemt_user_connections_current{user="hello"} 546
telemt_user_octets_from_client{user="hello"} 194475044081 (181.12 GB)
telemt_user_octets_to_client{user="hello"} 3309619867792 (3.01 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 124276.1 (34h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11674600
telemt_connections_bad_total 477127
telemt_connections_current 722
telemt_connections_me_current 722
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4760020
telemt_upstream_connect_attempt_total 59642
telemt_upstream_connect_success_total 59206
telemt_upstream_connect_fail_total 425
telemt_upstream_connect_attempts_per_request{bucket="1"} 59631
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27229
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 425
telemt_me_reconnect_attempts_total 48874
telemt_me_reconnect_success_total 1803
telemt_me_reader_eof_total 1474
telemt_me_idle_close_by_peer_total 1473
telemt_me_route_drop_no_conn_total 4085653
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5610031
telemt_me_endpoint_quarantine_total 836
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 949
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
telemt_me_writers_warm_current 24
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31522
telemt_desync_full_logged_total 10745
telemt_desync_suppressed_total 20777
telemt_desync_frames_bucket_total{bucket="1_2"} 6271
telemt_desync_frames_bucket_total{bucket="3_10"} 12432
telemt_desync_frames_bucket_total{bucket="gt_10"} 12819
telemt_pool_swap_total 131
telemt_pool_force_close_total 3857
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 375
telemt_me_draining_writers_reap_progress_total 45256
telemt_me_writer_removed_unexpected_total 1525
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3744
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43080
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3416
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41399
telemt_me_writer_teardown_success_total{mode="normal"} 46824
telemt_me_writer_teardown_noop_total 45263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92087
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.682427
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92087
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 375
telemt_me_refill_failed_total 2735
telemt_me_writer_restored_same_endpoint_total 1600
telemt_me_writer_restored_fallback_total 26
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5602594
telemt_user_connections_current{user="hello"} 722
telemt_user_octets_from_client{user="hello"} 119025589936 (110.85 GB)
telemt_user_octets_to_client{user="hello"} 2167088535122 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 355
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 105246.9 (29h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1512160
telemt_connections_bad_total 36695
telemt_connections_current 418
telemt_connections_me_current 418
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 30373
telemt_upstream_connect_attempt_total 49413
telemt_upstream_connect_success_total 49257
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 49385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25838
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 786
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2210
telemt_me_reconnect_success_total 893
telemt_me_reader_eof_total 879
telemt_me_idle_close_by_peer_total 879
telemt_me_route_drop_no_conn_total 516128
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1343706
telemt_me_endpoint_quarantine_total 854
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 868
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
telemt_me_writers_active_current 47
telemt_desync_total 8836
telemt_desync_full_logged_total 2599
telemt_desync_suppressed_total 6237
telemt_desync_frames_bucket_total{bucket="1_2"} 2432
telemt_desync_frames_bucket_total{bucket="3_10"} 3385
telemt_desync_frames_bucket_total{bucket="gt_10"} 3019
telemt_pool_swap_total 113
telemt_pool_force_close_total 2910
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 163
telemt_me_draining_writers_reap_progress_total 41730
telemt_me_writer_removed_unexpected_total 847
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3207
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39409
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2822
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38820
telemt_me_writer_teardown_success_total{mode="normal"} 42616
telemt_me_writer_teardown_noop_total 41734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84350
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.227782
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84350
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 163
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 758
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 1339520
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 25868030173 (24.09 GB)
telemt_user_octets_to_client{user="hello"} 573248620911 (533.88 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 187444.4 (52h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13313125
telemt_connections_bad_total 1600586
telemt_connections_current 558
telemt_connections_me_current 558
telemt_handshake_timeouts_total 388520
telemt_upstream_connect_attempt_total 73386
telemt_upstream_connect_success_total 73038
telemt_upstream_connect_fail_total 212
telemt_upstream_connect_attempts_per_request{bucket="1"} 73250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36833
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 212
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2934
telemt_me_reconnect_success_total 1471
telemt_me_reader_eof_total 1455
telemt_me_idle_close_by_peer_total 1455
telemt_me_route_drop_no_conn_total 4481222
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10038047
telemt_me_endpoint_quarantine_total 1328
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1415
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 42036
telemt_desync_full_logged_total 13728
telemt_desync_suppressed_total 28308
telemt_desync_frames_bucket_total{bucket="1_2"} 10162
telemt_desync_frames_bucket_total{bucket="3_10"} 15448
telemt_desync_frames_bucket_total{bucket="gt_10"} 16426
telemt_pool_swap_total 208
telemt_pool_force_close_total 5568
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 675
telemt_me_draining_writers_reap_progress_total 66299
telemt_me_writer_removed_unexpected_total 1393
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5249
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62495
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5394
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60731
telemt_me_writer_teardown_success_total{mode="normal"} 67744
telemt_me_writer_teardown_noop_total 66301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 131435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 133153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 133536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 133912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 134032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 134045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 134045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 134045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 134045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 134045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 134045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 134045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 134045
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.765336
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 134045
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 675
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1289
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 10004765
telemt_user_connections_current{user="hello"} 558
telemt_user_octets_from_client{user="hello"} 194629519928 (181.26 GB)
telemt_user_octets_to_client{user="hello"} 4436155534756 (4.03 TB)
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 187440.9 (52h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11621214
telemt_connections_bad_total 1352061
telemt_connections_current 562
telemt_connections_me_current 562
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 310678
telemt_upstream_connect_attempt_total 100918
telemt_upstream_connect_success_total 100030
telemt_upstream_connect_fail_total 680
telemt_upstream_connect_attempts_per_request{bucket="1"} 100710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42467
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 680
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10460
telemt_me_reconnect_success_total 2569
telemt_me_reader_eof_total 2380
telemt_me_idle_close_by_peer_total 2379
telemt_me_seq_mismatch_total 97
telemt_me_route_drop_no_conn_total 5648440
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8948494
telemt_me_endpoint_quarantine_total 1514
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 52
telemt_me_single_endpoint_outage_exit_total 52
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 1418
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 33
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 41729
telemt_desync_full_logged_total 13433
telemt_desync_suppressed_total 28296
telemt_desync_frames_bucket_total{bucket="1_2"} 10756
telemt_desync_frames_bucket_total{bucket="3_10"} 15349
telemt_desync_frames_bucket_total{bucket="gt_10"} 15624
telemt_pool_swap_total 198
telemt_pool_force_close_total 5343
telemt_pool_stale_pick_total 372
telemt_me_writer_close_signal_drop_total 663
telemt_me_draining_writers_reap_progress_total 66377
telemt_me_writer_removed_unexpected_total 2423
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6613
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62270
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4872
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61034
telemt_me_writer_teardown_success_total{mode="normal"} 68883
telemt_me_writer_teardown_noop_total 66382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 132575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 134357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 134896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 135215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 135265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 135265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 135265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 135265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 135265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 135265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 135265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 135265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 135265
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.455666
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 135265
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 663
telemt_me_refill_failed_total 408
telemt_me_writer_restored_same_endpoint_total 2066
telemt_me_writer_restored_fallback_total 132
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 225
telemt_user_connections_total{user="hello"} 8953100
telemt_user_connections_current{user="hello"} 562
telemt_user_octets_from_client{user="hello"} 157242956724 (146.44 GB)
telemt_user_octets_to_client{user="hello"} 3484699853210 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 56
```