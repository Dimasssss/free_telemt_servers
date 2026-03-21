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

# Server Metrics 2026-03-21 14:06:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 63054.3 (17h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2145593
telemt_connections_bad_total 104766
telemt_connections_current 1805
telemt_connections_me_current 1805
telemt_handshake_timeouts_total 74367
telemt_upstream_connect_attempt_total 24097
telemt_upstream_connect_success_total 23976
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 24054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15445
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1350
telemt_me_reconnect_success_total 567
telemt_me_reader_eof_total 539
telemt_me_idle_close_by_peer_total 539
telemt_me_route_drop_no_conn_total 1776932
telemt_me_route_drop_channel_closed_total 541
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1707737
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_endpoint_quarantine_total 443
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 494
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
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 16
telemt_desync_total 6757
telemt_desync_full_logged_total 2308
telemt_desync_suppressed_total 4449
telemt_desync_frames_bucket_total{bucket="1_2"} 1511
telemt_desync_frames_bucket_total{bucket="3_10"} 2579
telemt_desync_frames_bucket_total{bucket="gt_10"} 2667
telemt_pool_swap_total 68
telemt_pool_force_close_total 2060
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 415
telemt_me_draining_writers_reap_progress_total 21562
telemt_me_writer_removed_unexpected_total 521
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1782
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20093
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1983
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19502
telemt_me_writer_teardown_success_total{mode="normal"} 21875
telemt_me_writer_teardown_noop_total 21568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43443
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 185.214225
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43443
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 415
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 491
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 1706432
telemt_user_connections_current{user="hello"} 1805
telemt_user_octets_from_client{user="hello"} 24941081583 (23.23 GB)
telemt_user_octets_to_client{user="hello"} 430612636275 (401.04 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 652
telemt_user_unique_ips_recent_window{user="hello"} 358
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 2607.7 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233043
telemt_connections_bad_total 8341
telemt_connections_current 2380
telemt_connections_me_current 2380
telemt_handshake_timeouts_total 6704
telemt_upstream_connect_attempt_total 1026
telemt_upstream_connect_success_total 1024
telemt_upstream_connect_attempts_per_request{bucket="1"} 1024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 554
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 454
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 104
telemt_me_reconnect_success_total 19
telemt_me_reader_eof_total 18
telemt_me_idle_close_by_peer_total 18
telemt_me_route_drop_no_conn_total 131393
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205707
telemt_me_endpoint_quarantine_total 20
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 24
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_me_writers_active_current 43
telemt_desync_total 810
telemt_desync_full_logged_total 323
telemt_desync_suppressed_total 487
telemt_desync_frames_bucket_total{bucket="1_2"} 166
telemt_desync_frames_bucket_total{bucket="3_10"} 293
telemt_desync_frames_bucket_total{bucket="gt_10"} 351
telemt_pool_swap_total 2
telemt_pool_force_close_total 52
telemt_me_writer_close_signal_drop_total 10
telemt_me_draining_writers_reap_progress_total 658
telemt_me_writer_removed_unexpected_total 16
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 634
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 50
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 606
telemt_me_writer_teardown_success_total{mode="normal"} 676
telemt_me_writer_teardown_noop_total 658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1334
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.183023
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1334
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 10
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 203108
telemt_user_connections_current{user="hello"} 2381
telemt_user_octets_from_client{user="hello"} 3962931335 (3.69 GB)
telemt_user_octets_to_client{user="hello"} 47760893463 (44.48 GB)
telemt_user_msgs_from_client{user="hello"} 423
telemt_user_msgs_to_client{user="hello"} 734
telemt_user_unique_ips_current{user="hello"} 1146
telemt_user_unique_ips_recent_window{user="hello"} 1434
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 63052.1 (17h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4232330
telemt_connections_bad_total 399248
telemt_connections_current 4606
telemt_connections_me_current 4606
telemt_handshake_timeouts_total 161287
telemt_upstream_connect_attempt_total 23856
telemt_upstream_connect_success_total 23814
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 23819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12950
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 914
telemt_me_reconnect_success_total 541
telemt_me_reader_eof_total 539
telemt_me_idle_close_by_peer_total 539
telemt_me_route_drop_no_conn_total 2281503
telemt_me_route_drop_channel_closed_total 40
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3432735
telemt_me_endpoint_quarantine_total 397
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 477
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
telemt_me_writers_warm_current 20
telemt_desync_total 14297
telemt_desync_full_logged_total 4832
telemt_desync_suppressed_total 9465
telemt_desync_frames_bucket_total{bucket="1_2"} 3033
telemt_desync_frames_bucket_total{bucket="3_10"} 5633
telemt_desync_frames_bucket_total{bucket="gt_10"} 5631
telemt_pool_swap_total 66
telemt_pool_force_close_total 2121
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 327
telemt_me_draining_writers_reap_progress_total 21628
telemt_me_writer_removed_unexpected_total 520
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1873
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20075
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1935
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 186
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19507
telemt_me_writer_teardown_success_total{mode="normal"} 21948
telemt_me_writer_teardown_noop_total 21657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43605
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 68.890657
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43605
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 327
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 492
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 3428530
telemt_user_connections_current{user="hello"} 4606
telemt_user_octets_from_client{user="hello"} 56328918984 (52.46 GB)
telemt_user_octets_to_client{user="hello"} 1162529878768 (1.06 TB)
telemt_user_unique_ips_current{user="hello"} 1687
telemt_user_unique_ips_recent_window{user="hello"} 1013
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 63053.3 (17h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3452938
telemt_connections_bad_total 384655
telemt_connections_current 3815
telemt_connections_me_current 3815
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 127517
telemt_upstream_connect_attempt_total 28157
telemt_upstream_connect_success_total 27881
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 28016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12905
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 480
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1167
telemt_me_reconnect_success_total 551
telemt_me_reader_eof_total 516
telemt_me_idle_close_by_peer_total 516
telemt_me_route_drop_no_conn_total 1078895
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2502399
telemt_me_endpoint_quarantine_total 407
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 481
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
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 15
telemt_desync_total 11451
telemt_desync_full_logged_total 3879
telemt_desync_suppressed_total 7572
telemt_desync_frames_bucket_total{bucket="1_2"} 2865
telemt_desync_frames_bucket_total{bucket="3_10"} 4422
telemt_desync_frames_bucket_total{bucket="gt_10"} 4164
telemt_pool_swap_total 68
telemt_pool_force_close_total 1941
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 175
telemt_me_draining_writers_reap_progress_total 20780
telemt_me_writer_removed_unexpected_total 501
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1751
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19536
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1812
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 129
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18839
telemt_me_writer_teardown_success_total{mode="normal"} 21287
telemt_me_writer_teardown_noop_total 20781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42068
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.966900
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42068
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 175
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 465
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 2502804
telemt_user_connections_current{user="hello"} 3815
telemt_user_octets_from_client{user="hello"} 46661756661 (43.46 GB)
telemt_user_octets_to_client{user="hello"} 1172096914359 (1.07 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1488
telemt_user_unique_ips_recent_window{user="hello"} 532
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 63017.3 (17h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3356631
telemt_connections_bad_total 357983
telemt_connections_current 3654
telemt_connections_me_current 3654
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 98193
telemt_upstream_connect_attempt_total 33318
telemt_upstream_connect_success_total 33087
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 33220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14263
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 281
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 846
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1286
telemt_me_reconnect_success_total 626
telemt_me_reader_eof_total 570
telemt_me_idle_close_by_peer_total 570
telemt_me_route_drop_no_conn_total 1031484
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2460127
telemt_me_endpoint_quarantine_total 457
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 470
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
telemt_me_writers_active_current 44
telemt_desync_total 11483
telemt_desync_full_logged_total 3813
telemt_desync_suppressed_total 7670
telemt_desync_frames_bucket_total{bucket="1_2"} 2907
telemt_desync_frames_bucket_total{bucket="3_10"} 4320
telemt_desync_frames_bucket_total{bucket="gt_10"} 4256
telemt_pool_swap_total 66
telemt_pool_force_close_total 1876
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 215
telemt_me_draining_writers_reap_progress_total 22104
telemt_me_writer_removed_unexpected_total 543
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1860
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20822
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1707
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 169
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20228
telemt_me_writer_teardown_success_total{mode="normal"} 22682
telemt_me_writer_teardown_noop_total 22109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44791
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.347450
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44791
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 215
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 545
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2464798
telemt_user_connections_current{user="hello"} 3654
telemt_user_octets_from_client{user="hello"} 53512924125 (49.84 GB)
telemt_user_octets_to_client{user="hello"} 1164324250488 (1.06 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1468
telemt_user_unique_ips_recent_window{user="hello"} 525
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 63056.4 (17h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11509416
telemt_connections_bad_total 770525
telemt_connections_current 5880
telemt_connections_me_current 5880
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 358396
telemt_upstream_connect_attempt_total 112593
telemt_upstream_connect_success_total 102902
telemt_upstream_connect_fail_total 8710
telemt_upstream_connect_attempts_per_request{bucket="1"} 111612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24221
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 527
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8710
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 3656
telemt_me_reconnect_success_total 1299
telemt_me_reader_eof_total 937
telemt_me_idle_close_by_peer_total 936
telemt_me_route_drop_no_conn_total 21333602
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9427126
telemt_me_endpoint_quarantine_total 483
telemt_me_single_endpoint_outage_enter_total 69
telemt_me_single_endpoint_outage_exit_total 69
telemt_me_single_endpoint_outage_reconnect_attempt_total 154
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 154
telemt_me_single_endpoint_shadow_rotate_total 493
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_me_writers_warm_current 3
telemt_desync_total 17276
telemt_desync_full_logged_total 5493
telemt_desync_suppressed_total 11783
telemt_desync_frames_bucket_total{bucket="1_2"} 3747
telemt_desync_frames_bucket_total{bucket="3_10"} 7573
telemt_desync_frames_bucket_total{bucket="gt_10"} 5956
telemt_pool_swap_total 63
telemt_pool_force_close_total 2026
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 423
telemt_me_draining_writers_reap_progress_total 20437
telemt_me_writer_removed_unexpected_total 1249
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2682
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18832
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1686
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 340
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18411
telemt_me_writer_teardown_success_total{mode="normal"} 21514
telemt_me_writer_teardown_noop_total 20447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41961
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 161.610117
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41961
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 423
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 917
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 63
telemt_me_writer_removed_unexpected_minus_restored_total 323
telemt_user_connections_total{user="hello"} 9501885
telemt_user_connections_current{user="hello"} 5880
telemt_user_octets_from_client{user="hello"} 70191468703 (65.37 GB)
telemt_user_octets_to_client{user="hello"} 747213415103 (695.90 GB)
telemt_user_msgs_from_client{user="hello"} 228562
telemt_user_msgs_to_client{user="hello"} 540142
telemt_user_unique_ips_current{user="hello"} 2020
telemt_user_unique_ips_recent_window{user="hello"} 1195
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 63024.1 (17h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3374363
telemt_connections_bad_total 381931
telemt_connections_current 3937
telemt_connections_me_current 3937
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 74144
telemt_upstream_connect_attempt_total 27023
telemt_upstream_connect_success_total 26734
telemt_upstream_connect_fail_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 26989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13883
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 255
telemt_me_reconnect_attempts_total 2585
telemt_me_reconnect_success_total 955
telemt_me_reader_eof_total 948
telemt_me_idle_close_by_peer_total 948
telemt_me_route_drop_no_conn_total 1345158
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2585558
telemt_me_endpoint_quarantine_total 396
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 473
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
telemt_me_writers_active_current 44
telemt_desync_total 12258
telemt_desync_full_logged_total 4262
telemt_desync_suppressed_total 7996
telemt_desync_frames_bucket_total{bucket="1_2"} 2358
telemt_desync_frames_bucket_total{bucket="3_10"} 4890
telemt_desync_frames_bucket_total{bucket="gt_10"} 5010
telemt_pool_swap_total 62
telemt_pool_force_close_total 1797
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 173
telemt_me_draining_writers_reap_progress_total 22624
telemt_me_writer_removed_unexpected_total 919
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2220
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21353
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1554
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 243
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20827
telemt_me_writer_teardown_success_total{mode="normal"} 23573
telemt_me_writer_teardown_noop_total 22625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46198
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.941423
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46198
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 173
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 819
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 2569699
telemt_user_connections_current{user="hello"} 3937
telemt_user_octets_from_client{user="hello"} 54499405080 (50.76 GB)
telemt_user_octets_to_client{user="hello"} 1106872724670 (1.01 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1523
telemt_user_unique_ips_recent_window{user="hello"} 543
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 63018.7 (17h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5178020
telemt_connections_bad_total 250940
telemt_connections_current 3846
telemt_connections_me_current 3846
telemt_handshake_timeouts_total 2282679
telemt_upstream_connect_attempt_total 24791
telemt_upstream_connect_success_total 24756
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 24759
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13405
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 292
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 1098
telemt_me_reconnect_success_total 466
telemt_me_reader_eof_total 467
telemt_me_idle_close_by_peer_total 467
telemt_me_route_drop_no_conn_total 1228860
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2340779
telemt_me_endpoint_quarantine_total 466
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 487
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
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 1
telemt_desync_total 11146
telemt_desync_full_logged_total 3915
telemt_desync_suppressed_total 7231
telemt_desync_frames_bucket_total{bucket="1_2"} 2054
telemt_desync_frames_bucket_total{bucket="3_10"} 4396
telemt_desync_frames_bucket_total{bucket="gt_10"} 4696
telemt_pool_swap_total 68
telemt_pool_force_close_total 1750
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 152
telemt_me_draining_writers_reap_progress_total 22171
telemt_me_writer_removed_unexpected_total 449
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1543
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21104
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1680
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 70
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20421
telemt_me_writer_teardown_success_total{mode="normal"} 22647
telemt_me_writer_teardown_noop_total 22171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44818
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.881935
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44818
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 152
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 404
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2333492
telemt_user_connections_current{user="hello"} 3846
telemt_user_octets_from_client{user="hello"} 52444424504 (48.84 GB)
telemt_user_octets_to_client{user="hello"} 1071316779828 (997.74 GB)
telemt_user_unique_ips_current{user="hello"} 1494
telemt_user_unique_ips_recent_window{user="hello"} 566
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 61009.9 (16h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1108754
telemt_connections_bad_total 135452
telemt_connections_current 755
telemt_connections_me_current 755
telemt_handshake_timeouts_total 393004
telemt_upstream_connect_attempt_total 28570
telemt_upstream_connect_success_total 28567
telemt_upstream_connect_attempts_per_request{bucket="1"} 28567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16740
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1218
telemt_me_reconnect_success_total 470
telemt_me_reader_eof_total 467
telemt_me_idle_close_by_peer_total 467
telemt_me_route_drop_no_conn_total 231582
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 509452
telemt_me_endpoint_quarantine_total 559
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 514
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
telemt_me_writers_active_current 48
telemt_desync_total 3298
telemt_desync_full_logged_total 1222
telemt_desync_suppressed_total 2076
telemt_desync_frames_bucket_total{bucket="1_2"} 590
telemt_desync_frames_bucket_total{bucket="3_10"} 1177
telemt_desync_frames_bucket_total{bucket="gt_10"} 1531
telemt_pool_swap_total 67
telemt_pool_force_close_total 1527
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 107
telemt_me_draining_writers_reap_progress_total 25617
telemt_me_writer_removed_unexpected_total 441
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1877
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24192
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1524
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24090
telemt_me_writer_teardown_success_total{mode="normal"} 26069
telemt_me_writer_teardown_noop_total 25617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51686
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.417888
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51686
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 107
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 381
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 509223
telemt_user_connections_current{user="hello"} 755
telemt_user_octets_from_client{user="hello"} 10480666235 (9.76 GB)
telemt_user_octets_to_client{user="hello"} 192019632817 (178.83 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 63028.5 (17h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3683284
telemt_connections_bad_total 343652
telemt_connections_current 5167
telemt_connections_me_current 5167
telemt_handshake_timeouts_total 113675
telemt_upstream_connect_attempt_total 25555
telemt_upstream_connect_success_total 25451
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 25523
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12759
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_reconnect_attempts_total 1031
telemt_me_reconnect_success_total 583
telemt_me_reader_eof_total 543
telemt_me_idle_close_by_peer_total 543
telemt_me_route_drop_no_conn_total 1081037
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2916713
telemt_me_endpoint_quarantine_total 468
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 483
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
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 2
telemt_desync_total 11600
telemt_desync_full_logged_total 3830
telemt_desync_suppressed_total 7770
telemt_desync_frames_bucket_total{bucket="1_2"} 2764
telemt_desync_frames_bucket_total{bucket="3_10"} 4310
telemt_desync_frames_bucket_total{bucket="gt_10"} 4526
telemt_pool_swap_total 69
telemt_pool_force_close_total 1790
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 193
telemt_me_draining_writers_reap_progress_total 22948
telemt_me_writer_removed_unexpected_total 533
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1793
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21687
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1755
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21158
telemt_me_writer_teardown_success_total{mode="normal"} 23480
telemt_me_writer_teardown_noop_total 22948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46428
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.260119
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46428
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 193
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 515
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 2909012
telemt_user_connections_current{user="hello"} 5167
telemt_user_octets_from_client{user="hello"} 61261054472 (57.05 GB)
telemt_user_octets_to_client{user="hello"} 1373562277364 (1.25 TB)
telemt_user_unique_ips_current{user="hello"} 1749
telemt_user_unique_ips_recent_window{user="hello"} 616
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 63025.4 (17h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3321774
telemt_connections_bad_total 292655
telemt_connections_current 4051
telemt_connections_me_current 4051
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 97259
telemt_upstream_connect_attempt_total 41729
telemt_upstream_connect_success_total 41459
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 41682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14453
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 590
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_reconnect_attempts_total 3537
telemt_me_reconnect_success_total 751
telemt_me_reader_eof_total 659
telemt_me_idle_close_by_peer_total 659
telemt_me_seq_mismatch_total 31
telemt_me_route_drop_no_conn_total 1176580
telemt_me_route_drop_channel_closed_total 84
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2667354
telemt_me_endpoint_quarantine_total 531
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 482
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
telemt_desync_total 10253
telemt_desync_full_logged_total 3499
telemt_desync_suppressed_total 6754
telemt_desync_frames_bucket_total{bucket="1_2"} 2599
telemt_desync_frames_bucket_total{bucket="3_10"} 3792
telemt_desync_frames_bucket_total{bucket="gt_10"} 3862
telemt_pool_swap_total 68
telemt_pool_force_close_total 1736
telemt_me_writer_close_signal_drop_total 186
telemt_me_draining_writers_reap_progress_total 22089
telemt_me_writer_removed_unexpected_total 671
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2101
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20690
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1621
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 115
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20353
telemt_me_writer_teardown_success_total{mode="normal"} 22791
telemt_me_writer_teardown_noop_total 22090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44881
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.334112
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44881
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 186
telemt_me_refill_failed_total 158
telemt_me_writer_restored_same_endpoint_total 574
telemt_me_writer_restored_fallback_total 40
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 2676399
telemt_user_connections_current{user="hello"} 4051
telemt_user_octets_from_client{user="hello"} 48405995833 (45.08 GB)
telemt_user_octets_to_client{user="hello"} 1152352631728 (1.05 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1550
telemt_user_unique_ips_recent_window{user="hello"} 547
```