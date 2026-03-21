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

Можете писать свой ник в коментарии к переводу

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
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
- Оплачен до: 25 марта
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
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
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

# Server Metrics 2026-03-21 17:05:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 73766.4 (20h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2655903
telemt_connections_bad_total 157516
telemt_connections_current 1508
telemt_connections_me_current 1508
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 81995
telemt_upstream_connect_attempt_total 30857
telemt_upstream_connect_success_total 30725
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 30814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17955
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 36
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1751
telemt_me_reconnect_success_total 694
telemt_me_reader_eof_total 667
telemt_me_idle_close_by_peer_total 667
telemt_me_route_drop_no_conn_total 2251538
telemt_me_route_drop_channel_closed_total 715
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2123607
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 506
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 571
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
telemt_desync_total 8462
telemt_desync_full_logged_total 2944
telemt_desync_suppressed_total 5518
telemt_desync_frames_bucket_total{bucket="1_2"} 1838
telemt_desync_frames_bucket_total{bucket="3_10"} 3206
telemt_desync_frames_bucket_total{bucket="gt_10"} 3418
telemt_pool_swap_total 79
telemt_pool_force_close_total 2393
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 545
telemt_me_draining_writers_reap_progress_total 24896
telemt_me_writer_removed_unexpected_total 645
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2124
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23200
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2268
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 125
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22503
telemt_me_writer_teardown_success_total{mode="normal"} 25324
telemt_me_writer_teardown_noop_total 24904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50228
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 242.573797
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50228
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 545
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 595
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2124761
telemt_user_connections_current{user="hello"} 1508
telemt_user_octets_from_client{user="hello"} 30627566125 (28.52 GB)
telemt_user_octets_to_client{user="hello"} 523963805782 (487.98 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 557
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 269.2 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5445
telemt_connections_bad_total 148
telemt_connections_current 726
telemt_connections_me_current 726
telemt_handshake_timeouts_total 129
telemt_upstream_connect_attempt_total 182
telemt_upstream_connect_success_total 179
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 96
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 81
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 1
telemt_me_route_drop_no_conn_total 1808
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4731
telemt_me_endpoint_quarantine_total 5
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 19
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_me_draining_writers_reap_progress_total 95
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 94
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 95
telemt_me_writer_teardown_success_total{mode="normal"} 95
telemt_me_writer_teardown_noop_total 95
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 190
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.002011
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 190
telemt_user_connections_total{user="hello"} 4733
telemt_user_connections_current{user="hello"} 726
telemt_user_octets_from_client{user="hello"} 36087388 (34.42 MB)
telemt_user_octets_to_client{user="hello"} 1468153712 (1.37 GB)
telemt_user_unique_ips_current{user="hello"} 545
telemt_user_unique_ips_recent_window{user="hello"} 363
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 73764.0 (20h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5534737
telemt_connections_bad_total 458923
telemt_connections_current 3530
telemt_connections_me_current 3530
telemt_handshake_timeouts_total 181188
telemt_upstream_connect_attempt_total 26988
telemt_upstream_connect_success_total 26929
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 26935
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14709
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1204
telemt_me_reconnect_success_total 608
telemt_me_reader_eof_total 612
telemt_me_idle_close_by_peer_total 612
telemt_me_route_drop_no_conn_total 3455580
telemt_me_route_drop_channel_closed_total 48
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4561767
telemt_me_endpoint_quarantine_total 460
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 551
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
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
telemt_desync_total 18489
telemt_desync_full_logged_total 6232
telemt_desync_suppressed_total 12257
telemt_desync_frames_bucket_total{bucket="1_2"} 3909
telemt_desync_frames_bucket_total{bucket="3_10"} 7332
telemt_desync_frames_bucket_total{bucket="gt_10"} 7248
telemt_pool_swap_total 78
telemt_pool_force_close_total 2587
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 409
telemt_me_draining_writers_reap_progress_total 24531
telemt_me_writer_removed_unexpected_total 592
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2141
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22676
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 34
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2378
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 209
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21944
telemt_me_writer_teardown_success_total{mode="normal"} 24817
telemt_me_writer_teardown_noop_total 24565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49382
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.353920
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49382
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 409
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 548
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 4556312
telemt_user_connections_current{user="hello"} 3530
telemt_user_octets_from_client{user="hello"} 71768542640 (66.84 GB)
telemt_user_octets_to_client{user="hello"} 1436415527764 (1.31 TB)
telemt_user_unique_ips_current{user="hello"} 1443
telemt_user_unique_ips_recent_window{user="hello"} 529
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 73765.6 (20h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4435067
telemt_connections_bad_total 451736
telemt_connections_current 4312
telemt_connections_me_current 4312
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 149746
telemt_upstream_connect_attempt_total 31297
telemt_upstream_connect_success_total 31008
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 31150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14651
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 497
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1425
telemt_me_reconnect_success_total 626
telemt_me_reader_eof_total 591
telemt_me_idle_close_by_peer_total 591
telemt_me_route_drop_no_conn_total 1485051
telemt_me_route_drop_channel_closed_total 139
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3296883
telemt_me_endpoint_quarantine_total 461
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 560
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_desync_total 15798
telemt_desync_full_logged_total 5194
telemt_desync_suppressed_total 10604
telemt_desync_frames_bucket_total{bucket="1_2"} 3895
telemt_desync_frames_bucket_total{bucket="3_10"} 6144
telemt_desync_frames_bucket_total{bucket="gt_10"} 5759
telemt_pool_swap_total 80
telemt_pool_force_close_total 2375
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 248
telemt_me_draining_writers_reap_progress_total 23617
telemt_me_writer_removed_unexpected_total 572
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2033
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22116
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2210
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 165
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21242
telemt_me_writer_teardown_success_total{mode="normal"} 24149
telemt_me_writer_teardown_noop_total 23620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47769
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 28.954072
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47769
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 248
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 530
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 3295834
telemt_user_connections_current{user="hello"} 4312
telemt_user_octets_from_client{user="hello"} 78646368081 (73.25 GB)
telemt_user_octets_to_client{user="hello"} 1505732863311 (1.37 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1704
telemt_user_unique_ips_recent_window{user="hello"} 724
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 73729.1 (20h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4373375
telemt_connections_bad_total 431160
telemt_connections_current 4031
telemt_connections_me_current 4031
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 130877
telemt_upstream_connect_attempt_total 36539
telemt_upstream_connect_success_total 36292
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 36425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16011
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 298
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 871
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 1509
telemt_me_reconnect_success_total 681
telemt_me_reader_eof_total 627
telemt_me_idle_close_by_peer_total 627
telemt_me_route_drop_no_conn_total 1580710
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3274516
telemt_me_endpoint_quarantine_total 509
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 552
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
telemt_desync_total 15216
telemt_desync_full_logged_total 4984
telemt_desync_suppressed_total 10232
telemt_desync_frames_bucket_total{bucket="1_2"} 3766
telemt_desync_frames_bucket_total{bucket="3_10"} 5748
telemt_desync_frames_bucket_total{bucket="gt_10"} 5702
telemt_pool_swap_total 78
telemt_pool_force_close_total 2274
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 273
telemt_me_draining_writers_reap_progress_total 24979
telemt_me_writer_removed_unexpected_total 595
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2116
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23482
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2082
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 192
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22705
telemt_me_writer_teardown_success_total{mode="normal"} 25598
telemt_me_writer_teardown_noop_total 24986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50584
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.924447
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50584
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 273
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 588
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 3277600
telemt_user_connections_current{user="hello"} 4031
telemt_user_octets_from_client{user="hello"} 81319688237 (75.73 GB)
telemt_user_octets_to_client{user="hello"} 1502498606848 (1.37 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1537
telemt_user_unique_ips_recent_window{user="hello"} 678
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 73768.5 (20h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15204052
telemt_connections_bad_total 975932
telemt_connections_current 5867
telemt_connections_me_current 5867
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 439652
telemt_upstream_connect_attempt_total 147842
telemt_upstream_connect_success_total 132037
telemt_upstream_connect_fail_total 14627
telemt_upstream_connect_attempts_per_request{bucket="1"} 146664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 93054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29989
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 817
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14627
telemt_me_keepalive_timeout_total 262
telemt_me_reconnect_attempts_total 4141
telemt_me_reconnect_success_total 1543
telemt_me_reader_eof_total 1067
telemt_me_idle_close_by_peer_total 1066
telemt_me_route_drop_no_conn_total 30110751
telemt_me_route_drop_channel_closed_total 94
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12530359
telemt_me_endpoint_quarantine_total 549
telemt_me_single_endpoint_outage_enter_total 86
telemt_me_single_endpoint_outage_exit_total 86
telemt_me_single_endpoint_outage_reconnect_attempt_total 195
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 195
telemt_me_single_endpoint_shadow_rotate_total 577
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
telemt_me_writers_active_current 86
telemt_desync_total 21960
telemt_desync_full_logged_total 6763
telemt_desync_suppressed_total 15197
telemt_desync_frames_bucket_total{bucket="1_2"} 4814
telemt_desync_frames_bucket_total{bucket="3_10"} 9583
telemt_desync_frames_bucket_total{bucket="gt_10"} 7563
telemt_pool_swap_total 74
telemt_pool_force_close_total 2439
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 559
telemt_me_draining_writers_reap_progress_total 23316
telemt_me_writer_removed_unexpected_total 1476
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3115
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21439
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2056
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 383
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20877
telemt_me_writer_teardown_success_total{mode="normal"} 24554
telemt_me_writer_teardown_noop_total 23328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47882
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 179.505130
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47882
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 559
telemt_me_refill_failed_total 88
telemt_me_writer_restored_same_endpoint_total 1083
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 383
telemt_user_connections_total{user="hello"} 12628848
telemt_user_connections_current{user="hello"} 5867
telemt_user_octets_from_client{user="hello"} 101848976430 (94.85 GB)
telemt_user_octets_to_client{user="hello"} 850536958059 (792.12 GB)
telemt_user_msgs_from_client{user="hello"} 290173
telemt_user_msgs_to_client{user="hello"} 585212
telemt_user_unique_ips_current{user="hello"} 2120
telemt_user_unique_ips_recent_window{user="hello"} 1101
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 73736.2 (20h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4373146
telemt_connections_bad_total 461541
telemt_connections_current 4385
telemt_connections_me_current 4385
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 92889
telemt_upstream_connect_attempt_total 30552
telemt_upstream_connect_success_total 30158
telemt_upstream_connect_fail_total 325
telemt_upstream_connect_attempts_per_request{bucket="1"} 30483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15810
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 325
telemt_me_reconnect_attempts_total 3129
telemt_me_reconnect_success_total 1103
telemt_me_reader_eof_total 1087
telemt_me_idle_close_by_peer_total 1087
telemt_me_route_drop_no_conn_total 1875007
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3384020
telemt_me_endpoint_quarantine_total 449
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 546
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
telemt_me_writers_active_current 45
telemt_desync_total 16449
telemt_desync_full_logged_total 5717
telemt_desync_suppressed_total 10732
telemt_desync_frames_bucket_total{bucket="1_2"} 3196
telemt_desync_frames_bucket_total{bucket="3_10"} 6508
telemt_desync_frames_bucket_total{bucket="gt_10"} 6745
telemt_pool_swap_total 73
telemt_pool_force_close_total 2174
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 227
telemt_me_draining_writers_reap_progress_total 25623
telemt_me_writer_removed_unexpected_total 1056
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2577
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24138
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1862
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 312
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23449
telemt_me_writer_teardown_success_total{mode="normal"} 26715
telemt_me_writer_teardown_noop_total 25624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52339
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.881567
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52339
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 227
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 946
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 3366729
telemt_user_connections_current{user="hello"} 4385
telemt_user_octets_from_client{user="hello"} 88142876768 (82.09 GB)
telemt_user_octets_to_client{user="hello"} 1376653646666 (1.25 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1790
telemt_user_unique_ips_recent_window{user="hello"} 618
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 10571.8 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1603927
telemt_connections_bad_total 60415
telemt_connections_current 3914
telemt_connections_me_current 3914
telemt_handshake_timeouts_total 733183
telemt_upstream_connect_attempt_total 3499
telemt_upstream_connect_success_total 3438
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 3493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1871
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 461
telemt_me_reconnect_success_total 118
telemt_me_reader_eof_total 111
telemt_me_idle_close_by_peer_total 111
telemt_me_route_drop_no_conn_total 550336
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 739871
telemt_me_endpoint_quarantine_total 42
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 78
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
telemt_desync_total 4003
telemt_desync_full_logged_total 1281
telemt_desync_suppressed_total 2722
telemt_desync_frames_bucket_total{bucket="1_2"} 748
telemt_desync_frames_bucket_total{bucket="3_10"} 1500
telemt_desync_frames_bucket_total{bucket="gt_10"} 1755
telemt_pool_swap_total 10
telemt_pool_force_close_total 329
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 28
telemt_me_draining_writers_reap_progress_total 2986
telemt_me_writer_removed_unexpected_total 113
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 274
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2825
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 274
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2657
telemt_me_writer_teardown_success_total{mode="normal"} 3099
telemt_me_writer_teardown_noop_total 2986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 6004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 6032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 6085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 6085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 6085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 6085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 6085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 6085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 6085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 6085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 6085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 6085
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.249450
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 6085
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 28
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 99
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 738695
telemt_user_connections_current{user="hello"} 3914
telemt_user_octets_from_client{user="hello"} 17501304384 (16.30 GB)
telemt_user_octets_to_client{user="hello"} 281820976812 (262.47 GB)
telemt_user_unique_ips_current{user="hello"} 1531
telemt_user_unique_ips_recent_window{user="hello"} 568
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 71722.1 (19h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1452073
telemt_connections_bad_total 157791
telemt_connections_current 3485
telemt_connections_me_current 3485
telemt_handshake_timeouts_total 509048
telemt_upstream_connect_attempt_total 32912
telemt_upstream_connect_success_total 32901
telemt_upstream_connect_attempts_per_request{bucket="1"} 32901
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19366
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1375
telemt_me_reconnect_success_total 582
telemt_me_reader_eof_total 583
telemt_me_idle_close_by_peer_total 583
telemt_me_route_drop_no_conn_total 336919
telemt_me_route_drop_channel_closed_total 35
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 697411
telemt_me_endpoint_quarantine_total 627
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 596
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
telemt_me_writers_active_current 45
telemt_desync_total 4101
telemt_desync_full_logged_total 1465
telemt_desync_suppressed_total 2636
telemt_desync_frames_bucket_total{bucket="1_2"} 788
telemt_desync_frames_bucket_total{bucket="3_10"} 1472
telemt_desync_frames_bucket_total{bucket="gt_10"} 1841
telemt_pool_swap_total 78
telemt_pool_force_close_total 1860
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 121
telemt_me_draining_writers_reap_progress_total 29488
telemt_me_writer_removed_unexpected_total 550
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2246
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27811
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1828
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27628
telemt_me_writer_teardown_success_total{mode="normal"} 30057
telemt_me_writer_teardown_noop_total 29488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59545
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.406385
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59545
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 121
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 486
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 696886
telemt_user_connections_current{user="hello"} 3485
telemt_user_octets_from_client{user="hello"} 14619830675 (13.62 GB)
telemt_user_octets_to_client{user="hello"} 263784907625 (245.67 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 1445
telemt_user_unique_ips_recent_window{user="hello"} 563
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 73740.4 (20h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4924605
telemt_connections_bad_total 455040
telemt_connections_current 4801
telemt_connections_me_current 4801
telemt_handshake_timeouts_total 159454
telemt_upstream_connect_attempt_total 28832
telemt_upstream_connect_success_total 28713
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 28796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14491
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_reconnect_attempts_total 1233
telemt_me_reconnect_success_total 643
telemt_me_reader_eof_total 613
telemt_me_idle_close_by_peer_total 613
telemt_me_route_drop_no_conn_total 1496031
telemt_me_route_drop_channel_closed_total 40
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3876124
telemt_me_endpoint_quarantine_total 519
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 563
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
telemt_desync_total 15036
telemt_desync_full_logged_total 4989
telemt_desync_suppressed_total 10047
telemt_desync_frames_bucket_total{bucket="1_2"} 3577
telemt_desync_frames_bucket_total{bucket="3_10"} 5569
telemt_desync_frames_bucket_total{bucket="gt_10"} 5890
telemt_pool_swap_total 81
telemt_pool_force_close_total 2152
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 253
telemt_me_draining_writers_reap_progress_total 25858
telemt_me_writer_removed_unexpected_total 599
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2085
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24376
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2101
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23706
telemt_me_writer_teardown_success_total{mode="normal"} 26461
telemt_me_writer_teardown_noop_total 25859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52320
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.406757
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52320
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 253
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 572
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 3866238
telemt_user_connections_current{user="hello"} 4801
telemt_user_octets_from_client{user="hello"} 76480186956 (71.23 GB)
telemt_user_octets_to_client{user="hello"} 1805430148804 (1.64 TB)
telemt_user_unique_ips_current{user="hello"} 1772
telemt_user_unique_ips_recent_window{user="hello"} 672
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 73737.2 (20h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4313557
telemt_connections_bad_total 390878
telemt_connections_current 4229
telemt_connections_me_current 4229
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 132206
telemt_upstream_connect_attempt_total 45313
telemt_upstream_connect_success_total 44990
telemt_upstream_connect_fail_total 267
telemt_upstream_connect_attempts_per_request{bucket="1"} 45257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16321
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 605
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 267
telemt_me_reconnect_attempts_total 4133
telemt_me_reconnect_success_total 916
telemt_me_reader_eof_total 796
telemt_me_idle_close_by_peer_total 796
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 1581469
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3436851
telemt_me_endpoint_quarantine_total 608
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 556
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
telemt_desync_total 13468
telemt_desync_full_logged_total 4576
telemt_desync_suppressed_total 8892
telemt_desync_frames_bucket_total{bucket="1_2"} 3352
telemt_desync_frames_bucket_total{bucket="3_10"} 4999
telemt_desync_frames_bucket_total{bucket="gt_10"} 5117
telemt_pool_swap_total 79
telemt_pool_force_close_total 2095
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 245
telemt_me_draining_writers_reap_progress_total 25207
telemt_me_writer_removed_unexpected_total 809
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2495
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23554
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1919
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 176
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23112
telemt_me_writer_teardown_success_total{mode="normal"} 26049
telemt_me_writer_teardown_noop_total 25209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51258
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.241435
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51258
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 245
telemt_me_refill_failed_total 183
telemt_me_writer_restored_same_endpoint_total 705
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 3444505
telemt_user_connections_current{user="hello"} 4229
telemt_user_octets_from_client{user="hello"} 62646615865 (58.34 GB)
telemt_user_octets_to_client{user="hello"} 1451843344108 (1.32 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1663
telemt_user_unique_ips_recent_window{user="hello"} 592
```