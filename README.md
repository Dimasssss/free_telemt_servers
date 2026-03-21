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

# Server Metrics 2026-03-21 21:15:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 529.4 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11507
telemt_connections_bad_total 356
telemt_connections_current 929
telemt_connections_me_current 929
telemt_handshake_timeouts_total 448
telemt_upstream_connect_attempt_total 224
telemt_upstream_connect_success_total 224
telemt_upstream_connect_attempts_per_request{bucket="1"} 224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 91
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 132
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_me_route_drop_no_conn_total 2377
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9936
telemt_me_endpoint_quarantine_total 6
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 52
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_me_draining_writers_reap_progress_total 143
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 141
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 143
telemt_me_writer_teardown_success_total{mode="normal"} 143
telemt_me_writer_teardown_noop_total 143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 286
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.151829
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 286
telemt_user_connections_total{user="hello"} 9934
telemt_user_connections_current{user="hello"} 929
telemt_user_octets_from_client{user="hello"} 76064152 (72.54 MB)
telemt_user_octets_to_client{user="hello"} 2965043416 (2.76 GB)
telemt_user_unique_ips_current{user="hello"} 367
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 13895.4 (3h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 524689
telemt_connections_bad_total 24763
telemt_connections_current 693
telemt_connections_me_current 693
telemt_handshake_timeouts_total 18436
telemt_upstream_connect_attempt_total 5537
telemt_upstream_connect_success_total 5424
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 5524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2998
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_reconnect_attempts_total 473
telemt_me_reconnect_success_total 180
telemt_me_reader_eof_total 156
telemt_me_idle_close_by_peer_total 156
telemt_me_route_drop_no_conn_total 292058
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 425182
telemt_me_endpoint_quarantine_total 114
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 113
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 12
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
telemt_desync_total 1862
telemt_desync_full_logged_total 1060
telemt_desync_suppressed_total 802
telemt_desync_frames_bucket_total{bucket="1_2"} 381
telemt_desync_frames_bucket_total{bucket="3_10"} 714
telemt_desync_frames_bucket_total{bucket="gt_10"} 767
telemt_pool_swap_total 15
telemt_pool_force_close_total 447
telemt_me_writer_close_signal_drop_total 36
telemt_me_draining_writers_reap_progress_total 4814
telemt_me_writer_removed_unexpected_total 146
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 423
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4534
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 440
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4367
telemt_me_writer_teardown_success_total{mode="normal"} 4957
telemt_me_writer_teardown_noop_total 4814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 9389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 9610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 9673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 9757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 9769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 9771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 9771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 9771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 9771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 9771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 9771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 9771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 9771
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.882287
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 9771
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 36
telemt_me_refill_failed_total 16
telemt_me_writer_restored_same_endpoint_total 121
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 424655
telemt_user_connections_current{user="hello"} 693
telemt_user_octets_from_client{user="hello"} 6994533780 (6.51 GB)
telemt_user_octets_to_client{user="hello"} 135185201060 (125.90 GB)
telemt_user_unique_ips_current{user="hello"} 449
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 88755.0 (24h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7041281
telemt_connections_bad_total 543631
telemt_connections_current 2618
telemt_connections_me_current 2618
telemt_handshake_timeouts_total 220945
telemt_upstream_connect_attempt_total 31855
telemt_upstream_connect_success_total 31792
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 31799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17338
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1355
telemt_me_reconnect_success_total 678
telemt_me_reader_eof_total 688
telemt_me_idle_close_by_peer_total 688
telemt_me_route_drop_no_conn_total 4404735
telemt_me_route_drop_channel_closed_total 65
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5756469
telemt_me_endpoint_quarantine_total 554
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 658
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
telemt_desync_total 23900
telemt_desync_full_logged_total 7962
telemt_desync_suppressed_total 15938
telemt_desync_frames_bucket_total{bucket="1_2"} 4992
telemt_desync_frames_bucket_total{bucket="3_10"} 9459
telemt_desync_frames_bucket_total{bucket="gt_10"} 9449
telemt_pool_swap_total 95
telemt_pool_force_close_total 3221
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 523
telemt_me_draining_writers_reap_progress_total 29025
telemt_me_writer_removed_unexpected_total 661
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2477
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26801
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 37
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2988
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 233
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25804
telemt_me_writer_teardown_success_total{mode="normal"} 29278
telemt_me_writer_teardown_noop_total 29062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58340
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 143.351939
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58340
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 523
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 607
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 5749530
telemt_user_connections_current{user="hello"} 2618
telemt_user_octets_from_client{user="hello"} 99140215416 (92.33 GB)
telemt_user_octets_to_client{user="hello"} 1828790906088 (1.66 TB)
telemt_user_unique_ips_current{user="hello"} 1104
telemt_user_unique_ips_recent_window{user="hello"} 284
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 88757.4 (24h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5721636
telemt_connections_bad_total 559843
telemt_connections_current 2956
telemt_connections_me_current 2956
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 186824
telemt_upstream_connect_attempt_total 35887
telemt_upstream_connect_success_total 35565
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 35733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17970
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17026
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 542
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1681
telemt_me_reconnect_success_total 706
telemt_me_reader_eof_total 682
telemt_me_idle_close_by_peer_total 682
telemt_me_route_drop_no_conn_total 1975131
telemt_me_route_drop_channel_closed_total 226
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4274095
telemt_me_endpoint_quarantine_total 540
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 677
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
telemt_me_writers_active_current 45
telemt_desync_total 20511
telemt_desync_full_logged_total 6822
telemt_desync_suppressed_total 13689
telemt_desync_frames_bucket_total{bucket="1_2"} 5002
telemt_desync_frames_bucket_total{bucket="3_10"} 7930
telemt_desync_frames_bucket_total{bucket="gt_10"} 7579
telemt_pool_swap_total 97
telemt_pool_force_close_total 2949
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 333
telemt_me_draining_writers_reap_progress_total 27706
telemt_me_writer_removed_unexpected_total 659
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2395
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25901
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2750
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24757
telemt_me_writer_teardown_success_total{mode="normal"} 28296
telemt_me_writer_teardown_noop_total 27711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56007
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 45.699534
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56007
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 333
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 606
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 4265251
telemt_user_connections_current{user="hello"} 2956
telemt_user_octets_from_client{user="hello"} 129112557857 (120.25 GB)
telemt_user_octets_to_client{user="hello"} 1969671714267 (1.79 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1186
telemt_user_unique_ips_recent_window{user="hello"} 316
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 88720.4 (24h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5647243
telemt_connections_bad_total 509616
telemt_connections_current 2354
telemt_connections_me_current 2354
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 172953
telemt_upstream_connect_attempt_total 42328
telemt_upstream_connect_success_total 42049
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 42184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18476
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 338
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1041
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1739
telemt_me_reconnect_success_total 771
telemt_me_reader_eof_total 716
telemt_me_idle_close_by_peer_total 716
telemt_me_route_drop_no_conn_total 2029003
telemt_me_route_drop_channel_closed_total 104
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4258269
telemt_me_endpoint_quarantine_total 597
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 662
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
telemt_me_writers_active_current 43
telemt_desync_total 20252
telemt_desync_full_logged_total 6656
telemt_desync_suppressed_total 13596
telemt_desync_frames_bucket_total{bucket="1_2"} 5032
telemt_desync_frames_bucket_total{bucket="3_10"} 7663
telemt_desync_frames_bucket_total{bucket="gt_10"} 7557
telemt_pool_swap_total 95
telemt_pool_force_close_total 2823
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 338
telemt_me_draining_writers_reap_progress_total 29154
telemt_me_writer_removed_unexpected_total 685
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2488
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27355
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2610
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26331
telemt_me_writer_teardown_success_total{mode="normal"} 29843
telemt_me_writer_teardown_noop_total 29164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59007
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.406593
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59007
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 338
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 667
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 4260183
telemt_user_connections_current{user="hello"} 2354
telemt_user_octets_from_client{user="hello"} 124179024583 (115.65 GB)
telemt_user_octets_to_client{user="hello"} 1944634023139 (1.77 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 999
telemt_user_unique_ips_recent_window{user="hello"} 326
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 88760.1 (24h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19328427
telemt_connections_bad_total 1289237
telemt_connections_current 3444
telemt_connections_me_current 3444
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 541353
telemt_upstream_connect_attempt_total 181939
telemt_upstream_connect_success_total 164671
telemt_upstream_connect_fail_total 15808
telemt_upstream_connect_attempts_per_request{bucket="1"} 180479
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37248
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1152
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8851
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15808
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 59655
telemt_me_reconnect_success_total 1908
telemt_me_reader_eof_total 1260
telemt_me_idle_close_by_peer_total 1259
telemt_me_route_drop_no_conn_total 39209337
telemt_me_route_drop_channel_closed_total 116
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15865476
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 653
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 239
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 239
telemt_me_single_endpoint_shadow_rotate_total 690
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_desync_total 29935
telemt_desync_full_logged_total 8835
telemt_desync_suppressed_total 21100
telemt_desync_frames_bucket_total{bucket="1_2"} 6560
telemt_desync_frames_bucket_total{bucket="3_10"} 13275
telemt_desync_frames_bucket_total{bucket="gt_10"} 10100
telemt_pool_swap_total 90
telemt_pool_force_close_total 3027
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 694
telemt_me_draining_writers_reap_progress_total 27379
telemt_me_writer_removed_unexpected_total 1798
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3744
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25177
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2537
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 490
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24352
telemt_me_writer_teardown_success_total{mode="normal"} 28921
telemt_me_writer_teardown_noop_total 27405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56326
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 205.041363
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56326
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 694
telemt_me_refill_failed_total 3519
telemt_me_writer_restored_same_endpoint_total 1332
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14223
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 15990539
telemt_user_connections_current{user="hello"} 3444
telemt_user_octets_from_client{user="hello"} 159579297014 (148.62 GB)
telemt_user_octets_to_client{user="hello"} 994055079750 (925.79 GB)
telemt_user_msgs_from_client{user="hello"} 361669
telemt_user_msgs_to_client{user="hello"} 643484
telemt_user_unique_ips_current{user="hello"} 1366
telemt_user_unique_ips_recent_window{user="hello"} 435
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 88727.1 (24h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5525134
telemt_connections_bad_total 526807
telemt_connections_current 2799
telemt_connections_me_current 2799
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 114026
telemt_upstream_connect_attempt_total 45454
telemt_upstream_connect_success_total 44956
telemt_upstream_connect_fail_total 413
telemt_upstream_connect_attempts_per_request{bucket="1"} 45369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25879
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18749
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 327
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 413
telemt_me_reconnect_attempts_total 11119
telemt_me_reconnect_success_total 1282
telemt_me_reader_eof_total 1211
telemt_me_idle_close_by_peer_total 1211
telemt_me_route_drop_no_conn_total 2293100
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4295773
telemt_me_endpoint_quarantine_total 542
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 15
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 15
telemt_me_single_endpoint_shadow_rotate_total 661
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
telemt_desync_total 21426
telemt_desync_full_logged_total 7432
telemt_desync_suppressed_total 13994
telemt_desync_frames_bucket_total{bucket="1_2"} 4087
telemt_desync_frames_bucket_total{bucket="3_10"} 8332
telemt_desync_frames_bucket_total{bucket="gt_10"} 9007
telemt_pool_swap_total 90
telemt_pool_force_close_total 2670
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 336
telemt_me_draining_writers_reap_progress_total 29965
telemt_me_writer_removed_unexpected_total 1191
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3047
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28122
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2304
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 366
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27295
telemt_me_writer_teardown_success_total{mode="normal"} 31169
telemt_me_writer_teardown_noop_total 29966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61135
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.511070
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61135
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 336
telemt_me_refill_failed_total 593
telemt_me_writer_restored_same_endpoint_total 1083
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 1512
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4285319
telemt_user_connections_current{user="hello"} 2799
telemt_user_octets_from_client{user="hello"} 114467400713 (106.61 GB)
telemt_user_octets_to_client{user="hello"} 1740073481915 (1.58 TB)
telemt_user_msgs_from_client{user="hello"} 59697
telemt_user_msgs_to_client{user="hello"} 266554
telemt_user_unique_ips_current{user="hello"} 1141
telemt_user_unique_ips_recent_window{user="hello"} 322
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 25562.8 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3271126
telemt_connections_bad_total 120698
telemt_connections_current 2361
telemt_connections_me_current 2361
telemt_handshake_timeouts_total 1390027
telemt_upstream_connect_attempt_total 8374
telemt_upstream_connect_success_total 8266
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 8368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4530
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_reconnect_attempts_total 2219
telemt_me_reconnect_success_total 277
telemt_me_reader_eof_total 217
telemt_me_idle_close_by_peer_total 217
telemt_me_route_drop_no_conn_total 938065
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1563439
telemt_me_endpoint_quarantine_total 125
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 191
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 8682
telemt_desync_full_logged_total 2890
telemt_desync_suppressed_total 5792
telemt_desync_frames_bucket_total{bucket="1_2"} 1560
telemt_desync_frames_bucket_total{bucket="3_10"} 3307
telemt_desync_frames_bucket_total{bucket="gt_10"} 3815
telemt_pool_swap_total 27
telemt_pool_force_close_total 877
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 82
telemt_me_draining_writers_reap_progress_total 7296
telemt_me_writer_removed_unexpected_total 234
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 678
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6860
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 765
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 112
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6419
telemt_me_writer_teardown_success_total{mode="normal"} 7538
telemt_me_writer_teardown_noop_total 7297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 14512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 14694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 14743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 14835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 14835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 14835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 14835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 14835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 14835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 14835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 14835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 14835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 14835
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.353719
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 14835
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 82
telemt_me_refill_failed_total 119
telemt_me_writer_restored_same_endpoint_total 226
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 192
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1558909
telemt_user_connections_current{user="hello"} 2361
telemt_user_octets_from_client{user="hello"} 45848404496 (42.70 GB)
telemt_user_octets_to_client{user="hello"} 658654438380 (613.42 GB)
telemt_user_unique_ips_current{user="hello"} 1025
telemt_user_unique_ips_recent_window{user="hello"} 317
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 6534.4 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86014
telemt_connections_bad_total 838
telemt_connections_current 1447
telemt_connections_me_current 1447
telemt_handshake_timeouts_total 1849
telemt_upstream_connect_attempt_total 2820
telemt_upstream_connect_success_total 2812
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 2819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1148
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1624
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 65
telemt_me_reconnect_success_total 34
telemt_me_reader_eof_total 34
telemt_me_idle_close_by_peer_total 34
telemt_me_route_drop_no_conn_total 23213
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72978
telemt_me_endpoint_quarantine_total 46
telemt_me_single_endpoint_shadow_rotate_total 61
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 627
telemt_desync_full_logged_total 163
telemt_desync_suppressed_total 464
telemt_desync_frames_bucket_total{bucket="1_2"} 248
telemt_desync_frames_bucket_total{bucket="3_10"} 211
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 7
telemt_pool_force_close_total 191
telemt_me_writer_close_signal_drop_total 10
telemt_me_draining_writers_reap_progress_total 2445
telemt_me_writer_removed_unexpected_total 34
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 169
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2310
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 189
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2254
telemt_me_writer_teardown_success_total{mode="normal"} 2479
telemt_me_writer_teardown_noop_total 2445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4924
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.482813
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4924
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 10
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 31
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 72852
telemt_user_connections_current{user="hello"} 1447
telemt_user_octets_from_client{user="hello"} 1826556276 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 51409335460 (47.88 GB)
telemt_user_unique_ips_current{user="hello"} 612
telemt_user_unique_ips_recent_window{user="hello"} 282
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 88731.6 (24h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6564207
telemt_connections_bad_total 667111
telemt_connections_current 2930
telemt_connections_me_current 2930
telemt_handshake_timeouts_total 189354
telemt_upstream_connect_attempt_total 33580
telemt_upstream_connect_success_total 33445
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 33543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16834
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_reconnect_attempts_total 1408
telemt_me_reconnect_success_total 713
telemt_me_reader_eof_total 688
telemt_me_idle_close_by_peer_total 688
telemt_me_route_drop_no_conn_total 2021832
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 22
telemt_me_route_drop_queue_full_profile_total{profile="high"} 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5031045
telemt_me_endpoint_quarantine_total 591
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 676
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
telemt_me_writers_active_current 43
telemt_desync_total 19225
telemt_desync_full_logged_total 6419
telemt_desync_suppressed_total 12806
telemt_desync_frames_bucket_total{bucket="1_2"} 4682
telemt_desync_frames_bucket_total{bucket="3_10"} 7010
telemt_desync_frames_bucket_total{bucket="gt_10"} 7533
telemt_pool_swap_total 98
telemt_pool_force_close_total 2682
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 338
telemt_me_draining_writers_reap_progress_total 30157
telemt_me_writer_removed_unexpected_total 670
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2447
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28388
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2597
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27475
telemt_me_writer_teardown_success_total{mode="normal"} 30835
telemt_me_writer_teardown_noop_total 30159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60994
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.875886
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60994
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 338
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 637
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 5006795
telemt_user_connections_current{user="hello"} 2930
telemt_user_octets_from_client{user="hello"} 100344631148 (93.45 GB)
telemt_user_octets_to_client{user="hello"} 2345537672776 (2.13 TB)
telemt_user_unique_ips_current{user="hello"} 1141
telemt_user_unique_ips_recent_window{user="hello"} 320
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 88728.6 (24h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5579298
telemt_connections_bad_total 523842
telemt_connections_current 2939
telemt_connections_me_current 2939
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 159754
telemt_upstream_connect_attempt_total 49902
telemt_upstream_connect_success_total 49531
telemt_upstream_connect_fail_total 312
telemt_upstream_connect_attempts_per_request{bucket="1"} 49843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18705
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 312
telemt_me_reconnect_attempts_total 4531
telemt_me_reconnect_success_total 1001
telemt_me_reader_eof_total 887
telemt_me_idle_close_by_peer_total 887
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 2078217
telemt_me_route_drop_channel_closed_total 187
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4396028
telemt_me_endpoint_quarantine_total 699
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 673
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
telemt_me_writers_active_current 43
telemt_desync_total 17876
telemt_desync_full_logged_total 6029
telemt_desync_suppressed_total 11847
telemt_desync_frames_bucket_total{bucket="1_2"} 4419
telemt_desync_frames_bucket_total{bucket="3_10"} 6562
telemt_desync_frames_bucket_total{bucket="gt_10"} 6895
telemt_pool_swap_total 96
telemt_pool_force_close_total 2617
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 334
telemt_me_draining_writers_reap_progress_total 29309
telemt_me_writer_removed_unexpected_total 898
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2930
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27319
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2417
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 200
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26692
telemt_me_writer_teardown_success_total{mode="normal"} 30249
telemt_me_writer_teardown_noop_total 29313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59562
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.043019
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59562
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 334
telemt_me_refill_failed_total 201
telemt_me_writer_restored_same_endpoint_total 770
telemt_me_writer_restored_fallback_total 48
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 4399944
telemt_user_connections_current{user="hello"} 2939
telemt_user_octets_from_client{user="hello"} 84055265021 (78.28 GB)
telemt_user_octets_to_client{user="hello"} 1858416083620 (1.69 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1202
telemt_user_unique_ips_recent_window{user="hello"} 297
```