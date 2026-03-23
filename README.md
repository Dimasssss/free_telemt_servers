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

# Server Metrics 2026-03-23 05:10:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 115451.0 (32h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3999059
telemt_connections_bad_total 390467
telemt_connections_current 2008
telemt_connections_me_current 2008
telemt_handshake_timeouts_total 133716
telemt_upstream_connect_attempt_total 43004
telemt_upstream_connect_success_total 43003
telemt_upstream_connect_attempts_per_request{bucket="1"} 43003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27905
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 96
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 5
telemt_me_keepalive_timeout_total 594
telemt_me_reconnect_attempts_total 1495
telemt_me_reconnect_success_total 676
telemt_me_reader_eof_total 696
telemt_me_idle_close_by_peer_total 696
telemt_me_route_drop_no_conn_total 3089767
telemt_me_route_drop_channel_closed_total 1285
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3262151
telemt_me_writer_pick_total{mode="p2c",result="full"} 18
telemt_me_endpoint_quarantine_total 824
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 904
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
telemt_me_writers_active_current 46
telemt_desync_total 13822
telemt_desync_full_logged_total 4413
telemt_desync_suppressed_total 9409
telemt_desync_frames_bucket_total{bucket="1_2"} 3595
telemt_desync_frames_bucket_total{bucket="3_10"} 5117
telemt_desync_frames_bucket_total{bucket="gt_10"} 5110
telemt_pool_swap_total 128
telemt_pool_force_close_total 3915
telemt_pool_stale_pick_total 36
telemt_me_writer_close_signal_drop_total 725
telemt_me_draining_writers_reap_progress_total 39409
telemt_me_writer_removed_unexpected_total 670
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2823
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36859
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3850
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 65
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35494
telemt_me_writer_teardown_success_total{mode="normal"} 39682
telemt_me_writer_teardown_noop_total 39422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79104
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 417.225717
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79104
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 725
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 606
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 3249896
telemt_user_connections_current{user="hello"} 2008
telemt_user_octets_from_client{user="hello"} 44752654088 (41.68 GB)
telemt_user_octets_to_client{user="hello"} 876178566532 (816.00 GB)
telemt_user_unique_ips_current{user="hello"} 617
telemt_user_unique_ips_recent_window{user="hello"} 521
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 128817.3 (35h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4133187
telemt_connections_bad_total 384440
telemt_connections_current 728
telemt_connections_me_current 728
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 106157
telemt_upstream_connect_attempt_total 80489
telemt_upstream_connect_success_total 79522
telemt_upstream_connect_fail_total 858
telemt_upstream_connect_attempts_per_request{bucket="1"} 80380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35365
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 858
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10821
telemt_me_reconnect_success_total 3881
telemt_me_reader_eof_total 3858
telemt_me_idle_close_by_peer_total 3858
telemt_me_route_drop_no_conn_total 3665908
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3277241
telemt_me_endpoint_quarantine_total 1048
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 53
telemt_me_single_endpoint_outage_exit_total 53
telemt_me_single_endpoint_outage_reconnect_attempt_total 54
telemt_me_single_endpoint_outage_reconnect_success_total 52
telemt_me_single_endpoint_quarantine_bypass_total 54
telemt_me_single_endpoint_shadow_rotate_total 1012
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_me_writers_warm_current 38
telemt_desync_total 13492
telemt_desync_full_logged_total 7604
telemt_desync_suppressed_total 5888
telemt_desync_frames_bucket_total{bucket="1_2"} 3076
telemt_desync_frames_bucket_total{bucket="3_10"} 5294
telemt_desync_frames_bucket_total{bucket="gt_10"} 5122
telemt_pool_swap_total 121
telemt_pool_force_close_total 3368
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 260
telemt_me_draining_writers_reap_progress_total 53954
telemt_me_writer_removed_unexpected_total 3778
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6822
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50952
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2886
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 482
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50586
telemt_me_writer_teardown_success_total{mode="normal"} 57774
telemt_me_writer_teardown_noop_total 53955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111729
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.833422
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111729
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 260
telemt_me_refill_failed_total 273
telemt_me_writer_restored_same_endpoint_total 3437
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 310
telemt_user_connections_total{user="hello"} 3291687
telemt_user_connections_current{user="hello"} 728
telemt_user_octets_from_client{user="hello"} 44295648823 (41.25 GB)
telemt_user_octets_to_client{user="hello"} 826755830117 (769.98 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 438
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 203677.2 (56h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16626880
telemt_connections_bad_total 1685490
telemt_connections_current 1343
telemt_connections_me_current 1343
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 406328
telemt_upstream_connect_attempt_total 91606
telemt_upstream_connect_success_total 91499
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 91516
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45192
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1731
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3206
telemt_me_reconnect_success_total 1678
telemt_me_reader_eof_total 1636
telemt_me_idle_close_by_peer_total 1634
telemt_me_route_drop_no_conn_total 14105259
telemt_me_route_drop_channel_closed_total 146
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13205800
telemt_me_endpoint_quarantine_total 1381
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1544
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
telemt_desync_total 55037
telemt_desync_full_logged_total 17586
telemt_desync_suppressed_total 37451
telemt_desync_frames_bucket_total{bucket="1_2"} 12279
telemt_desync_frames_bucket_total{bucket="3_10"} 21552
telemt_desync_frames_bucket_total{bucket="gt_10"} 21206
telemt_pool_swap_total 221
telemt_pool_force_close_total 7095
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1100
telemt_me_draining_writers_reap_progress_total 70468
telemt_me_writer_removed_unexpected_total 1569
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5915
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65408
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6625
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63373
telemt_me_writer_teardown_success_total{mode="normal"} 71323
telemt_me_writer_teardown_noop_total 70522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 130460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 134292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 136106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 138517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 140184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 141235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 141806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 141836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 141837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 141841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 141843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 141845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 141845
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 318.933648
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 141845
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1100
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1456
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 13205660
telemt_user_connections_current{user="hello"} 1343
telemt_user_octets_from_client{user="hello"} 199899648653 (186.17 GB)
telemt_user_octets_to_client{user="hello"} 3581378538255 (3.26 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 532
telemt_user_unique_ips_recent_window{user="hello"} 267
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 203678.5 (56h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12145664
telemt_connections_bad_total 1287827
telemt_connections_current 1054
telemt_connections_me_current 1054
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 351654
telemt_upstream_connect_attempt_total 105949
telemt_upstream_connect_success_total 104537
telemt_upstream_connect_fail_total 899
telemt_upstream_connect_attempts_per_request{bucket="1"} 105436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45088
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3808
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 899
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4675
telemt_me_reconnect_success_total 2008
telemt_me_reader_eof_total 1869
telemt_me_idle_close_by_peer_total 1869
telemt_me_route_drop_no_conn_total 4604660
telemt_me_route_drop_channel_closed_total 503
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8984598
telemt_me_endpoint_quarantine_total 1391
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1560
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
telemt_desync_total 39461
telemt_desync_full_logged_total 13299
telemt_desync_suppressed_total 26162
telemt_desync_frames_bucket_total{bucket="1_2"} 9783
telemt_desync_frames_bucket_total{bucket="3_10"} 15168
telemt_desync_frames_bucket_total{bucket="gt_10"} 14510
telemt_pool_swap_total 218
telemt_pool_force_close_total 6440
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 722
telemt_me_draining_writers_reap_progress_total 68537
telemt_me_writer_removed_unexpected_total 1900
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6014
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64285
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5928
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62097
telemt_me_writer_teardown_success_total{mode="normal"} 70299
telemt_me_writer_teardown_noop_total 68562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 132074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 135331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 136486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 137677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 138436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 138776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 138851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 138853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 138859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 138861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 138861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 138861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 138861
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.681652
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 138861
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 722
telemt_me_refill_failed_total 143
telemt_me_writer_restored_same_endpoint_total 1714
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 8922176
telemt_user_connections_current{user="hello"} 1054
telemt_user_octets_from_client{user="hello"} 219611606000 (204.53 GB)
telemt_user_octets_to_client{user="hello"} 4023057502163 (3.66 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 417
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 203642.5 (56h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11290463
telemt_connections_bad_total 1032763
telemt_connections_current 904
telemt_connections_me_current 904
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 354569
telemt_upstream_connect_attempt_total 90371
telemt_upstream_connect_success_total 88795
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 89000
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43682
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2068
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5886
telemt_me_reconnect_success_total 2472
telemt_me_reader_eof_total 2218
telemt_me_idle_close_by_peer_total 2217
telemt_me_route_drop_no_conn_total 5373051
telemt_me_route_drop_channel_closed_total 384
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8493614
telemt_me_endpoint_quarantine_total 1442
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1522
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 72
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
telemt_desync_total 38630
telemt_desync_full_logged_total 12824
telemt_desync_suppressed_total 25806
telemt_desync_frames_bucket_total{bucket="1_2"} 9759
telemt_desync_frames_bucket_total{bucket="3_10"} 14792
telemt_desync_frames_bucket_total{bucket="gt_10"} 14079
telemt_pool_swap_total 214
telemt_pool_force_close_total 6328
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 762
telemt_me_draining_writers_reap_progress_total 69144
telemt_me_writer_removed_unexpected_total 2364
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6750
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64694
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5757
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62816
telemt_me_writer_teardown_success_total{mode="normal"} 71444
telemt_me_writer_teardown_noop_total 69215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 134806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 137539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 138504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 139577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 140178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 140392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 140520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 140551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 140559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 140572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 140605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 140608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 140659
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.966292
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 140659
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 762
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 2153
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 8485439
telemt_user_connections_current{user="hello"} 904
telemt_user_octets_from_client{user="hello"} 194014454191 (180.69 GB)
telemt_user_octets_to_client{user="hello"} 3521579318461 (3.20 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 343
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 73922.7 (20h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11609405
telemt_connections_bad_total 686772
telemt_connections_current 1701
telemt_connections_me_current 1701
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 311783
telemt_upstream_connect_attempt_total 66962
telemt_upstream_connect_success_total 63397
telemt_upstream_connect_fail_total 2311
telemt_upstream_connect_attempts_per_request{bucket="1"} 65708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22736
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6051
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2311
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8377
telemt_me_reconnect_success_total 1527
telemt_me_reader_eof_total 955
telemt_me_idle_close_by_peer_total 954
telemt_me_route_drop_no_conn_total 25362840
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9611430
telemt_me_endpoint_quarantine_total 580
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 213
telemt_me_single_endpoint_outage_reconnect_success_total 56
telemt_me_single_endpoint_quarantine_bypass_total 213
telemt_me_single_endpoint_shadow_rotate_total 596
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_me_writers_active_current 41
telemt_me_writers_warm_current 5
telemt_desync_total 17190
telemt_desync_full_logged_total 4779
telemt_desync_suppressed_total 12411
telemt_desync_frames_bucket_total{bucket="1_2"} 3327
telemt_desync_frames_bucket_total{bucket="3_10"} 7021
telemt_desync_frames_bucket_total{bucket="gt_10"} 6842
telemt_pool_swap_total 76
telemt_pool_force_close_total 2368
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 529
telemt_me_draining_writers_reap_progress_total 24444
telemt_me_writer_removed_unexpected_total 1412
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3179
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22629
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2042
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 326
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22076
telemt_me_writer_teardown_success_total{mode="normal"} 25808
telemt_me_writer_teardown_noop_total 24463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50271
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.842438
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50271
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 529
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 972
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 422
telemt_user_connections_total{user="hello"} 9639015
telemt_user_connections_current{user="hello"} 1701
telemt_user_octets_from_client{user="hello"} 90398387207 (84.19 GB)
telemt_user_octets_to_client{user="hello"} 710988091549 (662.16 GB)
telemt_user_msgs_from_client{user="hello"} 71666
telemt_user_msgs_to_client{user="hello"} 62721
telemt_user_unique_ips_current{user="hello"} 579
telemt_user_unique_ips_recent_window{user="hello"} 680
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 203649.2 (56h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11254302
telemt_connections_bad_total 991052
telemt_connections_current 1110
telemt_connections_me_current 1110
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 250877
telemt_upstream_connect_attempt_total 119303
telemt_upstream_connect_success_total 118061
telemt_upstream_connect_fail_total 1065
telemt_upstream_connect_attempts_per_request{bucket="1"} 119126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47177
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1376
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1065
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73523
telemt_me_reconnect_success_total 3255
telemt_me_reader_eof_total 2950
telemt_me_idle_close_by_peer_total 2947
telemt_me_route_drop_no_conn_total 5312802
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8860188
telemt_me_endpoint_quarantine_total 1387
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1548
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
telemt_desync_total 47203
telemt_desync_full_logged_total 16228
telemt_desync_suppressed_total 30975
telemt_desync_frames_bucket_total{bucket="1_2"} 9588
telemt_desync_frames_bucket_total{bucket="3_10"} 18102
telemt_desync_frames_bucket_total{bucket="gt_10"} 19513
telemt_pool_swap_total 210
telemt_pool_force_close_total 6050
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 682
telemt_me_draining_writers_reap_progress_total 73198
telemt_me_writer_removed_unexpected_total 2967
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7298
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 68914
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5301
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 67148
telemt_me_writer_teardown_success_total{mode="normal"} 76212
telemt_me_writer_teardown_noop_total 73199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 147255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 148675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 149094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 149367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 149401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 149404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 149404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 149407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 149411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 149411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 149411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 149411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 149411
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.359083
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 149411
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 682
telemt_me_refill_failed_total 4322
telemt_me_writer_restored_same_endpoint_total 2740
telemt_me_writer_restored_fallback_total 56
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7369
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 8862844
telemt_user_connections_current{user="hello"} 1110
telemt_user_octets_from_client{user="hello"} 198857018457 (185.20 GB)
telemt_user_octets_to_client{user="hello"} 3388424076716 (3.08 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 428
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 140485.5 (39h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12029965
telemt_connections_bad_total 493070
telemt_connections_current 1265
telemt_connections_me_current 1265
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4857321
telemt_upstream_connect_attempt_total 68203
telemt_upstream_connect_success_total 67714
telemt_upstream_connect_fail_total 476
telemt_upstream_connect_attempts_per_request{bucket="1"} 68190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31818
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 476
telemt_me_reconnect_attempts_total 49314
telemt_me_reconnect_success_total 1955
telemt_me_reader_eof_total 1638
telemt_me_idle_close_by_peer_total 1637
telemt_me_route_drop_no_conn_total 4135963
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5778855
telemt_me_endpoint_quarantine_total 969
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1083
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
telemt_me_writers_warm_current 30
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32485
telemt_desync_full_logged_total 11104
telemt_desync_suppressed_total 21381
telemt_desync_frames_bucket_total{bucket="1_2"} 6518
telemt_desync_frames_bucket_total{bucket="3_10"} 12793
telemt_desync_frames_bucket_total{bucket="gt_10"} 13174
telemt_pool_swap_total 149
telemt_pool_force_close_total 4221
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 391
telemt_me_draining_writers_reap_progress_total 53047
telemt_me_writer_removed_unexpected_total 1677
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4190
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50589
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3777
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48826
telemt_me_writer_teardown_success_total{mode="normal"} 54779
telemt_me_writer_teardown_noop_total 53054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107833
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.810900
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107833
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 391
telemt_me_refill_failed_total 2751
telemt_me_writer_restored_same_endpoint_total 1728
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5770803
telemt_user_connections_current{user="hello"} 1265
telemt_user_octets_from_client{user="hello"} 121550780988 (113.20 GB)
telemt_user_octets_to_client{user="hello"} 2246731898282 (2.04 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 532
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 121456.3 (33h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1673546
telemt_connections_bad_total 37277
telemt_connections_current 885
telemt_connections_me_current 885
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 35137
telemt_upstream_connect_attempt_total 57242
telemt_upstream_connect_success_total 57063
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 57214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 837
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 2503
telemt_me_reconnect_success_total 1008
telemt_me_reader_eof_total 1004
telemt_me_idle_close_by_peer_total 1004
telemt_me_route_drop_no_conn_total 559274
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1487415
telemt_me_endpoint_quarantine_total 1027
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1002
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
telemt_desync_total 10290
telemt_desync_full_logged_total 2908
telemt_desync_suppressed_total 7382
telemt_desync_frames_bucket_total{bucket="1_2"} 3237
telemt_desync_frames_bucket_total{bucket="3_10"} 3869
telemt_desync_frames_bucket_total{bucket="gt_10"} 3184
telemt_pool_swap_total 131
telemt_pool_force_close_total 3302
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 177
telemt_me_draining_writers_reap_progress_total 48800
telemt_me_writer_removed_unexpected_total 967
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3683
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46128
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3214
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45498
telemt_me_writer_teardown_success_total{mode="normal"} 49811
telemt_me_writer_teardown_noop_total 48804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98615
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.670915
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98615
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 177
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 863
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 1483016
telemt_user_connections_current{user="hello"} 885
telemt_user_octets_from_client{user="hello"} 27427072909 (25.54 GB)
telemt_user_octets_to_client{user="hello"} 611529778051 (569.53 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 330
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 203653.8 (56h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13538602
telemt_connections_bad_total 1634853
telemt_connections_current 1214
telemt_connections_me_current 1214
telemt_handshake_timeouts_total 396328
telemt_upstream_connect_attempt_total 82155
telemt_upstream_connect_success_total 81790
telemt_upstream_connect_fail_total 228
telemt_upstream_connect_attempts_per_request{bucket="1"} 82018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41218
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 228
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3220
telemt_me_reconnect_success_total 1617
telemt_me_reader_eof_total 1608
telemt_me_idle_close_by_peer_total 1608
telemt_me_route_drop_no_conn_total 4524335
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 44
telemt_me_route_drop_queue_full_profile_total{profile="high"} 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10208207
telemt_me_endpoint_quarantine_total 1510
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1549
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
telemt_me_writers_active_current 44
telemt_desync_total 42862
telemt_desync_full_logged_total 13983
telemt_desync_suppressed_total 28879
telemt_desync_frames_bucket_total{bucket="1_2"} 10448
telemt_desync_frames_bucket_total{bucket="3_10"} 15726
telemt_desync_frames_bucket_total{bucket="gt_10"} 16688
telemt_pool_swap_total 226
telemt_pool_force_close_total 5901
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 700
telemt_me_draining_writers_reap_progress_total 74378
telemt_me_writer_removed_unexpected_total 1538
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5719
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 70257
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5727
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 68477
telemt_me_writer_teardown_success_total{mode="normal"} 75976
telemt_me_writer_teardown_noop_total 74380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 147715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 149464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 149847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 150223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 150343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 150356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 150356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 150356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 150356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 150356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 150356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 150356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 150356
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.984940
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 150356
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 700
telemt_me_refill_failed_total 86
telemt_me_writer_restored_same_endpoint_total 1423
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 10174637
telemt_user_connections_current{user="hello"} 1214
telemt_user_octets_from_client{user="hello"} 196788567460 (183.27 GB)
telemt_user_octets_to_client{user="hello"} 4535531750804 (4.13 TB)
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 203650.4 (56h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11856332
telemt_connections_bad_total 1386695
telemt_connections_current 1177
telemt_connections_me_current 1177
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 319278
telemt_upstream_connect_attempt_total 109978
telemt_upstream_connect_success_total 109030
telemt_upstream_connect_fail_total 738
telemt_upstream_connect_attempts_per_request{bucket="1"} 109768
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59207
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46839
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 738
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 11072
telemt_me_reconnect_success_total 2757
telemt_me_reader_eof_total 2561
telemt_me_idle_close_by_peer_total 2560
telemt_me_seq_mismatch_total 107
telemt_me_route_drop_no_conn_total 5690969
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9128571
telemt_me_endpoint_quarantine_total 1685
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1554
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
telemt_me_writers_active_current 44
telemt_desync_total 42487
telemt_desync_full_logged_total 13675
telemt_desync_suppressed_total 28812
telemt_desync_frames_bucket_total{bucket="1_2"} 11041
telemt_desync_frames_bucket_total{bucket="3_10"} 15602
telemt_desync_frames_bucket_total{bucket="gt_10"} 15844
telemt_pool_swap_total 216
telemt_pool_force_close_total 5657
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 684
telemt_me_draining_writers_reap_progress_total 74686
telemt_me_writer_removed_unexpected_total 2596
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7130
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 70253
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5186
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 69029
telemt_me_writer_teardown_success_total{mode="normal"} 77383
telemt_me_writer_teardown_noop_total 74691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 149332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 151151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 151705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 152024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 152074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 152074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 152074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 152074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 152074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 152074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 152074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 152074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 152074
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.831714
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 152074
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 684
telemt_me_refill_failed_total 432
telemt_me_writer_restored_same_endpoint_total 2199
telemt_me_writer_restored_fallback_total 142
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 9133013
telemt_user_connections_current{user="hello"} 1177
telemt_user_octets_from_client{user="hello"} 159147701252 (148.22 GB)
telemt_user_octets_to_client{user="hello"} 3575582376294 (3.25 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 438
telemt_user_unique_ips_recent_window{user="hello"} 185
```