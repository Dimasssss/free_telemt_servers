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

# Server Metrics 2026-03-21 23:07:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 7243.1 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123728
telemt_connections_bad_total 9697
telemt_connections_current 705
telemt_connections_me_current 705
telemt_handshake_timeouts_total 5887
telemt_upstream_connect_attempt_total 2812
telemt_upstream_connect_success_total 2811
telemt_upstream_connect_attempts_per_request{bucket="1"} 2811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1048
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1751
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 72
telemt_me_reconnect_success_total 38
telemt_me_reader_eof_total 38
telemt_me_idle_close_by_peer_total 38
telemt_me_route_drop_no_conn_total 25686
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100343
telemt_me_endpoint_quarantine_total 43
telemt_me_single_endpoint_shadow_rotate_total 63
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
telemt_me_writers_active_current 48
telemt_me_writers_warm_current 16
telemt_desync_total 626
telemt_desync_full_logged_total 198
telemt_desync_suppressed_total 428
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 198
telemt_desync_frames_bucket_total{bucket="gt_10"} 299
telemt_pool_swap_total 7
telemt_pool_force_close_total 188
telemt_me_writer_close_signal_drop_total 15
telemt_me_draining_writers_reap_progress_total 2455
telemt_me_writer_removed_unexpected_total 36
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 176
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2316
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 184
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2267
telemt_me_writer_teardown_success_total{mode="normal"} 2492
telemt_me_writer_teardown_noop_total 2455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4947
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.509662
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4947
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 15
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 100240
telemt_user_connections_current{user="hello"} 705
telemt_user_octets_from_client{user="hello"} 1252716436 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 36418193320 (33.92 GB)
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 20608.2 (5h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 634969
telemt_connections_bad_total 29755
telemt_connections_current 757
telemt_connections_me_current 757
telemt_handshake_timeouts_total 24031
telemt_upstream_connect_attempt_total 8524
telemt_upstream_connect_success_total 8375
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 8509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4600
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_reconnect_attempts_total 691
telemt_me_reconnect_success_total 255
telemt_me_reader_eof_total 216
telemt_me_idle_close_by_peer_total 216
telemt_me_route_drop_no_conn_total 319515
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 517512
telemt_me_endpoint_quarantine_total 170
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 164
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_me_writers_active_current 42
telemt_desync_total 2302
telemt_desync_full_logged_total 1314
telemt_desync_suppressed_total 988
telemt_desync_frames_bucket_total{bucket="1_2"} 483
telemt_desync_frames_bucket_total{bucket="3_10"} 865
telemt_desync_frames_bucket_total{bucket="gt_10"} 954
telemt_pool_swap_total 22
telemt_pool_force_close_total 626
telemt_me_writer_close_signal_drop_total 51
telemt_me_draining_writers_reap_progress_total 7507
telemt_me_writer_removed_unexpected_total 205
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 649
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7061
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 619
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6881
telemt_me_writer_teardown_success_total{mode="normal"} 7710
telemt_me_writer_teardown_noop_total 7507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 14779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 15037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 15111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 15203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 15215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 15217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 15217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 15217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 15217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 15217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 15217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 15217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 15217
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.240198
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 15217
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 51
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 179
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 516807
telemt_user_connections_current{user="hello"} 757
telemt_user_octets_from_client{user="hello"} 8781247232 (8.18 GB)
telemt_user_octets_to_client{user="hello"} 177450576504 (165.26 GB)
telemt_user_unique_ips_current{user="hello"} 498
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 95468.8 (26h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7334104
telemt_connections_bad_total 563923
telemt_connections_current 2193
telemt_connections_me_current 2193
telemt_handshake_timeouts_total 234685
telemt_upstream_connect_attempt_total 34466
telemt_upstream_connect_success_total 34397
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 34404
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18691
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1468
telemt_me_reconnect_success_total 721
telemt_me_reader_eof_total 730
telemt_me_idle_close_by_peer_total 730
telemt_me_route_drop_no_conn_total 4481416
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5998735
telemt_me_endpoint_quarantine_total 600
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 705
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
telemt_me_writers_warm_current 29
telemt_desync_total 25463
telemt_desync_full_logged_total 8395
telemt_desync_suppressed_total 17068
telemt_desync_frames_bucket_total{bucket="1_2"} 5456
telemt_desync_frames_bucket_total{bucket="3_10"} 9951
telemt_desync_frames_bucket_total{bucket="gt_10"} 10056
telemt_pool_swap_total 102
telemt_pool_force_close_total 3450
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 560
telemt_me_draining_writers_reap_progress_total 31376
telemt_me_writer_removed_unexpected_total 702
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2666
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28989
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3211
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27926
telemt_me_writer_teardown_success_total{mode="normal"} 31655
telemt_me_writer_teardown_noop_total 31420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63075
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 151.344595
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63075
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 560
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 644
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 5991379
telemt_user_connections_current{user="hello"} 2193
telemt_user_octets_from_client{user="hello"} 102835454112 (95.77 GB)
telemt_user_octets_to_client{user="hello"} 1952801854440 (1.78 TB)
telemt_user_unique_ips_current{user="hello"} 1009
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 95470.5 (26h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6029844
telemt_connections_bad_total 576136
telemt_connections_current 1780
telemt_connections_me_current 1780
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 198376
telemt_upstream_connect_attempt_total 38402
telemt_upstream_connect_success_total 38064
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 38242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19125
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18369
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 543
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1788
telemt_me_reconnect_success_total 753
telemt_me_reader_eof_total 730
telemt_me_idle_close_by_peer_total 730
telemt_me_route_drop_no_conn_total 2131066
telemt_me_route_drop_channel_closed_total 250
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4513704
telemt_me_endpoint_quarantine_total 580
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 727
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
telemt_me_writers_warm_current 26
telemt_desync_total 21688
telemt_desync_full_logged_total 7278
telemt_desync_suppressed_total 14410
telemt_desync_frames_bucket_total{bucket="1_2"} 5243
telemt_desync_frames_bucket_total{bucket="3_10"} 8403
telemt_desync_frames_bucket_total{bucket="gt_10"} 8042
telemt_pool_swap_total 104
telemt_pool_force_close_total 3141
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 342
telemt_me_draining_writers_reap_progress_total 29932
telemt_me_writer_removed_unexpected_total 705
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2558
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28013
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2942
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26791
telemt_me_writer_teardown_success_total{mode="normal"} 30571
telemt_me_writer_teardown_noop_total 29938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60509
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.823959
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60509
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 342
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 649
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 4467339
telemt_user_connections_current{user="hello"} 1780
telemt_user_octets_from_client{user="hello"} 137270809469 (127.84 GB)
telemt_user_octets_to_client{user="hello"} 2085260289183 (1.90 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 868
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 95434.5 (26h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5952635
telemt_connections_bad_total 537755
telemt_connections_current 1642
telemt_connections_me_current 1642
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 188989
telemt_upstream_connect_attempt_total 44768
telemt_upstream_connect_success_total 44467
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 44602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19791
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1045
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1792
telemt_me_reconnect_success_total 808
telemt_me_reader_eof_total 755
telemt_me_idle_close_by_peer_total 755
telemt_me_route_drop_no_conn_total 2086808
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4447074
telemt_me_endpoint_quarantine_total 639
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 710
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
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
telemt_me_writers_warm_current 11
telemt_desync_total 21612
telemt_desync_full_logged_total 7157
telemt_desync_suppressed_total 14455
telemt_desync_frames_bucket_total{bucket="1_2"} 5308
telemt_desync_frames_bucket_total{bucket="3_10"} 8244
telemt_desync_frames_bucket_total{bucket="gt_10"} 8060
telemt_pool_swap_total 102
telemt_pool_force_close_total 3021
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 363
telemt_me_draining_writers_reap_progress_total 31336
telemt_me_writer_removed_unexpected_total 723
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2636
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29429
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2806
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28315
telemt_me_writer_teardown_success_total{mode="normal"} 32065
telemt_me_writer_teardown_noop_total 31347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63412
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.129617
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63412
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 363
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 699
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 4448607
telemt_user_connections_current{user="hello"} 1642
telemt_user_octets_from_client{user="hello"} 130337546835 (121.39 GB)
telemt_user_octets_to_client{user="hello"} 2037193033635 (1.85 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 777
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 95472.9 (26h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19807401
telemt_connections_bad_total 1421140
telemt_connections_current 2146
telemt_connections_me_current 2146
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 567706
telemt_upstream_connect_attempt_total 185887
telemt_upstream_connect_success_total 168390
telemt_upstream_connect_fail_total 15951
telemt_upstream_connect_attempts_per_request{bucket="1"} 184341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 119380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38914
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1220
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8876
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15951
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64171
telemt_me_reconnect_success_total 2094
telemt_me_reader_eof_total 1303
telemt_me_idle_close_by_peer_total 1302
telemt_me_route_drop_no_conn_total 39427312
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16169187
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 716
telemt_me_single_endpoint_outage_enter_total 121
telemt_me_single_endpoint_outage_exit_total 121
telemt_me_single_endpoint_outage_reconnect_attempt_total 257
telemt_me_single_endpoint_outage_reconnect_success_total 60
telemt_me_single_endpoint_quarantine_bypass_total 257
telemt_me_single_endpoint_shadow_rotate_total 744
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_me_writers_active_current 39
telemt_me_writers_warm_current 9
telemt_desync_total 31078
telemt_desync_full_logged_total 9219
telemt_desync_suppressed_total 21859
telemt_desync_frames_bucket_total{bucket="1_2"} 6795
telemt_desync_frames_bucket_total{bucket="3_10"} 13763
telemt_desync_frames_bucket_total{bucket="gt_10"} 10520
telemt_pool_swap_total 97
telemt_pool_force_close_total 3261
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 744
telemt_me_draining_writers_reap_progress_total 29566
telemt_me_writer_removed_unexpected_total 1964
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4065
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27198
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2745
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 516
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26305
telemt_me_writer_teardown_success_total{mode="normal"} 31263
telemt_me_writer_teardown_noop_total 29592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60855
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 209.313739
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60855
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 744
telemt_me_refill_failed_total 3783
telemt_me_writer_restored_same_endpoint_total 1453
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14670
telemt_me_writer_removed_unexpected_minus_restored_total 490
telemt_user_connections_total{user="hello"} 16295097
telemt_user_connections_current{user="hello"} 2146
telemt_user_octets_from_client{user="hello"} 178526049418 (166.27 GB)
telemt_user_octets_to_client{user="hello"} 1082495683314 (1008.15 GB)
telemt_user_msgs_from_client{user="hello"} 363849
telemt_user_msgs_to_client{user="hello"} 645823
telemt_user_unique_ips_current{user="hello"} 894
telemt_user_unique_ips_recent_window{user="hello"} 978
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 95440.4 (26h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5756797
telemt_connections_bad_total 536258
telemt_connections_current 1733
telemt_connections_me_current 1733
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 118649
telemt_upstream_connect_attempt_total 52793
telemt_upstream_connect_success_total 52185
telemt_upstream_connect_fail_total 518
telemt_upstream_connect_attempts_per_request{bucket="1"} 52703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20596
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 338
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 518
telemt_me_reconnect_attempts_total 67991
telemt_me_reconnect_success_total 1658
telemt_me_reader_eof_total 1432
telemt_me_idle_close_by_peer_total 1432
telemt_me_route_drop_no_conn_total 2344372
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4490423
telemt_me_endpoint_quarantine_total 613
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 714
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
telemt_me_writers_active_current 128
telemt_me_writers_warm_current 8
telemt_desync_total 22735
telemt_desync_full_logged_total 7924
telemt_desync_suppressed_total 14811
telemt_desync_frames_bucket_total{bucket="1_2"} 4317
telemt_desync_frames_bucket_total{bucket="3_10"} 8805
telemt_desync_frames_bucket_total{bucket="gt_10"} 9613
telemt_pool_swap_total 97
telemt_pool_force_close_total 2833
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 369
telemt_me_draining_writers_reap_progress_total 32546
telemt_me_writer_removed_unexpected_total 1480
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3508
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30539
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2465
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 368
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29713
telemt_me_writer_teardown_success_total{mode="normal"} 34047
telemt_me_writer_teardown_noop_total 32547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66594
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.681387
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66594
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 369
telemt_me_refill_failed_total 4114
telemt_me_writer_restored_same_endpoint_total 1404
telemt_me_writer_restored_fallback_total 26
telemt_me_no_writer_failfast_total 223
telemt_me_async_recovery_trigger_total 7257
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 4483553
telemt_user_connections_current{user="hello"} 1733
telemt_user_octets_from_client{user="hello"} 120348259780 (112.08 GB)
telemt_user_octets_to_client{user="hello"} 1824534241998 (1.66 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 868
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 32276.2 (8h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3627887
telemt_connections_bad_total 128114
telemt_connections_current 1491
telemt_connections_me_current 1491
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1524443
telemt_upstream_connect_attempt_total 20878
telemt_upstream_connect_success_total 20746
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 20871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6501
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_reconnect_attempts_total 45496
telemt_me_reconnect_success_total 849
telemt_me_reader_eof_total 515
telemt_me_idle_close_by_peer_total 515
telemt_me_route_drop_no_conn_total 983368
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1739697
telemt_me_endpoint_quarantine_total 215
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 241
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_me_writers_active_current 127
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 9673
telemt_desync_full_logged_total 3273
telemt_desync_suppressed_total 6400
telemt_desync_frames_bucket_total{bucket="1_2"} 1714
telemt_desync_frames_bucket_total{bucket="3_10"} 3697
telemt_desync_frames_bucket_total{bucket="gt_10"} 4262
telemt_pool_swap_total 34
telemt_pool_force_close_total 1121
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 115
telemt_me_draining_writers_reap_progress_total 10417
telemt_me_writer_removed_unexpected_total 598
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1189
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9843
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 955
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 166
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9296
telemt_me_writer_teardown_success_total{mode="normal"} 11032
telemt_me_writer_teardown_noop_total 10418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 21043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 21284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 21344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 21450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 21450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 21450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 21450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 21450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 21450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 21450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 21450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 21450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 21450
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.818596
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 21450
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 115
telemt_me_refill_failed_total 2594
telemt_me_writer_restored_same_endpoint_total 761
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1743504
telemt_user_connections_current{user="hello"} 1491
telemt_user_octets_from_client{user="hello"} 51361762280 (47.83 GB)
telemt_user_octets_to_client{user="hello"} 747415776626 (696.09 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 718
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 13247.3 (3h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145546
telemt_connections_bad_total 1364
telemt_connections_current 350
telemt_connections_me_current 350
telemt_handshake_timeouts_total 3491
telemt_upstream_connect_attempt_total 5916
telemt_upstream_connect_success_total 5899
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 5915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3357
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 125
telemt_me_reconnect_success_total 79
telemt_me_reader_eof_total 80
telemt_me_idle_close_by_peer_total 80
telemt_me_route_drop_no_conn_total 41089
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 126839
telemt_me_endpoint_quarantine_total 107
telemt_me_single_endpoint_shadow_rotate_total 117
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
telemt_me_writers_active_current 47
telemt_desync_total 945
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 710
telemt_desync_frames_bucket_total{bucket="1_2"} 383
telemt_desync_frames_bucket_total{bucket="3_10"} 344
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 14
telemt_pool_force_close_total 341
telemt_me_writer_close_signal_drop_total 18
telemt_me_draining_writers_reap_progress_total 5247
telemt_me_writer_removed_unexpected_total 78
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 353
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4974
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 339
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4906
telemt_me_writer_teardown_success_total{mode="normal"} 5327
telemt_me_writer_teardown_noop_total 5247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 10458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 10549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 10564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 10574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 10574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 10574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 10574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 10574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 10574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 10574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 10574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 10574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 10574
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.652809
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 10574
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 18
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 73
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 126654
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 2381866544 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 76886513444 (71.61 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 95444.7 (26h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6890788
telemt_connections_bad_total 700756
telemt_connections_current 1925
telemt_connections_me_current 1925
telemt_handshake_timeouts_total 195705
telemt_upstream_connect_attempt_total 36253
telemt_upstream_connect_success_total 36108
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 36216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18155
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_reconnect_attempts_total 1471
telemt_me_reconnect_success_total 756
telemt_me_reader_eof_total 735
telemt_me_idle_close_by_peer_total 735
telemt_me_route_drop_no_conn_total 2080976
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5242306
telemt_me_endpoint_quarantine_total 635
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 728
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_me_writers_warm_current 11
telemt_desync_total 20140
telemt_desync_full_logged_total 6741
telemt_desync_suppressed_total 13399
telemt_desync_frames_bucket_total{bucket="1_2"} 4889
telemt_desync_frames_bucket_total{bucket="3_10"} 7335
telemt_desync_frames_bucket_total{bucket="gt_10"} 7916
telemt_pool_swap_total 105
telemt_pool_force_close_total 2877
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 360
telemt_me_draining_writers_reap_progress_total 32579
telemt_me_writer_removed_unexpected_total 712
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2641
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30663
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2789
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29702
telemt_me_writer_teardown_success_total{mode="normal"} 33304
telemt_me_writer_teardown_noop_total 32581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65885
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.479158
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65885
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 360
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 677
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 5217654
telemt_user_connections_current{user="hello"} 1925
telemt_user_octets_from_client{user="hello"} 104865687352 (97.66 GB)
telemt_user_octets_to_client{user="hello"} 2453056777540 (2.23 TB)
telemt_user_unique_ips_current{user="hello"} 892
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 95441.4 (26h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5909877
telemt_connections_bad_total 566509
telemt_connections_current 1823
telemt_connections_me_current 1823
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 165506
telemt_upstream_connect_attempt_total 52368
telemt_upstream_connect_success_total 51973
telemt_upstream_connect_fail_total 336
telemt_upstream_connect_attempts_per_request{bucket="1"} 52309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19943
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 336
telemt_me_reconnect_attempts_total 5237
telemt_me_reconnect_success_total 1060
telemt_me_reader_eof_total 935
telemt_me_idle_close_by_peer_total 935
telemt_me_seq_mismatch_total 40
telemt_me_route_drop_no_conn_total 2133694
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4611909
telemt_me_endpoint_quarantine_total 742
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 724
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 8
telemt_desync_total 18909
telemt_desync_full_logged_total 6376
telemt_desync_suppressed_total 12533
telemt_desync_frames_bucket_total{bucket="1_2"} 4708
telemt_desync_frames_bucket_total{bucket="3_10"} 6886
telemt_desync_frames_bucket_total{bucket="gt_10"} 7315
telemt_pool_swap_total 103
telemt_pool_force_close_total 2832
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 360
telemt_me_draining_writers_reap_progress_total 31509
telemt_me_writer_removed_unexpected_total 947
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3121
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29378
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2609
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28677
telemt_me_writer_teardown_success_total{mode="normal"} 32499
telemt_me_writer_teardown_noop_total 31513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64012
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.562724
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64012
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 360
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 821
telemt_me_writer_restored_fallback_total 51
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 4615310
telemt_user_connections_current{user="hello"} 1823
telemt_user_octets_from_client{user="hello"} 88006407521 (81.96 GB)
telemt_user_octets_to_client{user="hello"} 1986427106564 (1.81 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 823
telemt_user_unique_ips_recent_window{user="hello"} 183
```