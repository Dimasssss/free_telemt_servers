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

# Server Metrics 2026-03-23 01:36:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 102600.9 (28h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3549830
telemt_connections_bad_total 318723
telemt_connections_current 858
telemt_connections_me_current 858
telemt_handshake_timeouts_total 111153
telemt_upstream_connect_attempt_total 38169
telemt_upstream_connect_success_total 38168
telemt_upstream_connect_attempts_per_request{bucket="1"} 38168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24799
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1405
telemt_me_reconnect_success_total 609
telemt_me_reader_eof_total 626
telemt_me_idle_close_by_peer_total 626
telemt_me_route_drop_no_conn_total 2988935
telemt_me_route_drop_channel_closed_total 1234
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2925771
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 719
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 799
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_me_writers_active_current 44
telemt_desync_total 12580
telemt_desync_full_logged_total 3956
telemt_desync_suppressed_total 8624
telemt_desync_frames_bucket_total{bucket="1_2"} 3375
telemt_desync_frames_bucket_total{bucket="3_10"} 4585
telemt_desync_frames_bucket_total{bucket="gt_10"} 4620
telemt_pool_swap_total 113
telemt_pool_force_close_total 3482
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 659
telemt_me_draining_writers_reap_progress_total 34949
telemt_me_writer_removed_unexpected_total 603
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2502
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32699
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3426
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31467
telemt_me_writer_teardown_success_total{mode="normal"} 35201
telemt_me_writer_teardown_noop_total 34960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70161
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 378.701267
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70161
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 659
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 545
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 2914813
telemt_user_connections_current{user="hello"} 858
telemt_user_octets_from_client{user="hello"} 41650599160 (38.79 GB)
telemt_user_octets_to_client{user="hello"} 798704726684 (743.85 GB)
telemt_user_unique_ips_current{user="hello"} 402
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 115966.8 (32h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4008068
telemt_connections_bad_total 369988
telemt_connections_current 382
telemt_connections_me_current 382
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100840
telemt_upstream_connect_attempt_total 72297
telemt_upstream_connect_success_total 71439
telemt_upstream_connect_fail_total 765
telemt_upstream_connect_attempts_per_request{bucket="1"} 72204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31448
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 765
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10144
telemt_me_reconnect_success_total 3640
telemt_me_reader_eof_total 3634
telemt_me_idle_close_by_peer_total 3634
telemt_me_route_drop_no_conn_total 3641749
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3183974
telemt_me_endpoint_quarantine_total 923
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 45
telemt_me_single_endpoint_outage_exit_total 45
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 905
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
telemt_desync_total 12980
telemt_desync_full_logged_total 7281
telemt_desync_suppressed_total 5699
telemt_desync_frames_bucket_total{bucket="1_2"} 2945
telemt_desync_frames_bucket_total{bucket="3_10"} 5092
telemt_desync_frames_bucket_total{bucket="gt_10"} 4943
telemt_pool_swap_total 108
telemt_pool_force_close_total 3095
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 254
telemt_me_draining_writers_reap_progress_total 47775
telemt_me_writer_removed_unexpected_total 3563
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6260
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45112
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2637
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44680
telemt_me_writer_teardown_success_total{mode="normal"} 51372
telemt_me_writer_teardown_noop_total 47776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99148
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.627904
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99148
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 254
telemt_me_refill_failed_total 252
telemt_me_writer_restored_same_endpoint_total 3248
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 3197275
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 43148707223 (40.19 GB)
telemt_user_octets_to_client{user="hello"} 793091896908 (738.62 GB)
telemt_user_msgs_from_client{user="hello"} 49657
telemt_user_msgs_to_client{user="hello"} 185005
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 190826.8 (53h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16357486
telemt_connections_bad_total 1656834
telemt_connections_current 1028
telemt_connections_me_current 1028
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 397799
telemt_upstream_connect_attempt_total 85602
telemt_upstream_connect_success_total 85496
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 85513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41894
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1720
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3015
telemt_me_reconnect_success_total 1589
telemt_me_reader_eof_total 1537
telemt_me_idle_close_by_peer_total 1535
telemt_me_route_drop_no_conn_total 14048400
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12987839
telemt_me_endpoint_quarantine_total 1270
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1436
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 4
telemt_desync_total 53897
telemt_desync_full_logged_total 17126
telemt_desync_suppressed_total 36771
telemt_desync_frames_bucket_total{bucket="1_2"} 12015
telemt_desync_frames_bucket_total{bucket="3_10"} 21041
telemt_desync_frames_bucket_total{bucket="gt_10"} 20841
telemt_pool_swap_total 206
telemt_pool_force_close_total 6740
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1064
telemt_me_draining_writers_reap_progress_total 64948
telemt_me_writer_removed_unexpected_total 1479
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5529
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60175
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6270
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58208
telemt_me_writer_teardown_success_total{mode="normal"} 65704
telemt_me_writer_teardown_noop_total 65001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 119543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 123209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 124985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 127377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 129044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 130095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 130666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 130696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 130697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 130701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 130703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 130705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 130705
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.794882
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 130705
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1064
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1376
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 12987860
telemt_user_connections_current{user="hello"} 1028
telemt_user_octets_from_client{user="hello"} 191368098861 (178.23 GB)
telemt_user_octets_to_client{user="hello"} 3493268003287 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 491
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 190828.1 (53h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11895861
telemt_connections_bad_total 1239034
telemt_connections_current 602
telemt_connections_me_current 602
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344653
telemt_upstream_connect_attempt_total 99960
telemt_upstream_connect_success_total 98632
telemt_upstream_connect_fail_total 875
telemt_upstream_connect_attempts_per_request{bucket="1"} 99507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41782
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3801
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 875
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4443
telemt_me_reconnect_success_total 1893
telemt_me_reader_eof_total 1760
telemt_me_idle_close_by_peer_total 1760
telemt_me_route_drop_no_conn_total 4558056
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8829457
telemt_me_endpoint_quarantine_total 1274
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1454
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 4
telemt_desync_total 38902
telemt_desync_full_logged_total 13091
telemt_desync_suppressed_total 25811
telemt_desync_frames_bucket_total{bucket="1_2"} 9638
telemt_desync_frames_bucket_total{bucket="3_10"} 14940
telemt_desync_frames_bucket_total{bucket="gt_10"} 14324
telemt_pool_swap_total 203
telemt_pool_force_close_total 6100
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 711
telemt_me_draining_writers_reap_progress_total 63167
telemt_me_writer_removed_unexpected_total 1789
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5616
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59197
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5588
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57067
telemt_me_writer_teardown_success_total{mode="normal"} 64813
telemt_me_writer_teardown_noop_total 63192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 121255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 124481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 125630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 126821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 127580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 127920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 127995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 127997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 128003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 128005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 128005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 128005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 128005
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.441753
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 128005
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 711
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1620
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 8767214
telemt_user_connections_current{user="hello"} 602
telemt_user_octets_from_client{user="hello"} 217915620876 (202.95 GB)
telemt_user_octets_to_client{user="hello"} 3965737865143 (3.61 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 284
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 190792.1 (52h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11069194
telemt_connections_bad_total 976728
telemt_connections_current 503
telemt_connections_me_current 503
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345629
telemt_upstream_connect_attempt_total 84260
telemt_upstream_connect_success_total 82701
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 82906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40217
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2031
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2363
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5762
telemt_me_reconnect_success_total 2384
telemt_me_reader_eof_total 2129
telemt_me_idle_close_by_peer_total 2128
telemt_me_route_drop_no_conn_total 5339165
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8366693
telemt_me_endpoint_quarantine_total 1340
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1413
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
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
telemt_desync_total 38202
telemt_desync_full_logged_total 12650
telemt_desync_suppressed_total 25552
telemt_desync_frames_bucket_total{bucket="1_2"} 9646
telemt_desync_frames_bucket_total{bucket="3_10"} 14622
telemt_desync_frames_bucket_total{bucket="gt_10"} 13934
telemt_pool_swap_total 199
telemt_pool_force_close_total 6000
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 741
telemt_me_draining_writers_reap_progress_total 63558
telemt_me_writer_removed_unexpected_total 2279
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6370
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59399
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5429
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57558
telemt_me_writer_teardown_success_total{mode="normal"} 65769
telemt_me_writer_teardown_noop_total 63629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 123565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 126280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 127243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 128316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 128917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 129131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 129259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 129290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 129298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 129311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 129344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 129347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 129398
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.802600
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 129398
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 741
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2074
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 8358648
telemt_user_connections_current{user="hello"} 503
telemt_user_octets_from_client{user="hello"} 192810068415 (179.57 GB)
telemt_user_octets_to_client{user="hello"} 3472941075481 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 61072.2 (16h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11272172
telemt_connections_bad_total 669224
telemt_connections_current 974
telemt_connections_me_current 974
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 275642
telemt_upstream_connect_attempt_total 58679
telemt_upstream_connect_success_total 55599
telemt_upstream_connect_fail_total 2033
telemt_upstream_connect_attempts_per_request{bucket="1"} 57632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19359
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6017
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2033
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7777
telemt_me_reconnect_success_total 1266
telemt_me_reader_eof_total 796
telemt_me_idle_close_by_peer_total 795
telemt_me_route_drop_no_conn_total 25293844
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9350487
telemt_me_endpoint_quarantine_total 454
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 489
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
telemt_me_writers_active_current 47
telemt_desync_total 16380
telemt_desync_full_logged_total 4475
telemt_desync_suppressed_total 11905
telemt_desync_frames_bucket_total{bucket="1_2"} 3109
telemt_desync_frames_bucket_total{bucket="3_10"} 6675
telemt_desync_frames_bucket_total{bucket="gt_10"} 6596
telemt_pool_swap_total 63
telemt_pool_force_close_total 2042
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 488
telemt_me_draining_writers_reap_progress_total 19225
telemt_me_writer_removed_unexpected_total 1152
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2596
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17725
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1735
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17183
telemt_me_writer_teardown_success_total{mode="normal"} 20321
telemt_me_writer_teardown_noop_total 19244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39565
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.909911
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39565
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 488
telemt_me_refill_failed_total 339
telemt_me_writer_restored_same_endpoint_total 813
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 326
telemt_user_connections_total{user="hello"} 9376353
telemt_user_connections_current{user="hello"} 974
telemt_user_octets_from_client{user="hello"} 87475268010 (81.47 GB)
telemt_user_octets_to_client{user="hello"} 614450980698 (572.25 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 412
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 190798.8 (52h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11017143
telemt_connections_bad_total 958119
telemt_connections_current 673
telemt_connections_me_current 673
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 242455
telemt_upstream_connect_attempt_total 113109
telemt_upstream_connect_success_total 111946
telemt_upstream_connect_fail_total 989
telemt_upstream_connect_attempts_per_request{bucket="1"} 112935
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43745
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 989
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72988
telemt_me_reconnect_success_total 3095
telemt_me_reader_eof_total 2786
telemt_me_idle_close_by_peer_total 2784
telemt_me_route_drop_no_conn_total 5265377
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8687360
telemt_me_endpoint_quarantine_total 1285
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 1440
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
telemt_me_writers_active_current 44
telemt_desync_total 46298
telemt_desync_full_logged_total 15868
telemt_desync_suppressed_total 30430
telemt_desync_frames_bucket_total{bucket="1_2"} 9406
telemt_desync_frames_bucket_total{bucket="3_10"} 17723
telemt_desync_frames_bucket_total{bucket="gt_10"} 19169
telemt_pool_swap_total 195
telemt_pool_force_close_total 5712
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 664
telemt_me_draining_writers_reap_progress_total 67667
telemt_me_writer_removed_unexpected_total 2813
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6888
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63629
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4963
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61955
telemt_me_writer_teardown_success_total{mode="normal"} 70517
telemt_me_writer_teardown_noop_total 67668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 136033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 137449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 137868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 138141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 138175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 138178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 138178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 138181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 138185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 138185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 138185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 138185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 138185
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.280628
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 138185
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 664
telemt_me_refill_failed_total 4302
telemt_me_writer_restored_same_endpoint_total 2611
telemt_me_writer_restored_fallback_total 52
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 8690320
telemt_user_connections_current{user="hello"} 673
telemt_user_octets_from_client{user="hello"} 194757877657 (181.38 GB)
telemt_user_octets_to_client{user="hello"} 3322140644760 (3.02 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 339
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 127635.0 (35h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11715709
telemt_connections_bad_total 482542
telemt_connections_current 462
telemt_connections_me_current 462
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4762245
telemt_upstream_connect_attempt_total 61552
telemt_upstream_connect_success_total 61103
telemt_upstream_connect_fail_total 437
telemt_upstream_connect_attempts_per_request{bucket="1"} 61540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28277
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 437
telemt_me_reconnect_attempts_total 49017
telemt_me_reconnect_success_total 1832
telemt_me_reader_eof_total 1504
telemt_me_idle_close_by_peer_total 1503
telemt_me_route_drop_no_conn_total 4095320
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5630577
telemt_me_endpoint_quarantine_total 865
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 980
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
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31698
telemt_desync_full_logged_total 10817
telemt_desync_suppressed_total 20881
telemt_desync_frames_bucket_total{bucket="1_2"} 6306
telemt_desync_frames_bucket_total{bucket="3_10"} 12503
telemt_desync_frames_bucket_total{bucket="gt_10"} 12889
telemt_pool_swap_total 135
telemt_pool_force_close_total 3924
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 377
telemt_me_draining_writers_reap_progress_total 47040
telemt_me_writer_removed_unexpected_total 1554
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3835
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44803
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3483
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43116
telemt_me_writer_teardown_success_total{mode="normal"} 48638
telemt_me_writer_teardown_noop_total 47047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95685
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.707446
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95685
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 377
telemt_me_refill_failed_total 2741
telemt_me_writer_restored_same_endpoint_total 1621
telemt_me_writer_restored_fallback_total 28
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5622727
telemt_user_connections_current{user="hello"} 462
telemt_user_octets_from_client{user="hello"} 120015134132 (111.77 GB)
telemt_user_octets_to_client{user="hello"} 2182953566078 (1.99 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 108606.0 (30h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1533652
telemt_connections_bad_total 36775
telemt_connections_current 435
telemt_connections_me_current 435
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 31199
telemt_upstream_connect_attempt_total 51260
telemt_upstream_connect_success_total 51100
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 51232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26632
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 792
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2264
telemt_me_reconnect_success_total 927
telemt_me_reader_eof_total 916
telemt_me_idle_close_by_peer_total 916
telemt_me_route_drop_no_conn_total 519462
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1363277
telemt_me_endpoint_quarantine_total 901
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 899
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
telemt_desync_total 9161
telemt_desync_full_logged_total 2654
telemt_desync_suppressed_total 6507
telemt_desync_frames_bucket_total{bucket="1_2"} 2628
telemt_desync_frames_bucket_total{bucket="3_10"} 3484
telemt_desync_frames_bucket_total{bucket="gt_10"} 3049
telemt_pool_swap_total 117
telemt_pool_force_close_total 2982
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 171
telemt_me_draining_writers_reap_progress_total 43393
telemt_me_writer_removed_unexpected_total 882
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3321
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40995
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2894
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40411
telemt_me_writer_teardown_success_total{mode="normal"} 44316
telemt_me_writer_teardown_noop_total 43397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87713
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.343220
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87713
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 171
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 790
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 1359084
telemt_user_connections_current{user="hello"} 435
telemt_user_octets_from_client{user="hello"} 26117131333 (24.32 GB)
telemt_user_octets_to_client{user="hello"} 577282686251 (537.64 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 190803.4 (53h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13339470
telemt_connections_bad_total 1605492
telemt_connections_current 605
telemt_connections_me_current 605
telemt_handshake_timeouts_total 389517
telemt_upstream_connect_attempt_total 75412
telemt_upstream_connect_success_total 75060
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 75276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37857
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3004
telemt_me_reconnect_success_total 1502
telemt_me_reader_eof_total 1487
telemt_me_idle_close_by_peer_total 1487
telemt_me_route_drop_no_conn_total 4484557
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10057596
telemt_me_endpoint_quarantine_total 1370
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1443
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_me_writers_active_current 45
telemt_desync_total 42146
telemt_desync_full_logged_total 13764
telemt_desync_suppressed_total 28382
telemt_desync_frames_bucket_total{bucket="1_2"} 10217
telemt_desync_frames_bucket_total{bucket="3_10"} 15486
telemt_desync_frames_bucket_total{bucket="gt_10"} 16443
telemt_pool_swap_total 211
telemt_pool_force_close_total 5611
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 679
telemt_me_draining_writers_reap_progress_total 68187
telemt_me_writer_removed_unexpected_total 1425
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5350
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64314
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5437
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62576
telemt_me_writer_teardown_success_total{mode="normal"} 69664
telemt_me_writer_teardown_noop_total 68189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 135238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 136961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 137344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 137720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 137840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 137853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 137853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 137853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 137853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 137853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 137853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 137853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 137853
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.795689
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 137853
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 679
telemt_me_refill_failed_total 81
telemt_me_writer_restored_same_endpoint_total 1319
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 10024299
telemt_user_connections_current{user="hello"} 605
telemt_user_octets_from_client{user="hello"} 194863466548 (181.48 GB)
telemt_user_octets_to_client{user="hello"} 4442868201948 (4.04 TB)
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 190799.8 (52h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11659029
telemt_connections_bad_total 1363008
telemt_connections_current 547
telemt_connections_me_current 547
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 311813
telemt_upstream_connect_attempt_total 102881
telemt_upstream_connect_success_total 101992
telemt_upstream_connect_fail_total 681
telemt_upstream_connect_attempts_per_request{bucket="1"} 102673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43401
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2068
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 681
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10492
telemt_me_reconnect_success_total 2599
telemt_me_reader_eof_total 2408
telemt_me_idle_close_by_peer_total 2407
telemt_me_seq_mismatch_total 100
telemt_me_route_drop_no_conn_total 5652080
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8969789
telemt_me_endpoint_quarantine_total 1548
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 52
telemt_me_single_endpoint_outage_exit_total 52
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 1445
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
telemt_me_writers_active_current 48
telemt_desync_total 41825
telemt_desync_full_logged_total 13465
telemt_desync_suppressed_total 28360
telemt_desync_frames_bucket_total{bucket="1_2"} 10806
telemt_desync_frames_bucket_total{bucket="3_10"} 15382
telemt_desync_frames_bucket_total{bucket="gt_10"} 15637
telemt_pool_swap_total 201
telemt_pool_force_close_total 5387
telemt_pool_stale_pick_total 372
telemt_me_writer_close_signal_drop_total 665
telemt_me_draining_writers_reap_progress_total 68194
telemt_me_writer_removed_unexpected_total 2452
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6710
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64021
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4916
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62807
telemt_me_writer_teardown_success_total{mode="normal"} 70731
telemt_me_writer_teardown_noop_total 68199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 136240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 138022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 138561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 138880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 138930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 138930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 138930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 138930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 138930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 138930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 138930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 138930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 138930
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.480630
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 138930
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 665
telemt_me_refill_failed_total 408
telemt_me_writer_restored_same_endpoint_total 2091
telemt_me_writer_restored_fallback_total 135
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 8974374
telemt_user_connections_current{user="hello"} 547
telemt_user_octets_from_client{user="hello"} 157462087784 (146.65 GB)
telemt_user_octets_to_client{user="hello"} 3492834582030 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 262
telemt_user_unique_ips_recent_window{user="hello"} 45
```