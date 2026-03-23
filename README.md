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

# Server Metrics 2026-03-23 04:44:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 113891.8 (31h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3880617
telemt_connections_bad_total 381619
telemt_connections_current 1370
telemt_connections_me_current 1370
telemt_handshake_timeouts_total 130307
telemt_upstream_connect_attempt_total 42452
telemt_upstream_connect_success_total 42451
telemt_upstream_connect_attempts_per_request{bucket="1"} 42451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27579
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 94
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1468
telemt_me_reconnect_success_total 666
telemt_me_reader_eof_total 684
telemt_me_idle_close_by_peer_total 684
telemt_me_route_drop_no_conn_total 3044116
telemt_me_route_drop_channel_closed_total 1252
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3159606
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 811
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 892
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
telemt_desync_total 13528
telemt_desync_full_logged_total 4327
telemt_desync_suppressed_total 9201
telemt_desync_frames_bucket_total{bucket="1_2"} 3553
telemt_desync_frames_bucket_total{bucket="3_10"} 4980
telemt_desync_frames_bucket_total{bucket="gt_10"} 4995
telemt_pool_swap_total 126
telemt_pool_force_close_total 3849
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 697
telemt_me_draining_writers_reap_progress_total 38891
telemt_me_writer_removed_unexpected_total 660
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2783
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36385
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3785
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 64
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35042
telemt_me_writer_teardown_success_total{mode="normal"} 39168
telemt_me_writer_teardown_noop_total 38904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78072
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 389.124842
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78072
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 697
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 599
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 3148070
telemt_user_connections_current{user="hello"} 1370
telemt_user_octets_from_client{user="hello"} 44166791912 (41.13 GB)
telemt_user_octets_to_client{user="hello"} 861425172892 (802.26 GB)
telemt_user_unique_ips_current{user="hello"} 559
telemt_user_unique_ips_recent_window{user="hello"} 219
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 127257.8 (35h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4105823
telemt_connections_bad_total 382604
telemt_connections_current 450
telemt_connections_me_current 450
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 104227
telemt_upstream_connect_attempt_total 79771
telemt_upstream_connect_success_total 78818
telemt_upstream_connect_fail_total 845
telemt_upstream_connect_attempts_per_request{bucket="1"} 79663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34929
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 845
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10762
telemt_me_reconnect_success_total 3862
telemt_me_reader_eof_total 3837
telemt_me_idle_close_by_peer_total 3837
telemt_me_route_drop_no_conn_total 3660492
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3259280
telemt_me_endpoint_quarantine_total 1037
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 52
telemt_me_single_endpoint_outage_exit_total 52
telemt_me_single_endpoint_outage_reconnect_attempt_total 53
telemt_me_single_endpoint_outage_reconnect_success_total 51
telemt_me_single_endpoint_quarantine_bypass_total 53
telemt_me_single_endpoint_shadow_rotate_total 1002
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
telemt_desync_total 13390
telemt_desync_full_logged_total 7539
telemt_desync_suppressed_total 5851
telemt_desync_frames_bucket_total{bucket="1_2"} 3052
telemt_desync_frames_bucket_total{bucket="3_10"} 5252
telemt_desync_frames_bucket_total{bucket="gt_10"} 5086
telemt_pool_swap_total 120
telemt_pool_force_close_total 3345
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 259
telemt_me_draining_writers_reap_progress_total 53379
telemt_me_writer_removed_unexpected_total 3760
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6773
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50405
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2863
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 482
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50034
telemt_me_writer_teardown_success_total{mode="normal"} 57178
telemt_me_writer_teardown_noop_total 53380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110558
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.819244
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110558
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 259
telemt_me_refill_failed_total 271
telemt_me_writer_restored_same_endpoint_total 3421
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 308
telemt_user_connections_total{user="hello"} 3273737
telemt_user_connections_current{user="hello"} 450
telemt_user_octets_from_client{user="hello"} 44135007767 (41.10 GB)
telemt_user_octets_to_client{user="hello"} 821445504285 (765.03 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 202117.6 (56h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16574596
telemt_connections_bad_total 1679911
telemt_connections_current 1526
telemt_connections_me_current 1526
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 404154
telemt_upstream_connect_attempt_total 90985
telemt_upstream_connect_success_total 90878
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 90895
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44849
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1731
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3183
telemt_me_reconnect_success_total 1672
telemt_me_reader_eof_total 1627
telemt_me_idle_close_by_peer_total 1625
telemt_me_route_drop_no_conn_total 14092291
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13163055
telemt_me_endpoint_quarantine_total 1370
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1530
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
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
telemt_desync_total 54796
telemt_desync_full_logged_total 17490
telemt_desync_suppressed_total 37306
telemt_desync_frames_bucket_total{bucket="1_2"} 12225
telemt_desync_frames_bucket_total{bucket="3_10"} 21451
telemt_desync_frames_bucket_total{bucket="gt_10"} 21120
telemt_pool_swap_total 219
telemt_pool_force_close_total 7046
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1091
telemt_me_draining_writers_reap_progress_total 69888
telemt_me_writer_removed_unexpected_total 1562
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5870
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64864
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6576
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62842
telemt_me_writer_teardown_success_total{mode="normal"} 70734
telemt_me_writer_teardown_noop_total 69941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 129357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 133156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 134949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 137347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 139014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 140065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 140636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 140666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 140667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 140671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 140673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 140675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 140675
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 318.472516
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 140675
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1091
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 1450
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 13162943
telemt_user_connections_current{user="hello"} 1526
telemt_user_octets_from_client{user="hello"} 199390883441 (185.70 GB)
telemt_user_octets_to_client{user="hello"} 3567117657415 (3.24 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 615
telemt_user_unique_ips_recent_window{user="hello"} 196
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 202123.5 (56h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12104777
telemt_connections_bad_total 1281261
telemt_connections_current 755
telemt_connections_me_current 755
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 350315
telemt_upstream_connect_attempt_total 105311
telemt_upstream_connect_success_total 103912
telemt_upstream_connect_fail_total 897
telemt_upstream_connect_attempts_per_request{bucket="1"} 104809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44765
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 197
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3807
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 897
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4648
telemt_me_reconnect_success_total 1998
telemt_me_reader_eof_total 1857
telemt_me_idle_close_by_peer_total 1857
telemt_me_route_drop_no_conn_total 4596052
telemt_me_route_drop_channel_closed_total 503
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8956312
telemt_me_endpoint_quarantine_total 1380
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1549
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_desync_total 39370
telemt_desync_full_logged_total 13252
telemt_desync_suppressed_total 26118
telemt_desync_frames_bucket_total{bucket="1_2"} 9757
telemt_desync_frames_bucket_total{bucket="3_10"} 15137
telemt_desync_frames_bucket_total{bucket="gt_10"} 14476
telemt_pool_swap_total 216
telemt_pool_force_close_total 6391
telemt_pool_stale_pick_total 13
telemt_me_writer_close_signal_drop_total 717
telemt_me_draining_writers_reap_progress_total 67957
telemt_me_writer_removed_unexpected_total 1889
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5966
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63741
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5879
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61566
telemt_me_writer_teardown_success_total{mode="normal"} 69707
telemt_me_writer_teardown_noop_total 67982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 130918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 134165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 135314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 136505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 137264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 137604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 137679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 137681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 137687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 137689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 137689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 137689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 137689
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.603554
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 137689
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 717
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 1704
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 8893955
telemt_user_connections_current{user="hello"} 755
telemt_user_octets_from_client{user="hello"} 219239665732 (204.18 GB)
telemt_user_octets_to_client{user="hello"} 4010032094951 (3.65 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 331
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 202083.1 (56h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11248603
telemt_connections_bad_total 1023034
telemt_connections_current 984
telemt_connections_me_current 984
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 351038
telemt_upstream_connect_attempt_total 89721
telemt_upstream_connect_success_total 88147
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 88352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43322
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2065
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5876
telemt_me_reconnect_success_total 2464
telemt_me_reader_eof_total 2211
telemt_me_idle_close_by_peer_total 2210
telemt_me_route_drop_no_conn_total 5365316
telemt_me_route_drop_channel_closed_total 384
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8467928
telemt_me_endpoint_quarantine_total 1429
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1508
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 71
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
telemt_desync_total 38551
telemt_desync_full_logged_total 12792
telemt_desync_suppressed_total 25759
telemt_desync_frames_bucket_total{bucket="1_2"} 9739
telemt_desync_frames_bucket_total{bucket="3_10"} 14765
telemt_desync_frames_bucket_total{bucket="gt_10"} 14047
telemt_pool_swap_total 212
telemt_pool_force_close_total 6278
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 759
telemt_me_draining_writers_reap_progress_total 68534
telemt_me_writer_removed_unexpected_total 2357
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6706
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64121
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5707
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62256
telemt_me_writer_teardown_success_total{mode="normal"} 70827
telemt_me_writer_teardown_noop_total 68605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 133581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 136312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 137277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 138350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 138951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 139165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 139293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 139324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 139332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 139345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 139378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 139381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 139432
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.945792
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 139432
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 759
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 2146
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 8459802
telemt_user_connections_current{user="hello"} 984
telemt_user_octets_from_client{user="hello"} 193654512435 (180.35 GB)
telemt_user_octets_to_client{user="hello"} 3512683206569 (3.19 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 396
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 72363.3 (20h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11541195
telemt_connections_bad_total 677922
telemt_connections_current 1602
telemt_connections_me_current 1602
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 305804
telemt_upstream_connect_attempt_total 64983
telemt_upstream_connect_success_total 61556
telemt_upstream_connect_fail_total 2213
telemt_upstream_connect_attempts_per_request{bucket="1"} 63769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22323
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6035
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2213
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8282
telemt_me_reconnect_success_total 1472
telemt_me_reader_eof_total 944
telemt_me_idle_close_by_peer_total 943
telemt_me_route_drop_no_conn_total 25346184
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9563206
telemt_me_endpoint_quarantine_total 572
telemt_me_single_endpoint_outage_enter_total 103
telemt_me_single_endpoint_outage_exit_total 103
telemt_me_single_endpoint_outage_reconnect_attempt_total 201
telemt_me_single_endpoint_outage_reconnect_success_total 51
telemt_me_single_endpoint_quarantine_bypass_total 201
telemt_me_single_endpoint_shadow_rotate_total 584
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 17072
telemt_desync_full_logged_total 4728
telemt_desync_suppressed_total 12344
telemt_desync_frames_bucket_total{bucket="1_2"} 3291
telemt_desync_frames_bucket_total{bucket="3_10"} 6982
telemt_desync_frames_bucket_total{bucket="gt_10"} 6799
telemt_pool_swap_total 75
telemt_pool_force_close_total 2341
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 518
telemt_me_draining_writers_reap_progress_total 23956
telemt_me_writer_removed_unexpected_total 1338
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3072
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22173
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2019
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 322
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21615
telemt_me_writer_teardown_success_total{mode="normal"} 25245
telemt_me_writer_teardown_noop_total 23975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49220
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.646623
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49220
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 518
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 950
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 9589621
telemt_user_connections_current{user="hello"} 1602
telemt_user_octets_from_client{user="hello"} 89946961890 (83.77 GB)
telemt_user_octets_to_client{user="hello"} 691214195261 (643.74 GB)
telemt_user_msgs_from_client{user="hello"} 69581
telemt_user_msgs_to_client{user="hello"} 60103
telemt_user_unique_ips_current{user="hello"} 622
telemt_user_unique_ips_recent_window{user="hello"} 228
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 202089.6 (56h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11211440
telemt_connections_bad_total 989937
telemt_connections_current 1376
telemt_connections_me_current 1376
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 247210
telemt_upstream_connect_attempt_total 118611
telemt_upstream_connect_success_total 117378
telemt_upstream_connect_fail_total 1056
telemt_upstream_connect_attempts_per_request{bucket="1"} 118434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46809
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1376
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1056
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73466
telemt_me_reconnect_success_total 3236
telemt_me_reader_eof_total 2931
telemt_me_idle_close_by_peer_total 2928
telemt_me_route_drop_no_conn_total 5301802
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8826376
telemt_me_endpoint_quarantine_total 1372
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1539
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_me_writers_active_current 48
telemt_desync_total 47076
telemt_desync_full_logged_total 16178
telemt_desync_suppressed_total 30898
telemt_desync_frames_bucket_total{bucket="1_2"} 9554
telemt_desync_frames_bucket_total{bucket="3_10"} 18061
telemt_desync_frames_bucket_total{bucket="gt_10"} 19461
telemt_pool_swap_total 208
telemt_pool_force_close_total 6007
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 680
telemt_me_draining_writers_reap_progress_total 72582
telemt_me_writer_removed_unexpected_total 2949
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7247
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 68330
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5258
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 66575
telemt_me_writer_teardown_success_total{mode="normal"} 75577
telemt_me_writer_teardown_noop_total 72583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 146004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 147424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 147843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 148116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 148150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 148153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 148153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 148156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 148160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 148160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 148160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 148160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 148160
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.353351
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 148160
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 680
telemt_me_refill_failed_total 4320
telemt_me_writer_restored_same_endpoint_total 2726
telemt_me_writer_restored_fallback_total 54
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7369
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 8829115
telemt_user_connections_current{user="hello"} 1376
telemt_user_octets_from_client{user="hello"} 198407655109 (184.78 GB)
telemt_user_octets_to_client{user="hello"} 3376156417188 (3.07 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 569
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 138925.9 (38h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11964980
telemt_connections_bad_total 492347
telemt_connections_current 878
telemt_connections_me_current 878
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4828907
telemt_upstream_connect_attempt_total 67543
telemt_upstream_connect_success_total 67063
telemt_upstream_connect_fail_total 467
telemt_upstream_connect_attempts_per_request{bucket="1"} 67530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31461
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 467
telemt_me_reconnect_attempts_total 49261
telemt_me_reconnect_success_total 1942
telemt_me_reader_eof_total 1624
telemt_me_idle_close_by_peer_total 1623
telemt_me_route_drop_no_conn_total 4126325
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5750935
telemt_me_endpoint_quarantine_total 960
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1073
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32353
telemt_desync_full_logged_total 11054
telemt_desync_suppressed_total 21299
telemt_desync_frames_bucket_total{bucket="1_2"} 6489
telemt_desync_frames_bucket_total{bucket="3_10"} 12745
telemt_desync_frames_bucket_total{bucket="gt_10"} 13119
telemt_pool_swap_total 148
telemt_pool_force_close_total 4202
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 390
telemt_me_draining_writers_reap_progress_total 52487
telemt_me_writer_removed_unexpected_total 1664
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4151
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50054
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3758
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48285
telemt_me_writer_teardown_success_total{mode="normal"} 54205
telemt_me_writer_teardown_noop_total 52494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106699
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.806730
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106699
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 390
telemt_me_refill_failed_total 2749
telemt_me_writer_restored_same_endpoint_total 1717
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5742906
telemt_user_connections_current{user="hello"} 878
telemt_user_octets_from_client{user="hello"} 121302550724 (112.97 GB)
telemt_user_octets_to_client{user="hello"} 2237421194102 (2.03 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 359
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 119896.6 (33h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1646013
telemt_connections_bad_total 37199
telemt_connections_current 560
telemt_connections_me_current 560
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 34285
telemt_upstream_connect_attempt_total 56644
telemt_upstream_connect_success_total 56468
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 56616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28976
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 828
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 2454
telemt_me_reconnect_success_total 997
telemt_me_reader_eof_total 992
telemt_me_idle_close_by_peer_total 992
telemt_me_route_drop_no_conn_total 549764
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1462977
telemt_me_endpoint_quarantine_total 1019
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 990
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
telemt_me_writers_active_current 45
telemt_desync_total 10187
telemt_desync_full_logged_total 2869
telemt_desync_suppressed_total 7318
telemt_desync_frames_bucket_total{bucket="1_2"} 3214
telemt_desync_frames_bucket_total{bucket="3_10"} 3841
telemt_desync_frames_bucket_total{bucket="gt_10"} 3132
telemt_pool_swap_total 130
telemt_pool_force_close_total 3276
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 176
telemt_me_draining_writers_reap_progress_total 48288
telemt_me_writer_removed_unexpected_total 955
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3651
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45636
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3188
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45012
telemt_me_writer_teardown_success_total{mode="normal"} 49287
telemt_me_writer_teardown_noop_total 48292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97579
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.569941
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97579
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 176
telemt_me_refill_failed_total 81
telemt_me_writer_restored_same_endpoint_total 854
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 1458604
telemt_user_connections_current{user="hello"} 560
telemt_user_octets_from_client{user="hello"} 27157992269 (25.29 GB)
telemt_user_octets_to_client{user="hello"} 605722730667 (564.12 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 202094.2 (56h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13500886
telemt_connections_bad_total 1630204
telemt_connections_current 1293
telemt_connections_me_current 1293
telemt_handshake_timeouts_total 395107
telemt_upstream_connect_attempt_total 81374
telemt_upstream_connect_success_total 81013
telemt_upstream_connect_fail_total 224
telemt_upstream_connect_attempts_per_request{bucket="1"} 81237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40079
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40829
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 224
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3173
telemt_me_reconnect_success_total 1605
telemt_me_reader_eof_total 1596
telemt_me_idle_close_by_peer_total 1596
telemt_me_route_drop_no_conn_total 4513960
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10178098
telemt_me_endpoint_quarantine_total 1490
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1536
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
telemt_me_writers_active_current 44
telemt_desync_total 42687
telemt_desync_full_logged_total 13937
telemt_desync_suppressed_total 28750
telemt_desync_frames_bucket_total{bucket="1_2"} 10394
telemt_desync_frames_bucket_total{bucket="3_10"} 15669
telemt_desync_frames_bucket_total{bucket="gt_10"} 16624
telemt_pool_swap_total 224
telemt_pool_force_close_total 5857
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 698
telemt_me_draining_writers_reap_progress_total 73664
telemt_me_writer_removed_unexpected_total 1526
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5680
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 69570
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5683
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 67807
telemt_me_writer_teardown_success_total{mode="normal"} 75250
telemt_me_writer_teardown_noop_total 73666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 146282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 148024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 148407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 148783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 148903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 148916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 148916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 148916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 148916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 148916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 148916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 148916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 148916
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.948472
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 148916
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 698
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1414
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 10144567
telemt_user_connections_current{user="hello"} 1293
telemt_user_octets_from_client{user="hello"} 196255909316 (182.78 GB)
telemt_user_octets_to_client{user="hello"} 4519513404244 (4.11 TB)
telemt_user_unique_ips_current{user="hello"} 477
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 202090.7 (56h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11818428
telemt_connections_bad_total 1384671
telemt_connections_current 1063
telemt_connections_me_current 1063
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 318204
telemt_upstream_connect_attempt_total 109224
telemt_upstream_connect_success_total 108282
telemt_upstream_connect_fail_total 734
telemt_upstream_connect_attempts_per_request{bucket="1"} 109016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46496
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 734
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 11010
telemt_me_reconnect_success_total 2741
telemt_me_reader_eof_total 2542
telemt_me_idle_close_by_peer_total 2541
telemt_me_seq_mismatch_total 106
telemt_me_route_drop_no_conn_total 5681002
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9094688
telemt_me_endpoint_quarantine_total 1663
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1542
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
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
telemt_desync_total 42361
telemt_desync_full_logged_total 13633
telemt_desync_suppressed_total 28728
telemt_desync_frames_bucket_total{bucket="1_2"} 11009
telemt_desync_frames_bucket_total{bucket="3_10"} 15552
telemt_desync_frames_bucket_total{bucket="gt_10"} 15800
telemt_pool_swap_total 214
telemt_pool_force_close_total 5618
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 682
telemt_me_draining_writers_reap_progress_total 73994
telemt_me_writer_removed_unexpected_total 2577
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7072
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 69599
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5147
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 68376
telemt_me_writer_teardown_success_total{mode="normal"} 76671
telemt_me_writer_teardown_noop_total 73999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 147955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 149762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 150301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 150620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 150670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 150670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 150670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 150670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 150670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 150670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 150670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 150670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 150670
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.650893
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 150670
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 682
telemt_me_refill_failed_total 429
telemt_me_writer_restored_same_endpoint_total 2188
telemt_me_writer_restored_fallback_total 141
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 248
telemt_user_connections_total{user="hello"} 9099159
telemt_user_connections_current{user="hello"} 1063
telemt_user_octets_from_client{user="hello"} 158782194780 (147.88 GB)
telemt_user_octets_to_client{user="hello"} 3562414330838 (3.24 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 412
telemt_user_unique_ips_recent_window{user="hello"} 157
```