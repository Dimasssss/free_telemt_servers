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

# Server Metrics 2026-03-21 21:04:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 88146.4 (24h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3123712
telemt_connections_bad_total 180664
telemt_connections_current 968
telemt_connections_me_current 968
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 97870
telemt_upstream_connect_attempt_total 35945
telemt_upstream_connect_success_total 35795
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 35902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21370
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 59
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1938
telemt_me_reconnect_success_total 774
telemt_me_reader_eof_total 743
telemt_me_idle_close_by_peer_total 743
telemt_me_route_drop_no_conn_total 2634111
telemt_me_route_drop_channel_closed_total 849
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2525404
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 592
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 687
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_desync_total 10108
telemt_desync_full_logged_total 3538
telemt_desync_suppressed_total 6570
telemt_desync_frames_bucket_total{bucket="1_2"} 2187
telemt_desync_frames_bucket_total{bucket="3_10"} 3783
telemt_desync_frames_bucket_total{bucket="gt_10"} 4138
telemt_pool_swap_total 95
telemt_pool_force_close_total 2871
telemt_pool_stale_pick_total 31
telemt_me_writer_close_signal_drop_total 646
telemt_me_draining_writers_reap_progress_total 29538
telemt_me_writer_removed_unexpected_total 724
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2465
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27538
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2731
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 140
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26667
telemt_me_writer_teardown_success_total{mode="normal"} 30003
telemt_me_writer_teardown_noop_total 29546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59549
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 300.802669
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59549
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 646
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 665
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 2524976
telemt_user_connections_current{user="hello"} 968
telemt_user_octets_from_client{user="hello"} 37336805621 (34.77 GB)
telemt_user_octets_to_client{user="hello"} 647312686354 (602.86 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 393
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 13283.9 (3h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 511505
telemt_connections_bad_total 23523
telemt_connections_current 1302
telemt_connections_me_current 1302
telemt_handshake_timeouts_total 18023
telemt_upstream_connect_attempt_total 5244
telemt_upstream_connect_success_total 5139
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 5231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2849
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_reconnect_attempts_total 367
telemt_me_reconnect_success_total 162
telemt_me_reader_eof_total 139
telemt_me_idle_close_by_peer_total 139
telemt_me_route_drop_no_conn_total 288342
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 415049
telemt_me_endpoint_quarantine_total 97
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 105
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 11
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
telemt_desync_total 1791
telemt_desync_full_logged_total 1029
telemt_desync_suppressed_total 762
telemt_desync_frames_bucket_total{bucket="1_2"} 367
telemt_desync_frames_bucket_total{bucket="3_10"} 686
telemt_desync_frames_bucket_total{bucket="gt_10"} 738
telemt_pool_swap_total 14
telemt_pool_force_close_total 420
telemt_me_writer_close_signal_drop_total 36
telemt_me_draining_writers_reap_progress_total 4565
telemt_me_writer_removed_unexpected_total 131
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 388
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4303
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 413
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4145
telemt_me_writer_teardown_success_total{mode="normal"} 4691
telemt_me_writer_teardown_noop_total 4565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 8875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 9095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 9158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 9242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 9254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 9256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 9256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 9256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 9256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 9256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 9256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 9256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 9256
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.869732
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 9256
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 36
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 111
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 414534
telemt_user_connections_current{user="hello"} 1302
telemt_user_octets_from_client{user="hello"} 6847562488 (6.38 GB)
telemt_user_octets_to_client{user="hello"} 129736010420 (120.83 GB)
telemt_user_unique_ips_current{user="hello"} 770
telemt_user_unique_ips_recent_window{user="hello"} 287
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 88144.0 (24h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7007008
telemt_connections_bad_total 541754
telemt_connections_current 3471
telemt_connections_me_current 3471
telemt_handshake_timeouts_total 219586
telemt_upstream_connect_attempt_total 31603
telemt_upstream_connect_success_total 31540
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 31547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17204
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1355
telemt_me_reconnect_success_total 678
telemt_me_reader_eof_total 687
telemt_me_idle_close_by_peer_total 687
telemt_me_route_drop_no_conn_total 4394080
telemt_me_route_drop_channel_closed_total 64
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5728864
telemt_me_endpoint_quarantine_total 544
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 651
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_desync_total 23756
telemt_desync_full_logged_total 7912
telemt_desync_suppressed_total 15844
telemt_desync_frames_bucket_total{bucket="1_2"} 4961
telemt_desync_frames_bucket_total{bucket="3_10"} 9406
telemt_desync_frames_bucket_total{bucket="gt_10"} 9389
telemt_pool_swap_total 94
telemt_pool_force_close_total 3182
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 517
telemt_me_draining_writers_reap_progress_total 28771
telemt_me_writer_removed_unexpected_total 661
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2464
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26571
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 37
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2949
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 233
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25589
telemt_me_writer_teardown_success_total{mode="normal"} 29035
telemt_me_writer_teardown_noop_total 28808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57843
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 141.854336
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57843
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 517
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 607
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 5721963
telemt_user_connections_current{user="hello"} 3471
telemt_user_octets_from_client{user="hello"} 98852096876 (92.06 GB)
telemt_user_octets_to_client{user="hello"} 1814948483476 (1.65 TB)
telemt_user_unique_ips_current{user="hello"} 1504
telemt_user_unique_ips_recent_window{user="hello"} 359
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 88145.2 (24h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5683736
telemt_connections_bad_total 552998
telemt_connections_current 2974
telemt_connections_me_current 2974
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 185904
telemt_upstream_connect_attempt_total 35658
telemt_upstream_connect_success_total 35340
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 35504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16917
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 542
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1674
telemt_me_reconnect_success_total 700
telemt_me_reader_eof_total 674
telemt_me_idle_close_by_peer_total 674
telemt_me_route_drop_no_conn_total 1964039
telemt_me_route_drop_channel_closed_total 225
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4248062
telemt_me_endpoint_quarantine_total 539
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 670
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
telemt_desync_total 20315
telemt_desync_full_logged_total 6758
telemt_desync_suppressed_total 13557
telemt_desync_frames_bucket_total{bucket="1_2"} 4957
telemt_desync_frames_bucket_total{bucket="3_10"} 7858
telemt_desync_frames_bucket_total{bucket="gt_10"} 7500
telemt_pool_swap_total 96
telemt_pool_force_close_total 2916
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 331
telemt_me_draining_writers_reap_progress_total 27496
telemt_me_writer_removed_unexpected_total 653
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2376
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25702
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2719
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 197
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24580
telemt_me_writer_teardown_success_total{mode="normal"} 28078
telemt_me_writer_teardown_noop_total 27501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55579
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 45.634755
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55579
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 331
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 600
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 4239916
telemt_user_connections_current{user="hello"} 2974
telemt_user_octets_from_client{user="hello"} 127817317469 (119.04 GB)
telemt_user_octets_to_client{user="hello"} 1952174271287 (1.78 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1285
telemt_user_unique_ips_recent_window{user="hello"} 346
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 88109.1 (24h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5604022
telemt_connections_bad_total 503817
telemt_connections_current 2362
telemt_connections_me_current 2362
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 171322
telemt_upstream_connect_attempt_total 42102
telemt_upstream_connect_success_total 41824
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 41959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18361
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 336
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1041
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1734
telemt_me_reconnect_success_total 767
telemt_me_reader_eof_total 711
telemt_me_idle_close_by_peer_total 711
telemt_me_route_drop_no_conn_total 2020421
telemt_me_route_drop_channel_closed_total 103
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4232040
telemt_me_endpoint_quarantine_total 592
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 656
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
telemt_desync_total 20072
telemt_desync_full_logged_total 6580
telemt_desync_suppressed_total 13492
telemt_desync_frames_bucket_total{bucket="1_2"} 4981
telemt_desync_frames_bucket_total{bucket="3_10"} 7596
telemt_desync_frames_bucket_total{bucket="gt_10"} 7495
telemt_pool_swap_total 94
telemt_pool_force_close_total 2795
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 335
telemt_me_draining_writers_reap_progress_total 28954
telemt_me_writer_removed_unexpected_total 681
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2471
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27167
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2582
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26159
telemt_me_writer_teardown_success_total{mode="normal"} 29638
telemt_me_writer_teardown_noop_total 28964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58602
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.376886
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58602
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 335
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 663
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 4234060
telemt_user_connections_current{user="hello"} 2362
telemt_user_octets_from_client{user="hello"} 123458249879 (114.98 GB)
telemt_user_octets_to_client{user="hello"} 1931880870383 (1.76 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1052
telemt_user_unique_ips_recent_window{user="hello"} 323
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 88148.6 (24h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19255588
telemt_connections_bad_total 1271855
telemt_connections_current 3582
telemt_connections_me_current 3582
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 538727
telemt_upstream_connect_attempt_total 181675
telemt_upstream_connect_success_total 164422
telemt_upstream_connect_fail_total 15806
telemt_upstream_connect_attempts_per_request{bucket="1"} 180228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37125
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1152
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8850
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15806
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 59646
telemt_me_reconnect_success_total 1900
telemt_me_reader_eof_total 1252
telemt_me_idle_close_by_peer_total 1251
telemt_me_route_drop_no_conn_total 39152050
telemt_me_route_drop_channel_closed_total 116
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15815507
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 645
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 239
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 239
telemt_me_single_endpoint_shadow_rotate_total 686
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
telemt_me_writers_active_current 86
telemt_desync_total 29741
telemt_desync_full_logged_total 8786
telemt_desync_suppressed_total 20955
telemt_desync_frames_bucket_total{bucket="1_2"} 6520
telemt_desync_frames_bucket_total{bucket="3_10"} 13169
telemt_desync_frames_bucket_total{bucket="gt_10"} 10052
telemt_pool_swap_total 89
telemt_pool_force_close_total 2975
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 27121
telemt_me_writer_removed_unexpected_total 1790
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3710
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24945
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2513
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 462
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24146
telemt_me_writer_teardown_success_total{mode="normal"} 28655
telemt_me_writer_teardown_noop_total 27147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55802
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 203.340660
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55802
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 3519
telemt_me_writer_restored_same_endpoint_total 1324
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14223
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 15940707
telemt_user_connections_current{user="hello"} 3582
telemt_user_octets_from_client{user="hello"} 156182147602 (145.46 GB)
telemt_user_octets_to_client{user="hello"} 987181676022 (919.38 GB)
telemt_user_msgs_from_client{user="hello"} 361669
telemt_user_msgs_to_client{user="hello"} 643484
telemt_user_unique_ips_current{user="hello"} 1427
telemt_user_unique_ips_recent_window{user="hello"} 448
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 88116.1 (24h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5496827
telemt_connections_bad_total 526027
telemt_connections_current 2871
telemt_connections_me_current 2871
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 113148
telemt_upstream_connect_attempt_total 45239
telemt_upstream_connect_success_total 44744
telemt_upstream_connect_fail_total 411
telemt_upstream_connect_attempts_per_request{bucket="1"} 45155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18644
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 411
telemt_me_reconnect_attempts_total 11085
telemt_me_reconnect_success_total 1280
telemt_me_reader_eof_total 1207
telemt_me_idle_close_by_peer_total 1207
telemt_me_route_drop_no_conn_total 2285918
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4270411
telemt_me_endpoint_quarantine_total 538
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 15
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 15
telemt_me_single_endpoint_shadow_rotate_total 653
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
telemt_desync_total 21205
telemt_desync_full_logged_total 7363
telemt_desync_suppressed_total 13842
telemt_desync_frames_bucket_total{bucket="1_2"} 4055
telemt_desync_frames_bucket_total{bucket="3_10"} 8251
telemt_desync_frames_bucket_total{bucket="gt_10"} 8899
telemt_pool_swap_total 89
telemt_pool_force_close_total 2637
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 330
telemt_me_draining_writers_reap_progress_total 29774
telemt_me_writer_removed_unexpected_total 1187
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3030
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27944
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2272
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 365
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27137
telemt_me_writer_teardown_success_total{mode="normal"} 30974
telemt_me_writer_teardown_noop_total 29775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60749
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.458270
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60749
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 330
telemt_me_refill_failed_total 591
telemt_me_writer_restored_same_endpoint_total 1081
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 1512
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 4260014
telemt_user_connections_current{user="hello"} 2871
telemt_user_octets_from_client{user="hello"} 114135430441 (106.30 GB)
telemt_user_octets_to_client{user="hello"} 1728935356663 (1.57 TB)
telemt_user_msgs_from_client{user="hello"} 59697
telemt_user_msgs_to_client{user="hello"} 266554
telemt_user_unique_ips_current{user="hello"} 1234
telemt_user_unique_ips_recent_window{user="hello"} 344
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 24951.8 (6h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3238945
telemt_connections_bad_total 119136
telemt_connections_current 2656
telemt_connections_me_current 2656
telemt_handshake_timeouts_total 1382898
telemt_upstream_connect_attempt_total 8124
telemt_upstream_connect_success_total 8017
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 8118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4400
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_reconnect_attempts_total 2215
telemt_me_reconnect_success_total 273
telemt_me_reader_eof_total 214
telemt_me_idle_close_by_peer_total 214
telemt_me_route_drop_no_conn_total 930423
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1541094
telemt_me_endpoint_quarantine_total 123
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 184
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
telemt_me_writers_active_current 45
telemt_desync_total 8547
telemt_desync_full_logged_total 2845
telemt_desync_suppressed_total 5702
telemt_desync_frames_bucket_total{bucket="1_2"} 1530
telemt_desync_frames_bucket_total{bucket="3_10"} 3244
telemt_desync_frames_bucket_total{bucket="gt_10"} 3773
telemt_pool_swap_total 26
telemt_pool_force_close_total 846
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 81
telemt_me_draining_writers_reap_progress_total 7069
telemt_me_writer_removed_unexpected_total 231
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 664
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6644
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 737
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 109
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6223
telemt_me_writer_teardown_success_total{mode="normal"} 7308
telemt_me_writer_teardown_noop_total 7070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 14075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 14248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 14297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 14378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 14378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 14378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 14378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 14378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 14378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 14378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 14378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 14378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 14378
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.185837
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 14378
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 81
telemt_me_refill_failed_total 119
telemt_me_writer_restored_same_endpoint_total 223
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 192
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1536662
telemt_user_connections_current{user="hello"} 2656
telemt_user_octets_from_client{user="hello"} 45302022416 (42.19 GB)
telemt_user_octets_to_client{user="hello"} 644354836408 (600.10 GB)
telemt_user_unique_ips_current{user="hello"} 1090
telemt_user_unique_ips_recent_window{user="hello"} 349
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 5922.9 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64923
telemt_connections_bad_total 184
telemt_connections_current 786
telemt_connections_me_current 786
telemt_handshake_timeouts_total 883
telemt_upstream_connect_attempt_total 2568
telemt_upstream_connect_success_total 2560
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 2567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1480
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 63
telemt_me_reconnect_success_total 32
telemt_me_reader_eof_total 32
telemt_me_idle_close_by_peer_total 32
telemt_me_route_drop_no_conn_total 19170
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57836
telemt_me_endpoint_quarantine_total 39
telemt_me_single_endpoint_shadow_rotate_total 53
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
telemt_me_writers_active_current 44
telemt_desync_total 405
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 282
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 146
telemt_desync_frames_bucket_total{bucket="gt_10"} 126
telemt_pool_swap_total 6
telemt_pool_force_close_total 160
telemt_me_writer_close_signal_drop_total 6
telemt_me_draining_writers_reap_progress_total 2213
telemt_me_writer_removed_unexpected_total 32
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 150
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2095
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 160
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2053
telemt_me_writer_teardown_success_total{mode="normal"} 2245
telemt_me_writer_teardown_noop_total 2213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4458
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.301466
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4458
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 6
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 29
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 57743
telemt_user_connections_current{user="hello"} 786
telemt_user_octets_from_client{user="hello"} 1215612188 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 42947590104 (40.00 GB)
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 88120.4 (24h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6525857
telemt_connections_bad_total 664578
telemt_connections_current 3243
telemt_connections_me_current 3243
telemt_handshake_timeouts_total 188272
telemt_upstream_connect_attempt_total 33355
telemt_upstream_connect_success_total 33222
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 33318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16734
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_reconnect_attempts_total 1405
telemt_me_reconnect_success_total 710
telemt_me_reader_eof_total 684
telemt_me_idle_close_by_peer_total 684
telemt_me_route_drop_no_conn_total 2013997
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 22
telemt_me_route_drop_queue_full_profile_total{profile="high"} 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5002552
telemt_me_endpoint_quarantine_total 585
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 670
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
telemt_desync_total 19084
telemt_desync_full_logged_total 6367
telemt_desync_suppressed_total 12717
telemt_desync_frames_bucket_total{bucket="1_2"} 4644
telemt_desync_frames_bucket_total{bucket="3_10"} 6957
telemt_desync_frames_bucket_total{bucket="gt_10"} 7483
telemt_pool_swap_total 97
telemt_pool_force_close_total 2652
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 336
telemt_me_draining_writers_reap_progress_total 29941
telemt_me_writer_removed_unexpected_total 667
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2430
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28185
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2568
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 84
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27289
telemt_me_writer_teardown_success_total{mode="normal"} 30615
telemt_me_writer_teardown_noop_total 29943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60558
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.868141
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60558
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 336
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 634
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 4978346
telemt_user_connections_current{user="hello"} 3243
telemt_user_octets_from_client{user="hello"} 99240397660 (92.42 GB)
telemt_user_octets_to_client{user="hello"} 2328204280568 (2.12 TB)
telemt_user_unique_ips_current{user="hello"} 1302
telemt_user_unique_ips_recent_window{user="hello"} 358
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 88117.1 (24h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5545276
telemt_connections_bad_total 520470
telemt_connections_current 3094
telemt_connections_me_current 3094
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 159056
telemt_upstream_connect_attempt_total 49680
telemt_upstream_connect_success_total 49311
telemt_upstream_connect_fail_total 310
telemt_upstream_connect_attempts_per_request{bucket="1"} 49621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18594
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 310
telemt_me_reconnect_attempts_total 4527
telemt_me_reconnect_success_total 999
telemt_me_reader_eof_total 887
telemt_me_idle_close_by_peer_total 887
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 2069841
telemt_me_route_drop_channel_closed_total 186
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4367681
telemt_me_endpoint_quarantine_total 694
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 669
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 17785
telemt_desync_full_logged_total 5998
telemt_desync_suppressed_total 11787
telemt_desync_frames_bucket_total{bucket="1_2"} 4397
telemt_desync_frames_bucket_total{bucket="3_10"} 6530
telemt_desync_frames_bucket_total{bucket="gt_10"} 6858
telemt_pool_swap_total 95
telemt_pool_force_close_total 2583
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 333
telemt_me_draining_writers_reap_progress_total 29100
telemt_me_writer_removed_unexpected_total 898
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2917
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27123
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2385
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 198
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26517
telemt_me_writer_teardown_success_total{mode="normal"} 30040
telemt_me_writer_teardown_noop_total 29104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59144
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.028532
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59144
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 333
telemt_me_refill_failed_total 201
telemt_me_writer_restored_same_endpoint_total 770
telemt_me_writer_restored_fallback_total 48
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 4371696
telemt_user_connections_current{user="hello"} 3094
telemt_user_octets_from_client{user="hello"} 83642649841 (77.90 GB)
telemt_user_octets_to_client{user="hello"} 1841646905220 (1.67 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1193
telemt_user_unique_ips_recent_window{user="hello"} 370
```