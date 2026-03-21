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

# Server Metrics 2026-03-21 15:53:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 69471.7 (19h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2475145
telemt_connections_bad_total 145203
telemt_connections_current 1402
telemt_connections_me_current 1402
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 78350
telemt_upstream_connect_attempt_total 29544
telemt_upstream_connect_success_total 29413
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 29501
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17122
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1715
telemt_me_reconnect_success_total 673
telemt_me_reader_eof_total 648
telemt_me_idle_close_by_peer_total 648
telemt_me_route_drop_no_conn_total 2124203
telemt_me_route_drop_channel_closed_total 653
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1972151
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 486
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 539
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
telemt_me_writers_active_current 42
telemt_desync_total 7806
telemt_desync_full_logged_total 2693
telemt_desync_suppressed_total 5113
telemt_desync_frames_bucket_total{bucket="1_2"} 1707
telemt_desync_frames_bucket_total{bucket="3_10"} 2964
telemt_desync_frames_bucket_total{bucket="gt_10"} 3135
telemt_pool_swap_total 75
telemt_pool_force_close_total 2243
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 508
telemt_me_draining_writers_reap_progress_total 23668
telemt_me_writer_removed_unexpected_total 626
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2040
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22038
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2124
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 119
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21425
telemt_me_writer_teardown_success_total{mode="normal"} 24078
telemt_me_writer_teardown_noop_total 23674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47752
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 221.482749
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47752
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 508
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 576
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 1973578
telemt_user_connections_current{user="hello"} 1402
telemt_user_octets_from_client{user="hello"} 27910243269 (25.99 GB)
telemt_user_octets_to_client{user="hello"} 488452886978 (454.91 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 545
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 596.8 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18580
telemt_connections_bad_total 1226
telemt_connections_current 1155
telemt_connections_me_current 1155
telemt_handshake_timeouts_total 503
telemt_upstream_connect_attempt_total 263
telemt_upstream_connect_success_total 263
telemt_upstream_connect_attempts_per_request{bucket="1"} 263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_route_drop_no_conn_total 7791
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15429
telemt_me_endpoint_quarantine_total 6
telemt_me_single_endpoint_shadow_rotate_total 8
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
telemt_desync_total 64
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 27
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 29
telemt_me_draining_writers_reap_progress_total 176
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 176
telemt_me_writer_teardown_success_total{mode="normal"} 176
telemt_me_writer_teardown_noop_total 176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 352
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.010133
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 352
telemt_user_connections_total{user="hello"} 15429
telemt_user_connections_current{user="hello"} 1155
telemt_user_octets_from_client{user="hello"} 126352524 (120.50 MB)
telemt_user_octets_to_client{user="hello"} 4392107268 (4.09 GB)
telemt_user_unique_ips_current{user="hello"} 792
telemt_user_unique_ips_recent_window{user="hello"} 397
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 69469.3 (19h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4998539
telemt_connections_bad_total 445485
telemt_connections_current 5242
telemt_connections_me_current 5242
telemt_handshake_timeouts_total 175351
telemt_upstream_connect_attempt_total 25700
telemt_upstream_connect_success_total 25645
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 25651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14000
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1163
telemt_me_reconnect_success_total 588
telemt_me_reader_eof_total 592
telemt_me_idle_close_by_peer_total 592
telemt_me_route_drop_no_conn_total 2872513
telemt_me_route_drop_channel_closed_total 46
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4088409
telemt_me_endpoint_quarantine_total 439
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 524
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
telemt_desync_total 16840
telemt_desync_full_logged_total 5666
telemt_desync_suppressed_total 11174
telemt_desync_frames_bucket_total{bucket="1_2"} 3564
telemt_desync_frames_bucket_total{bucket="3_10"} 6655
telemt_desync_frames_bucket_total{bucket="gt_10"} 6621
telemt_pool_swap_total 74
telemt_pool_force_close_total 2379
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 376
telemt_me_draining_writers_reap_progress_total 23283
telemt_me_writer_removed_unexpected_total 572
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2046
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21574
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2180
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20904
telemt_me_writer_teardown_success_total{mode="normal"} 23620
telemt_me_writer_teardown_noop_total 23315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46935
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 87.853912
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46935
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 376
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 529
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 4083529
telemt_user_connections_current{user="hello"} 5242
telemt_user_octets_from_client{user="hello"} 65548029748 (61.05 GB)
telemt_user_octets_to_client{user="hello"} 1334614501824 (1.21 TB)
telemt_user_unique_ips_current{user="hello"} 2133
telemt_user_unique_ips_recent_window{user="hello"} 620
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 69470.8 (19h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4043189
telemt_connections_bad_total 427749
telemt_connections_current 3944
telemt_connections_me_current 3944
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 141846
telemt_upstream_connect_attempt_total 30062
telemt_upstream_connect_success_total 29775
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 29915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13981
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 495
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1388
telemt_me_reconnect_success_total 608
telemt_me_reader_eof_total 570
telemt_me_idle_close_by_peer_total 570
telemt_me_route_drop_no_conn_total 1290179
telemt_me_route_drop_channel_closed_total 105
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2972571
telemt_me_endpoint_quarantine_total 446
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 528
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
telemt_desync_total 13928
telemt_desync_full_logged_total 4646
telemt_desync_suppressed_total 9282
telemt_desync_frames_bucket_total{bucket="1_2"} 3501
telemt_desync_frames_bucket_total{bucket="3_10"} 5385
telemt_desync_frames_bucket_total{bucket="gt_10"} 5042
telemt_pool_swap_total 76
telemt_pool_force_close_total 2178
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 220
telemt_me_draining_writers_reap_progress_total 22432
telemt_me_writer_removed_unexpected_total 553
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1935
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21050
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2020
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 158
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20254
telemt_me_writer_teardown_success_total{mode="normal"} 22985
telemt_me_writer_teardown_noop_total 22433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45418
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.083830
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45418
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 220
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 512
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 2972118
telemt_user_connections_current{user="hello"} 3944
telemt_user_octets_from_client{user="hello"} 63744046465 (59.37 GB)
telemt_user_octets_to_client{user="hello"} 1376349573807 (1.25 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1566
telemt_user_unique_ips_recent_window{user="hello"} 528
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 69435.2 (19h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3979888
telemt_connections_bad_total 410054
telemt_connections_current 3421
telemt_connections_me_current 3421
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 120450
telemt_upstream_connect_attempt_total 35340
telemt_upstream_connect_success_total 35101
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 35234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15316
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 295
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 864
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 1454
telemt_me_reconnect_success_total 662
telemt_me_reader_eof_total 604
telemt_me_idle_close_by_peer_total 604
telemt_me_route_drop_no_conn_total 1381322
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2954715
telemt_me_endpoint_quarantine_total 494
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 519
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
telemt_desync_total 13663
telemt_desync_full_logged_total 4533
telemt_desync_suppressed_total 9130
telemt_desync_frames_bucket_total{bucket="1_2"} 3411
telemt_desync_frames_bucket_total{bucket="3_10"} 5134
telemt_desync_frames_bucket_total{bucket="gt_10"} 5118
telemt_pool_swap_total 74
telemt_pool_force_close_total 2102
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 239
telemt_me_draining_writers_reap_progress_total 23871
telemt_me_writer_removed_unexpected_total 574
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2020
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22463
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1918
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 184
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21769
telemt_me_writer_teardown_success_total{mode="normal"} 24483
telemt_me_writer_teardown_noop_total 23877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48360
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.777583
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48360
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 239
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 569
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 2958397
telemt_user_connections_current{user="hello"} 3421
telemt_user_octets_from_client{user="hello"} 65621201145 (61.11 GB)
telemt_user_octets_to_client{user="hello"} 1363777271832 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1345
telemt_user_unique_ips_recent_window{user="hello"} 533
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 69473.9 (19h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13681250
telemt_connections_bad_total 886356
telemt_connections_current 5410
telemt_connections_me_current 5410
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 409841
telemt_upstream_connect_attempt_total 116495
telemt_upstream_connect_success_total 106577
telemt_upstream_connect_fail_total 8855
telemt_upstream_connect_attempts_per_request{bucket="1"} 115432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25849
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8855
telemt_me_keepalive_timeout_total 125
telemt_me_reconnect_attempts_total 3891
telemt_me_reconnect_success_total 1418
telemt_me_reader_eof_total 989
telemt_me_idle_close_by_peer_total 988
telemt_me_route_drop_no_conn_total 26801957
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11263892
telemt_me_endpoint_quarantine_total 536
telemt_me_single_endpoint_outage_enter_total 78
telemt_me_single_endpoint_outage_exit_total 78
telemt_me_single_endpoint_outage_reconnect_attempt_total 174
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 174
telemt_me_single_endpoint_shadow_rotate_total 544
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
telemt_me_writers_active_current 45
telemt_desync_total 19824
telemt_desync_full_logged_total 6196
telemt_desync_suppressed_total 13628
telemt_desync_frames_bucket_total{bucket="1_2"} 4313
telemt_desync_frames_bucket_total{bucket="3_10"} 8745
telemt_desync_frames_bucket_total{bucket="gt_10"} 6766
telemt_pool_swap_total 71
telemt_pool_force_close_total 2281
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 502
telemt_me_draining_writers_reap_progress_total 22188
telemt_me_writer_removed_unexpected_total 1350
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2912
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20419
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1909
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 372
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19907
telemt_me_writer_teardown_success_total{mode="normal"} 23331
telemt_me_writer_teardown_noop_total 22200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45531
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 172.944357
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45531
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 502
telemt_me_refill_failed_total 88
telemt_me_writer_restored_same_endpoint_total 992
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 348
telemt_user_connections_total{user="hello"} 11338629
telemt_user_connections_current{user="hello"} 5410
telemt_user_octets_from_client{user="hello"} 79353708505 (73.90 GB)
telemt_user_octets_to_client{user="hello"} 817850063889 (761.68 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 2023
telemt_user_unique_ips_recent_window{user="hello"} 1061
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 69441.6 (19h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3970933
telemt_connections_bad_total 431117
telemt_connections_current 3196
telemt_connections_me_current 3196
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 85580
telemt_upstream_connect_attempt_total 29180
telemt_upstream_connect_success_total 28862
telemt_upstream_connect_fail_total 273
telemt_upstream_connect_attempts_per_request{bucket="1"} 29135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15079
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 273
telemt_me_reconnect_attempts_total 2775
telemt_me_reconnect_success_total 1035
telemt_me_reader_eof_total 1038
telemt_me_idle_close_by_peer_total 1038
telemt_me_route_drop_no_conn_total 1693368
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3073052
telemt_me_endpoint_quarantine_total 427
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 516
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
telemt_desync_total 14802
telemt_desync_full_logged_total 5141
telemt_desync_suppressed_total 9661
telemt_desync_frames_bucket_total{bucket="1_2"} 2901
telemt_desync_frames_bucket_total{bucket="3_10"} 5875
telemt_desync_frames_bucket_total{bucket="gt_10"} 6026
telemt_pool_swap_total 69
telemt_pool_force_close_total 2009
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 205
telemt_me_draining_writers_reap_progress_total 24472
telemt_me_writer_removed_unexpected_total 1005
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2454
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23059
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1723
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 286
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22463
telemt_me_writer_teardown_success_total{mode="normal"} 25513
telemt_me_writer_teardown_noop_total 24473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49986
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.317132
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49986
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 205
telemt_me_refill_failed_total 95
telemt_me_writer_restored_same_endpoint_total 896
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 3056406
telemt_user_connections_current{user="hello"} 3196
telemt_user_octets_from_client{user="hello"} 80022207132 (74.53 GB)
telemt_user_octets_to_client{user="hello"} 1263491015874 (1.15 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1175
telemt_user_unique_ips_recent_window{user="hello"} 1248
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 6276.9 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 982631
telemt_connections_bad_total 33121
telemt_connections_current 4094
telemt_connections_me_current 4094
telemt_handshake_timeouts_total 462741
telemt_upstream_connect_attempt_total 2213
telemt_upstream_connect_success_total 2174
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 2207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 253
telemt_me_reconnect_success_total 88
telemt_me_reader_eof_total 79
telemt_me_idle_close_by_peer_total 79
telemt_me_route_drop_no_conn_total 402143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 446767
telemt_me_endpoint_quarantine_total 24
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 46
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
telemt_desync_total 2228
telemt_desync_full_logged_total 726
telemt_desync_suppressed_total 1502
telemt_desync_frames_bucket_total{bucket="1_2"} 402
telemt_desync_frames_bucket_total{bucket="3_10"} 843
telemt_desync_frames_bucket_total{bucket="gt_10"} 983
telemt_pool_swap_total 5
telemt_pool_force_close_total 172
telemt_me_writer_close_signal_drop_total 13
telemt_me_draining_writers_reap_progress_total 1850
telemt_me_writer_removed_unexpected_total 80
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1756
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 133
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 39
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1678
telemt_me_writer_teardown_success_total{mode="normal"} 1930
telemt_me_writer_teardown_noop_total 1850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3780
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.790170
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3780
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 13
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 77
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 446149
telemt_user_connections_current{user="hello"} 4094
telemt_user_octets_from_client{user="hello"} 11861996672 (11.05 GB)
telemt_user_octets_to_client{user="hello"} 166250477508 (154.83 GB)
telemt_user_unique_ips_current{user="hello"} 1646
telemt_user_unique_ips_recent_window{user="hello"} 970
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 67427.1 (18h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1267516
telemt_connections_bad_total 141250
telemt_connections_current 811
telemt_connections_me_current 811
telemt_handshake_timeouts_total 453666
telemt_upstream_connect_attempt_total 31405
telemt_upstream_connect_success_total 31398
telemt_upstream_connect_attempts_per_request{bucket="1"} 31398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18453
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1342
telemt_me_reconnect_success_total 567
telemt_me_reader_eof_total 564
telemt_me_idle_close_by_peer_total 564
telemt_me_route_drop_no_conn_total 277689
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 596304
telemt_me_endpoint_quarantine_total 600
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 562
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
telemt_me_writers_active_current 43
telemt_desync_total 3622
telemt_desync_full_logged_total 1314
telemt_desync_suppressed_total 2308
telemt_desync_frames_bucket_total{bucket="1_2"} 667
telemt_desync_frames_bucket_total{bucket="3_10"} 1303
telemt_desync_frames_bucket_total{bucket="gt_10"} 1652
telemt_pool_swap_total 73
telemt_pool_force_close_total 1711
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 114
telemt_me_draining_writers_reap_progress_total 28141
telemt_me_writer_removed_unexpected_total 534
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2130
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26561
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1682
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26430
telemt_me_writer_teardown_success_total{mode="normal"} 28691
telemt_me_writer_teardown_noop_total 28141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56832
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.540240
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56832
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 114
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 472
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 595917
telemt_user_connections_current{user="hello"} 811
telemt_user_octets_from_client{user="hello"} 12357779031 (11.51 GB)
telemt_user_octets_to_client{user="hello"} 229546819313 (213.78 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 318
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 69446.1 (19h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4416502
telemt_connections_bad_total 407987
telemt_connections_current 5052
telemt_connections_me_current 5052
telemt_handshake_timeouts_total 143300
telemt_upstream_connect_attempt_total 27501
telemt_upstream_connect_success_total 27388
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 27466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13786
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_reconnect_attempts_total 1189
telemt_me_reconnect_success_total 618
telemt_me_reader_eof_total 585
telemt_me_idle_close_by_peer_total 585
telemt_me_route_drop_no_conn_total 1338104
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3492360
telemt_me_endpoint_quarantine_total 501
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 529
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
telemt_desync_total 13632
telemt_desync_full_logged_total 4510
telemt_desync_suppressed_total 9122
telemt_desync_frames_bucket_total{bucket="1_2"} 3219
telemt_desync_frames_bucket_total{bucket="3_10"} 5074
telemt_desync_frames_bucket_total{bucket="gt_10"} 5339
telemt_pool_swap_total 77
telemt_pool_force_close_total 2003
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 226
telemt_me_draining_writers_reap_progress_total 24648
telemt_me_writer_removed_unexpected_total 573
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1973
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23250
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1955
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 48
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22645
telemt_me_writer_teardown_success_total{mode="normal"} 25223
telemt_me_writer_teardown_noop_total 24648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49871
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.917363
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49871
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 226
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 547
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 3483884
telemt_user_connections_current{user="hello"} 5052
telemt_user_octets_from_client{user="hello"} 70423368380 (65.59 GB)
telemt_user_octets_to_client{user="hello"} 1636263920936 (1.49 TB)
telemt_user_unique_ips_current{user="hello"} 1865
telemt_user_unique_ips_recent_window{user="hello"} 791
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 69442.8 (19h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3912961
telemt_connections_bad_total 357597
telemt_connections_current 1973
telemt_connections_me_current 1973
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 120944
telemt_upstream_connect_attempt_total 44010
telemt_upstream_connect_success_total 43701
telemt_upstream_connect_fail_total 256
telemt_upstream_connect_attempts_per_request{bucket="1"} 43957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15657
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 602
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 256
telemt_me_reconnect_attempts_total 3873
telemt_me_reconnect_success_total 873
telemt_me_reader_eof_total 763
telemt_me_idle_close_by_peer_total 763
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 1420205
telemt_me_route_drop_channel_closed_total 105
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3121233
telemt_me_endpoint_quarantine_total 582
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 20
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 20
telemt_me_single_endpoint_shadow_rotate_total 524
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
telemt_me_writers_active_current 33
telemt_desync_total 12198
telemt_desync_full_logged_total 4133
telemt_desync_suppressed_total 8065
telemt_desync_frames_bucket_total{bucket="1_2"} 3045
telemt_desync_frames_bucket_total{bucket="3_10"} 4532
telemt_desync_frames_bucket_total{bucket="gt_10"} 4621
telemt_pool_swap_total 75
telemt_pool_force_close_total 1944
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 216
telemt_me_draining_writers_reap_progress_total 24047
telemt_me_writer_removed_unexpected_total 776
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2361
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22495
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1778
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 166
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22103
telemt_me_writer_teardown_success_total{mode="normal"} 24856
telemt_me_writer_teardown_noop_total 24048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48904
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.166021
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48904
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 216
telemt_me_refill_failed_total 170
telemt_me_writer_restored_same_endpoint_total 677
telemt_me_writer_restored_fallback_total 42
telemt_me_async_recovery_trigger_total 57
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 3129529
telemt_user_connections_current{user="hello"} 1973
telemt_user_octets_from_client{user="hello"} 56743024005 (52.85 GB)
telemt_user_octets_to_client{user="hello"} 1336586123268 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1034
telemt_user_unique_ips_recent_window{user="hello"} 469
```