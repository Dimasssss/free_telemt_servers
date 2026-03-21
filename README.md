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

# Server Metrics 2026-03-21 23:17:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 7854.0 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131274
telemt_connections_bad_total 10287
telemt_connections_current 699
telemt_connections_me_current 699
telemt_handshake_timeouts_total 6333
telemt_upstream_connect_attempt_total 3096
telemt_upstream_connect_success_total 3095
telemt_upstream_connect_attempts_per_request{bucket="1"} 3095
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1940
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 83
telemt_me_reconnect_success_total 49
telemt_me_reader_eof_total 48
telemt_me_idle_close_by_peer_total 48
telemt_me_route_drop_no_conn_total 27241
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106577
telemt_me_endpoint_quarantine_total 52
telemt_me_single_endpoint_shadow_rotate_total 68
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_me_writers_active_current 45
telemt_desync_total 635
telemt_desync_full_logged_total 201
telemt_desync_suppressed_total 434
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 200
telemt_desync_frames_bucket_total{bucket="gt_10"} 306
telemt_pool_swap_total 8
telemt_pool_force_close_total 211
telemt_me_writer_close_signal_drop_total 17
telemt_me_draining_writers_reap_progress_total 2724
telemt_me_writer_removed_unexpected_total 46
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 200
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2571
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 207
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2513
telemt_me_writer_teardown_success_total{mode="normal"} 2771
telemt_me_writer_teardown_noop_total 2724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 5452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 5483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 5493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 5495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 5495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 5495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 5495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 5495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 5495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 5495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 5495
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.539217
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 5495
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 17
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 106477
telemt_user_connections_current{user="hello"} 699
telemt_user_octets_from_client{user="hello"} 1289839624 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 39930264528 (37.19 GB)
telemt_user_unique_ips_current{user="hello"} 327
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 21220.7 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 641958
telemt_connections_bad_total 30208
telemt_connections_current 468
telemt_connections_me_current 468
telemt_handshake_timeouts_total 24531
telemt_upstream_connect_attempt_total 8863
telemt_upstream_connect_success_total 8706
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 8846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3910
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4765
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_reconnect_attempts_total 772
telemt_me_reconnect_success_total 268
telemt_me_reader_eof_total 229
telemt_me_idle_close_by_peer_total 229
telemt_me_route_drop_no_conn_total 320828
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 523375
telemt_me_endpoint_quarantine_total 182
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 172
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_desync_total 2321
telemt_desync_full_logged_total 1327
telemt_desync_suppressed_total 994
telemt_desync_frames_bucket_total{bucket="1_2"} 490
telemt_desync_frames_bucket_total{bucket="3_10"} 873
telemt_desync_frames_bucket_total{bucket="gt_10"} 958
telemt_pool_swap_total 23
telemt_pool_force_close_total 654
telemt_me_writer_close_signal_drop_total 54
telemt_me_draining_writers_reap_progress_total 7795
telemt_me_writer_removed_unexpected_total 216
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 683
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7328
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 647
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7141
telemt_me_writer_teardown_success_total{mode="normal"} 8011
telemt_me_writer_teardown_noop_total 7795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 15349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 15614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 15700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 15792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 15804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 15806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 15806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 15806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 15806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 15806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 15806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 15806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 15806
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.340320
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 15806
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 54
telemt_me_refill_failed_total 27
telemt_me_writer_restored_same_endpoint_total 186
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 522664
telemt_user_connections_current{user="hello"} 468
telemt_user_octets_from_client{user="hello"} 8856711484 (8.25 GB)
telemt_user_octets_to_client{user="hello"} 180045058004 (167.68 GB)
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 96080.5 (26h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7357256
telemt_connections_bad_total 568226
telemt_connections_current 1838
telemt_connections_me_current 1838
telemt_handshake_timeouts_total 236766
telemt_upstream_connect_attempt_total 34723
telemt_upstream_connect_success_total 34654
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 34661
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18831
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1475
telemt_me_reconnect_success_total 729
telemt_me_reader_eof_total 737
telemt_me_idle_close_by_peer_total 737
telemt_me_route_drop_no_conn_total 4484996
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6015074
telemt_me_endpoint_quarantine_total 606
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 713
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
telemt_me_writers_active_current 46
telemt_desync_total 25506
telemt_desync_full_logged_total 8420
telemt_desync_suppressed_total 17086
telemt_desync_frames_bucket_total{bucket="1_2"} 5468
telemt_desync_frames_bucket_total{bucket="3_10"} 9966
telemt_desync_frames_bucket_total{bucket="gt_10"} 10072
telemt_pool_swap_total 103
telemt_pool_force_close_total 3477
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 562
telemt_me_draining_writers_reap_progress_total 31631
telemt_me_writer_removed_unexpected_total 709
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2690
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29227
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3238
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28154
telemt_me_writer_teardown_success_total{mode="normal"} 31917
telemt_me_writer_teardown_noop_total 31675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63592
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 151.488626
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63592
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 562
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 650
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 6007662
telemt_user_connections_current{user="hello"} 1838
telemt_user_octets_from_client{user="hello"} 103284177660 (96.19 GB)
telemt_user_octets_to_client{user="hello"} 1960996677528 (1.78 TB)
telemt_user_unique_ips_current{user="hello"} 856
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 96081.9 (26h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6049955
telemt_connections_bad_total 576537
telemt_connections_current 1617
telemt_connections_me_current 1617
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 199150
telemt_upstream_connect_attempt_total 38637
telemt_upstream_connect_success_total 38299
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 38477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18499
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 543
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1795
telemt_me_reconnect_success_total 760
telemt_me_reader_eof_total 737
telemt_me_idle_close_by_peer_total 737
telemt_me_route_drop_no_conn_total 2142913
telemt_me_route_drop_channel_closed_total 250
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4531428
telemt_me_endpoint_quarantine_total 587
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 735
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
telemt_desync_total 21779
telemt_desync_full_logged_total 7316
telemt_desync_suppressed_total 14463
telemt_desync_frames_bucket_total{bucket="1_2"} 5249
telemt_desync_frames_bucket_total{bucket="3_10"} 8449
telemt_desync_frames_bucket_total{bucket="gt_10"} 8081
telemt_pool_swap_total 105
telemt_pool_force_close_total 3168
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 343
telemt_me_draining_writers_reap_progress_total 30167
telemt_me_writer_removed_unexpected_total 712
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2586
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28227
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2969
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26999
telemt_me_writer_teardown_success_total{mode="normal"} 30813
telemt_me_writer_teardown_noop_total 30173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60986
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.832969
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60986
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 343
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 656
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 4480899
telemt_user_connections_current{user="hello"} 1617
telemt_user_octets_from_client{user="hello"} 137403351469 (127.97 GB)
telemt_user_octets_to_client{user="hello"} 2093452442911 (1.90 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 743
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 96046.5 (26h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5969825
telemt_connections_bad_total 538476
telemt_connections_current 1564
telemt_connections_me_current 1564
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 190058
telemt_upstream_connect_attempt_total 45056
telemt_upstream_connect_success_total 44749
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 44884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19931
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 355
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1046
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1800
telemt_me_reconnect_success_total 814
telemt_me_reader_eof_total 762
telemt_me_idle_close_by_peer_total 762
telemt_me_route_drop_no_conn_total 2090019
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4459734
telemt_me_endpoint_quarantine_total 646
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 717
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
telemt_me_writers_active_current 45
telemt_desync_total 21677
telemt_desync_full_logged_total 7186
telemt_desync_suppressed_total 14491
telemt_desync_frames_bucket_total{bucket="1_2"} 5320
telemt_desync_frames_bucket_total{bucket="3_10"} 8281
telemt_desync_frames_bucket_total{bucket="gt_10"} 8076
telemt_pool_swap_total 103
telemt_pool_force_close_total 3047
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 366
telemt_me_draining_writers_reap_progress_total 31601
telemt_me_writer_removed_unexpected_total 729
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2662
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29675
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2832
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28554
telemt_me_writer_teardown_success_total{mode="normal"} 32337
telemt_me_writer_teardown_noop_total 31612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63949
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.302924
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63949
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 366
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 705
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 4461248
telemt_user_connections_current{user="hello"} 1564
telemt_user_octets_from_client{user="hello"} 130546658023 (121.58 GB)
telemt_user_octets_to_client{user="hello"} 2043274194207 (1.86 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 801
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 96084.7 (26h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19845620
telemt_connections_bad_total 1432227
telemt_connections_current 2314
telemt_connections_me_current 2314
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 570343
telemt_upstream_connect_attempt_total 188270
telemt_upstream_connect_success_total 170691
telemt_upstream_connect_fail_total 16023
telemt_upstream_connect_attempts_per_request{bucket="1"} 186714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39518
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8878
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16023
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64265
telemt_me_reconnect_success_total 2125
telemt_me_reader_eof_total 1319
telemt_me_idle_close_by_peer_total 1318
telemt_me_route_drop_no_conn_total 39431899
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16189959
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 736
telemt_me_single_endpoint_outage_enter_total 122
telemt_me_single_endpoint_outage_exit_total 122
telemt_me_single_endpoint_outage_reconnect_attempt_total 258
telemt_me_single_endpoint_outage_reconnect_success_total 61
telemt_me_single_endpoint_quarantine_bypass_total 258
telemt_me_single_endpoint_shadow_rotate_total 748
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 31115
telemt_desync_full_logged_total 9233
telemt_desync_suppressed_total 21882
telemt_desync_frames_bucket_total{bucket="1_2"} 6807
telemt_desync_frames_bucket_total{bucket="3_10"} 13774
telemt_desync_frames_bucket_total{bucket="gt_10"} 10534
telemt_pool_swap_total 98
telemt_pool_force_close_total 3261
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 744
telemt_me_draining_writers_reap_progress_total 29791
telemt_me_writer_removed_unexpected_total 1981
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4118
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27387
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2745
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 516
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26530
telemt_me_writer_teardown_success_total{mode="normal"} 31505
telemt_me_writer_teardown_noop_total 29817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61322
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 209.344066
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61322
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 744
telemt_me_refill_failed_total 3787
telemt_me_writer_restored_same_endpoint_total 1467
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14672
telemt_me_writer_removed_unexpected_minus_restored_total 493
telemt_user_connections_total{user="hello"} 16317925
telemt_user_connections_current{user="hello"} 2314
telemt_user_octets_from_client{user="hello"} 180272107168 (167.89 GB)
telemt_user_octets_to_client{user="hello"} 1088852544766 (1014.07 GB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 1047
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 96052.0 (26h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5770379
telemt_connections_bad_total 536885
telemt_connections_current 1698
telemt_connections_me_current 1698
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 118755
telemt_upstream_connect_attempt_total 53107
telemt_upstream_connect_success_total 52496
telemt_upstream_connect_fail_total 521
telemt_upstream_connect_attempts_per_request{bucket="1"} 53017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20772
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 338
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 521
telemt_me_reconnect_attempts_total 68042
telemt_me_reconnect_success_total 1671
telemt_me_reader_eof_total 1447
telemt_me_idle_close_by_peer_total 1446
telemt_me_route_drop_no_conn_total 2347087
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4502294
telemt_me_endpoint_quarantine_total 628
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 719
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
telemt_me_writers_active_current 45
telemt_desync_total 22779
telemt_desync_full_logged_total 7950
telemt_desync_suppressed_total 14829
telemt_desync_frames_bucket_total{bucket="1_2"} 4320
telemt_desync_frames_bucket_total{bucket="3_10"} 8823
telemt_desync_frames_bucket_total{bucket="gt_10"} 9636
telemt_pool_swap_total 98
telemt_pool_force_close_total 2895
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 371
telemt_me_draining_writers_reap_progress_total 32910
telemt_me_writer_removed_unexpected_total 1494
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3548
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30878
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2494
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30015
telemt_me_writer_teardown_success_total{mode="normal"} 34426
telemt_me_writer_teardown_noop_total 32911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67337
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.867832
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67337
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 371
telemt_me_refill_failed_total 4116
telemt_me_writer_restored_same_endpoint_total 1415
telemt_me_writer_restored_fallback_total 26
telemt_me_no_writer_failfast_total 223
telemt_me_async_recovery_trigger_total 7257
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 4495412
telemt_user_connections_current{user="hello"} 1698
telemt_user_octets_from_client{user="hello"} 120735447440 (112.44 GB)
telemt_user_octets_to_client{user="hello"} 1831274223054 (1.67 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 816
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 32887.7 (9h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3643880
telemt_connections_bad_total 128653
telemt_connections_current 1420
telemt_connections_me_current 1420
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1527287
telemt_upstream_connect_attempt_total 21292
telemt_upstream_connect_success_total 21157
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 21285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6692
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_reconnect_attempts_total 45557
telemt_me_reconnect_success_total 877
telemt_me_reader_eof_total 548
telemt_me_idle_close_by_peer_total 548
telemt_me_route_drop_no_conn_total 985638
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1751688
telemt_me_endpoint_quarantine_total 224
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 246
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
telemt_me_writers_active_current 41
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 9749
telemt_desync_full_logged_total 3312
telemt_desync_suppressed_total 6437
telemt_desync_frames_bucket_total{bucket="1_2"} 1724
telemt_desync_frames_bucket_total{bucket="3_10"} 3728
telemt_desync_frames_bucket_total{bucket="gt_10"} 4297
telemt_pool_swap_total 35
telemt_pool_force_close_total 1181
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 117
telemt_me_draining_writers_reap_progress_total 10859
telemt_me_writer_removed_unexpected_total 630
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1246
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10261
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 975
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9678
telemt_me_writer_teardown_success_total{mode="normal"} 11507
telemt_me_writer_teardown_noop_total 10861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 21927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 22181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 22262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 22368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 22368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 22368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 22368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 22368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 22368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 22368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 22368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 22368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 22368
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.991817
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 22368
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 117
telemt_me_refill_failed_total 2596
telemt_me_writer_restored_same_endpoint_total 789
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1755443
telemt_user_connections_current{user="hello"} 1420
telemt_user_octets_from_client{user="hello"} 51552991404 (48.01 GB)
telemt_user_octets_to_client{user="hello"} 752741486374 (701.05 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 717
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 13858.7 (3h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148637
telemt_connections_bad_total 1366
telemt_connections_current 304
telemt_connections_me_current 304
telemt_handshake_timeouts_total 3505
telemt_upstream_connect_attempt_total 6239
telemt_upstream_connect_success_total 6222
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 6238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3532
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 125
telemt_me_reconnect_success_total 79
telemt_me_reader_eof_total 80
telemt_me_idle_close_by_peer_total 80
telemt_me_route_drop_no_conn_total 42177
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 129824
telemt_me_endpoint_quarantine_total 119
telemt_me_single_endpoint_shadow_rotate_total 125
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
telemt_me_writers_active_current 43
telemt_desync_total 945
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 710
telemt_desync_frames_bucket_total{bucket="1_2"} 383
telemt_desync_frames_bucket_total{bucket="3_10"} 344
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 15
telemt_pool_force_close_total 361
telemt_me_writer_close_signal_drop_total 18
telemt_me_draining_writers_reap_progress_total 5569
telemt_me_writer_removed_unexpected_total 78
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 374
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5275
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 359
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5208
telemt_me_writer_teardown_success_total{mode="normal"} 5649
telemt_me_writer_teardown_noop_total 5569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 11086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 11190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 11218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 11218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 11218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 11218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 11218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 11218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 11218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 11218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 11218
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.726137
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 11218
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 18
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 73
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 129633
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 2436676780 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 77933472636 (72.58 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 96056.7 (26h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6919443
telemt_connections_bad_total 704268
telemt_connections_current 1930
telemt_connections_me_current 1930
telemt_handshake_timeouts_total 196600
telemt_upstream_connect_attempt_total 36537
telemt_upstream_connect_success_total 36392
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 36500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18279
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_reconnect_attempts_total 1481
telemt_me_reconnect_success_total 766
telemt_me_reader_eof_total 745
telemt_me_idle_close_by_peer_total 745
telemt_me_route_drop_no_conn_total 2084512
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5256804
telemt_me_endpoint_quarantine_total 647
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 735
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
telemt_me_writers_active_current 46
telemt_desync_total 20238
telemt_desync_full_logged_total 6760
telemt_desync_suppressed_total 13478
telemt_desync_frames_bucket_total{bucket="1_2"} 4926
telemt_desync_frames_bucket_total{bucket="3_10"} 7353
telemt_desync_frames_bucket_total{bucket="gt_10"} 7959
telemt_pool_swap_total 106
telemt_pool_force_close_total 2899
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 361
telemt_me_draining_writers_reap_progress_total 32845
telemt_me_writer_removed_unexpected_total 721
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2672
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30908
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2811
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29946
telemt_me_writer_teardown_success_total{mode="normal"} 33580
telemt_me_writer_teardown_noop_total 32847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66427
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.501372
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66427
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 361
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 686
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 5232097
telemt_user_connections_current{user="hello"} 1930
telemt_user_octets_from_client{user="hello"} 105111026232 (97.89 GB)
telemt_user_octets_to_client{user="hello"} 2458623821536 (2.24 TB)
telemt_user_unique_ips_current{user="hello"} 846
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 96053.2 (26h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5935601
telemt_connections_bad_total 576916
telemt_connections_current 1840
telemt_connections_me_current 1840
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 165784
telemt_upstream_connect_attempt_total 52630
telemt_upstream_connect_success_total 52232
telemt_upstream_connect_fail_total 339
telemt_upstream_connect_attempts_per_request{bucket="1"} 52571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20079
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 339
telemt_me_reconnect_attempts_total 5274
telemt_me_reconnect_success_total 1065
telemt_me_reader_eof_total 941
telemt_me_idle_close_by_peer_total 941
telemt_me_seq_mismatch_total 41
telemt_me_route_drop_no_conn_total 2137276
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4625921
telemt_me_endpoint_quarantine_total 752
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 729
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
telemt_me_writers_active_current 42
telemt_desync_total 18955
telemt_desync_full_logged_total 6393
telemt_desync_suppressed_total 12562
telemt_desync_frames_bucket_total{bucket="1_2"} 4718
telemt_desync_frames_bucket_total{bucket="3_10"} 6907
telemt_desync_frames_bucket_total{bucket="gt_10"} 7330
telemt_pool_swap_total 104
telemt_pool_force_close_total 2856
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 361
telemt_me_draining_writers_reap_progress_total 31753
telemt_me_writer_removed_unexpected_total 954
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3148
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29602
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2633
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28897
telemt_me_writer_teardown_success_total{mode="normal"} 32750
telemt_me_writer_teardown_noop_total 31757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64507
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.574347
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64507
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 361
telemt_me_refill_failed_total 243
telemt_me_writer_restored_same_endpoint_total 825
telemt_me_writer_restored_fallback_total 52
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 4629290
telemt_user_connections_current{user="hello"} 1840
telemt_user_octets_from_client{user="hello"} 88165974397 (82.11 GB)
telemt_user_octets_to_client{user="hello"} 1991426774308 (1.81 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 801
telemt_user_unique_ips_recent_window{user="hello"} 179
```