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

# Server Metrics 2026-03-21 13:41:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 61531.2 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2034363
telemt_connections_bad_total 101687
telemt_connections_current 1670
telemt_connections_me_current 1670
telemt_handshake_timeouts_total 73190
telemt_upstream_connect_attempt_total 23627
telemt_upstream_connect_success_total 23512
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 23589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15109
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 1336
telemt_me_reconnect_success_total 554
telemt_me_reader_eof_total 528
telemt_me_idle_close_by_peer_total 528
telemt_me_route_drop_no_conn_total 1505572
telemt_me_route_drop_channel_closed_total 506
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1607054
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_endpoint_quarantine_total 436
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 487
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
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
telemt_desync_total 6345
telemt_desync_full_logged_total 2187
telemt_desync_suppressed_total 4158
telemt_desync_frames_bucket_total{bucket="1_2"} 1419
telemt_desync_frames_bucket_total{bucket="3_10"} 2401
telemt_desync_frames_bucket_total{bucket="gt_10"} 2525
telemt_pool_swap_total 67
telemt_pool_force_close_total 2004
telemt_pool_stale_pick_total 14
telemt_me_writer_close_signal_drop_total 381
telemt_me_draining_writers_reap_progress_total 21137
telemt_me_writer_removed_unexpected_total 507
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1745
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19721
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1929
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 75
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19133
telemt_me_writer_teardown_success_total{mode="normal"} 21466
telemt_me_writer_teardown_noop_total 21142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42608
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 168.447819
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42608
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 381
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 478
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 1605820
telemt_user_connections_current{user="hello"} 1670
telemt_user_octets_from_client{user="hello"} 23971128991 (22.32 GB)
telemt_user_octets_to_client{user="hello"} 419656935131 (390.84 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 598
telemt_user_unique_ips_recent_window{user="hello"} 258
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 1085.1 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135345
telemt_connections_bad_total 5035
telemt_connections_current 2462
telemt_connections_me_current 2462
telemt_handshake_timeouts_total 3868
telemt_upstream_connect_attempt_total 423
telemt_upstream_connect_success_total 421
telemt_upstream_connect_attempts_per_request{bucket="1"} 421
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 218
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 41
telemt_me_reconnect_success_total 10
telemt_me_reader_eof_total 6
telemt_me_idle_close_by_peer_total 6
telemt_me_route_drop_no_conn_total 66270
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116976
telemt_me_endpoint_quarantine_total 14
telemt_me_single_endpoint_shadow_rotate_total 15
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
telemt_desync_total 439
telemt_desync_full_logged_total 150
telemt_desync_suppressed_total 289
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 164
telemt_desync_frames_bucket_total{bucket="gt_10"} 194
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 293
telemt_me_writer_removed_unexpected_total 6
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 284
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 293
telemt_me_writer_teardown_success_total{mode="normal"} 299
telemt_me_writer_teardown_noop_total 293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 592
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.022386
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 592
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 116881
telemt_user_connections_current{user="hello"} 2462
telemt_user_octets_from_client{user="hello"} 2673002600 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 25238830760 (23.51 GB)
telemt_user_unique_ips_current{user="hello"} 1116
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 61528.9 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4050805
telemt_connections_bad_total 392352
telemt_connections_current 4750
telemt_connections_me_current 4750
telemt_handshake_timeouts_total 155616
telemt_upstream_connect_attempt_total 23374
telemt_upstream_connect_success_total 23335
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 23340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12686
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 898
telemt_me_reconnect_success_total 526
telemt_me_reader_eof_total 523
telemt_me_idle_close_by_peer_total 523
telemt_me_route_drop_no_conn_total 2048797
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3270729
telemt_me_endpoint_quarantine_total 392
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 469
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 17
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
telemt_desync_total 13764
telemt_desync_full_logged_total 4667
telemt_desync_suppressed_total 9097
telemt_desync_frames_bucket_total{bucket="1_2"} 2906
telemt_desync_frames_bucket_total{bucket="3_10"} 5419
telemt_desync_frames_bucket_total{bucket="gt_10"} 5439
telemt_pool_swap_total 65
telemt_pool_force_close_total 2078
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 319
telemt_me_draining_writers_reap_progress_total 21227
telemt_me_writer_removed_unexpected_total 506
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1843
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19699
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1895
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 183
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19149
telemt_me_writer_teardown_success_total{mode="normal"} 21542
telemt_me_writer_teardown_noop_total 21245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42787
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 65.969045
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42787
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 319
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 478
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 3266617
telemt_user_connections_current{user="hello"} 4750
telemt_user_octets_from_client{user="hello"} 53973369964 (50.27 GB)
telemt_user_octets_to_client{user="hello"} 1123105358348 (1.02 TB)
telemt_user_unique_ips_current{user="hello"} 1757
telemt_user_unique_ips_recent_window{user="hello"} 563
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 61530.1 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3311057
telemt_connections_bad_total 367810
telemt_connections_current 3973
telemt_connections_me_current 3973
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 124642
telemt_upstream_connect_attempt_total 27753
telemt_upstream_connect_success_total 27478
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 27613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12694
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 477
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1163
telemt_me_reconnect_success_total 548
telemt_me_reader_eof_total 512
telemt_me_idle_close_by_peer_total 512
telemt_me_route_drop_no_conn_total 1029830
telemt_me_route_drop_channel_closed_total 82
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2390756
telemt_me_endpoint_quarantine_total 401
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 473
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
telemt_desync_total 10899
telemt_desync_full_logged_total 3696
telemt_desync_suppressed_total 7203
telemt_desync_frames_bucket_total{bucket="1_2"} 2729
telemt_desync_frames_bucket_total{bucket="3_10"} 4194
telemt_desync_frames_bucket_total{bucket="gt_10"} 3976
telemt_pool_swap_total 67
telemt_pool_force_close_total 1906
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 173
telemt_me_draining_writers_reap_progress_total 20434
telemt_me_writer_removed_unexpected_total 498
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1736
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19201
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1780
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 126
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18528
telemt_me_writer_teardown_success_total{mode="normal"} 20937
telemt_me_writer_teardown_noop_total 20435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41372
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.981791
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41372
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 173
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 462
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 2391464
telemt_user_connections_current{user="hello"} 3973
telemt_user_octets_from_client{user="hello"} 44809910237 (41.73 GB)
telemt_user_octets_to_client{user="hello"} 1125245986459 (1.02 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1423
telemt_user_unique_ips_recent_window{user="hello"} 498
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 61494.1 (17h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3218611
telemt_connections_bad_total 343347
telemt_connections_current 3494
telemt_connections_me_current 3494
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 93220
telemt_upstream_connect_attempt_total 32918
telemt_upstream_connect_success_total 32691
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 32824
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14032
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 845
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1278
telemt_me_reconnect_success_total 618
telemt_me_reader_eof_total 562
telemt_me_idle_close_by_peer_total 562
telemt_me_route_drop_no_conn_total 990599
telemt_me_route_drop_channel_closed_total 31
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2356999
telemt_me_endpoint_quarantine_total 449
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 461
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
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
telemt_desync_total 10980
telemt_desync_full_logged_total 3655
telemt_desync_suppressed_total 7325
telemt_desync_frames_bucket_total{bucket="1_2"} 2785
telemt_desync_frames_bucket_total{bucket="3_10"} 4138
telemt_desync_frames_bucket_total{bucket="gt_10"} 4057
telemt_pool_swap_total 65
telemt_pool_force_close_total 1845
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 214
telemt_me_draining_writers_reap_progress_total 21755
telemt_me_writer_removed_unexpected_total 535
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1836
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20489
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1678
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 167
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19910
telemt_me_writer_teardown_success_total{mode="normal"} 22325
telemt_me_writer_teardown_noop_total 21760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44085
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.323774
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44085
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 214
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 539
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2361728
telemt_user_connections_current{user="hello"} 3494
telemt_user_octets_from_client{user="hello"} 51863826633 (48.30 GB)
telemt_user_octets_to_client{user="hello"} 1122138154892 (1.02 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1315
telemt_user_unique_ips_recent_window{user="hello"} 466
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 61533.5 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10953887
telemt_connections_bad_total 746062
telemt_connections_current 5100
telemt_connections_me_current 5100
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 346954
telemt_upstream_connect_attempt_total 110944
telemt_upstream_connect_success_total 101799
telemt_upstream_connect_fail_total 8199
telemt_upstream_connect_attempts_per_request{bucket="1"} 109998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23980
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 527
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5007
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8199
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 3610
telemt_me_reconnect_success_total 1260
telemt_me_reader_eof_total 916
telemt_me_idle_close_by_peer_total 915
telemt_me_route_drop_no_conn_total 20249043
telemt_me_route_drop_channel_closed_total 70
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8975048
telemt_me_endpoint_quarantine_total 464
telemt_me_single_endpoint_outage_enter_total 67
telemt_me_single_endpoint_outage_exit_total 67
telemt_me_single_endpoint_outage_reconnect_attempt_total 152
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 152
telemt_me_single_endpoint_shadow_rotate_total 482
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
telemt_me_writers_active_current 43
telemt_desync_total 16686
telemt_desync_full_logged_total 5327
telemt_desync_suppressed_total 11359
telemt_desync_frames_bucket_total{bucket="1_2"} 3593
telemt_desync_frames_bucket_total{bucket="3_10"} 7297
telemt_desync_frames_bucket_total{bucket="gt_10"} 5796
telemt_pool_swap_total 62
telemt_pool_force_close_total 2020
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 420
telemt_me_draining_writers_reap_progress_total 20090
telemt_me_writer_removed_unexpected_total 1226
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2623
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18521
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1686
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 334
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18070
telemt_me_writer_teardown_success_total{mode="normal"} 21144
telemt_me_writer_teardown_noop_total 20100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41244
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 161.498232
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41244
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 420
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 894
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 63
telemt_me_writer_removed_unexpected_minus_restored_total 323
telemt_user_connections_total{user="hello"} 9049171
telemt_user_connections_current{user="hello"} 5100
telemt_user_octets_from_client{user="hello"} 68396581597 (63.70 GB)
telemt_user_octets_to_client{user="hello"} 729226125746 (679.14 GB)
telemt_user_msgs_from_client{user="hello"} 227549
telemt_user_msgs_to_client{user="hello"} 539047
telemt_user_unique_ips_current{user="hello"} 1824
telemt_user_unique_ips_recent_window{user="hello"} 924
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 61501.1 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3244979
telemt_connections_bad_total 371434
telemt_connections_current 4123
telemt_connections_me_current 4123
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 71732
telemt_upstream_connect_attempt_total 26418
telemt_upstream_connect_success_total 26133
telemt_upstream_connect_fail_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 26388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12514
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13554
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 255
telemt_me_reconnect_attempts_total 2575
telemt_me_reconnect_success_total 945
telemt_me_reader_eof_total 938
telemt_me_idle_close_by_peer_total 938
telemt_me_route_drop_no_conn_total 1271535
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2477771
telemt_me_endpoint_quarantine_total 385
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 467
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
telemt_me_writers_active_current 89
telemt_desync_total 11560
telemt_desync_full_logged_total 4013
telemt_desync_suppressed_total 7547
telemt_desync_frames_bucket_total{bucket="1_2"} 2245
telemt_desync_frames_bucket_total{bucket="3_10"} 4603
telemt_desync_frames_bucket_total{bucket="gt_10"} 4712
telemt_pool_swap_total 61
telemt_pool_force_close_total 1741
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 165
telemt_me_draining_writers_reap_progress_total 22032
telemt_me_writer_removed_unexpected_total 909
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2177
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20794
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1527
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 214
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20291
telemt_me_writer_teardown_success_total{mode="normal"} 22971
telemt_me_writer_teardown_noop_total 22033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45004
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.831130
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45004
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 165
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 810
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 2462422
telemt_user_connections_current{user="hello"} 4123
telemt_user_octets_from_client{user="hello"} 51269522484 (47.75 GB)
telemt_user_octets_to_client{user="hello"} 1066401993946 (993.16 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1634
telemt_user_unique_ips_recent_window{user="hello"} 668
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 61495.5 (17h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4967497
telemt_connections_bad_total 243763
telemt_connections_current 3015
telemt_connections_me_current 3015
telemt_handshake_timeouts_total 2191611
telemt_upstream_connect_attempt_total 24350
telemt_upstream_connect_success_total 24316
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 24319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 290
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 1055
telemt_me_reconnect_success_total 453
telemt_me_reader_eof_total 454
telemt_me_idle_close_by_peer_total 454
telemt_me_route_drop_no_conn_total 1159329
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2235258
telemt_me_endpoint_quarantine_total 457
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 478
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_desync_total 10659
telemt_desync_full_logged_total 3754
telemt_desync_suppressed_total 6905
telemt_desync_frames_bucket_total{bucket="1_2"} 1982
telemt_desync_frames_bucket_total{bucket="3_10"} 4213
telemt_desync_frames_bucket_total{bucket="gt_10"} 4464
telemt_pool_swap_total 67
telemt_pool_force_close_total 1717
telemt_me_writer_close_signal_drop_total 150
telemt_me_draining_writers_reap_progress_total 21786
telemt_me_writer_removed_unexpected_total 436
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1510
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20739
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1653
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 64
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20069
telemt_me_writer_teardown_success_total{mode="normal"} 22249
telemt_me_writer_teardown_noop_total 21786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44035
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.708810
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44035
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 150
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 393
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 2228305
telemt_user_connections_current{user="hello"} 3015
telemt_user_octets_from_client{user="hello"} 46447394488 (43.26 GB)
telemt_user_octets_to_client{user="hello"} 1034783449188 (963.72 GB)
telemt_user_unique_ips_current{user="hello"} 1241
telemt_user_unique_ips_recent_window{user="hello"} 522
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 59487.1 (16h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1067730
telemt_connections_bad_total 134897
telemt_connections_current 708
telemt_connections_me_current 708
telemt_handshake_timeouts_total 374245
telemt_upstream_connect_attempt_total 27931
telemt_upstream_connect_success_total 27928
telemt_upstream_connect_attempts_per_request{bucket="1"} 27928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16367
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1191
telemt_me_reconnect_success_total 462
telemt_me_reader_eof_total 460
telemt_me_idle_close_by_peer_total 460
telemt_me_route_drop_no_conn_total 222473
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 488787
telemt_me_endpoint_quarantine_total 548
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 499
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_me_writers_warm_current 37
telemt_desync_total 3229
telemt_desync_full_logged_total 1196
telemt_desync_suppressed_total 2033
telemt_desync_frames_bucket_total{bucket="1_2"} 562
telemt_desync_frames_bucket_total{bucket="3_10"} 1154
telemt_desync_frames_bucket_total{bucket="gt_10"} 1513
telemt_pool_swap_total 65
telemt_pool_force_close_total 1473
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 103
telemt_me_draining_writers_reap_progress_total 25004
telemt_me_writer_removed_unexpected_total 434
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1834
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23615
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1470
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23531
telemt_me_writer_teardown_success_total{mode="normal"} 25449
telemt_me_writer_teardown_noop_total 25004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50453
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.331557
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50453
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 103
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 375
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 488575
telemt_user_connections_current{user="hello"} 708
telemt_user_octets_from_client{user="hello"} 9107764239 (8.48 GB)
telemt_user_octets_to_client{user="hello"} 186274521713 (173.48 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 284
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 61505.3 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3518040
telemt_connections_bad_total 328567
telemt_connections_current 4394
telemt_connections_me_current 4394
telemt_handshake_timeouts_total 105843
telemt_upstream_connect_attempt_total 25130
telemt_upstream_connect_success_total 25027
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 25099
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12534
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_reconnect_attempts_total 1026
telemt_me_reconnect_success_total 579
telemt_me_reader_eof_total 539
telemt_me_idle_close_by_peer_total 539
telemt_me_route_drop_no_conn_total 1020888
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2782784
telemt_me_endpoint_quarantine_total 464
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 476
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
telemt_desync_total 11161
telemt_desync_full_logged_total 3666
telemt_desync_suppressed_total 7495
telemt_desync_frames_bucket_total{bucket="1_2"} 2664
telemt_desync_frames_bucket_total{bucket="3_10"} 4147
telemt_desync_frames_bucket_total{bucket="gt_10"} 4350
telemt_pool_swap_total 68
telemt_pool_force_close_total 1759
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 189
telemt_me_draining_writers_reap_progress_total 22573
telemt_me_writer_removed_unexpected_total 529
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1767
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21334
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1727
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20814
telemt_me_writer_teardown_success_total{mode="normal"} 23101
telemt_me_writer_teardown_noop_total 22573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45674
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.648618
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45674
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 189
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 511
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 2775318
telemt_user_connections_current{user="hello"} 4394
telemt_user_octets_from_client{user="hello"} 58764384048 (54.73 GB)
telemt_user_octets_to_client{user="hello"} 1306437311828 (1.19 TB)
telemt_user_unique_ips_current{user="hello"} 1460
telemt_user_unique_ips_recent_window{user="hello"} 547
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 61502.1 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3161328
telemt_connections_bad_total 266464
telemt_connections_current 3537
telemt_connections_me_current 3537
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 93707
telemt_upstream_connect_attempt_total 41304
telemt_upstream_connect_success_total 41037
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 41259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25715
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14218
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 588
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_reconnect_attempts_total 3529
telemt_me_reconnect_success_total 743
telemt_me_reader_eof_total 651
telemt_me_idle_close_by_peer_total 651
telemt_me_seq_mismatch_total 30
telemt_me_route_drop_no_conn_total 1065665
telemt_me_route_drop_channel_closed_total 78
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2543365
telemt_me_endpoint_quarantine_total 524
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 476
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_desync_total 9860
telemt_desync_full_logged_total 3365
telemt_desync_suppressed_total 6495
telemt_desync_frames_bucket_total{bucket="1_2"} 2512
telemt_desync_frames_bucket_total{bucket="3_10"} 3648
telemt_desync_frames_bucket_total{bucket="gt_10"} 3700
telemt_pool_swap_total 67
telemt_pool_force_close_total 1706
telemt_me_writer_close_signal_drop_total 176
telemt_me_draining_writers_reap_progress_total 21722
telemt_me_writer_removed_unexpected_total 663
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2067
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20348
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1594
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 112
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20016
telemt_me_writer_teardown_success_total{mode="normal"} 22415
telemt_me_writer_teardown_noop_total 21723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44138
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.181068
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44138
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 176
telemt_me_refill_failed_total 158
telemt_me_writer_restored_same_endpoint_total 567
telemt_me_writer_restored_fallback_total 39
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 2552592
telemt_user_connections_current{user="hello"} 3537
telemt_user_octets_from_client{user="hello"} 46712502465 (43.50 GB)
telemt_user_octets_to_client{user="hello"} 1111006218404 (1.01 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1401
telemt_user_unique_ips_recent_window{user="hello"} 501
```