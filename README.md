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

# Server Metrics 2026-03-21 16:29:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 71605.3 (19h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2562436
telemt_connections_bad_total 153103
telemt_connections_current 1498
telemt_connections_me_current 1498
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 80820
telemt_upstream_connect_attempt_total 30184
telemt_upstream_connect_success_total 30053
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 30141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17529
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1744
telemt_me_reconnect_success_total 687
telemt_me_reader_eof_total 660
telemt_me_idle_close_by_peer_total 660
telemt_me_route_drop_no_conn_total 2157782
telemt_me_route_drop_channel_closed_total 675
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2041810
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 492
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 558
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
telemt_desync_total 8141
telemt_desync_full_logged_total 2817
telemt_desync_suppressed_total 5324
telemt_desync_frames_bucket_total{bucket="1_2"} 1783
telemt_desync_frames_bucket_total{bucket="3_10"} 3089
telemt_desync_frames_bucket_total{bucket="gt_10"} 3269
telemt_pool_swap_total 77
telemt_pool_force_close_total 2334
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 526
telemt_me_draining_writers_reap_progress_total 24266
telemt_me_writer_removed_unexpected_total 638
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2090
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22598
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2210
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21932
telemt_me_writer_teardown_success_total{mode="normal"} 24688
telemt_me_writer_teardown_noop_total 24273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48961
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 229.101148
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48961
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 526
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 588
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2043023
telemt_user_connections_current{user="hello"} 1498
telemt_user_octets_from_client{user="hello"} 29145226925 (27.14 GB)
telemt_user_octets_to_client{user="hello"} 506595663738 (471.80 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 572
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 2730.5 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124442
telemt_connections_bad_total 4849
telemt_connections_current 3803
telemt_connections_me_current 3803
telemt_handshake_timeouts_total 2334
telemt_upstream_connect_attempt_total 1121
telemt_upstream_connect_success_total 1120
telemt_upstream_connect_attempts_per_request{bucket="1"} 1120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 565
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 10
telemt_me_reconnect_success_total 9
telemt_me_reader_eof_total 9
telemt_me_idle_close_by_peer_total 9
telemt_me_route_drop_no_conn_total 96345
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108634
telemt_me_endpoint_quarantine_total 19
telemt_me_single_endpoint_shadow_rotate_total 26
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
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
telemt_me_writers_warm_current 8
telemt_desync_total 320
telemt_desync_full_logged_total 169
telemt_desync_suppressed_total 151
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 128
telemt_desync_frames_bucket_total{bucket="gt_10"} 105
telemt_pool_swap_total 2
telemt_pool_force_close_total 27
telemt_me_writer_close_signal_drop_total 19
telemt_me_draining_writers_reap_progress_total 951
telemt_me_writer_removed_unexpected_total 9
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 68
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 892
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 924
telemt_me_writer_teardown_success_total{mode="normal"} 960
telemt_me_writer_teardown_noop_total 951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1911
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.075435
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1911
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 19
telemt_me_writer_restored_same_endpoint_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 108197
telemt_user_connections_current{user="hello"} 3803
telemt_user_octets_from_client{user="hello"} 930640932 (887.53 MB)
telemt_user_octets_to_client{user="hello"} 20871535928 (19.44 GB)
telemt_user_unique_ips_current{user="hello"} 1363
telemt_user_unique_ips_recent_window{user="hello"} 746
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 71602.9 (19h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5299113
telemt_connections_bad_total 452190
telemt_connections_current 5638
telemt_connections_me_current 5638
telemt_handshake_timeouts_total 178036
telemt_upstream_connect_attempt_total 26350
telemt_upstream_connect_success_total 26292
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 26298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14371
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1175
telemt_me_reconnect_success_total 596
telemt_me_reader_eof_total 600
telemt_me_idle_close_by_peer_total 600
telemt_me_route_drop_no_conn_total 3256972
telemt_me_route_drop_channel_closed_total 47
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4358945
telemt_me_endpoint_quarantine_total 446
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 537
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
telemt_me_writers_active_current 45
telemt_desync_total 17819
telemt_desync_full_logged_total 5985
telemt_desync_suppressed_total 11834
telemt_desync_frames_bucket_total{bucket="1_2"} 3742
telemt_desync_frames_bucket_total{bucket="3_10"} 7092
telemt_desync_frames_bucket_total{bucket="gt_10"} 6985
telemt_pool_swap_total 76
telemt_pool_force_close_total 2498
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 396
telemt_me_draining_writers_reap_progress_total 23931
telemt_me_writer_removed_unexpected_total 580
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2098
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22138
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 34
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2294
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 204
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21433
telemt_me_writer_teardown_success_total{mode="normal"} 24236
telemt_me_writer_teardown_noop_total 23965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48201
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 97.313623
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48201
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 396
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 537
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 4353710
telemt_user_connections_current{user="hello"} 5638
telemt_user_octets_from_client{user="hello"} 68178893856 (63.50 GB)
telemt_user_octets_to_client{user="hello"} 1385323696648 (1.26 TB)
telemt_user_unique_ips_current{user="hello"} 2104
telemt_user_unique_ips_recent_window{user="hello"} 712
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 71604.4 (19h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4235982
telemt_connections_bad_total 439120
telemt_connections_current 4099
telemt_connections_me_current 4099
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 146934
telemt_upstream_connect_attempt_total 30731
telemt_upstream_connect_success_total 30443
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 30584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15582
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14338
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 496
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1402
telemt_me_reconnect_success_total 621
telemt_me_reader_eof_total 585
telemt_me_idle_close_by_peer_total 585
telemt_me_route_drop_no_conn_total 1353550
telemt_me_route_drop_channel_closed_total 110
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3131225
telemt_me_endpoint_quarantine_total 452
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 547
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
telemt_desync_total 14984
telemt_desync_full_logged_total 4946
telemt_desync_suppressed_total 10038
telemt_desync_frames_bucket_total{bucket="1_2"} 3709
telemt_desync_frames_bucket_total{bucket="3_10"} 5799
telemt_desync_frames_bucket_total{bucket="gt_10"} 5476
telemt_pool_swap_total 78
telemt_pool_force_close_total 2292
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 235
telemt_me_draining_writers_reap_progress_total 23070
telemt_me_writer_removed_unexpected_total 566
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1992
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21624
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2131
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 161
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20778
telemt_me_writer_teardown_success_total{mode="normal"} 23616
telemt_me_writer_teardown_noop_total 23073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46689
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 26.264149
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46689
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 235
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 525
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 3130482
telemt_user_connections_current{user="hello"} 4099
telemt_user_octets_from_client{user="hello"} 70440902717 (65.60 GB)
telemt_user_octets_to_client{user="hello"} 1440072435563 (1.31 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1588
telemt_user_unique_ips_recent_window{user="hello"} 588
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 71568.3 (19h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4181776
telemt_connections_bad_total 422292
telemt_connections_current 3522
telemt_connections_me_current 3522
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 126601
telemt_upstream_connect_attempt_total 35975
telemt_upstream_connect_success_total 35731
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 35864
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15676
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 296
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 865
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 1466
telemt_me_reconnect_success_total 672
telemt_me_reader_eof_total 615
telemt_me_idle_close_by_peer_total 615
telemt_me_route_drop_no_conn_total 1447171
telemt_me_route_drop_channel_closed_total 42
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3112834
telemt_me_endpoint_quarantine_total 504
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 537
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
telemt_me_writers_active_current 45
telemt_desync_total 14418
telemt_desync_full_logged_total 4744
telemt_desync_suppressed_total 9674
telemt_desync_frames_bucket_total{bucket="1_2"} 3580
telemt_desync_frames_bucket_total{bucket="3_10"} 5442
telemt_desync_frames_bucket_total{bucket="gt_10"} 5396
telemt_pool_swap_total 76
telemt_pool_force_close_total 2209
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 259
telemt_me_draining_writers_reap_progress_total 24482
telemt_me_writer_removed_unexpected_total 584
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2072
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23017
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2024
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 185
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22273
telemt_me_writer_teardown_success_total{mode="normal"} 25089
telemt_me_writer_teardown_noop_total 24489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49578
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.691947
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49578
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 259
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 579
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 3116207
telemt_user_connections_current{user="hello"} 3522
telemt_user_octets_from_client{user="hello"} 76466797065 (71.22 GB)
telemt_user_octets_to_client{user="hello"} 1436698442204 (1.31 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1351
telemt_user_unique_ips_recent_window{user="hello"} 545
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 71622.3 (19h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14438325
telemt_connections_bad_total 930113
telemt_connections_current 5638
telemt_connections_me_current 5638
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 423407
telemt_upstream_connect_attempt_total 117095
telemt_upstream_connect_success_total 107161
telemt_upstream_connect_fail_total 8859
telemt_upstream_connect_attempts_per_request{bucket="1"} 116020
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26179
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8859
telemt_me_keepalive_timeout_total 205
telemt_me_reconnect_attempts_total 3905
telemt_me_reconnect_success_total 1429
telemt_me_reader_eof_total 999
telemt_me_idle_close_by_peer_total 998
telemt_me_route_drop_no_conn_total 28595755
telemt_me_route_drop_channel_closed_total 93
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11919798
telemt_me_endpoint_quarantine_total 541
telemt_me_single_endpoint_outage_enter_total 78
telemt_me_single_endpoint_outage_exit_total 78
telemt_me_single_endpoint_outage_reconnect_attempt_total 174
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 174
telemt_me_single_endpoint_shadow_rotate_total 557
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
telemt_me_writers_active_current 43
telemt_desync_total 21094
telemt_desync_full_logged_total 6505
telemt_desync_suppressed_total 14589
telemt_desync_frames_bucket_total{bucket="1_2"} 4636
telemt_desync_frames_bucket_total{bucket="3_10"} 9215
telemt_desync_frames_bucket_total{bucket="gt_10"} 7243
telemt_pool_swap_total 73
telemt_pool_force_close_total 2391
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 523
telemt_me_draining_writers_reap_progress_total 22748
telemt_me_writer_removed_unexpected_total 1360
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2965
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20921
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2011
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 380
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20357
telemt_me_writer_teardown_success_total{mode="normal"} 23886
telemt_me_writer_teardown_noop_total 22760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46646
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 177.606043
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46646
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 523
telemt_me_refill_failed_total 88
telemt_me_writer_restored_same_endpoint_total 1002
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 348
telemt_user_connections_total{user="hello"} 11994308
telemt_user_connections_current{user="hello"} 5638
telemt_user_octets_from_client{user="hello"} 92300955233 (85.96 GB)
telemt_user_octets_to_client{user="hello"} 832755344389 (775.56 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 2127
telemt_user_unique_ips_recent_window{user="hello"} 1195
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 71575.0 (19h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4181822
telemt_connections_bad_total 446661
telemt_connections_current 4155
telemt_connections_me_current 4155
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 88352
telemt_upstream_connect_attempt_total 29843
telemt_upstream_connect_success_total 29503
telemt_upstream_connect_fail_total 292
telemt_upstream_connect_attempts_per_request{bucket="1"} 29795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15440
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 292
telemt_me_reconnect_attempts_total 3017
telemt_me_reconnect_success_total 1064
telemt_me_reader_eof_total 1058
telemt_me_idle_close_by_peer_total 1058
telemt_me_route_drop_no_conn_total 1795698
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3229485
telemt_me_endpoint_quarantine_total 436
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 533
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
telemt_desync_total 15630
telemt_desync_full_logged_total 5422
telemt_desync_suppressed_total 10208
telemt_desync_frames_bucket_total{bucket="1_2"} 3054
telemt_desync_frames_bucket_total{bucket="3_10"} 6195
telemt_desync_frames_bucket_total{bucket="gt_10"} 6381
telemt_pool_swap_total 71
telemt_pool_force_close_total 2104
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 213
telemt_me_draining_writers_reap_progress_total 25078
telemt_me_writer_removed_unexpected_total 1025
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2518
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23621
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1803
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 301
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22974
telemt_me_writer_teardown_success_total{mode="normal"} 26139
telemt_me_writer_teardown_noop_total 25079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51218
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.639398
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51218
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 213
telemt_me_refill_failed_total 107
telemt_me_writer_restored_same_endpoint_total 919
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 3212464
telemt_user_connections_current{user="hello"} 4155
telemt_user_octets_from_client{user="hello"} 83791166696 (78.04 GB)
telemt_user_octets_to_client{user="hello"} 1319540887922 (1.20 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1653
telemt_user_unique_ips_recent_window{user="hello"} 599
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 8410.6 (2h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1305367
telemt_connections_bad_total 47091
telemt_connections_current 3243
telemt_connections_me_current 3243
telemt_handshake_timeouts_total 608000
telemt_upstream_connect_attempt_total 2903
telemt_upstream_connect_success_total 2850
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 2897
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1547
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_reconnect_attempts_total 414
telemt_me_reconnect_success_total 107
telemt_me_reader_eof_total 100
telemt_me_idle_close_by_peer_total 100
telemt_me_route_drop_no_conn_total 488343
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 598395
telemt_me_endpoint_quarantine_total 36
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 64
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
telemt_me_writers_active_current 42
telemt_desync_total 3237
telemt_desync_full_logged_total 1011
telemt_desync_suppressed_total 2226
telemt_desync_frames_bucket_total{bucket="1_2"} 620
telemt_desync_frames_bucket_total{bucket="3_10"} 1173
telemt_desync_frames_bucket_total{bucket="gt_10"} 1444
telemt_pool_swap_total 8
telemt_pool_force_close_total 264
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 24
telemt_me_draining_writers_reap_progress_total 2458
telemt_me_writer_removed_unexpected_total 101
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 229
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2330
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 218
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2194
telemt_me_writer_teardown_success_total{mode="normal"} 2559
telemt_me_writer_teardown_noop_total 2458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 5017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 5017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 5017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 5017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 5017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 5017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 5017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 5017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 5017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 5017
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.828526
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 5017
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 24
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 89
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 597498
telemt_user_connections_current{user="hello"} 3243
telemt_user_octets_from_client{user="hello"} 14378289604 (13.39 GB)
telemt_user_octets_to_client{user="hello"} 224367164528 (208.96 GB)
telemt_user_unique_ips_current{user="hello"} 1253
telemt_user_unique_ips_recent_window{user="hello"} 563
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 69561.1 (19h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1324861
telemt_connections_bad_total 147745
telemt_connections_current 809
telemt_connections_me_current 809
telemt_handshake_timeouts_total 470339
telemt_upstream_connect_attempt_total 32189
telemt_upstream_connect_success_total 32180
telemt_upstream_connect_attempts_per_request{bucket="1"} 32180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18902
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1366
telemt_me_reconnect_success_total 573
telemt_me_reader_eof_total 574
telemt_me_idle_close_by_peer_total 574
telemt_me_route_drop_no_conn_total 292358
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 626885
telemt_me_endpoint_quarantine_total 616
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 580
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
telemt_me_writers_active_current 42
telemt_desync_total 3773
telemt_desync_full_logged_total 1352
telemt_desync_suppressed_total 2421
telemt_desync_frames_bucket_total{bucket="1_2"} 719
telemt_desync_frames_bucket_total{bucket="3_10"} 1344
telemt_desync_frames_bucket_total{bucket="gt_10"} 1710
telemt_pool_swap_total 76
telemt_pool_force_close_total 1799
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 115
telemt_me_draining_writers_reap_progress_total 28838
telemt_me_writer_removed_unexpected_total 542
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2189
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27209
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1769
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27039
telemt_me_writer_teardown_success_total{mode="normal"} 29398
telemt_me_writer_teardown_noop_total 28838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58236
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.760416
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58236
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 115
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 478
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 626443
telemt_user_connections_current{user="hello"} 809
telemt_user_octets_from_client{user="hello"} 12922838291 (12.04 GB)
telemt_user_octets_to_client{user="hello"} 243131401553 (226.43 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 71579.4 (19h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4657761
telemt_connections_bad_total 433908
telemt_connections_current 4695
telemt_connections_me_current 4695
telemt_handshake_timeouts_total 152712
telemt_upstream_connect_attempt_total 28194
telemt_upstream_connect_success_total 28076
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 28158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14154
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_reconnect_attempts_total 1204
telemt_me_reconnect_success_total 632
telemt_me_reader_eof_total 600
telemt_me_idle_close_by_peer_total 600
telemt_me_route_drop_no_conn_total 1429585
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3683318
telemt_me_endpoint_quarantine_total 511
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 547
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
telemt_me_writers_active_current 47
telemt_desync_total 14371
telemt_desync_full_logged_total 4742
telemt_desync_suppressed_total 9629
telemt_desync_frames_bucket_total{bucket="1_2"} 3394
telemt_desync_frames_bucket_total{bucket="3_10"} 5341
telemt_desync_frames_bucket_total{bucket="gt_10"} 5636
telemt_pool_swap_total 79
telemt_pool_force_close_total 2089
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 246
telemt_me_draining_writers_reap_progress_total 25273
telemt_me_writer_removed_unexpected_total 587
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2031
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23832
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2041
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 48
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23184
telemt_me_writer_teardown_success_total{mode="normal"} 25863
telemt_me_writer_teardown_noop_total 25274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51137
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.371941
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51137
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 246
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 561
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 3673743
telemt_user_connections_current{user="hello"} 4695
telemt_user_octets_from_client{user="hello"} 73390625952 (68.35 GB)
telemt_user_octets_to_client{user="hello"} 1723502326100 (1.57 TB)
telemt_user_unique_ips_current{user="hello"} 1673
telemt_user_unique_ips_recent_window{user="hello"} 619
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 71576.4 (19h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4113099
telemt_connections_bad_total 371166
telemt_connections_current 4124
telemt_connections_me_current 4124
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 128164
telemt_upstream_connect_attempt_total 44673
telemt_upstream_connect_success_total 44359
telemt_upstream_connect_fail_total 258
telemt_upstream_connect_attempts_per_request{bucket="1"} 44617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16004
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 602
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 258
telemt_me_reconnect_attempts_total 4048
telemt_me_reconnect_success_total 901
telemt_me_reader_eof_total 780
telemt_me_idle_close_by_peer_total 780
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 1503332
telemt_me_route_drop_channel_closed_total 116
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3280386
telemt_me_endpoint_quarantine_total 592
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 543
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
telemt_me_writers_active_current 46
telemt_desync_total 12776
telemt_desync_full_logged_total 4329
telemt_desync_suppressed_total 8447
telemt_desync_frames_bucket_total{bucket="1_2"} 3183
telemt_desync_frames_bucket_total{bucket="3_10"} 4750
telemt_desync_frames_bucket_total{bucket="gt_10"} 4843
telemt_pool_swap_total 77
telemt_pool_force_close_total 2034
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 227
telemt_me_draining_writers_reap_progress_total 24641
telemt_me_writer_removed_unexpected_total 793
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2432
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23035
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1861
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22607
telemt_me_writer_teardown_success_total{mode="normal"} 25467
telemt_me_writer_teardown_noop_total 24642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50109
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.664062
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50109
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 227
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 693
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 3288250
telemt_user_connections_current{user="hello"} 4124
telemt_user_octets_from_client{user="hello"} 59536723825 (55.45 GB)
telemt_user_octets_to_client{user="hello"} 1395151917544 (1.27 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1567
telemt_user_unique_ips_recent_window{user="hello"} 553
```