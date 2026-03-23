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

# Server Metrics 2026-03-23 04:39:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 113586.5 (31h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3870170
telemt_connections_bad_total 380394
telemt_connections_current 927
telemt_connections_me_current 927
telemt_handshake_timeouts_total 129797
telemt_upstream_connect_attempt_total 42349
telemt_upstream_connect_success_total 42348
telemt_upstream_connect_attempts_per_request{bucket="1"} 42348
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27504
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 94
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1463
telemt_me_reconnect_success_total 661
telemt_me_reader_eof_total 678
telemt_me_idle_close_by_peer_total 678
telemt_me_route_drop_no_conn_total 3042169
telemt_me_route_drop_channel_closed_total 1248
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3151406
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 811
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 887
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
telemt_me_writers_active_current 43
telemt_desync_total 13497
telemt_desync_full_logged_total 4315
telemt_desync_suppressed_total 9182
telemt_desync_frames_bucket_total{bucket="1_2"} 3552
telemt_desync_frames_bucket_total{bucket="3_10"} 4963
telemt_desync_frames_bucket_total{bucket="gt_10"} 4982
telemt_pool_swap_total 126
telemt_pool_force_close_total 3849
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 697
telemt_me_draining_writers_reap_progress_total 38817
telemt_me_writer_removed_unexpected_total 654
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2777
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36311
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3785
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 64
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34968
telemt_me_writer_teardown_success_total{mode="normal"} 39088
telemt_me_writer_teardown_noop_total 38830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77918
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 389.072884
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77918
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 697
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 594
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 3139889
telemt_user_connections_current{user="hello"} 927
telemt_user_octets_from_client{user="hello"} 44099567716 (41.07 GB)
telemt_user_octets_to_client{user="hello"} 857735264140 (798.83 GB)
telemt_user_unique_ips_current{user="hello"} 312
telemt_user_unique_ips_recent_window{user="hello"} 286
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 126952.5 (35h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4101758
telemt_connections_bad_total 382133
telemt_connections_current 893
telemt_connections_me_current 893
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 103987
telemt_upstream_connect_attempt_total 79563
telemt_upstream_connect_success_total 78616
telemt_upstream_connect_fail_total 838
telemt_upstream_connect_attempts_per_request{bucket="1"} 79454
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34817
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 838
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10708
telemt_me_reconnect_success_total 3845
telemt_me_reader_eof_total 3826
telemt_me_idle_close_by_peer_total 3826
telemt_me_route_drop_no_conn_total 3659602
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3256177
telemt_me_endpoint_quarantine_total 1016
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 51
telemt_me_single_endpoint_outage_exit_total 51
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 997
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_me_writers_active_current 94
telemt_me_writers_warm_current 13
telemt_desync_total 13374
telemt_desync_full_logged_total 7529
telemt_desync_suppressed_total 5845
telemt_desync_frames_bucket_total{bucket="1_2"} 3048
telemt_desync_frames_bucket_total{bucket="3_10"} 5249
telemt_desync_frames_bucket_total{bucket="gt_10"} 5077
telemt_pool_swap_total 119
telemt_pool_force_close_total 3292
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 258
telemt_me_draining_writers_reap_progress_total 53126
telemt_me_writer_removed_unexpected_total 3749
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6740
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50175
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2834
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49834
telemt_me_writer_teardown_success_total{mode="normal"} 56915
telemt_me_writer_teardown_noop_total 53127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110042
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.767113
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110042
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 258
telemt_me_refill_failed_total 270
telemt_me_writer_restored_same_endpoint_total 3411
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 307
telemt_user_connections_total{user="hello"} 3270649
telemt_user_connections_current{user="hello"} 893
telemt_user_octets_from_client{user="hello"} 44039756879 (41.02 GB)
telemt_user_octets_to_client{user="hello"} 820423080297 (764.08 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 505
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 201812.5 (56h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16566159
telemt_connections_bad_total 1679485
telemt_connections_current 1113
telemt_connections_me_current 1113
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 403745
telemt_upstream_connect_attempt_total 90873
telemt_upstream_connect_success_total 90766
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 90783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44789
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1731
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3181
telemt_me_reconnect_success_total 1669
telemt_me_reader_eof_total 1625
telemt_me_idle_close_by_peer_total 1623
telemt_me_route_drop_no_conn_total 14090784
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13155859
telemt_me_endpoint_quarantine_total 1370
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1528
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
telemt_me_writers_active_current 43
telemt_desync_total 54765
telemt_desync_full_logged_total 17474
telemt_desync_suppressed_total 37291
telemt_desync_frames_bucket_total{bucket="1_2"} 12221
telemt_desync_frames_bucket_total{bucket="3_10"} 21438
telemt_desync_frames_bucket_total{bucket="gt_10"} 21106
telemt_pool_swap_total 219
telemt_pool_force_close_total 7046
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1091
telemt_me_draining_writers_reap_progress_total 69800
telemt_me_writer_removed_unexpected_total 1560
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5864
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64780
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6576
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62754
telemt_me_writer_teardown_success_total{mode="normal"} 70644
telemt_me_writer_teardown_noop_total 69853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 129179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 132978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 134771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 137169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 138836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 139887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 140458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 140488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 140489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 140493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 140495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 140497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 140497
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 318.470251
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 140497
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1091
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 1448
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 13155746
telemt_user_connections_current{user="hello"} 1113
telemt_user_octets_from_client{user="hello"} 199295877141 (185.61 GB)
telemt_user_octets_to_client{user="hello"} 3564297090315 (3.24 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 403
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 201814.2 (56h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12096868
telemt_connections_bad_total 1280974
telemt_connections_current 938
telemt_connections_me_current 938
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 349733
telemt_upstream_connect_attempt_total 105182
telemt_upstream_connect_success_total 103787
telemt_upstream_connect_fail_total 897
telemt_upstream_connect_attempts_per_request{bucket="1"} 104684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44697
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 196
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3807
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 897
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4641
telemt_me_reconnect_success_total 1992
telemt_me_reader_eof_total 1850
telemt_me_idle_close_by_peer_total 1850
telemt_me_route_drop_no_conn_total 4590688
telemt_me_route_drop_channel_closed_total 501
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8949620
telemt_me_endpoint_quarantine_total 1380
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1546
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_me_writers_active_current 42
telemt_desync_total 39341
telemt_desync_full_logged_total 13246
telemt_desync_suppressed_total 26095
telemt_desync_frames_bucket_total{bucket="1_2"} 9751
telemt_desync_frames_bucket_total{bucket="3_10"} 15122
telemt_desync_frames_bucket_total{bucket="gt_10"} 14468
telemt_pool_swap_total 216
telemt_pool_force_close_total 6365
telemt_pool_stale_pick_total 13
telemt_me_writer_close_signal_drop_total 717
telemt_me_draining_writers_reap_progress_total 67842
telemt_me_writer_removed_unexpected_total 1883
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5953
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63632
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5853
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61477
telemt_me_writer_teardown_success_total{mode="normal"} 69585
telemt_me_writer_teardown_noop_total 67867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 130681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 133928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 135077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 136268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 137027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 137367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 137442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 137444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 137450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 137452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 137452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 137452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 137452
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.600691
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 137452
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 717
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 1698
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 8887267
telemt_user_connections_current{user="hello"} 938
telemt_user_octets_from_client{user="hello"} 219182748856 (204.13 GB)
telemt_user_octets_to_client{user="hello"} 4008708150367 (3.65 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 386
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 201777.9 (56h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11237586
telemt_connections_bad_total 1018311
telemt_connections_current 967
telemt_connections_me_current 967
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 350628
telemt_upstream_connect_attempt_total 89621
telemt_upstream_connect_success_total 88048
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 88253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43258
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2064
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5872
telemt_me_reconnect_success_total 2462
telemt_me_reader_eof_total 2209
telemt_me_idle_close_by_peer_total 2208
telemt_me_route_drop_no_conn_total 5364219
telemt_me_route_drop_channel_closed_total 384
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8462798
telemt_me_endpoint_quarantine_total 1429
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1506
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 71
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
telemt_desync_total 38543
telemt_desync_full_logged_total 12789
telemt_desync_suppressed_total 25754
telemt_desync_frames_bucket_total{bucket="1_2"} 9738
telemt_desync_frames_bucket_total{bucket="3_10"} 14761
telemt_desync_frames_bucket_total{bucket="gt_10"} 14044
telemt_pool_swap_total 212
telemt_pool_force_close_total 6252
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 758
telemt_me_draining_writers_reap_progress_total 68429
telemt_me_writer_removed_unexpected_total 2355
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6698
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64022
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5681
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62177
telemt_me_writer_teardown_success_total{mode="normal"} 70720
telemt_me_writer_teardown_noop_total 68500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 133370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 136100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 137065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 138138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 138739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 138953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 139081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 139112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 139120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 139133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 139166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 139169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 139220
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.942073
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 139220
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 758
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 2144
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 8454678
telemt_user_connections_current{user="hello"} 967
telemt_user_octets_from_client{user="hello"} 193614941955 (180.32 GB)
telemt_user_octets_to_client{user="hello"} 3511344673445 (3.19 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 419
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 72058.0 (20h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11528461
telemt_connections_bad_total 676933
telemt_connections_current 1637
telemt_connections_me_current 1637
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 304579
telemt_upstream_connect_attempt_total 64817
telemt_upstream_connect_success_total 61396
telemt_upstream_connect_fail_total 2210
telemt_upstream_connect_attempts_per_request{bucket="1"} 63606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22242
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2210
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8270
telemt_me_reconnect_success_total 1464
telemt_me_reader_eof_total 940
telemt_me_idle_close_by_peer_total 939
telemt_me_route_drop_no_conn_total 25343622
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9553402
telemt_me_endpoint_quarantine_total 560
telemt_me_single_endpoint_outage_enter_total 102
telemt_me_single_endpoint_outage_exit_total 102
telemt_me_single_endpoint_outage_reconnect_attempt_total 200
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 200
telemt_me_single_endpoint_shadow_rotate_total 576
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 9
telemt_desync_total 17050
telemt_desync_full_logged_total 4717
telemt_desync_suppressed_total 12333
telemt_desync_frames_bucket_total{bucket="1_2"} 3290
telemt_desync_frames_bucket_total{bucket="3_10"} 6969
telemt_desync_frames_bucket_total{bucket="gt_10"} 6791
telemt_pool_swap_total 74
telemt_pool_force_close_total 2314
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 515
telemt_me_draining_writers_reap_progress_total 23791
telemt_me_writer_removed_unexpected_total 1334
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3056
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22020
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1992
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 322
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21477
telemt_me_writer_teardown_success_total{mode="normal"} 25076
telemt_me_writer_teardown_noop_total 23810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48886
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.630518
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48886
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 515
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 946
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 9579836
telemt_user_connections_current{user="hello"} 1637
telemt_user_octets_from_client{user="hello"} 89746399962 (83.58 GB)
telemt_user_octets_to_client{user="hello"} 688257377061 (640.99 GB)
telemt_user_msgs_from_client{user="hello"} 69581
telemt_user_msgs_to_client{user="hello"} 60103
telemt_user_unique_ips_current{user="hello"} 619
telemt_user_unique_ips_recent_window{user="hello"} 235
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 201784.5 (56h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11202286
telemt_connections_bad_total 988214
telemt_connections_current 1214
telemt_connections_me_current 1214
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 246818
telemt_upstream_connect_attempt_total 118499
telemt_upstream_connect_success_total 117266
telemt_upstream_connect_fail_total 1056
telemt_upstream_connect_attempts_per_request{bucket="1"} 118322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46740
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1375
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1056
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73466
telemt_me_reconnect_success_total 3236
telemt_me_reader_eof_total 2931
telemt_me_idle_close_by_peer_total 2928
telemt_me_route_drop_no_conn_total 5300068
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8819899
telemt_me_endpoint_quarantine_total 1372
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1532
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
telemt_me_writers_active_current 44
telemt_desync_total 47038
telemt_desync_full_logged_total 16163
telemt_desync_suppressed_total 30875
telemt_desync_frames_bucket_total{bucket="1_2"} 9550
telemt_desync_frames_bucket_total{bucket="3_10"} 18046
telemt_desync_frames_bucket_total{bucket="gt_10"} 19442
telemt_pool_swap_total 208
telemt_pool_force_close_total 5982
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 677
telemt_me_draining_writers_reap_progress_total 72456
telemt_me_writer_removed_unexpected_total 2949
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7239
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 68212
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5233
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 66474
telemt_me_writer_teardown_success_total{mode="normal"} 75451
telemt_me_writer_teardown_noop_total 72457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 145752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 147172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 147591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 147864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 147898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 147901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 147901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 147904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 147908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 147908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 147908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 147908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 147908
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.345584
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 147908
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 677
telemt_me_refill_failed_total 4320
telemt_me_writer_restored_same_endpoint_total 2726
telemt_me_writer_restored_fallback_total 54
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7369
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 8822679
telemt_user_connections_current{user="hello"} 1214
telemt_user_octets_from_client{user="hello"} 198124051953 (184.52 GB)
telemt_user_octets_to_client{user="hello"} 3374501138372 (3.07 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 515
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 138620.9 (38h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11955083
telemt_connections_bad_total 492341
telemt_connections_current 970
telemt_connections_me_current 970
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4825917
telemt_upstream_connect_attempt_total 67359
telemt_upstream_connect_success_total 66880
telemt_upstream_connect_fail_total 466
telemt_upstream_connect_attempts_per_request{bucket="1"} 67346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31379
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 466
telemt_me_reconnect_attempts_total 49242
telemt_me_reconnect_success_total 1941
telemt_me_reader_eof_total 1623
telemt_me_idle_close_by_peer_total 1622
telemt_me_route_drop_no_conn_total 4125065
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5745519
telemt_me_endpoint_quarantine_total 955
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1068
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32337
telemt_desync_full_logged_total 11046
telemt_desync_suppressed_total 21291
telemt_desync_frames_bucket_total{bucket="1_2"} 6488
telemt_desync_frames_bucket_total{bucket="3_10"} 12741
telemt_desync_frames_bucket_total{bucket="gt_10"} 13108
telemt_pool_swap_total 147
telemt_pool_force_close_total 4175
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 389
telemt_me_draining_writers_reap_progress_total 52307
telemt_me_writer_removed_unexpected_total 1663
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4144
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49880
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3731
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48132
telemt_me_writer_teardown_success_total{mode="normal"} 54024
telemt_me_writer_teardown_noop_total 52314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106338
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.774966
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106338
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 389
telemt_me_refill_failed_total 2748
telemt_me_writer_restored_same_endpoint_total 1717
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5737493
telemt_user_connections_current{user="hello"} 970
telemt_user_octets_from_client{user="hello"} 121254735572 (112.93 GB)
telemt_user_octets_to_client{user="hello"} 2236370973474 (2.03 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 411
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 119591.4 (33h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1641092
telemt_connections_bad_total 37197
telemt_connections_current 691
telemt_connections_me_current 691
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 34213
telemt_upstream_connect_attempt_total 56482
telemt_upstream_connect_success_total 56306
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 56454
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28904
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 826
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2452
telemt_me_reconnect_success_total 995
telemt_me_reader_eof_total 990
telemt_me_idle_close_by_peer_total 990
telemt_me_route_drop_no_conn_total 547085
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1458384
telemt_me_endpoint_quarantine_total 1013
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 988
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
telemt_desync_total 10148
telemt_desync_full_logged_total 2859
telemt_desync_suppressed_total 7289
telemt_desync_frames_bucket_total{bucket="1_2"} 3212
telemt_desync_frames_bucket_total{bucket="3_10"} 3818
telemt_desync_frames_bucket_total{bucket="gt_10"} 3118
telemt_pool_swap_total 129
telemt_pool_force_close_total 3247
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 176
telemt_me_draining_writers_reap_progress_total 48131
telemt_me_writer_removed_unexpected_total 953
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3630
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45498
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3159
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44884
telemt_me_writer_teardown_success_total{mode="normal"} 49128
telemt_me_writer_teardown_noop_total 48135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97263
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.564553
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97263
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 176
telemt_me_refill_failed_total 81
telemt_me_writer_restored_same_endpoint_total 852
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 1454035
telemt_user_connections_current{user="hello"} 691
telemt_user_octets_from_client{user="hello"} 27091479013 (25.23 GB)
telemt_user_octets_to_client{user="hello"} 604468282543 (562.95 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 201789.1 (56h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13493284
telemt_connections_bad_total 1629524
telemt_connections_current 1261
telemt_connections_me_current 1261
telemt_handshake_timeouts_total 394803
telemt_upstream_connect_attempt_total 81236
telemt_upstream_connect_success_total 80875
telemt_upstream_connect_fail_total 224
telemt_upstream_connect_attempts_per_request{bucket="1"} 81099
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40764
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 224
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3170
telemt_me_reconnect_success_total 1603
telemt_me_reader_eof_total 1594
telemt_me_idle_close_by_peer_total 1594
telemt_me_route_drop_no_conn_total 4512427
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10171749
telemt_me_endpoint_quarantine_total 1490
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1533
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
telemt_desync_total 42671
telemt_desync_full_logged_total 13933
telemt_desync_suppressed_total 28738
telemt_desync_frames_bucket_total{bucket="1_2"} 10389
telemt_desync_frames_bucket_total{bucket="3_10"} 15665
telemt_desync_frames_bucket_total{bucket="gt_10"} 16617
telemt_pool_swap_total 224
telemt_pool_force_close_total 5833
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 695
telemt_me_draining_writers_reap_progress_total 73529
telemt_me_writer_removed_unexpected_total 1524
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5675
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 69438
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5659
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 67696
telemt_me_writer_teardown_success_total{mode="normal"} 75113
telemt_me_writer_teardown_noop_total 73531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 146015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 147752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 148135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 148511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 148631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 148644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 148644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 148644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 148644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 148644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 148644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 148644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 148644
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.929321
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 148644
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 695
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1412
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 10138244
telemt_user_connections_current{user="hello"} 1261
telemt_user_octets_from_client{user="hello"} 196189173188 (182.72 GB)
telemt_user_octets_to_client{user="hello"} 4516418932020 (4.11 TB)
telemt_user_unique_ips_current{user="hello"} 472
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 201785.7 (56h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11811450
telemt_connections_bad_total 1383895
telemt_connections_current 1151
telemt_connections_me_current 1151
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 317919
telemt_upstream_connect_attempt_total 109088
telemt_upstream_connect_success_total 108146
telemt_upstream_connect_fail_total 734
telemt_upstream_connect_attempts_per_request{bucket="1"} 108880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46432
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 734
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 11005
telemt_me_reconnect_success_total 2737
telemt_me_reader_eof_total 2537
telemt_me_idle_close_by_peer_total 2536
telemt_me_seq_mismatch_total 106
telemt_me_route_drop_no_conn_total 5679418
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9088847
telemt_me_endpoint_quarantine_total 1663
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1540
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
telemt_me_writers_active_current 46
telemt_desync_total 42343
telemt_desync_full_logged_total 13629
telemt_desync_suppressed_total 28714
telemt_desync_frames_bucket_total{bucket="1_2"} 11007
telemt_desync_frames_bucket_total{bucket="3_10"} 15549
telemt_desync_frames_bucket_total{bucket="gt_10"} 15787
telemt_pool_swap_total 214
telemt_pool_force_close_total 5595
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 680
telemt_me_draining_writers_reap_progress_total 73861
telemt_me_writer_removed_unexpected_total 2573
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7061
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 69472
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5124
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 68266
telemt_me_writer_teardown_success_total{mode="normal"} 76533
telemt_me_writer_teardown_noop_total 73866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 147693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 149491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 150030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 150349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 150399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 150399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 150399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 150399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 150399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 150399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 150399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 150399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 150399
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.623390
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 150399
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 680
telemt_me_refill_failed_total 429
telemt_me_writer_restored_same_endpoint_total 2184
telemt_me_writer_restored_fallback_total 141
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 248
telemt_user_connections_total{user="hello"} 9093353
telemt_user_connections_current{user="hello"} 1151
telemt_user_octets_from_client{user="hello"} 158734463504 (147.83 GB)
telemt_user_octets_to_client{user="hello"} 3559453837586 (3.24 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 431
telemt_user_unique_ips_recent_window{user="hello"} 153
```