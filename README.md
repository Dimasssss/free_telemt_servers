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

# Server Metrics 2026-03-23 00:45:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 99547.4 (27h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3484865
telemt_connections_bad_total 302883
telemt_connections_current 851
telemt_connections_me_current 851
telemt_handshake_timeouts_total 109018
telemt_upstream_connect_attempt_total 36909
telemt_upstream_connect_success_total 36908
telemt_upstream_connect_attempts_per_request{bucket="1"} 36908
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23974
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1386
telemt_me_reconnect_success_total 592
telemt_me_reader_eof_total 608
telemt_me_idle_close_by_peer_total 608
telemt_me_route_drop_no_conn_total 2979995
telemt_me_route_drop_channel_closed_total 1231
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2882258
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 697
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 776
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 12380
telemt_desync_full_logged_total 3877
telemt_desync_suppressed_total 8503
telemt_desync_frames_bucket_total{bucket="1_2"} 3343
telemt_desync_frames_bucket_total{bucket="3_10"} 4503
telemt_desync_frames_bucket_total{bucket="gt_10"} 4534
telemt_pool_swap_total 110
telemt_pool_force_close_total 3403
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 651
telemt_me_draining_writers_reap_progress_total 33800
telemt_me_writer_removed_unexpected_total 587
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2446
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31588
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3347
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30397
telemt_me_writer_teardown_success_total{mode="normal"} 34034
telemt_me_writer_teardown_noop_total 33811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67845
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 376.141675
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67845
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 651
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 530
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2871397
telemt_user_connections_current{user="hello"} 851
telemt_user_octets_from_client{user="hello"} 40954606072 (38.14 GB)
telemt_user_octets_to_client{user="hello"} 786352481680 (732.35 GB)
telemt_user_unique_ips_current{user="hello"} 405
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 112913.1 (31h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3991869
telemt_connections_bad_total 365774
telemt_connections_current 181
telemt_connections_me_current 181
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100519
telemt_upstream_connect_attempt_total 70158
telemt_upstream_connect_success_total 69321
telemt_upstream_connect_fail_total 744
telemt_upstream_connect_attempts_per_request{bucket="1"} 70065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30486
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 744
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9940
telemt_me_reconnect_success_total 3589
telemt_me_reader_eof_total 3586
telemt_me_idle_close_by_peer_total 3586
telemt_me_route_drop_no_conn_total 3640299
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3173553
telemt_me_endpoint_quarantine_total 886
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 44
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 44
telemt_me_single_endpoint_shadow_rotate_total 881
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
telemt_me_writers_active_current 44
telemt_desync_total 12944
telemt_desync_full_logged_total 7255
telemt_desync_suppressed_total 5689
telemt_desync_frames_bucket_total{bucket="1_2"} 2939
telemt_desync_frames_bucket_total{bucket="3_10"} 5074
telemt_desync_frames_bucket_total{bucket="gt_10"} 4931
telemt_pool_swap_total 105
telemt_pool_force_close_total 3052
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 252
telemt_me_draining_writers_reap_progress_total 46298
telemt_me_writer_removed_unexpected_total 3518
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6133
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43714
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2594
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43246
telemt_me_writer_teardown_success_total{mode="normal"} 49847
telemt_me_writer_teardown_noop_total 46299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96146
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.589270
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96146
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 252
telemt_me_refill_failed_total 244
telemt_me_writer_restored_same_endpoint_total 3212
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 3186390
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 43045071403 (40.09 GB)
telemt_user_octets_to_client{user="hello"} 790242974151 (735.97 GB)
telemt_user_msgs_from_client{user="hello"} 48526
telemt_user_msgs_to_client{user="hello"} 183196
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 187772.9 (52h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16316423
telemt_connections_bad_total 1644180
telemt_connections_current 844
telemt_connections_me_current 844
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 397050
telemt_upstream_connect_attempt_total 83992
telemt_upstream_connect_success_total 83888
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 83905
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40981
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1715
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2988
telemt_me_reconnect_success_total 1566
telemt_me_reader_eof_total 1513
telemt_me_idle_close_by_peer_total 1511
telemt_me_route_drop_no_conn_total 14043421
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12961062
telemt_me_endpoint_quarantine_total 1234
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1412
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 53742
telemt_desync_full_logged_total 17056
telemt_desync_suppressed_total 36686
telemt_desync_frames_bucket_total{bucket="1_2"} 11975
telemt_desync_frames_bucket_total{bucket="3_10"} 20962
telemt_desync_frames_bucket_total{bucket="gt_10"} 20805
telemt_pool_swap_total 203
telemt_pool_force_close_total 6681
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1058
telemt_me_draining_writers_reap_progress_total 63476
telemt_me_writer_removed_unexpected_total 1457
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5440
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58768
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6211
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56795
telemt_me_writer_teardown_success_total{mode="normal"} 64208
telemt_me_writer_teardown_noop_total 63529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 116632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 120245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 122017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 124409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 126076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 127127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 127698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 127728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 127729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 127733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 127735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 127737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 127737
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.597708
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 127737
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1058
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1354
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 12961106
telemt_user_connections_current{user="hello"} 844
telemt_user_octets_from_client{user="hello"} 191001152813 (177.88 GB)
telemt_user_octets_to_client{user="hello"} 3486396555207 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 187774.2 (52h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11862180
telemt_connections_bad_total 1231190
telemt_connections_current 482
telemt_connections_me_current 482
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344533
telemt_upstream_connect_attempt_total 98379
telemt_upstream_connect_success_total 97057
telemt_upstream_connect_fail_total 869
telemt_upstream_connect_attempts_per_request{bucket="1"} 97926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40860
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3800
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 869
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4408
telemt_me_reconnect_success_total 1874
telemt_me_reader_eof_total 1740
telemt_me_idle_close_by_peer_total 1740
telemt_me_route_drop_no_conn_total 4553590
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8807167
telemt_me_endpoint_quarantine_total 1244
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1432
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
telemt_desync_total 38752
telemt_desync_full_logged_total 13048
telemt_desync_suppressed_total 25704
telemt_desync_frames_bucket_total{bucket="1_2"} 9602
telemt_desync_frames_bucket_total{bucket="3_10"} 14886
telemt_desync_frames_bucket_total{bucket="gt_10"} 14264
telemt_pool_swap_total 200
telemt_pool_force_close_total 6042
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 708
telemt_me_draining_writers_reap_progress_total 61711
telemt_me_writer_removed_unexpected_total 1770
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5537
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57800
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5530
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55669
telemt_me_writer_teardown_success_total{mode="normal"} 63337
telemt_me_writer_teardown_noop_total 61736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 118330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 121550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 122698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 123889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 124648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 124988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 125063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 125065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 125071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 125073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 125073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 125073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 125073
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.400266
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 125073
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 708
telemt_me_refill_failed_total 136
telemt_me_writer_restored_same_endpoint_total 1602
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 8744931
telemt_user_connections_current{user="hello"} 482
telemt_user_octets_from_client{user="hello"} 217726184696 (202.77 GB)
telemt_user_octets_to_client{user="hello"} 3959699174879 (3.60 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 187738.4 (52h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11043148
telemt_connections_bad_total 972654
telemt_connections_current 574
telemt_connections_me_current 574
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345525
telemt_upstream_connect_attempt_total 82683
telemt_upstream_connect_success_total 81124
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 81329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39351
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2026
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5730
telemt_me_reconnect_success_total 2355
telemt_me_reader_eof_total 2100
telemt_me_idle_close_by_peer_total 2099
telemt_me_route_drop_no_conn_total 5335486
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8348099
telemt_me_endpoint_quarantine_total 1321
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1388
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
telemt_me_writers_active_current 43
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
telemt_me_draining_writers_reap_progress_total 62143
telemt_me_writer_removed_unexpected_total 2250
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6283
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58042
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5368
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56204
telemt_me_writer_teardown_success_total{mode="normal"} 64325
telemt_me_writer_teardown_noop_total 62214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 120707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 123421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 124384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 125457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 126058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 126272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 126400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 126431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 126439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 126452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 126485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 126488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 126539
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.775759
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 126539
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 739
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2045
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 8340067
telemt_user_connections_current{user="hello"} 574
telemt_user_octets_from_client{user="hello"} 192654567303 (179.42 GB)
telemt_user_octets_to_client{user="hello"} 3467118245177 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 58018.7 (16h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11221049
telemt_connections_bad_total 668614
telemt_connections_current 949
telemt_connections_me_current 949
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 269234
telemt_upstream_connect_attempt_total 56544
telemt_upstream_connect_success_total 53654
telemt_upstream_connect_fail_total 1911
telemt_upstream_connect_attempts_per_request{bucket="1"} 55565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18469
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6006
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1911
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7508
telemt_me_reconnect_success_total 1184
telemt_me_reader_eof_total 755
telemt_me_idle_close_by_peer_total 754
telemt_me_route_drop_no_conn_total 25287692
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9314745
telemt_me_endpoint_quarantine_total 437
telemt_me_single_endpoint_outage_enter_total 86
telemt_me_single_endpoint_outage_exit_total 86
telemt_me_single_endpoint_outage_reconnect_attempt_total 159
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 159
telemt_me_single_endpoint_shadow_rotate_total 460
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 16296
telemt_desync_full_logged_total 4436
telemt_desync_suppressed_total 11860
telemt_desync_frames_bucket_total{bucket="1_2"} 3088
telemt_desync_frames_bucket_total{bucket="3_10"} 6630
telemt_desync_frames_bucket_total{bucket="gt_10"} 6578
telemt_pool_swap_total 60
telemt_pool_force_close_total 1986
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 478
telemt_me_draining_writers_reap_progress_total 18084
telemt_me_writer_removed_unexpected_total 1070
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2430
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16666
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1679
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16098
telemt_me_writer_teardown_success_total{mode="normal"} 19096
telemt_me_writer_teardown_noop_total 18103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37199
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.678455
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37199
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 478
telemt_me_refill_failed_total 337
telemt_me_writer_restored_same_endpoint_total 772
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 9340074
telemt_user_connections_current{user="hello"} 949
telemt_user_octets_from_client{user="hello"} 87176006866 (81.19 GB)
telemt_user_octets_to_client{user="hello"} 603125950069 (561.70 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 390
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 187744.9 (52h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10977857
telemt_connections_bad_total 942920
telemt_connections_current 771
telemt_connections_me_current 771
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 241917
telemt_upstream_connect_attempt_total 111590
telemt_upstream_connect_success_total 110439
telemt_upstream_connect_fail_total 978
telemt_upstream_connect_attempts_per_request{bucket="1"} 111417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42894
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1359
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 978
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72871
telemt_me_reconnect_success_total 3066
telemt_me_reader_eof_total 2753
telemt_me_idle_close_by_peer_total 2751
telemt_me_route_drop_no_conn_total 5260398
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8666124
telemt_me_endpoint_quarantine_total 1266
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 1418
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
telemt_me_writers_active_current 44
telemt_desync_total 46199
telemt_desync_full_logged_total 15813
telemt_desync_suppressed_total 30386
telemt_desync_frames_bucket_total{bucket="1_2"} 9390
telemt_desync_frames_bucket_total{bucket="3_10"} 17682
telemt_desync_frames_bucket_total{bucket="gt_10"} 19127
telemt_pool_swap_total 192
telemt_pool_force_close_total 5644
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 662
telemt_me_draining_writers_reap_progress_total 66300
telemt_me_writer_removed_unexpected_total 2782
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6802
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62315
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4895
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60656
telemt_me_writer_teardown_success_total{mode="normal"} 69117
telemt_me_writer_teardown_noop_total 66301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 133274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 134682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 135101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 135374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 135408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 135411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 135411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 135414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 135418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 135418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 135418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 135418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 135418
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.245890
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 135418
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 662
telemt_me_refill_failed_total 4297
telemt_me_writer_restored_same_endpoint_total 2587
telemt_me_writer_restored_fallback_total 51
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8669137
telemt_user_connections_current{user="hello"} 771
telemt_user_octets_from_client{user="hello"} 194527885393 (181.17 GB)
telemt_user_octets_to_client{user="hello"} 3311089019008 (3.01 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 347
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 124581.2 (34h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11680055
telemt_connections_bad_total 479644
telemt_connections_current 462
telemt_connections_me_current 462
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4760062
telemt_upstream_connect_attempt_total 59836
telemt_upstream_connect_success_total 59400
telemt_upstream_connect_fail_total 425
telemt_upstream_connect_attempts_per_request{bucket="1"} 59825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27330
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 425
telemt_me_reconnect_attempts_total 48899
telemt_me_reconnect_success_total 1808
telemt_me_reader_eof_total 1479
telemt_me_idle_close_by_peer_total 1478
telemt_me_route_drop_no_conn_total 4086007
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5611779
telemt_me_endpoint_quarantine_total 841
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 953
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31543
telemt_desync_full_logged_total 10752
telemt_desync_suppressed_total 20791
telemt_desync_frames_bucket_total{bucket="1_2"} 6275
telemt_desync_frames_bucket_total{bucket="3_10"} 12441
telemt_desync_frames_bucket_total{bucket="gt_10"} 12827
telemt_pool_swap_total 132
telemt_pool_force_close_total 3876
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 375
telemt_me_draining_writers_reap_progress_total 45442
telemt_me_writer_removed_unexpected_total 1530
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3761
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43254
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3435
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41566
telemt_me_writer_teardown_success_total{mode="normal"} 47015
telemt_me_writer_teardown_noop_total 45449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92464
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.684839
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92464
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 375
telemt_me_refill_failed_total 2736
telemt_me_writer_restored_same_endpoint_total 1604
telemt_me_writer_restored_fallback_total 26
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5604314
telemt_user_connections_current{user="hello"} 462
telemt_user_octets_from_client{user="hello"} 119035031216 (110.86 GB)
telemt_user_octets_to_client{user="hello"} 2167603112530 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 257
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 105552.1 (29h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1514144
telemt_connections_bad_total 36705
telemt_connections_current 388
telemt_connections_me_current 388
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 30433
telemt_upstream_connect_attempt_total 49646
telemt_upstream_connect_success_total 49490
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 49618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25935
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 787
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2237
telemt_me_reconnect_success_total 903
telemt_me_reader_eof_total 890
telemt_me_idle_close_by_peer_total 890
telemt_me_route_drop_no_conn_total 516426
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1345522
telemt_me_endpoint_quarantine_total 871
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 870
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
telemt_me_writers_active_current 44
telemt_desync_total 8856
telemt_desync_full_logged_total 2603
telemt_desync_suppressed_total 6253
telemt_desync_frames_bucket_total{bucket="1_2"} 2444
telemt_desync_frames_bucket_total{bucket="3_10"} 3392
telemt_desync_frames_bucket_total{bucket="gt_10"} 3020
telemt_pool_swap_total 114
telemt_pool_force_close_total 2926
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 165
telemt_me_draining_writers_reap_progress_total 41927
telemt_me_writer_removed_unexpected_total 858
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3231
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39593
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2838
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39001
telemt_me_writer_teardown_success_total{mode="normal"} 42824
telemt_me_writer_teardown_noop_total 41931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84755
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.238535
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84755
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 165
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 768
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 1341334
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 25873749317 (24.10 GB)
telemt_user_octets_to_client{user="hello"} 573575957771 (534.18 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 187749.5 (52h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13315333
telemt_connections_bad_total 1600698
telemt_connections_current 573
telemt_connections_me_current 573
telemt_handshake_timeouts_total 388536
telemt_upstream_connect_attempt_total 73528
telemt_upstream_connect_success_total 73180
telemt_upstream_connect_fail_total 212
telemt_upstream_connect_attempts_per_request{bucket="1"} 73392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36901
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 212
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2934
telemt_me_reconnect_success_total 1471
telemt_me_reader_eof_total 1455
telemt_me_idle_close_by_peer_total 1455
telemt_me_route_drop_no_conn_total 4481550
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10039952
telemt_me_endpoint_quarantine_total 1328
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1418
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
telemt_desync_total 42049
telemt_desync_full_logged_total 13734
telemt_desync_suppressed_total 28315
telemt_desync_frames_bucket_total{bucket="1_2"} 10168
telemt_desync_frames_bucket_total{bucket="3_10"} 15452
telemt_desync_frames_bucket_total{bucket="gt_10"} 16429
telemt_pool_swap_total 208
telemt_pool_force_close_total 5568
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 675
telemt_me_draining_writers_reap_progress_total 66432
telemt_me_writer_removed_unexpected_total 1393
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5254
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62623
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5394
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60864
telemt_me_writer_teardown_success_total{mode="normal"} 67877
telemt_me_writer_teardown_noop_total 66434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 131701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 133419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 133802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 134178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 134298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 134311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 134311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 134311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 134311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 134311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 134311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 134311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 134311
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.766136
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 134311
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 675
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1289
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 10006670
telemt_user_connections_current{user="hello"} 573
telemt_user_octets_from_client{user="hello"} 194721539972 (181.35 GB)
telemt_user_octets_to_client{user="hello"} 4436976282736 (4.04 TB)
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 187746.0 (52h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11624598
telemt_connections_bad_total 1353403
telemt_connections_current 547
telemt_connections_me_current 547
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 310922
telemt_upstream_connect_attempt_total 101067
telemt_upstream_connect_success_total 100179
telemt_upstream_connect_fail_total 680
telemt_upstream_connect_attempts_per_request{bucket="1"} 100859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42532
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 680
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10460
telemt_me_reconnect_success_total 2569
telemt_me_reader_eof_total 2380
telemt_me_idle_close_by_peer_total 2379
telemt_me_seq_mismatch_total 97
telemt_me_route_drop_no_conn_total 5648676
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8950098
telemt_me_endpoint_quarantine_total 1515
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 52
telemt_me_single_endpoint_outage_exit_total 52
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 1422
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_desync_total 41735
telemt_desync_full_logged_total 13435
telemt_desync_suppressed_total 28300
telemt_desync_frames_bucket_total{bucket="1_2"} 10759
telemt_desync_frames_bucket_total{bucket="3_10"} 15352
telemt_desync_frames_bucket_total{bucket="gt_10"} 15624
telemt_pool_swap_total 198
telemt_pool_force_close_total 5343
telemt_pool_stale_pick_total 372
telemt_me_writer_close_signal_drop_total 663
telemt_me_draining_writers_reap_progress_total 66525
telemt_me_writer_removed_unexpected_total 2423
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6615
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62416
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4872
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61182
telemt_me_writer_teardown_success_total{mode="normal"} 69031
telemt_me_writer_teardown_noop_total 66530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 132871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 134653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 135192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 135511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 135561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 135561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 135561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 135561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 135561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 135561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 135561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 135561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 135561
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.457072
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 135561
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 663
telemt_me_refill_failed_total 408
telemt_me_writer_restored_same_endpoint_total 2066
telemt_me_writer_restored_fallback_total 132
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 225
telemt_user_connections_total{user="hello"} 8954703
telemt_user_connections_current{user="hello"} 547
telemt_user_octets_from_client{user="hello"} 157314170300 (146.51 GB)
telemt_user_octets_to_client{user="hello"} 3486026948886 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 44
```